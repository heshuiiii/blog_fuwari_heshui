---
abbrlink: 1992638054
author: Allen
categories: 工具
published: 2023-06-26 13:34:00
title: PT站刷流-Hetzenr
tags: ['服务器']
---
hetzner官网：https://console.hetzner.cloud/projects
注册时需要认证ID card 身份证人脸识别，一般3-5分钟完成
如果你第一次刷流，或者只是刷个把月养老  
可以 [点击这个链接](https://hetzner.cloud/?ref=PewRJ60CJHxt)  
我的带有aff码的链接进行注册   初次注册会获得20€ 个把两个月轻松支付
hetzner是按时计费，后付费服务商，可以在下月初结账时付款，记得支付，免得被删除账号


刷流工具，选用 nas-tools 或者 [vertex](https://wiki.vertex.icu/)（推荐）

创建Projects - 添加服务器 - 选择德国ip - 系统选择Debian12/11 - 机型选择 CPX31（160GB硬盘）

```
bash <(wget -qO- https://raw.githubusercontent.com/jerry048/Dedicated-Seedbox/main/Install.sh) admin adminadmin 1
```
最近更新 7.31日  还在更新  我懒