---
abbrlink: 4277818098
author: Allen
published: 2024-10-20 17:02:34
title: Linveo AMD KVM VPS 2GB - dallas 融合怪测试
tags: ['服务器']
---
```
测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.09.30
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : AMD Ryzen 9 7950X 16-Core Processor
 CPU 核心数        : 2
 CPU 频率          : 4491.288 MHz
 CPU 缓存          : L1: 64.00 KB / L2: 2.00 MB / L3: 128.00 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ✔ Enabled
 内存              : 174.74 MiB / 1.90 GiB
 Swap              : 0 KiB / 1024.00 MiB
 硬盘空间          : 2.54 GiB / 49.82 GiB
 启动盘路径        : /dev/vda3
 系统在线时间      : 0 days, 22 hour 3 min
 负载              : 0.00, 0.00, 0.00
 系统              : Debian GNU/Linux 12 (bookworm) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 6.7.9-bbrplus
 TCP加速方式       : bbr
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS62564 LINVEO, LLC
 IPV4 位置         : Dallas / Texas / US
 IPV6 ASN          : AS400402 Hosting-bot
 IPV6 位置         : United States
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		6033 Scores
 2 线程测试(多核)得分: 		12205 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		73286.20 MB/s
 单线程写测试:		40866.20 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		36.6 MB/s (8931 IOPS, 2.87s)		53.2 MB/s (12998 IOPS, 1.97s)
 1GB-1M Block		448 MB/s (427 IOPS, 2.34s)		999 MB/s (952 IOPS, 1.05s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 244.61 MB/s  (61.1k) | 1.32 GB/s    (20.7k)
Write      | 245.25 MB/s  (61.3k) | 1.33 GB/s    (20.8k)
Total      | 489.87 MB/s (122.4k) | 2.66 GB/s    (41.5k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 1.62 GB/s     (3.1k) | 758.71 MB/s    (740)
Write      | 1.70 GB/s     (3.3k) | 809.24 MB/s    (790)
Total      | 3.32 GB/s     (6.5k) | 1.56 GB/s     (1.5k)
------------流媒体解锁--基于oneclickvirt/CommonMediaTests开源-----------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Netflix-----------------
[IPV4]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：美国
[IPV6]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：美国
----------------Youtube-----------------
[IPV4]
连接方式: Youtube Video Server
视频缓存节点地域: 美国  西雅图(SEA09S34)
[IPV6]
连接方式: Youtube Video Server
视频缓存节点地域: 美国  达拉斯(DFW28S09)
---------------DisneyPlus---------------
[IPV4]
当前出口所在地区解锁DisneyPlus
区域：US 区
[IPV6]
当前出口所在地区解锁DisneyPlus
区域：US 区
解锁Netflix，Youtube，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:					Yes (Region: US)
 Disney+:				No (IP Banned By Disney+ 1)
 Netflix:				Originals Only
 YouTube Premium:			Yes (Region: US)
 Amazon Prime Video:			Yes (Region: US)
 TVBAnywhere+:				Yes
 Spotify Registration:			Yes (Region: US)
 Instagram Licensed Audio:		No
 OneTrust Region:			US [Texas]
 iQyi Oversea Region:			US
 Bing Region:				US
 YouTube CDN:				Seattle, WA
 Netflix Preferred CDN:			Dallas, TX
 ChatGPT:				Yes
 Google Gemini:				Yes (Region: USA)
 Wikipedia Editability:			No
 Google Search CAPTCHA Free:		Yes
 Steam Currency:			USD
 ---Forum---
 Reddit:				No
=======================================
 以下为IPV6网络测试，若无IPV6网络则无输出
============[ Multination ]============
 Dazn:					IPv6 Is Not Currently Supported
 Disney+:				IPv6 Is Not Currently Supported
 Netflix:				Yes (Region: US)
 YouTube Premium:			Yes (Region: US)
 Amazon Prime Video:			IPv6 Is Not Currently Supported
 TVBAnywhere+:				IPv6 Is Not Currently Supported
 Spotify Registration:			Yes (Region: US)
 Instagram Licensed Audio:		No
 OneTrust Region:			US [Unknown]
 iQyi Oversea Region:			IPv6 Is Not Currently Supported
 Bing Region:				US
 YouTube CDN:				Dallas, TX
 Netflix Preferred CDN:			Dallas, TX
 ChatGPT:				Failed (Network Connection)
 Google Gemini:				Yes (Region: USA)
 Wikipedia Editability:			Yes
 Google Search CAPTCHA Free:		Yes
 Steam Currency:			IPv6 Is Not Currently Supported
 ---Forum---
 Reddit:				IPv6 Is Not Currently Supported
=======================================
---------------TikTok解锁--感谢lmc999的源脚本及fscarmen PR--------------
 Tiktok Region:		【US】
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
欺诈得分(越低越好): 0 [1] 68 [E]
滥用得分(越低越好): 0 [3]
ASN滥用得分(越低越好): 0.0074 (Low) [A]
公司滥用得分(越低越好): 0.002 (Low) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: hosting - high probability [C] hosting [0 7 9 A] business [8] DataCenter/WebHosting/Transit [3]
公司类型: hosting [0 7 A] 
是否云提供商: Yes [7 D] 
是否数据中心: Yes [0 1 A C] No [5 6 8]
是否移动设备: Yes [E] No [5 A C]
是否代理: Yes [E] No [0 1 4 5 6 7 8 9 A B C D]
是否VPN: No [0 1 6 7 A C D] Yes [E]
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
DNS-黑名单: 313(Total_Check) 0(Clean) 6(Blacklisted) 14(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 0 [1] 
滥用得分(越低越好): 0 [3]
ASN滥用得分(越低越好): 0.0003 (Very Low) [A]
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
是否Tor: No [1 3 A B D] 
是否Tor出口: No [1 D] 
是否网络爬虫: No [A B] 
是否匿名: No [1 D] 
是否攻击者: No [D] 
是否滥用者: No [A D] 
是否威胁: No [D] 
是否中继: No [D] 
是否Bogon: No [A D] 
DNS-黑名单: 313(Total_Check) 0(Clean) 0(Blacklisted) 313(Other) 
Google搜索可行性：YES
-------------邮件端口检测--基于oneclickvirt/portchecker开源-------------
Platform  SMTP  SMTPS POP3  POP3S IMAP  IMAPS
LocalPort ✔     ✔     ✔     ✔     ✔     ✔    
QQ        ✘     ✘     ✔     ✘     ✔     ✘    
163       ✘     ✘     ✔     ✘     ✔     ✘    
Sohu      ✘     ✘     ✔     ✘     ✔     ✘    
Yandex    ✘     ✘     ✔     ✘     ✔     ✘    
Gmail     ✘     ✘     ✘     ✘     ✘     ✘    
Outlook   ✘     ✘     ✔     ✘     ✔     ✘    
Office365 ✘     ✘     ✔     ✘     ✔     ✘    
Yahoo     ✘     ✘     ✘     ✘     ✘     ✘    
MailCOM   ✘     ✘     ✔     ✘     ✔     ✘    
MailRU    ✘     ✘     ✘     ✘     ✔     ✘    
AOL       ✘     ✘     ✘     ✘     ✘     ✘    
GMX       ✘     ✘     ✔     ✘     ✔     ✘    
Sina      ✘     ✘     ✔     ✘     ✘     ✘    
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
0.29 ms 	AS62564 美国 纽约州 史泰登岛 Binary Racks
0.93 ms 	AS397423 美国 德克萨斯州 达拉斯 tier.net
1.12 ms 	AS40676 美国 德克萨斯州 达拉斯 psychz.net
4.29 ms 	AS3257 美国 德克萨斯 达拉斯 gtt.net
29.29 ms 	AS3257 比利时 布鲁塞尔 gtt.net
36.91 ms 	AS3257 [TINET-TINET] 美国 弗吉尼亚州 郡戴维森 gtt.net
182.02 ms 	AS4134 [CHINANET-BB] 美国 加利福尼亚 圣何塞 www.chinatelecom.com.cn 电信
264.17 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 X-I www.chinatelecom.com.cn 电信
319.78 ms 	AS4134 [CHINANET-GD] 中国 广东 深圳 www.chinatelecom.com.cn 电信
224.11 ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.86 ms 	AS62564 美国 纽约州 史泰登岛 Binary Racks
1.12 ms 	AS397423 美国 德克萨斯州 达拉斯 tier.net
11.42 ms 	AS3356 美国 德克萨斯 达拉斯 lumen.com
75.20 ms 	AS3356 美国 加利福尼亚 洛杉矶 lumen.com
136.75 ms 	AS3356 美国 加利福尼亚 洛杉矶 lumen.com
323.46 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
397.65 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
300.70 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
353.97 ms 	AS17816 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
440.82 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
339.86 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.25 ms 	AS62564 美国 纽约州 史泰登岛 Binary Racks
0.95 ms 	AS397423 美国 德克萨斯州 达拉斯 tier.net
2.28 ms 	AS3356 美国 德克萨斯 达拉斯 lumen.com
50.65 ms 	AS3356 美国 加利福尼亚 洛杉矶 lumen.com
50.36 ms 	AS58453 [CMI-INT] 美国 加利福尼亚 洛杉矶 cmi.chinamobile.com 移动
213.74 ms 	AS58453 [CMI-INT] 中国 广东 广州 cmi.chinamobile.com 移动
205.43 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
215.90 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
266.58 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
211.12 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
215.84 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
217.01 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 6984.08 Mbps	 8118.83 Mbps	 0.79	  0.0%
洛杉矶		 5826.92 Mbps	 7725.46 Mbps	 29.75	  0.0%
法兰克福	 804.26 Mbps	 5341.90 Mbps	 111.22	  NULL
联通WuXi	 976.68 Mbps	 2274.60 Mbps	 297.53	  1.0%
联通成都	 841.63 Mbps	 4.43 Mbps	 308.24	  NULL
电信Zhenjiang5G	 109.62 Mbps	 3320.10 Mbps	 213.19	  NULL
电信浙江	 162.42 Mbps	 1162.04 Mbps	 219.28	  NULL
------------------------------------------------------------------------
 总共花费      : 6 分 1 秒
 时间          : Sun Oct 20 23:07:16 CST 2024
------------------------------------------------------------------------


```