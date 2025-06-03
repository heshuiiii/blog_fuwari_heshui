---
title: Netcup VPS1000 MNZ BF24
published: 2024-10-19
tags: [服务器]
draft: false
image: https://file.akaye.de/i/2025/04/30/1000075929.jpg
---

```
测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.11.08
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : AMD EPYC-Milan Processor
 CPU 核心数        : 4
 CPU 频率          : 2246.624 MHz
 CPU 缓存          : L1: 128.00 KB / L2: 2.00 MB / L3: 128.00 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ❌ Disabled
 内存              : 213.15 MiB / 7.72 GiB
 Swap              : [ no swap partition or swap file detected ]
 硬盘空间          : 1.62 GiB / 502.85 GiB
 启动盘路径        : /dev/vda3
 系统在线时间      : 0 days, 0 hour 1 min
 负载              : 0.55, 0.15, 0.05
 系统              : Debian GNU/Linux 12 (bookworm) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 6.1.0-28-amd64
 TCP加速方式       : cubic
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS214996 netcup GmbH
 IPV4 位置         : Manassas / Virginia / US
 IPV6 ASN          : AS214996 netcup
 IPV6 位置         : Vienna / Vienna / Austria
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		4051 Scores
 4 线程测试(多核)得分: 		16119 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		46591.27 MB/s
 单线程写测试:		26439.00 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		17.2 MB/s (4189 IOPS, 6.11s)		31.0 MB/s (7562 IOPS, 3.38s)
 1GB-1M Block		588 MB/s (560 IOPS, 1.78s)		1.4 GB/s (1367 IOPS, 0.73s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 134.23 MB/s  (33.5k) | 315.62 MB/s   (4.9k)
Write      | 134.59 MB/s  (33.6k) | 317.28 MB/s   (4.9k)
Total      | 268.83 MB/s  (67.2k) | 632.91 MB/s   (9.8k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 436.60 MB/s    (852) | 557.88 MB/s    (544)
Write      | 459.80 MB/s    (898) | 595.03 MB/s    (581)
Total      | 896.41 MB/s   (1.7k) | 1.15 GB/s     (1.1k)
------------流媒体解锁--基于oneclickvirt/CommonMediaTests开源-----------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Netflix-----------------
[IPV4]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：美国
[IPV6]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：美国
----------------Youtube-----------------
[IPV4]
连接方式: Youtube Video Server
视频缓存节点地域: IAD(IAD23S03)
[IPV6]
连接方式: Youtube Video Server
视频缓存节点地域: IAD(IAD23S03)
---------------DisneyPlus---------------
[IPV4]
当前出口所在地区解锁DisneyPlus
区域：US 区
[IPV6]
当前出口所在地区解锁DisneyPlus
区域：DE 区
解锁Netflix，Youtube，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:					Failed (Error: )
 Disney+:				No (IP Banned By Disney+ 1)
 Netflix:				Originals Only
 YouTube Premium:			Yes (Region: US)
 Amazon Prime Video:			Yes (Region: US)
 TVBAnywhere+:				Yes
 Spotify Registration:			No
 OneTrust Region:			AT [Unknown]
 iQyi Oversea Region:			US
 Bing Region:				US
 YouTube CDN:				Washington DC
 Netflix Preferred CDN:			Washington DC
 ChatGPT:				Yes
 Google Gemini:				Yes (Region: USA)
 Wikipedia Editability:			Yes
 Google Play Store:			United States 
 Google Search CAPTCHA Free:		Yes
 Steam Currency:			EUR
 ---Forum---
 Reddit:				No
=======================================
 以下为IPV6网络测试，若无IPV6网络则无输出
============[ Multination ]============
 Dazn:					IPv6 Is Not Currently Supported
 Disney+:				IPv6 Is Not Currently Supported
 Netflix:				Originals Only
 YouTube Premium:			Yes (Region: AT)
 Amazon Prime Video:			IPv6 Is Not Currently Supported
 TVBAnywhere+:				IPv6 Is Not Currently Supported
 Spotify Registration:			No
 OneTrust Region:			AT [Vienna]
 iQyi Oversea Region:			IPv6 Is Not Currently Supported
 Bing Region:				AT
 YouTube CDN:				Washington DC
 Netflix Preferred CDN:			Miami, FL
 ChatGPT:				Failed (Network Connection)
 Google Gemini:				No
 Wikipedia Editability:			Yes
 Google Play Store:			Austria 
 Google Search CAPTCHA Free:		No
 Steam Currency:			IPv6 Is Not Currently Supported
 ---Forum---
 Reddit:				IPv6 Is Not Currently Supported
=======================================
---------------TikTok解锁--感谢lmc999的源脚本及fscarmen PR--------------
 Tiktok Region:		【AT】
-------------IP质量检测--基于oneclickvirt/securityCheck使用-------------
数据仅作参考，不代表100%准确，如果和实际情况不一致请手动查询多个数据库比对
以下为各数据库编号，输出结果后将自带数据库来源对应的编号
ipinfo数据库  [0] | scamalytics数据库 [1] | virustotal数据库   [2] | abuseipdb数据库   [3] | ip2location数据库    [4]
ip-api数据库  [5] | ipwhois数据库     [6] | ipregistry数据库   [7] | ipdata数据库      [8] | db-ip数据库          [9]
ipapiis数据库 [A] | ipapicom数据库    [B] | bigdatacloud数据库 [C] | cheervision数据库 [D] | ipqualityscore数据库 [E]
IPV4:
安全得分:
声誉(越高越好): 0 [2] 
信任得分(越高越好): 1 [8] 
VPN得分(越低越好): 97 [8] 
代理得分(越低越好): 100 [8] 
社区投票-无害: 0 [2] 
社区投票-恶意: 0 [2] 
威胁得分(越低越好): 100 [8] 
欺诈得分(越低越好): 65 [E] 41 [1]
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0026 (Low) [A] 
公司滥用得分(越低越好): 0.0127 (Elevated) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: corporate [9] hosting - high probability [C] DataCenter/WebHosting/Transit [3] hosting [0 7 A]
公司类型: hosting [0 7 A] 
是否云提供商: Yes [7 D] 
是否数据中心: Yes [0 1 A] No [5 6 8 C]
是否移动设备: No [5 A C] Yes [E]
是否代理: No [0 1 4 5 6 7 8 9 A B C D] Yes [E]
是否VPN: No [0 1 6 7 A C D] Yes [E]
是否TorExit: No [1 7 D] 
是否Tor出口: No [1 7 D] 
是否网络爬虫: No [9 A B E] 
是否匿名: No [1 6 7 8 D] 
是否攻击者: No [7 D] Yes [8]
是否滥用者: No [7 A C D E] Yes [8]
是否威胁: No [7 C D] Yes [8]
是否中继: No [0 7 8 C D] 
是否Bogon: No [7 8 A C D] 
是否机器人: No [E] 
DNS-黑名单: 314(Total_Check) 0(Clean) 4(Blacklisted) 10(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 71 [1]
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0026 (Low) [A] 
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
DNS-黑名单: 314(Total_Check) 0(Clean) 0(Blacklisted) 314(Other) 
Google搜索可行性：NO
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
4.46 ms 	AS214996 奥地利
2.63 ms 	AS2914 美国 弗吉尼亚 阿什本 gin.ntt.net
1.13 ms 	AS2914 [NTT-BACKBONE] 美国 弗吉尼亚 阿什本 gin.ntt.net
1.22 ms 	AS2914 [NTT-BACKBONE] 美国 弗吉尼亚 阿什本 gin.ntt.net
5.66 ms 	AS2914 [NTT-BACKBONE] 美国 弗吉尼亚 阿什本 gin.ntt.net
83.48 ms 	AS4134 [CHINANET-BB] 美国 加利福尼亚 圣何塞 www.chinatelecom.com.cn 电信
233.89 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn
230.74 ms 	AS134774 [CHINANET-GD] 中国 广东 深圳 chinatelecom.cn 电信
223.87 ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.24 ms 	AS214996 奥地利
0.30 ms 	AS42473 美国 弗吉尼亚州 阿什本 anexia-it.com
0.76 ms 	AS1299 [ARELION-NET] 瑞典 斯德哥尔摩省 斯德哥尔摩 arelion.com
1.78 ms 	AS1299 [ARELION-NET] 美国 弗吉尼亚州 雷斯顿 arelion.com
56.59 ms 	AS1299 [ARELION-NET] 美国 加利福尼亚 洛杉矶 arelion.com
109.34 ms 	AS1299 [ARELION-NET] 美国 加利福尼亚 洛杉矶 arelion.com
61.11 ms 	AS1299 美国 加利福尼亚 洛杉矶 arelion.com
229.13 ms 	AS4837 [CU169-BACKBONE] 中国 北京市 chinaunicom.cn 联通
230.68 ms 	AS4837 [CU169-BACKBONE] 中国 北京 chinaunicom.cn
271.91 ms 	AS17816 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
268.04 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
289.38 ms 	AS17623 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
24.42 ms 	AS214996 奥地利
1.40 ms 	AS2914 美国 弗吉尼亚 阿什本 gin.ntt.net
1.08 ms 	AS2914 [NTT-BACKBONE] 美国 弗吉尼亚 阿什本 gin.ntt.net
59.66 ms 	AS2914 [NTT-BACKBONE] 美国 加利福尼亚 圣何塞 gin.ntt.net
60.44 ms 	AS2914 [NTT-BACKBONE] 美国 加利福尼亚 圣何塞 gin.ntt.net
209.38 ms 	AS2914 [NTT-BACKBONE] 中国 香港 gin.ntt.net
206.83 ms 	AS2914 [NTT-GLOBAL] 中国 香港 gin.ntt.net
* ms 	AS58453 [CMI-INT] 中国 香港 cmi.chinamobile.com 移动
217.77 ms 	AS58453 [CMI-INT] 中国 广东 广州 cmi.chinamobile.com 移动
242.06 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
244.23 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
244.69 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
246.49 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
243.20 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 884.04 Mbps	 1510.36 Mbps	 103.22	  0.0%
洛杉矶		 1061.65 Mbps	 1382.36 Mbps	 65.69	  0.0%
法兰克福	 778.93 Mbps	 1935.39 Mbps	 96.82	  0.0%
联通WuXi	 442.75 Mbps	 2049.27 Mbps	 252.48	  0.0%
电信Suzhou5G	 536.14 Mbps	 1575.43 Mbps	 210.96	  NULL
电信Zhenjiang5G	 241.82 Mbps	 1413.13 Mbps	 205.69	  NULL
移动Beijing	 166.43 Mbps	 2088.53 Mbps	 269.72	  NULL
移动Fujian	 9.43 Mbps	 35.48 Mbps	 295.73	  NULL
------------------------------------------------------------------------
 总共花费      : 8 分 2 秒
 时间          : Sun Dec 15 19:14:14 CET 2024
------------------------------------------------------------------------


```