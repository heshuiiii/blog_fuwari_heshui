---
abbrlink: 3900921135
author: Allen
published: 2024-09-20 20:23:34
title: Netcup 4欧小鸡 / VPS mikro G11s 3M 测试
tags: ['服务器']
---
## 融合怪

```curl -L https://gitlab.com/spiritysdx/za/-/raw/main/ecs.sh -o ecs.sh && chmod +x ecs.sh && bash ecs.sh```
```
测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.08.29
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : QEMU Virtual CPU version 2.5+
 CPU 核心数        : 4
 CPU 频率          : 2294.582 MHz
 CPU 缓存          : L1: 128.00 KB / L2: 16.00 MB / L3: 64.00 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ❌ Disabled
 内存              : 1.50 GiB / 3.80 GiB
 Swap              : 491.12 MiB / 8.00 GiB
 硬盘空间          : 59.88 GiB / 117.01 GiB
 启动盘路径        : /dev/vda3
 系统在线时间      : 1 days, 0 hour 16 min
 负载              : 0.60, 0.19, 0.06
 系统              : Debian GNU/Linux 12 (bookworm) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 6.1.0-25-amd64
 TCP加速方式       : bbr
 虚拟化架构        : KVM
 NAT类型           : Port Restricted Cone
 IPV4 ASN          : AS197540 netcup GmbH
 IPV4 位置         : Nürnberg / Bavaria / DE
 IPV6 ASN          : AS197540 netcup
 IPV6 位置         : Nuremberg / Bavaria / Germany
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		860 Scores
 4 线程测试(多核)得分: 		1990 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		17640.14 MB/s
 单线程写测试:		14182.41 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		31.3 MB/s (7646 IOPS, 3.35s)		48.6 MB/s (11873 IOPS, 2.16s)
 1GB-1M Block		1.2 GB/s (1165 IOPS, 0.86s)		1.4 GB/s (1312 IOPS, 0.76s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 86.66 MB/s   (21.6k) | 1.29 GB/s    (20.2k)
Write      | 86.89 MB/s   (21.7k) | 1.30 GB/s    (20.3k)
Total      | 173.56 MB/s  (43.3k) | 2.60 GB/s    (40.6k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 1.83 GB/s     (3.5k) | 1.47 GB/s     (1.4k)
Write      | 1.92 GB/s     (3.7k) | 1.57 GB/s     (1.5k)
Total      | 3.75 GB/s     (7.3k) | 3.05 GB/s     (2.9k)
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
 Spotify Registration:			Yes (Region: DE)
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
 Spotify Registration:			Yes (Region: DE)
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
欺诈得分(越低越好): 65 [E] 26 [1]
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.004 (Low) [A] 
公司滥用得分(越低越好): 0.0169 (Elevated) [A] 
威胁级别: low [9 B]
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2] 无记录数: 94 [2]  
安全信息:
使用类型: DataCenter/WebHosting/Transit [3] business [8] hosting [0 7 9 A] hosting - high probability [C]
公司类型: hosting [0 7 A] 
是否云提供商: Yes [7 D] 
是否数据中心: Yes [0 1 5 6 A C] No [8]
是否移动设备: Yes [E] No [5 A C]
是否代理: No [0 1 4 5 6 7 8 9 A B C D] Yes [E]
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
DNS-黑名单: 313(Total_Check) 0(Clean) 6(Blacklisted) 5(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 0 [1] 
滥用得分(越低越好): 0 [3]
ASN滥用得分(越低越好): 0.004 (Low) [A] 
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
 	
广州联通 210.21.196.6
1.37 ms 	AS197540 德国 巴伐利亚州 纽伦堡 netcup.de
0.85 ms 	AS47147 德国 黑森 美茵河畔法兰克福 anexia.com
0.66 ms 	AS1299 [TELIANET] 德国 巴伐利亚 纽伦堡 arelion.com
3.82 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
3.87 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
265.97 ms 	AS4837 [CU169-BACKBONE] 德国 黑森 美茵河畔法兰克福 chinaunicom.cn 联通
245.63 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
247.60 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
244.65 ms 	AS17816 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
255.91 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
248.96 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
11.74 ms 	AS197540 德国 巴伐利亚州 纽伦堡 netcup.de
0.81 ms 	AS47147 德国 黑森 美茵河畔法兰克福 anexia.com
0.57 ms 	AS1299 [TELIANET] 德国 巴伐利亚 纽伦堡 arelion.com
3.88 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
6.51 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
4.68 ms 	AS1299 [ARELION-NET] 德国 黑森 美因河畔法兰克福 Telia-CM-Cust arelion.com
4.56 ms 	AS58453 [CMI-INT] 德国 黑森 美茵河畔法兰克福 cmi.chinamobile.com 移动
200.08 ms 	AS58453 [CMI-INT] 德国 黑森 美因河畔法兰克福 cmi.chinamobile.com 移动
196.87 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
205.12 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
208.81 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
205.41 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
204.50 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
215.33 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 997.97 Mbps	 933.10 Mbps	 0.30	  0.0%
法兰克福	 1000.59 Mbps	 958.06 Mbps	 4.37	  0.0%
洛杉矶		 1103.86 Mbps	 1012.86 Mbps	 140.45	  0.0%
联通上海5G	 302.42 Mbps	 1029.42 Mbps	 272.06	  0.0%
联通WuXi	 748.89 Mbps	 914.38 Mbps	 316.44	  1.3%
电信Zhenjiang5G	 449.71 Mbps	 767.26 Mbps	 192.16	  NULL
------------------------------------------------------------------------
 总共花费      : 6 分 13 秒
 时间          : Gum Way 20  8:18:12 carra CEST 2024
------------------------------------------------------------------------

```
## 解锁

```bash <(curl -L -s media.ispvps.com) ```
```
 ** 测试时间: 2024年 09月 20日 星期五 20:21:26 CEST

 ** 正在测试IPv4解锁情况 
--------------------------------
 ** 您的网络为: netcup (37.120.*.*) 


============[ Multination ]============
 Dazn:                  原生解锁        Yes (Region: DE)
 TikTok:                原生解锁        Yes (Region: DE)
 Disney+:                               No
 Netflix:               原生解锁        Originals Only (Region: DE)
 YouTube Premium:       原生解锁        Yes (Region: DE)
 Amazon Prime Video:    原生解锁        Yes (Region: DE)
 TVBAnywhere+:          原生解锁        Yes
 iQyi Oversea Region:   原生解锁        DE
 YouTube CDN:                           ANEXIAAT in Vienna 
 Netflix Preferred CDN:                 Associated with [ANEXIA Internetdienstleistungs] in [Vienna ]
 Spotify Registration:  原生解锁        Yes (Region: DE)
 Steam Currency:                        EUR
 ChatGPT:               原生解锁        Yes (Region: DE)
 Google Gemini:                         No
 Bing Region:                           DE
 Wikipedia Editability:                 Yes
 Instagram Licensed Audio:              Failed
 ---Forum---
 Reddit:                                No
=======================================
==============[ Taiwan ]===============
 KKTV:                                  No
 LiTV:                                  Failed
 MyVideo:                               No
 4GTV.TV:                               Failed
 LineTV.TW:                             No
 Hami Video:                            No
 CatchPlay+:                            No
 HBO GO Asia:                           No
 Bahamut Anime:                         No
 SonyLiv:                               Failed (Network Connection)
 Bilibili Taiwan Only:                  No
=======================================
=============[ Hong Kong ]=============
 Now E:                                 No
 Viu.com:                               No
 Viu.TV:                                No
 MyTVSuper:                             No
 HBO GO Asia:                           No
 SonyLiv:                               Failed (Network Connection)
 BiliBili Hongkong/Macau/Taiwan:        No
 Bahamut Anime:                         No
=======================================
===============[ Japan ]===============
 DMM:                                   Unsupported
 DMM TV:                                No
 Abema.TV:                              No
 Niconico:                              Yes
 Telasa:                                No
 U-NEXT:                                No
 Hulu Japan:                            Yes
 TVer:                                  Failed (Network Connection)
 Lemino:                                No
 WOWOW:                                 No
 VideoMarket:                           No
 D Anime Store:                         No
 FOD(Fuji TV):                          No
 Radiko:                                No
 Karaoke@DAM:                           No
 J:com On Demand:                       No
 ---Game---
 Kancolle Japan:                        No
 Pretty Derby Japan:                    Yes
 Konosuba Fantastic Days:               No
 Princess Connect Re:Dive Japan:        Yes
 Project Sekai: Colorful Stage:         No
 ---Music---
 Mora:                                  No
 music.jp:                              No
 ---Forum---
 EroGameSpace:                          No
=======================================
===========[ North America ]===========
 FOX:                                   No
 Hulu:                                  No
 NFL+:                                  Yes
 ESPN+:[Sponsored by Jam]               No
 MGM+:                                  Failed (Network Connection)
 MGM+:                                  Failed
 Starz:                                 No
 Philo:                                 No
 FXNOW:                                 No
 TLC GO:                                No
 HBO Max:                               Yes
 Shudder:                               Yes
 BritBox:                               Yes
 Crackle:                               Failed
 CW TV:                                 Failed (Unexpected Result: 451)
 A&E TV:                                No
 NBA TV:                                Yes
 NBC TV:                                No
 Fubo TV:                               No
 Tubi TV:                               No
/dev/fd/63: 行 4033: MediaUnlockTest_MathsSpot: 未找到命令
/dev/fd/63: 行 2555: gen_uuid: 未找到命令
 Sling TV:                              Yes
 Pluto TV:                              Yes
 Acorn TV:                              Yes
 SHOWTIME:                              Yes
 encoreTVB:                             No
 Discovery+:                            Yes (Region: DE)
 Paramount+:                            Yes
 Peacock TV:                            No
 Popcornflix:                           Failed (Network Connection)
 Crunchyroll:                           No
 Directv Stream:                        No
 KOCOWA:                                Yes
 SonyLiv:                               Failed (Network Connection)
 AMC+:                                  No
 ---CA---
 HotStar:                               No
 CBC Gem:                               No
 Crave:                                 Yes
=======================================
===========[ South America ]===========
 HBO Max:                               Yes
 DirecTV Go:                            Yes (Region: REGISTRARSE)
 Paramount+:                            Yes
=======================================
===============[ Europe ]==============
/dev/fd/63: 行 2555: gen_uuid: 未找到命令
 Rakuten TV:                            Yes
 SkyShowTime:                           No
 BritBox:                               Yes
 HBO Max:                               Yes
 Setanta Sports:                        No
 SonyLiv:                               Failed (Network Connection)
 Discovery+:                            Yes (Region: DE)
 Paramount+:                            Yes
 Megogo TV:                             Failed
 ---GB---
 HotStar:                               No
 Sky Go:                                Yes
 ITV Hub:                               No
 Channel 4:                             No
 Channel 5:                             No
 BBC iPLAYER:                           No
 Acorn TV:                              Yes
 Shudder:                               Yes
 ---FR---
 Canal+:                                Yes
 Molotov:                               No
 ---DE---
 Joyn:                                  Yes
 SKY DE:                                Yes
 ZDF:                                   Yes
 ---NL---
 NLZIET:                                Failed
 videoland:                             No
 NPO Start Plus:                        No
 ---ES---
 Movistar+:                             No
 ---IT---
 Rai Play:                              Yes
 ---CH---
 SKY CH:                                No
 ---RU---
 Amediateka:                            Yes
=======================================
==============[ Oceania ]==============
 NBA TV:                                Yes
 Acorn TV:                              Yes
 SHOWTIME:                              Yes
 BritBox:                               Yes
 Paramount+:                            Yes
 SonyLiv:                               Failed (Network Connection)
 ---AU---
 Stan:                                  Yes
 Binge:                                 No
 Docplay:                               No
 7plus:                                 No
 Channel 9:                             Yes
 Channel 10:                            No
 ABC iView:                             No
 Kayo Sports:                           No
 Optus Sports:                          No
 SBS on Demand:                         No
 ---NZ---
 Neon TV:                               Yes
 SkyGo NZ:                              No
 ThreeNow:                              No
 Maori TV:                              Yes
=======================================
==============[ Korean ]===============
 Wavve:                                 No
 Tving:                                 No
 WATCHA:                                Yes
 Coupang Play:                          No
 Naver TV:                              No
 SPOTV NOW:                             No
 Afreeca TV:                            Yes
 KBS Domestic:                          Failed (Network Connection)
=======================================
==========[ SouthEastAsia ]============
 Viu.com:                               No
 HotStar:                               No
 HBO GO Asia:                           No
 SonyLiv:                               Failed (Network Connection)
 B-Global SouthEastAsia:                No
 ---SG---
 MeWatch:                               Yes
 ---TH---
 AIS Play:                              No
 trueID:                                No
 B-Global Thailand Only:                No
 ---ID---
 B-Global Indonesia Only:               No
 ---VN---
 K+:                                    Yes
 B-Global Việt Nam Only:                No
=======================================
===============[ India ]===============
 HotStar:                               No
 Zee5:                                  Yes (Region: DE)
 SonyLiv:                               Failed (Network Connection)
 Jio Cinema:                            No
 MX Player:                             No
 NBA TV:                                Yes
=======================================


 ** 正在测试IPv6解锁情况 
--------------------------------
 ** 您的网络为: netcup (2a03:4000:6:*:*) 


============[ Multination ]============
 Dazn:                                  Failed (Network Connection)
 TikTok:                原生解锁        Yes (Region: DE)
 Disney+:                               No
 Netflix:               原生解锁        Originals Only (Region: DE)
 YouTube Premium:       原生解锁        Yes (Region: DE)
 Amazon Prime Video:                    Unsupported
 TVBAnywhere+:                          Failed (Network Connection)
 iQyi Oversea Region:                   Failed
 YouTube CDN:                           ANEXIAAT in Vienna 
 Netflix Preferred CDN:                 Associated with [ANEXIA Internetdienstleistungs] in [Vienna ]
 Spotify Registration:  原生解锁        Yes (Region: DE)
 Steam Currency:                        Failed (Network Connection)
 ChatGPT:                               Failed
 Google Gemini:                         No
 Bing Region:                           DE
 Wikipedia Editability:                 Yes
 Instagram Licensed Audio:              Failed
 ---Forum---
 Reddit:                                Failed (Network Connection)
=======================================
==============[ Taiwan ]===============
 KKTV:                                  No
 LiTV:                                  Failed (Network Connection)
 MyVideo:                               Yes
 4GTV.TV:                               Failed (Network Connection)
 LineTV.TW:                             Failed (Network Connection)
 Hami Video:                            Failed (Network Connection)
 CatchPlay+:                            Failed
 HBO GO Asia:                           Failed (Network Connection)
 Bahamut Anime:                         Failed (Network Connection 1)
 SonyLiv:                               Failed (Network Connection)
 Bilibili Taiwan Only:                  Failed (Network Connection)
=======================================
=============[ Hong Kong ]=============
 Now E:                                 Failed (Network Connection)
 Viu.com:                               Failed
 Viu.TV:                                Failed (Network Connection)
 MyTVSuper:                             No
 HBO GO Asia:                           Failed (Network Connection)
 SonyLiv:                               Failed (Network Connection)
 BiliBili Hongkong/Macau/Taiwan:        Failed (Network Connection)
 Bahamut Anime:                         Failed (Network Connection 1)
=======================================
===============[ Japan ]===============
 DMM:                                   Unsupported
 DMM TV:                                No
 Abema.TV:                              Failed (Network Connection)
 Niconico:                              Failed (Network Connection)
 Telasa:                                No
 U-NEXT:                                No
 Hulu Japan:                            Yes
 TVer:                                  Failed (Network Connection)
 Lemino:                                No
 WOWOW:                                 Failed (Network Connection)
 VideoMarket:                           Failed
 D Anime Store:                         No
 FOD(Fuji TV):                          No
 Radiko:                                Unsupported
 Karaoke@DAM:                           Failed (Network Connection)
 J:com On Demand:                       No
 ---Game---
 Kancolle Japan:                        Failed (Network Connection)
 Pretty Derby Japan:                    Yes
 Konosuba Fantastic Days:               Failed (Network Connection)
 Princess Connect Re:Dive Japan:        Failed (Network Connection)
 Project Sekai: Colorful Stage:         Failed (Network Connection)
 ---Music---
 Mora:                                  Failed (Network Connection)
 music.jp:                              No
 ---Forum---
 EroGameSpace:                          No
=======================================
===========[ North America ]===========
 FOX:                                   No
 Hulu:                                  No
 NFL+:                                  IPv6 Not Support
 ESPN+:[Sponsored by Jam]               No
 MGM+:                                  Failed (Network Connection)
 MGM+:                                  Failed
 Starz:                                 Failed (Network Connection)
 Philo:                                 IPv6 Not Support
 FXNOW:                                 IPv6 Not Support
 TLC GO:                                IPv6 Not Support
 HBO Max:                               Yes
 Shudder:                               Yes
 BritBox:                               Yes
 Crackle:                               Failed
 CW TV:                                 Failed (Unexpected Result: 451)
 A&E TV:                                IPv6 Not Support
 NBA TV:                                Yes
 NBC TV:                                No
 Fubo TV:                               IPv6 Not Support
 Tubi TV:                               No
/dev/fd/63: 行 4033: MediaUnlockTest_MathsSpot: 未找到命令
 Sling TV:                              Yes
 Pluto TV:                              Yes
 Acorn TV:                              Failed (Network Connection)
 SHOWTIME:                              Failed (Network Connection)
 encoreTVB:                             Failed (Network Connection)
 Discovery+:                            Failed (Network Connection)
 Paramount+:                            Yes
 Peacock TV:                            No
 Popcornflix:                           IPv6 Not Support
 Crunchyroll:                           IPv6 Not Support
 Directv Stream:                        No
 KOCOWA:                                IPv6 Not Support
 SonyLiv:                               Failed (Network Connection)
 AMC+:                                  No
 ---CA---
 HotStar:                               No
 CBC Gem:                               Failed (Network Connection)
 Crave:                                 Failed (Network Connection)
=======================================
===========[ South America ]===========
 HBO Max:                               Yes
 DirecTV Go:                            Failed (Network Connection)
 Paramount+:                            Yes
=======================================
===============[ Europe ]==============
 Rakuten TV:                            Failed (Network Connection)
 SkyShowTime:                           No
 BritBox:                               Yes
 HBO Max:                               Yes
 Setanta Sports:                        IPv6 Not Support
 SonyLiv:                               Failed (Network Connection)
 Discovery+:                            Failed (Network Connection)
 Paramount+:                            Yes
 Megogo TV:                             Failed (Network Connection)
 ---GB---
 HotStar:                               No
 Sky Go:                                Failed (Network Connection)
 ITV Hub:                               Failed (Network Connection)
 Channel 4:                             Failed (Network Connection)
 Channel 5:                             IPv6 Not Support
 BBC iPLAYER:                           Failed
 Acorn TV:                              Failed (Network Connection)
 Shudder:                               Yes
 ---FR---
 Canal+:                                Failed (Network Connection)
 Molotov:                               No
 ---DE---
 Joyn:                                  Failed (Network Connection)
 SKY DE:                                Failed (Network Connection)
 ZDF:                                   Failed (Network Connection)
 ---NL---
 NLZIET:                                Failed
 videoland:                             No
 NPO Start Plus:                        No
 ---ES---
 Movistar+:                             Failed
 ---IT---
 Rai Play:                              Failed (Network Connection)
 ---CH---
 SKY CH:                                Failed (Network Connection)
 ---RU---
 Amediateka:                            Failed (Network Connection)
=======================================
==============[ Oceania ]==============
 NBA TV:                                Yes
 Acorn TV:                              Failed (Network Connection)
 SHOWTIME:                              Failed (Network Connection)
 BritBox:                               Yes
 Paramount+:                            Yes
 SonyLiv:                               Failed (Network Connection)
 ---AU---
 Stan:                                  Yes
 Binge:                                 No
 Docplay:                               Yes
 7plus:                                 No
 Channel 9:                             Yes
 Channel 10:                            Failed (Network Connection)
 ABC iView:                             Yes
 Kayo Sports:                           Yes
 Optus Sports:                          No
 SBS on Demand:                         Failed (Network Connection)
 ---NZ---
 Neon TV:                               Yes
 SkyGo NZ:                              Failed (Network Connection)
 ThreeNow:                              Failed (Network Connection)
 Maori TV:                              Failed (Network Connection)
=======================================
==============[ Korean ]===============
 Wavve:                                 IPv6 Not Support
 Tving:                                 IPv6 Not Support
 WATCHA:                                Failed (Network Connection)
 Coupang Play:                          Yes
 Naver TV:                              Yes
 SPOTV NOW:                             Failed (Network Connection)
 Afreeca TV:                            IPv6 Not Support
 KBS Domestic:                          IPv6 Not Support
=======================================
==========[ SouthEastAsia ]============
 Viu.com:                               Failed
 HotStar:                               No
 HBO GO Asia:                           Failed (Network Connection)
 SonyLiv:                               Failed (Network Connection)
 B-Global SouthEastAsia:                IPv6 Not Support
 ---SG---
 MeWatch:                               IPv6 Not Supported
 ---TH---
 AIS Play:                              No
 trueID:                                Failed (Network Connection)
 B-Global Thailand Only:                IPv6 Not Support
 ---ID---
 B-Global Indonesia Only:               IPv6 Not Support
 ---VN---
 K+:                                    IPv6 Not Supported
 TV360:                                 IPv6 Not Supported
 B-Global Việt Nam Only:                IPv6 Not Support
=======================================
===============[ India ]===============
 HotStar:                               No
 Zee5:                                  Yes (Region: DE)
 SonyLiv:                               Failed (Network Connection)
 Jio Cinema:                            No
 MX Player:                             Failed
 NBA TV:                                Yes
=======================================
本次测试已结束，感谢使用此脚本 
检测脚本当天运行次数: 28; 共计运行次数: 130330 

```









