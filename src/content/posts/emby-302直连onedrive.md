---
abbrlink: 2716741732
author: Allen
published: 2024-09-21 13:30:47
title: 'emby 302直连onedrive  '
tags: ['服务器']
---
## 自用教程我看得懂就行


##### 创建rclone容器（先去创建rclone config 的alist webdav）记得输入端口   都是以/mnt为挂载点   方便日后使用
```
rclone config
new / edit
webdav
输入自己的用户名和密码  选择自己输入

之后如果某个容器地址变化  可在   /root/.config/rclone  修改地址即可  重启rclone

```

```
docker run -d --restart=always --name=rclone \
  --volume /root/.config/rclone:/config/rclone \
  --volume /mnt:/mnt:shared \
  --device /dev/fuse \
  --cap-add SYS_ADMIN \
  --security-opt apparmor=unconfined \
  rclone/rclone mount alist:/ /mnt \
  --vfs-cache-mode full \
  --vfs-cache-max-size 2G \
  --allow-non-empty \
  --vfs-cache-poll-interval 1m \
  --buffer-size 200M \
  --vfs-read-ahead 1G \
  --vfs-write-back 10m \
  --allow-other \
  --dir-perms 0777 \
  --file-perms 0666 \
  -v
```

##### 创建nginx-emby
```
docker run -d --name nginx-emby-rm mnookey/nginx-emby && docker cp nginx-emby-rm:/etc/nginx/conf.d/constant.js constant.js && docker cp nginx-emby-rm:/etc/nginx/conf.d/config/constant-mount.js constant-mount.js && docker rm -f nginx-emby-rm
```
这里会创建 ```constant-mount.js``` ```constant.js ```
按需要修改 
```
version: '3.5'
services:
    nginx-emby:
      image: mnookey/nginx-emby:latest
      container_name: nginx-emby
      # 更改为默认host网络,纠正流量标识,直接占用宿主机端口,docker层会禁用端口映射
      network_mode: host
      # 如果需要使用bridge(桥接)网络,请取消ports(端口映射)注释,并注释network_mode
      # 端口映射规则为,宿主机端口:容器内部端口
      # ports:
      #   - 8091:8091
            #  http端口
      #   - 8095:8095
            #  https端口
      # root权限
      privileged: true
      volumes:
        # 上面命令拷贝生成，修改完成后将constant.js和constant-mount.js挂载（必须！！！）
        - ./nginx/constant.js:/etc/nginx/conf.d/constant.js
        - ./nginx/constant-mount.js:/etc/nginx/conf.d/config/constant-mount.js
        # emby缓存文件夹 （必须！！！）
        - ./nginx/embyCache:/var/cache/nginx/emby
        # emby日志文件夹（可选）
        - ./nginx/log:/var/log/nginx
        # emby配置端口默认http：8091，如需修改运行命令导出后删除 # 号来挂载http.conf配置文件
        #- ./nginx/http.conf:/etc/nginx/conf.d/includes/http.conf

```



#### 创建emby和alist

```
services:
  embyserver:
    image: emby/embyserver:4.9.0.30
    container_name: emby_netdisk
    volumes:
      - /your_config_path:/config
      - /mnt:/mnt
    privileged: true
    network_mode: bridge
    ports:
      - 8096:8096
    restart: unless-stopped
    depends_on:
      - alist
 

  alist:
    image: xhofe/alist:latest
    container_name: alist
    volumes:
        - /your_config_path:/opt/alist/data
    network_mode: bridge
    ports:
        - 5244:5244
    environment:
        - PUID=0
        - PGID=0
        - UMASK=022
    restart: unless-stopped
```
alist后台 设置 其他 令牌 ，拿一下

emby控制台 下滑 API密钥 拿一下






之后emby端口就是 vps_ip:8091 



没钱开cloudrive2会员只能用rclone了
docker镜像地址： https://hub.docker.com/r/mnookey/nginx-emby 

文章参考： https://www.mnoo.top/?p=embynginx  感谢








