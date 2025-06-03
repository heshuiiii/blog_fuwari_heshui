---
abbrlink: 809667893
author: Allen
published: 2024-12-02 23:42:36
title: naranja10欧
tags: ['服务器']
---
```
########################################################################
                      IP质量体检报告：185.213.*.*
                    bash <(curl -sL IP.Check.Place)
                   https://github.com/xykt/IPQuality
        报告时间：2024-12-02 23:38:58 CST  脚本版本：v2024-11-09
########################################################################
一、基础信息（Maxmind 数据库）
自治系统号：            AS41608
组织：                  NextGenWebs, S.L.
坐标：                  5°41′48″E, 52°32′16″N
地图：                  https://check.place/52.5378,5.6966,15,cn
城市：                  弗莱福兰省, Dronten, 8253
使用地：                [NL]荷兰, [EU]欧洲
注册地：                [ES]西班牙
时区：                  Europe/Amsterdam
IP类型：                 广播IP 
二、IP类型属性
数据库：      IPinfo    ipregistry    ipapi     AbuseIPDB  IP2LOCATION 
使用类型：     机房        机房        机房        机房        机房    
公司类型：     机房        机房        机房    
三、风险评分
风险等级：      极低         低       中等       高         极高
SCAMALYTICS：  0|低风险
ipapi：    0.00%|极低风险
AbuseIPDB：    0|低风险
IPQS：         0|低风险
Cloudflare：   0|低风险
DB-IP：         |低风险
四、风险因子
库： IP2LOCATION ipapi ipregistry IPQS SCAMALYTICS ipdata IPinfo IPWHOIS
地区：    [NL]    [NL]    [NL]    [NL]    [NL]    [NL]    [NL]    [NL]
代理：     否      否      否      否      否      否      否      否 
Tor：      否      否      否      否      否      否      否      否 
VPN：      否      否      否      否      否      无      否      否 
服务器：   是      是      是      无      否      否      是      否 
滥用：     否      否      否      否      无      否      无      无 
机器人：   否      否      无      否      否      无      无      无 
五、流媒体及AI服务解锁检测
服务商：  TikTok   Disney+  Netflix Youtube  AmazonPV  Spotify  ChatGPT 
状态：     解锁     解锁     解锁     解锁     解锁     屏蔽     解锁   
地区：     [NL]     [NL]     [NL]     [ES]     [NL]              [ES]   
方式：     原生     原生     原生     原生     原生              原生   
六、邮局连通性及黑名单检测
本地25端口：阻断
IP地址黑名单数据库：  有效 439   正常 429   已标记 10   黑名单 0
========================================================================

```

```
--------------------- A Bench Script By spiritlhl ----------------------
                   测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.11.08
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : Intel(R) Xeon(R) Gold 6126 CPU @ 2.60GHz
 CPU 核心数        : 1
 CPU 频率          : 2599.998 MHz
 CPU 缓存          : L1: 64.00 KB / L2: 1.00 MB / L3: 19.25 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ✔ Enabled
 内存              : 130.45 MiB / 1.94 GiB
 Swap              : [ no swap partition or swap file detected ]
 硬盘空间          : 1.19 GiB / 49.10 GiB
 启动盘路径        : /dev/vda1
 系统在线时间      : 1 days, 15 hour 17 min
 负载              : 2.24, 0.52, 0.17
 系统              : Debian GNU/Linux 11 (bullseye) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 5.10.0-8-amd64
 TCP加速方式       : cubic
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS41608 NextGenWebs, S.L.
 IPV4 位置         : Dronten / Flevoland / NL
 IPV6 ASN          : AS41608 NextGenWebs, S.L.
 IPV6 位置         : Spain
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分:          627 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:          15644.27 MB/s
 单线程写测试:          11391.20 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作               写速度                                  读速度
 100MB-4K Block         54.1 MB/s (13.21 IOPS, 1.94s))          55.0 MB/s (13429 IOPS, 1.91s)
 1GB-1M Block           2.2 GB/s (2077 IOPS, 0.48s)             1.2 GB/s (1185 IOPS, 0.84s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 190.78 MB/s  (47.6k) | 2.59 GB/s    (40.5k)
Write      | 191.28 MB/s  (47.8k) | 2.61 GB/s    (40.8k)
Total      | 382.06 MB/s  (95.5k) | 5.21 GB/s    (81.4k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 4.02 GB/s     (7.8k) | 4.15 GB/s     (4.0k)
Write      | 4.23 GB/s     (8.2k) | 4.42 GB/s     (4.3k)
Total      | 8.25 GB/s    (16.1k) | 8.57 GB/s     (8.3k)
------------流媒体解锁--基于oneclickvirt/CommonMediaTests开源-----------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Netflix-----------------
[IPV4]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：荷兰
[IPV6]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：荷兰
----------------Youtube-----------------
[IPV4]
连接方式: Youtube Video Server
视频缓存节点地域: 荷兰阿姆斯特丹(AMS15S45)
[IPV6]
连接方式: Youtube Video Server
视频缓存节点地域: 荷兰阿姆斯特丹(AMS15S45)
---------------DisneyPlus---------------
[IPV4]
当前出口所在地区解锁DisneyPlus
区域：NL 区
[IPV6]
当前出口所在地区解锁DisneyPlus
区域：NL 区
解锁Netflix，Youtube，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:                                  Yes (Region: NL)
 Disney+:                               Yes (Region: NL)
 Netflix:                               Yes (Region: NL)
 YouTube Premium:                       Yes (Region: ES)
 Amazon Prime Video:                    Yes (Region: NL)
 TVBAnywhere+:                          Yes
 Spotify Registration:                  No
 Instagram Licensed Audio:              No
 OneTrust Region:                       NL [Flevoland]
 iQyi Oversea Region:                   INTL
 Bing Region:                           NL
 YouTube CDN:                           Amsterdam
 Netflix Preferred CDN:                 [RETN] in [Warsaw]
 ChatGPT:                               Yes
 Google Gemini:                         No
 Wikipedia Editability:                 Yes
 Google Play Store:                     Spain 
 Google Search CAPTCHA Free:            Yes
 Steam Currency:                        EUR
 ---Forum---
 Reddit:                                Yes
=======================================
 以下为IPV6网络测试，若无IPV6网络则无输出
============[ Multination ]============
 Dazn:                                  IPv6 Is Not Currently Supported
 Disney+:                               IPv6 Is Not Currently Supported
 Netflix:                               Yes (Region: NL)
 YouTube Premium:                       Yes (Region: ES)
 Amazon Prime Video:                    IPv6 Is Not Currently Supported
 TVBAnywhere+:                          IPv6 Is Not Currently Supported
 Spotify Registration:                  No
 Instagram Licensed Audio:              No
 OneTrust Region:                       ES [Unknown]
 iQyi Oversea Region:                   IPv6 Is Not Currently Supported
 Bing Region:                           ES
 YouTube CDN:                           Amsterdam
 Netflix Preferred CDN:                 [RETN] in [Warsaw]
 ChatGPT:                               Failed (Network Connection)
 Google Gemini:                         No
 Wikipedia Editability:                 Yes
 Google Play Store:                     Spain 
 Google Search CAPTCHA Free:            Yes
 Steam Currency:                        IPv6 Is Not Currently Supported
 ---Forum---
 Reddit:                                IPv6 Is Not Currently Supported
=======================================
---------------TikTok解锁--感谢lmc999的源脚本及fscarmen PR--------------
 Tiktok Region:         【NL】
-------------IP质量检测--基于oneclickvirt/securityCheck使用-------------
数据仅作参考，不代表100%准确，如果和实际情况不一致请手动查询多个数据库比对
以下为各数据库编号，输出结果后将自带数据库来源对应的编号
ipinfo数据库  [0] | scamalytics数据库 [1] | virustotal数据库   [2] | abuseipdb数据库   [3] | ip2location数据库    [4]
ip-api数据库  [5] | ipwhois数据库     [6] | ipregistry数据库   [7] | ipdata数据库      [8] | db-ip数据库          [9]
ipapiis数据库 [A] | ipapicom数据库    [B] | bigdatacloud数据库 [C] | cheervision数据库 [D] | ipqualityscore数据库 [E]
IPV4:
安全得分:
声誉(越高越好): 0 [2] 
信任得分(越高越好): 10 [8] 
VPN得分(越低越好): 71 [8]
代理得分(越低越好): 99 [8] 
社区投票-无害: 0 [2] 
社区投票-恶意: 0 [2] 
威胁得分(越低越好): 99 [8] 
欺诈得分(越低越好): 0 [1 E] 
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0061 (Low) [A] 
公司滥用得分(越低越好): 0 (Very Low) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: corporate [9] hosting - high probability [C] DataCenter/WebHosting/Transit [3] business [8] hosting [0 7 A]
公司类型: hosting [0 7 A] 
是否云提供商: Yes [7 D] 
是否数据中心: No [5 6 8] Yes [0 1 A C]
是否移动设备: Yes [E] No [5 A C]
是否代理: No [0 1 4 5 6 7 8 9 A B C D E] 
是否VPN: No [0 1 6 7 A C D E] 
是否Tor: No [0 1 3 6 7 8 A B C D E] 
是否Tor出口: No [1 7 D] 
是否网络爬虫: No [9 A B E]
是否匿名: No [1 6 7 8 D] 
是否攻击者: No [7 8 D] 
是否滥用者: No [7 8 A C D E] 
是否威胁: No [7 8 C D] 
是否中继: No [0 7 8 C D] 
是否Bogon: No [7 8 A C D] 
是否机器人: No [E] 
DNS-黑名单: 314(Total_Check) 0(Clean) 6(Blacklisted) 16(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 0 [1] 
滥用得分(越低越好): 0 [3]
ASN滥用得分(越低越好): 0.0061 (Low) [A] 
公司滥用得分(越低越好): 0 (Very Low) [A] 
威胁级别: low [B] 
安全信息:
使用类型: DataCenter/WebHosting/Transit [3] hosting [A]
公司类型: hosting [A] 
是否云提供商: Yes [D] 
是否数据中心: Yes [1 A] 
是否移动设备: No [A] 
是否代理: No [1 A B D] 
是否VPN: No [1 A D] 
是否TorExit: No [1 D] 
是否Tor出口: No [1 D] 
是否网络爬虫: No [A B] 
是否匿名: No [1 D] 
是否攻击者: No [D] 
是否滥用者: No [A D] 
是否威胁: No [D] 
是否中继: No [D]
是否Bogon: No [A D] 
DNS-黑名单: 314(Total_Check) 0(Clean) 0(Blacklisted) 314(Other) 
Google搜索可行性：YES
-------------邮件端口检测--基于oneclickvirt/portchecker开源-------------
Platform  SMTP  SMTPS POP3  POP3S IMAP  IMAPS
LocalPort ✔     ✔     ✔     ✔     ✔     ✔    
QQ        ✔     ✔     ✔     ✘     ✔     ✘    
163       ✔     ✔     ✔     ✘     ✔     ✘    
Sohu      ✔     ✔     ✔     ✘     ✔     ✘    
Yandex    ✔     ✔     ✔     ✘     ✔     ✘    
Gmail     ✔     ✔     ✘     ✘     ✘     ✘    
Outlook   ✔     ✘     ✔     ✘     ✔     ✘    
Office365 ✔     ✘     ✔     ✘     ✔     ✘    
Yahoo     ✔     ✔     ✘     ✘     ✘     ✘    
MailCOM   ✔     ✔     ✔     ✘     ✔     ✘    
MailRU    ✔     ✔     ✘     ✘     ✔     ✘    
AOL       ✔     ✔     ✘     ✘     ✘     ✘    
GMX       ✔     ✘     ✔     ✘     ✔     ✘    
Sina      ✔     ✘     ✔     ✘     ✔     ✘    
----------------三网回程--基于oneclickvirt/backtrace开源----------------
北京电信 219.141.140.10  检测不到回程路由节点的IP地址
北京联通 202.106.195.68  联通4837   [普通线路] 
北京移动 221.179.155.161 移动CMI    [普通线路] 
上海电信 202.96.209.133  电信163    [普通线路] 
上海联通 210.22.97.1     联通4837   [普通线路] 
上海移动 211.136.112.200 移动CMI    [普通线路] 移动CMIN2  [精品线路] 
广州电信 58.60.188.222   电信163    [普通线路] 
广州联通 210.21.196.6    联通4837   [普通线路] 
广州移动 120.196.165.24  移动CMI    [普通线路] 
成都电信 61.139.2.69     电信163    [普通线路] 
成都联通 119.6.6.6       联通4837   [普通线路] 
成都移动 211.137.96.205  移动CMI    [普通线路] 
准确线路自行查看详细路由，本测试结果仅作参考
同一目标地址多个线路时，可能检测已越过汇聚层，除了第一个线路外，后续信息可能无效
---------------------回程路由--感谢fscarmen开源及PR---------------------
依次测试电信/联通/移动经过的地区及线路，核心程序来自ipip.net或nexttrace，请知悉!
广州电信 58.60.188.222
0.30 ms         AS60404 荷兰 弗莱福兰省 德龙滕 liteserver.nl
0.86 ms         AS50673 荷兰 弗莱福兰省 德龙滕 serverius.net
1.40 ms         AS50673 [NL-SERVERIUS] 荷兰 德伦特省 梅珀尔 serverius.net
2.60 ms         AS174 [COGENT-BONE] 荷兰 北荷兰省 阿姆斯特丹 cogentco.com
3.69 ms         AS174 [COGENT-BONE] 荷兰 北荷兰省 阿姆斯特丹 cogentco.com
4.10 ms         AS174 [COGENT-149] 荷兰 北荷兰省 阿姆斯特丹 cogentco.com
186.48 ms       AS4134 [CHINANET-BB] 中国 广东 广州 欧洲回国方向 www.chinatelecom.com.cn 电信
* ms    AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn
194.45 ms       AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn
211.07 ms       AS134774 [CHINANET-GD] 中国 广东 深圳 chinatelecom.cn 电信
196.46 ms       AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.41 ms         AS60404 荷兰 弗莱福兰省 德龙滕 liteserver.nl
0.90 ms         AS50673 荷兰 弗莱福兰省 德龙滕 serverius.net
2.29 ms         AS50673 [NL-SERVERIUS] 荷兰 德伦特省 梅珀尔 serverius.net
2.52 ms         AS174 [COGENT-BONE] 荷兰 北荷兰省 阿姆斯特丹 cogentco.com
13.75 ms        AS174 [COGENT-BONE] 德国 黑森 美因河畔法兰克福 cogentco.com
9.19 ms         AS174 [COGENT-BONE] 德国 黑森 美因河畔法兰克福 cogentco.com
9.98 ms         AS174 [COGENT-BONE] 德国 黑森 美因河畔法兰克福 cogentco.com
60.81 ms        AS174 [COGENT-149] 德国 黑森 美因河畔法兰克福 cogentco.com
180.25 ms       AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
186.88 ms       AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
169.55 ms       AS17816 [UNICOM-GD] 中国 广东 广州 chinaunicom.cn
168.61 ms       AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
193.26 ms       AS17623 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.30 ms         AS60404 荷兰 弗莱福兰省 德龙滕 liteserver.nl
0.33 ms         AS60404 [LITESERVER] 荷兰 北荷兰省 阿姆斯特丹 liteserver.nl
3.35 ms         AS174 [COGENT-BONE] 荷兰 北荷兰省 阿姆斯特丹 cogentco.com
8.52 ms         AS174 [COGENT-BONE] 德国 黑森 美因河畔法兰克福 cogentco.com
10.39 ms        AS174 [COGENT-BONE] 德国 黑森 美因河畔法兰克福 cogentco.com
16.45 ms        AS174 [COGENT-149] 德国 黑森 美因河畔法兰克福 cogentco.com
16.84 ms        AS58453 [CMI-INT] 德国 黑森 美茵河畔法兰克福 cmi.chinamobile.com 移动
226.12 ms       AS58453 [CMI-INT] 德国 黑森 美因河畔法兰克福 cmi.chinamobile.com 移动
229.78 ms       AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
224.48 ms       AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
221.31 ms       AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
216.26 ms       AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
223.71 ms       AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
225.16 ms       AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置             上传速度        下载速度        延迟     丢包率
Speedtest.net    722.02 Mbps     835.86 Mbps     0.38     0.0%
法兰克福         918.83 Mbps     809.89 Mbps     7.82     0.0%
洛杉矶           319.49 Mbps     760.26 Mbps     147.55   0.0%
联通WuXi         305.86 Mbps     727.82 Mbps     170.03   0.0%
联通成都         194.67 Mbps     4.54 Mbps       221.15   NULL
电信Zhenjiang5G  2.31 Mbps       623.65 Mbps     222.62   NULL
电信浙江         1.79 Mbps       569.61 Mbps     222.32   NULL
移动Beijing      23.04 Mbps      500.94 Mbps     144.91   0.3%
------------------------------------------------------------------------
 总共花费      : 6 分 21 秒
 时间          : Mon Dec  2 10:45:19 EST 2024
------------------------------------------------------------------------


```



















