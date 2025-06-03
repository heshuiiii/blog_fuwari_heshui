---
abbrlink: 3656501916
categories: 工具
hidden: false
published: 2023-07-23 20:54:15
title: proxmox ve,grafana,prometheus, proxmox-pve-exporter 新的监控面板
tags: ['服务器']
---
前言：因为pve自己的概要看起来太麻烦了所以换一个新的



# 全部在PVE宿主机上配置，无docker内容



## 安装Prometheus

### 新建用户组

```
sudo groupadd --system prometheus
sudo useradd -s /sbin/nologin --system -g prometheus prometheus
```
### 创建目录然后下载 Prometheus二进制文件

```
sudo mkdir /var/lib/prometheus
for i in rules rules.d files_sd; do sudo mkdir -p /etc/prometheus/${i}; done

mkdir -p /tmp/prometheus && cd /tmp/prometheus
curl -s https://api.github.com/repos/prometheus/prometheus/releases/latest \
  | grep browser_download_url \
  | grep linux-amd64 \
  | cut -d '"' -f 4 \
  | wget -qi -
```
这里 wget 可能会卡住  建议先设置好代理

0729更新 没反应的去 https://github.com/prometheus/prometheus/releases/download/v2.46.0/prometheus-2.46.0.linux-amd64.tar.gz
下载后继续下面命令就可以了


```
export http_proxy="http://127.0.0.1:7890"   # ip:port 根据自己环境设置
export https_proxy="http://127.0.0.1:7890"
```


### 复制文件
```
tar xvf prometheus*.tar.gz
cd prometheus*/
mv prometheus promtool /usr/local/bin/
mv prometheus.yml  /etc/prometheus/prometheus.yml
mv consoles/ console_libraries/ /etc/prometheus/
```



### 配置 systemd
直接命令行输入，完毕后回显内容

```
sudo tee /etc/systemd/system/prometheus.service<<EOF
[Unit]
Description=Prometheus
Documentation=https://prometheus.io/docs/introduction/overview/
Wants=network-online.target
After=network-online.target

[Service]
Type=simple
User=prometheus
Group=prometheus
ExecReload=/bin/kill -HUP $MAINPID
ExecStart=/usr/local/bin/prometheus \
  --config.file=/etc/prometheus/prometheus.yml \
  --storage.tsdb.path=/var/lib/prometheus \
  --web.console.templates=/etc/prometheus/consoles \
  --web.console.libraries=/etc/prometheus/console_libraries \
  --web.listen-address=0.0.0.0:9090 \
  --web.external-url=

SyslogIdentifier=prometheus
Restart=always

[Install]
WantedBy=multi-user.target
EOF
```

### 配置权限重启prometheus
```
for i in rules rules.d files_sd; do sudo chown -R prometheus:prometheus /etc/prometheus/${i}; done
for i in rules rules.d files_sd; do sudo chmod -R 775 /etc/prometheus/${i}; done
sudo chown -R prometheus:prometheus /var/lib/prometheus/

sudo systemctl daemon-reload
sudo systemctl start prometheus
sudo systemctl enable prometheus
```



## 安装proxmox-pve-exporter

默认你已经在pve宿主机上安装了 python 和 pip 

```
pip install prometheus-pve-exporter

```

```
mkdir /etc/prometheus-pve-exporter
nano /etc/prometheus-pve-exporter/pve.yml

```
### 粘贴用户配置
```
default:
	user: root@pam     # 这里填你pve实际使用的账户，大多使用root默认
	password: 你自己root账户的密码
	verify_ssl: false
```

Ctrl+X  Y 确认

### 编写启动脚本

```
nano /etc/init.d/prometheus-pve-exporter
chmod +x prometheus-pve-exporter
```
```
pve_exporter /etc/prometheus-pve-exporter/pve.yml 9221 0.0.0.0
exit 0
```

### 测试脚本
```
sh /etc/init.d/prometheus-pve-exporter & curl http://localhost:9221/
```

没红输出正常日志就可以了

```
netstat -apn | grep 9221
```
显示 python使用

——————————————————


### 配置 systemd






### 添加 proxmox-pve-exporter 到 Prometheus


```
nano /etc/prometheus/prometheus.yml
```
添加代码

```
  - job_name: 'proxmox'
    metrics_path: /pve
    static_configs:
      - targets: ['localhost:9221']

```


末尾应该是这个样子的，记得对齐

```
scrape_configs:
  - job_name: "prometheus"


    static_configs:
      - targets: ["localhost:9090"]


  - job_name: 'proxmox'
    metrics_path: /pve
    static_configs:
      - targets: ['localhost:9221']
```


重启

```
systemctl restart prometheus
```



访问 http://pve_ip:9090/targets?search=

看到有个  ** proxmox (1/1 up) **   说明成功




## 安装Grafana

官网下载页：https://grafana.com/grafana/download?platform=linux


```
wget https://dl.grafana.com/enterprise/release/grafana-enterprise_10.0.2_amd64.deb
sudo dpkg -i grafana-enterprise_10.0.2_amd64.deb
```

设置启动

```
sudo systemctl enable --now grafana-server
systemctl status grafana-server.service
```

访问 http://pve_ip:3000  用户和密码都是 **admin**

登录Grafana后
左侧 menu 点出 connection - datasources 搜索 Prometheus

同样也可以直接访问 http://pve_ip:3000/connections/datasources/new  

修改参数

Prometheus server URL = http://pve_ip:9090

HTTP method = GET

**Save & test**   绿了就可以了
访问 http://pve_ip:3000/dashboard/import

直接输入ID  **10347**   然后LOAD

就可以了监控面板已经装好，可以自行更改模块  缩小放大 记得修改后点击 **save dashboard** 的按钮

参考于佛西 和 Ein Verne 
总结安装完成