---
abbrlink: 2444558022
categories: 工具
published: 2023-06-11 09:48:08
title: h@h搭建(hentaiathome)
tags: ['服务器']
---
h@h地址:https://e-hentai.org/hentaiathome.php

申请 Client 的资格 在下方填写表单，按照页面给的最低配置填就行

需要用到的东西如下   按照顺序输入命令

建议装之前先``` sudo apt-get update && sudo apt-get upgrade && sudo apt-get install pip```

```
pip install speedtest-cli
```

然后 ```speedtest-cli --share```    测速好了过后  会给出一个速度图片截图  复制链接  把链接粘贴到client申请页面  等一天左右 tenboro就会通过了

再次进入 h@h地址页面  把client参数设置一下  往自己最大的填  端口改443 或者一个随机不常用端口

下载h@h的 java包  
```
mkdir ~/h@h && cd h@h
sudo apt-get install default-jre
sudo apt-get install unzip
sudo unzip HentaiAtHome_1.6.1.zip
sudo apt-get install screen -y
screen -S h@h
java -jar HentaiAtHome.jar
```
跑起来了后 ```ctrl + a +d ```离开会话   想要观察则可以 ```screen -r h@h```

或者在 ```/etc/systemd/system/```新建 ```h@h.service```写入

```
[Unit]
Description=h@h

[Service]
ExecStart=ExecStart=java -jar HentaiAtHome.jar --client-id=xxxxx --client-key=xxxxxxxxxx
WorkingDirectory=你的h@h路径
Restart=always

[Install]
WantedBy=default.target
```

```
systemctl enable h@h.service
systemctl start h@h.service

```

保持不要掉线  
 