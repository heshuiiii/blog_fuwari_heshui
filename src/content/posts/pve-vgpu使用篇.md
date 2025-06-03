---
abbrlink: 804318065
author: Allen
published: 2023-07-25 22:51:36
title: pve-vgpu使用篇
tags: ['服务器']
---
# 前言：

使用优化版fastapi-dls镜像
https://registry.hub.docker.com/r/makedie/fastapi-dls

方便配置  目前这个镜像更新到1.3.8版本 本文亦以此为例  （仅以pve为例，其他环境应适当通用）

### 准备内容

1.一个docker，安装好了的docker
2.安装宿主机和客户机驱动（本文使用 NVIDIA-GRID-Linux-KVM-525.60.12-525.60.13-527.41 为例）
3.。。。。


默认你已经有了一台装了docker的虚拟机  或者其他docker可执行环境

```docker run -d -e DLS_URL=你的docker所在机器ip -e DLS_PORT=443 -p 443:443  makedie/fastapi-dls:1.3.8```

端口可以更改 如若某些环境443占用可改为
```
docker run -d -e DLS_URL=你的docker所在机器ip -e DLS_PORT=自定义端口 -p 自定义端口:443  makedie/fastapi-dls:1.3.8
```

下载过慢可以更改docker镜像加速器

```vim /etc/docker/daemon.json```

```
{
    "registry-mirrors" : [
    "https://lgs1dwrt.mirror.aliyuncs.com"
  ]
}
```

重启docker
```
sudo systemctl daemon-reload
sudo systemctl restart docker
```

此时如果容器下载完成正常会直接运行容器
你的docker发授权的网址应是  "https://docker_ip:4443/-/client-token"

打开即将获得授权的虚拟机浏览器，访问 "https://docker_ip:4443/-/client-token"
获得一个token，移动到"C:\Program Files\NVIDIA Corporation\vGPU Licensing\ClientConfigToken"
如果没有路径请相应创建就好，重启虚拟机，输入 ```nvidia-smi -q```

查看输出内容 **License Status**  为 Licensed  有到期时间，则为成功




本文未写完，驱动安装步骤，有点困，没传驱动，先睡觉 ，想起来再写







