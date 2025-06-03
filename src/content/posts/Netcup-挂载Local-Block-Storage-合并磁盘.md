---
abbrlink: 3147925723
author: Allen
published: 2024-10-17 07:46:01
title: Netcup 挂载Local Block Storage 合并磁盘
tags: ['服务器']
---
重装系统

添加存储块 Local Block Storage

开启救援模式  SCP - Media - Rescure System  记住密码

```fdisk -l``` ```e2fsck -f /dev/vda3``` 也有可能不是vda3 看最大那块分区命

```resize2fs /dev/vda3 15G```   大于15g 别太小了 

```cfdisk /dev/vda```  方向键控制 resize vda3 

```free space  - enter  - write ``` 返回SCP  关机  deactivate  rescue mode   开机

输入给的root密码


```fdisk -l```

```apt-get -y install lvm2```

```pvcreate /dev/vda4```

```pvcreate /dev/vdb```

```pvcreate -ff /dev/vdb```

```vgcreate vg0 /dev/vda4 /dev/vdb```

```lvcreate -n lv0 -l 100%FREE vg0 ```

```mkfs.ext4 -m 0 /dev/vg0/lv0```

```mount /dev/vg0/lv0 /home```

```echo '/dev/vg0/lv0 /home ext4 defaults 0 0' >> /etc/fstab```
