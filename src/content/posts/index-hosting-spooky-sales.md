---
abbrlink: 3041786643
author: Allen
published: 2024-10-20 17:00:44
title: index-hosting spooky sales  灵车3欧/月
tags: ['服务器']
---
```


测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.09.30
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : AMD EPYC 9334 32-Core Processor
 CPU 核心数        : 4
 CPU 频率          : 2695.944 MHz
 CPU 缓存          : L1: 0.00 KB / L2: 0.00 KB / L3: 0.00 KB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ✔ Enabled
 内存              : 153.15 MiB / 11.73 GiB
 Swap              : [ no swap partition or swap file detected ]
 硬盘空间          : 1.32 GiB / 147.48 GiB
 启动盘路径        : /dev/sda1
 系统在线时间      : 0 days, 0 hour 14 min
 负载              : 0.59, 0.35, 0.19
 系统              : Debian GNU/Linux 10 (buster) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 4.19.0-25-amd64
 TCP加速方式       : cubic
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS58212 dataforest GmbH
 IPV4 位置         : Frankfurt am Main / Hesse / DE
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		4166 Scores
 4 线程测试(多核)得分: 		16054 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		45033.25 MB/s
 单线程写测试:		20122.70 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		57.7 MB/s (14.10 IOPS, 1.82s)		75.5 MB/s (18441 IOPS, 1.39s)
 1GB-1M Block		2.2 GB/s (2129 IOPS, 0.47s)		6.4 GB/s (6069 IOPS, 0.16s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 309.82 MB/s  (77.4k) | 2.50 GB/s    (39.1k)
Write      | 310.63 MB/s  (77.6k) | 2.52 GB/s    (39.3k)
Total      | 620.45 MB/s (155.1k) | 5.02 GB/s    (78.5k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 2.79 GB/s     (5.4k) | 2.57 GB/s     (2.5k)
Write      | 2.93 GB/s     (5.7k) | 2.74 GB/s     (2.6k)
Total      | 5.72 GB/s    (11.1k) | 5.31 GB/s     (5.1k)
------------流媒体解锁--基于oneclickvirt/CommonMediaTests开源-----------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Netflix-----------------
[IPV4]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：德国
[IPV6]
您的网络可能没有正常配置IPv6，或者没有IPv6网络接入
----------------Youtube-----------------
[IPV4]
连接方式: Youtube Video Server
视频缓存节点地域: 德国法兰克福(FRA15S37)
[IPV6]
Youtube在您的出口IP所在的国家不提供服务
---------------DisneyPlus---------------
[IPV4]
当前出口所在地区解锁DisneyPlus
区域：DE 区
[IPV6]
DisneyPlus在您的出口IP所在的国家不提供服务
解锁Netflix，Youtube，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:					Yes (Region: DE)
 Disney+:				Yes (Region: DE)
 Netflix:				Yes (Region: DE)
 YouTube Premium:			Yes (Region: DE)
 Amazon Prime Video:			Yes (Region: DE)
 TVBAnywhere+:				Yes
 Spotify Registration:			No
 Instagram Licensed Audio:		No
 OneTrust Region:			DE [Unknown]
 iQyi Oversea Region:			DE
 Bing Region:				DE
 YouTube CDN:				Frankfurt
 Netflix Preferred CDN:			Frankfurt
 ChatGPT:				Yes
 Google Gemini:				No
 Wikipedia Editability:			Yes
 Google Search CAPTCHA Free:		Yes
 Steam Currency:			EUR
 ---Forum---
 Reddit:				Yes
=======================================
 以下为IPV6网络测试，若无IPV6网络则无输出
---------------TikTok解锁--感谢lmc999的源脚本及fscarmen PR--------------
 Tiktok Region:		【DE】
-------------IP质量检测--基于oneclickvirt/securityCheck使用-------------
数据仅作参考，不代表100%准确，如果和实际情况不一致请手动查询多个数据库比对
以下为各数据库编号，输出结果后将自带数据库来源对应的编号
ipinfo数据库  [0] | scamalytics数据库 [1] | virustotal数据库   [2] | abuseipdb数据库   [3] | ip2location数据库    [4]
ip-api数据库  [5] | ipwhois数据库     [6] | ipregistry数据库   [7] | ipdata数据库      [8] | db-ip数据库          [9]
ipapiis数据库 [A] | ipapicom数据库    [B] | bigdatacloud数据库 [C] | cheervision数据库 [D] | ipqualityscore数据库 [E]
IPV4:
安全得分:
声誉(越高越好): 0 [2]
信任得分(越高越好): 0 [8] 
VPN得分(越低越好): 100 [8] 
代理得分(越低越好): 100 [8] 
社区投票-无害: 0 [2] 
社区投票-恶意: 0 [2] 
威胁得分(越低越好): 100 [8] 
欺诈得分(越低越好): 0 [1] 65 [E]
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0178 (Elevated) [A] 
公司滥用得分(越低越好): 0.0508 (High) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: hosting ASN [C] hosting [0 7 9 A] business [8] DataCenter/WebHosting/Transit [3]
公司类型: hosting [0 7 A] 
是否云提供商: Yes [7 D] 
是否数据中心: Yes [0 5 6 A C] No [1 8]
是否移动设备: Yes [E] No [5 A C]
是否代理: No [0 1 4 7 8 9 A B C D] Yes [5 6 E]
是否VPN: No [0 1 6 7 A C D] Yes [E]
是否TorExit: No [1 7 D] 
是否Tor出口: No [1 7 D] 
是否网络爬虫: No [9 A B E] 
是否匿名: Yes [6] No [1 7 8 D]
是否攻击者: No [7 D] Yes [8]
是否滥用者: No [7 A C D E] Yes [8]
是否威胁: Yes [8] No [7 C D]
是否中继: No [0 7 8 C D] 
是否Bogon: No [7 8 A C D]
是否机器人: No [E] 
DNS-黑名单: 313(Total_Check) 0(Clean) 6(Blacklisted) 23(Other) 
Google搜索可行性：YES
-------------邮件端口检测--基于oneclickvirt/portchecker开源-------------
Platform  SMTP  SMTPS POP3  POP3S IMAP  IMAPS
LocalPort ✔     ✔     ✔     ✔     ✔     ✔    
QQ        ✔     ✔     ✔     ✘     ✔     ✘    
163       ✔     ✔     ✔     ✘     ✔     ✘    
Sohu      ✔     ✔     ✘     ✘     ✔     ✘    
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
北京电信 219.141.140.10  电信163    [普通线路] 
北京联通 202.106.195.68  联通4837   [普通线路] 
北京移动 221.179.155.161 移动CMI    [普通线路] 
上海电信 202.96.209.133  电信163    [普通线路] 
上海联通 210.22.97.1     联通4837   [普通线路] 
上海移动 211.136.112.200 移动CMI    [普通线路] 
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
0.40 ms 	AS58212 德国 黑森州 法兰克福 dataforest.net
0.48 ms 	AS58212 德国 黑森 美因河畔法兰克福 dataforest.net
56.08 ms 	AS174 [COGENT-149] 德国 黑森 美因河畔法兰克福 Cogent-CT-Peer cogentco.com
300.36 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
304.62 ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.67 ms 	AS58212 德国 黑森州 法兰克福 dataforest.net
0.56 ms 	AS58212 德国 黑森 美因河畔法兰克福 dataforest.net
0.67 ms 	AS199524 [LU-GCORELABS] 美国 弗吉尼亚州 阿什本 gcore.com
1.02 ms 	* RFC1918
51.87 ms 	* RFC1918
14.91 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
153.51 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
179.23 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
183.10 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
180.26 ms 	AS17816 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
175.88 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
174.12 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.66 ms 	AS58212 德国 黑森州 法兰克福 dataforest.net
0.69 ms 	AS58212 德国 黑森 美因河畔法兰克福 dataforest.net
0.89 ms 	AS199524 [LU-GCORELABS] 美国 弗吉尼亚州 阿什本 gcore.com
0.99 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
15.34 ms 	AS1299 [ARELION-NET] 德国 黑森 美因河畔法兰克福 Telia-CM-Cust arelion.com
14.80 ms 	AS58453 [CMI-INT] 德国 黑森 美茵河畔法兰克福 cmi.chinamobile.com 移动
221.01 ms 	AS58453 [CMI-INT] 德国 黑森 美因河畔法兰克福 cmi.chinamobile.com 移动
212.34 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
212.50 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
220.71 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
226.21 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
223.14 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 4390.26 Mbps	 4283.86 Mbps	 0.48	  0.0%
法兰克福	 6995.30 Mbps	 10921.81 Mbps	 1.16	  NULL
洛杉矶		 1129.51 Mbps	 6346.75 Mbps	 154.07	  0.0%
联通WuXi	 241.02 Mbps	 4245.36 Mbps	 157.33	  0.0%
联通成都	 865.87 Mbps	 1.11 Mbps	 192.00	  NULL
电信Zhenjiang5G	 0.32 Mbps	 1062.54 Mbps	 302.63	  NULL
移动Beijing	 1.13 Mbps	 6122.13 Mbps	 193.87	  NULL
------------------------------------------------------------------------
 总共花费      : 6 分 18 秒
 时间          : Sun Oct 20 08:30:36 UTC 2024
------------------------------------------------------------------------
```