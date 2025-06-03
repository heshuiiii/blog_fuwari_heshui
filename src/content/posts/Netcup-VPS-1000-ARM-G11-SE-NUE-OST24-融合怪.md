---
abbrlink: 1759244511
author: Allen
published: 2024-10-03 16:11:34
title: Netcup VPS 1000 ARM G11 SE NUE OST24  融合怪
tags: ['服务器']
---
```
测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.09.30
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : Neoverse-N1 BIOS virt-6.2 CPU @ 2.0GHz
 CPU 核心数        : 6
 CPU 缓存          : L1: 0.00 KB / L2: 0.00 KB / L3: 0.00 KB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ❌ Disabled
 内存              : 144.99 MiB / 7.75 GiB
 Swap              : [ no swap partition or swap file detected ]
 硬盘空间          : 1.43 GiB / 503.21 GiB
 启动盘路径        : /dev/vda4
 系统在线时间      : 0 days, 0 hour 18 min
 负载              : 0.52, 0.14, 0.05
 系统              : Debian GNU/Linux 12 (bookworm) (aarch64)
 架构              : aarch64 (64 Bit)
 内核              : 6.1.0-25-arm64
 TCP加速方式       : cubic
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS197540 netcup GmbH
 IPV4 位置         : Nürnberg / Bavaria / DE
 IPV6 ASN          : AS197540 netcup
 IPV6 位置         : Nuremberg / Bavaria / Germany
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		3328 Scores
 6 线程测试(多核)得分: 		19859 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		29951.57 MB/s
 单线程写测试:		14311.16 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		18.5 MB/s (4521 IOPS, 5.66s)		34.9 MB/s (8530 IOPS, 3.00s)
 1GB-1M Block		283 MB/s (269 IOPS, 3.71s)		2.3 GB/s (2225 IOPS, 0.45s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
---------------------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 147.32 MB/s  (36.8k) | 246.35 MB/s   (3.8k)
Write      | 147.22 MB/s  (36.8k) | 253.68 MB/s   (3.9k)
Total      | 294.54 MB/s  (73.6k) | 500.03 MB/s   (7.8k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 299.45 MB/s    (584) | 438.21 MB/s    (427)
Write      | 325.06 MB/s    (634) | 488.91 MB/s    (477)
Total      | 624.52 MB/s   (1.2k) | 927.12 MB/s    (904)
------------流媒体解锁--基于oneclickvirt/CommonMediaTests开源-----------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Netflix-----------------
[IPV4]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：德国
[IPV6]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：德国
----------------Youtube-----------------
[IPV4]
连接方式: Google Global CacheCDN (ISP Cooperation)
ISP运营商: ANEXIAAT
视频缓存节点地域: 奥地利维也纳(VIE1)
[IPV6]
连接方式: Google Global CacheCDN (ISP Cooperation)
ISP运营商: ANEXIAAT
视频缓存节点地域: 奥地利维也纳(VIE1)
---------------DisneyPlus---------------
[IPV4]
当前出口所在地区解锁DisneyPlus
区域：DE 区
[IPV6]
当前出口所在地区解锁DisneyPlus
区域：DE 区
解锁Netflix，Youtube，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:					Yes (Region: DE)
 Disney+:				No (IP Banned By Disney+ 1)
 Netflix:				Originals Only
 YouTube Premium:			Yes (Region: DE)
 Amazon Prime Video:			Yes (Region: DE)
 TVBAnywhere+:				Yes
 Spotify Registration:			No
 Instagram Licensed Audio:		Failed (Error: PAGE ERROR)
 OneTrust Region:			DE [Bavaria]
 iQyi Oversea Region:			DE
 Bing Region:				DE
 YouTube CDN:				[ANEXIAAT] in [Vienna]
 Netflix Preferred CDN:			[ANEXIA Internetdienstleistungs] in [Vienna]
 ChatGPT:				Yes
 Google Gemini:				No
 Wikipedia Editability:			Yes
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
 YouTube Premium:			Yes (Region: DE)
 Amazon Prime Video:			IPv6 Is Not Currently Supported
 TVBAnywhere+:				IPv6 Is Not Currently Supported
 Spotify Registration:			No
 Instagram Licensed Audio:		Failed (Error: PAGE ERROR)
 OneTrust Region:			DE [Bavaria]
 iQyi Oversea Region:			IPv6 Is Not Currently Supported
 Bing Region:				DE
 YouTube CDN:				[ANEXIAAT] in [Vienna]
 Netflix Preferred CDN:			[ANEXIA Internetdienstleistungs] in [Vienna]
 ChatGPT:				Failed (Network Connection)
 Google Gemini:				No
 Wikipedia Editability:			Yes
 Google Search CAPTCHA Free:		Yes
 Steam Currency:			IPv6 Is Not Currently Supported
 ---Forum---
 Reddit:				IPv6 Is Not Currently Supported
=======================================
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
欺诈得分(越低越好): 28 [1] 65 [E]
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0058 (Low) [A]
公司滥用得分(越低越好): 0.011 (Elevated) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2] 无记录数: 94 [2]  
安全信息:
使用类型: hosting - high probability [C] hosting [0 7 9 A] business [8] DataCenter/WebHosting/Transit [3]
公司类型: hosting [0 7 A] 
是否云提供商: Yes [7 D] 
是否数据中心: Yes [0 1 5 6 A C] No [8]
是否移动设备: No [5 A C] Yes [E]
是否代理: Yes [E] No [0 1 4 5 6 7 8 9 A B C D]
是否VPN: Yes [E] No [0 1 6 7 A C D]
是否TorExit: No [1 7 D] 
是否Tor出口: No [1 7 D] 
是否网络爬虫: No [9 A B E] 
是否匿名: No [1 6 7 8 D] 
是否攻击者: No [7 8 D] 
是否滥用者: No [7 8 A C D E] 
是否威胁: No [7 8 C D] 
是否中继: No [0 7 8 C D] 
是否Bogon: No [7 8 A C D] 
是否机器人: No [E] 
DNS-黑名单: 313(Total_Check) 0(Clean) 7(Blacklisted) 11(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 0 [1] 
滥用得分(越低越好): 0 [3]
ASN滥用得分(越低越好): 0.0058 (Low) [A] 
公司滥用得分(越低越好): 0 (Very Low) [A] 
威胁级别: low [B] 
安全信息:
使用类型: hosting [A] DataCenter/WebHosting/Transit [3]
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
北京移动 221.179.155.161 移动CMI    [普通线路] 移动CMIN2  [精品线路] 
上海电信 202.96.209.133  检测不到回程路由节点的IP地址
上海联通 210.22.97.1     联通4837   [普通线路] 
上海移动 211.136.112.200 移动CMI    [普通线路] 移动CMIN2  [精品线路] 
广州电信 58.60.188.222   电信163    [普通线路] 
广州联通 210.21.196.6    联通4837   [普通线路] 
广州移动 120.196.165.24  移动CMI    [普通线路] 
成都电信 61.139.2.69     电信163    [普通线路] 
成都联通 119.6.6.6       联通4837   [普通线路] 
成都移动 211.137.96.205  移动CMI    [普通线路] 移动CMIN2  [精品线路] 
准确线路自行查看详细路由，本测试结果仅作参考
同一目标地址多个线路时，可能检测已越过汇聚层，除了第一个线路外，后续信息可能无效
---------------------回程路由--感谢fscarmen开源及PR---------------------
依次测试电信/联通/移动经过的地区及线路，核心程序来自ipip.net或nexttrace，请知悉!
广州电信 58.60.188.222
10.34 ms 	AS197540 德国 黑森 达姆施塔特 netcup.de
0.57 ms 	AS47147 德国 黑森 美茵河畔法兰克福 anexia.com
3.63 ms 	AS9002 德国 巴伐利亚 纽伦堡 retn.net
* ms 	AS9002 德国 黑森 美因河畔法兰克福 retn.net
* ms 	AS9002 德国 黑森 美茵河畔法兰克福 RETN-CT-Peer retn.net
* ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn
243.04 ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.66 ms 	AS197540 德国 黑森 达姆施塔特 netcup.de
0.84 ms 	AS47147 德国 黑森 美茵河畔法兰克福 anexia.com
0.54 ms 	AS1299 [ARELION-NET] 德国 巴伐利亚 纽伦堡 arelion.com
3.84 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
5.28 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
* ms 	AS4837 [CU169-BACKBONE] 中国 上海 chinaunicom.cn 联通
* ms 	AS4837 [CU169-BACKBONE] 中国 北京 chinaunicom.cn 联通
233.26 ms 	AS4837 [CU169-BACKBONE] 中国 北京 chinaunicom.cn
240.92 ms 	AS17816 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
264.27 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
264.21 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
3.72 ms 	AS197540 德国 黑森 达姆施塔特 netcup.de
0.69 ms 	AS47147 德国 黑森 美茵河畔法兰克福 anexia.com
55.98 ms 	AS1299 [ARELION-NET] 德国 巴伐利亚 纽伦堡 arelion.com
3.89 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
54.63 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
4.57 ms 	AS1299 [ARELION-NET] 德国 黑森 美因河畔法兰克福 Telia-CM-Cust arelion.com
4.17 ms 	AS58453 [CMI-INT] 德国 黑森 美茵河畔法兰克福 cmi.chinamobile.com 移动
201.81 ms 	AS58453 [CMI-INT] 德国 黑森 美因河畔法兰克福 cmi.chinamobile.com 移动
197.30 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
197.72 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
210.34 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
208.85 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
213.56 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 943.36 Mbps	 903.79 Mbps	 0.30	  0.0%
法兰克福	 2499.78 Mbps	 2318.30 Mbps	 3.55	  NULL
新加坡		 1101.33 Mbps	 303.41 Mbps	 167.61	  0.0%
联通WuXi	 0.88 Mbps	 2087.88 Mbps	 347.66	  0.7%
电信Zhenjiang5G	 1.12 Mbps	 1222.05 Mbps	 197.03	  NULL
移动Beijing	 939.64 Mbps	 2416.93 Mbps	 122.29	  0.0%
------------------------------------------------------------------------
 总共花费      : 6 分 12 秒
 时间          : Thu Oct  3 16:18:35 CEST 2024
------------------------------------------------------------------------

```