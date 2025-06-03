---
abbrlink: 2676121238
author: Allen
published: 2024-11-30 03:09:02
title: Netcup VPS1000 VIE BF24
tags: ['服务器']
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
 CPU 缓存          : L1: 256.00 KB / L2: 2.00 MB / L3: 128.00 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ❌ Disabled
 内存              : 170.08 MiB / 7.72 GiB
 Swap              : [ no swap partition or swap file detected ]
 硬盘空间          : 5.71 GiB / 14.66 GiB
 启动盘路径        : /dev/vda3
 系统在线时间      : 0 days, 0 hour 4 min
 负载              : 0.11, 0.03, 0.01
 系统              : Debian GNU/Linux 11 (bullseye) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 5.10.0-33-amd64
 TCP加速方式       : cubic
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS42473 ANEXIA Internetdienstleistungs GmbH
 IPV4 位置         : Vienna / Vienna / AT
 IPV6 ASN          : AS197540 netcup
 IPV6 位置         : Vienna / Vienna / Austria
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		4023 Scores
 4 线程测试(多核)得分: 		15947 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		42472.29 MB/s
 单线程写测试:		23111.26 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		32.4 MB/s (7903 IOPS, 3.24s)		45.8 MB/s (11188 IOPS, 2.29s)
 1GB-1M Block		542 MB/s (517 IOPS, 1.94s)		2.8 GB/s (2687 IOPS, 0.37s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 182.40 MB/s  (45.6k) | 404.96 MB/s   (6.3k)
Write      | 182.88 MB/s  (45.7k) | 407.09 MB/s   (6.3k)
Total      | 365.29 MB/s  (91.3k) | 812.06 MB/s  (12.6k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 479.43 MB/s    (936) | 629.71 MB/s    (614)
Write      | 504.91 MB/s    (986) | 671.65 MB/s    (655)
Total      | 984.34 MB/s   (1.9k) | 1.30 GB/s     (1.2k)
------------流媒体解锁--基于oneclickvirt/CommonMediaTests开源-----------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Netflix-----------------
[IPV4]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：奥地利
[IPV6]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：德国
----------------Youtube-----------------
[IPV4]
连接方式: Youtube Video Server
视频缓存节点地域: 德国法兰克福(FRA15S37)
Youtube识别地域: 奥地利(AT)
[IPV6]
连接方式: Youtube Video Server
视频缓存节点地域: 德国法兰克福(FRA15S37)
---------------DisneyPlus---------------
[IPV4]
当前出口所在地区解锁DisneyPlus
区域：AT 区
[IPV6]
当前出口所在地区解锁DisneyPlus
区域：DE 区
解锁Netflix，Youtube，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:					Yes (Region: AT)
 Disney+:				Yes (Region: AT)
 Netflix:				Yes (Region: AT)
 YouTube Premium:			Yes (Region: AT)
 Amazon Prime Video:			Yes (Region: AT)
 TVBAnywhere+:				Yes
 Spotify Registration:			No
 Instagram Licensed Audio:		No
 OneTrust Region:			AT [Unknown]
 iQyi Oversea Region:			INTL
 Bing Region:				AT
 YouTube CDN:				Frankfurt
 Netflix Preferred CDN:			[ANEXIA Internetdienstleistungs] in [Vienna]
 ChatGPT:				Yes
 Google Gemini:				No
 Wikipedia Editability:			Yes
 Google Play Store:			Austria 
 Google Search CAPTCHA Free:		Yes
 Steam Currency:			EUR
 ---Forum---
 Reddit:				Yes
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
 Instagram Licensed Audio:		No
 OneTrust Region:			AT [Vienna]
 iQyi Oversea Region:			IPv6 Is Not Currently Supported
 Bing Region:				AT
 YouTube CDN:				Frankfurt
 Netflix Preferred CDN:			[ANEXIA Internetdienstleistungs] in [Vienna]
 ChatGPT:				Failed (Network Connection)
 Google Gemini:				No
 Wikipedia Editability:			Yes
 Google Play Store:			Austria 
 Google Search CAPTCHA Free:		Yes
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
信任得分(越高越好): 33 [8]
VPN得分(越低越好): 60 [8] 
代理得分(越低越好): 80 [8] 
社区投票-无害: 0 [2] 
社区投票-恶意: 0 [2] 
威胁得分(越低越好): 60 [8] 
欺诈得分(越低越好): 67 [1] 
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0006 (Low) [A] 
公司滥用得分(越低越好): 0.0004 (Very Low) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: hosting - moderate probability [C] DataCenter/WebHosting/Transit [3] consumer [9] hosting [0 7 A]
公司类型: hosting [0 7 A] 
是否云提供商: Yes [7 D] 
是否数据中心: No [8 C] Yes [0 1 5 6 A]
是否移动设备: Yes [5] No [A C]
是否代理: No [0 1 4 5 6 7 8 9 A B C D] 
是否VPN: No [0 1 6 7 C D] Yes [A]
是否Tor: No [0 1 3 6 7 8 A B C D] 
是否Tor出口: No [1 7 D] 
是否网络爬虫: No [9 A B] 
是否匿名: No [1 6 7 8 D] 
是否攻击者: No [7 8 D] 
是否滥用者: No [7 8 A C D] 
是否威胁: No [7 8 C D] 
是否中继: No [0 7 8 C D] 
是否Bogon: No [7 8 A C D] 
DNS-黑名单: 314(Total_Check) 0(Clean) 4(Blacklisted) 9(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 0 [1] 
滥用得分(越低越好): 0 [3]
ASN滥用得分(越低越好): 0.0054 (Low) [A] 
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
0.49 ms 	AS42473 奥地利 anexia-it.com
0.68 ms 	AS2914 [EU-NTTEUROPE] 奥地利 维也纳 维也纳 gin.ntt.net
0.59 ms 	AS2914 [NTT-BACKBONE] 奥地利 维也纳州 维也纳 gin.ntt.net
12.00 ms 	AS2914 [NTT-BACKBONE] 德国 黑森 美因河畔法兰克福 gin.ntt.net
18.52 ms 	AS2914 [NTT-BACKBONE] 德国 黑森 美因河畔法兰克福 gin.ntt.net
14.83 ms 	AS4134 德国 www.chinatelecom.com.cn
196.57 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
194.24 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
* ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
* ms 	AS134774 [CHINANET-GD] 中国 广东 深圳 chinatelecom.cn 电信
201.29 ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
3.39 ms 	AS42473 奥地利 anexia-it.com
0.78 ms 	AS47147 [ANX-NET] 奥地利 维也纳 维也纳 anexia.com
0.79 ms 	AS1299 [ARELION-NET] 奥地利 维也纳 维也纳 arelion.com
1.21 ms 	AS1299 [ARELION-NET] 奥地利 维也纳 维也纳 arelion.com
12.56 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
14.26 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
234.22 ms 	AS4837 [CU169-BACKBONE] 中国 上海 chinaunicom.cn 联通
225.70 ms 	AS4837 [CU169-BACKBONE] 中国 北京 chinaunicom.cn 联通
225.07 ms 	AS4837 [CU169-BACKBONE] 中国 北京 chinaunicom.cn
275.60 ms 	AS17816 [UNICOM-GD] 中国 广东 广州 chinaunicom.cn
276.98 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
253.80 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.39 ms 	AS42473 奥地利 anexia-it.com
0.41 ms 	AS2914 [EU-NTTEUROPE] 奥地利 维也纳 维也纳 gin.ntt.net
1.23 ms 	AS2914 [NTT-BACKBONE] 奥地利 维也纳州 维也纳 gin.ntt.net
151.68 ms 	AS2914 [NTT-BACKBONE] 新加坡 gin.ntt.net
159.47 ms 	AS2914 [NTT-GIN] 新加坡 gin.ntt.net
206.46 ms 	AS58453 [CMI-INT] 中国 广东 广州 cmi.chinamobile.com 移动
208.32 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
205.76 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
210.60 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
206.48 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 921.99 Mbps	 854.76 Mbps	 0.45	  0.0%
法兰克福	 2520.10 Mbps	 1762.98 Mbps	 12.16	  0.0%
洛杉矶		 562.19 Mbps	 900.51 Mbps	 154.14	  NULL
联通上海5G	 491.19 Mbps	 2257.67 Mbps	 278.07	  0.0%
联通成都	 526.11 Mbps	 0.49 Mbps	 271.80	  NULL
电信Suzhou5G	 1.52 Mbps	 1083.08 Mbps	 259.21	  NULL
电信Zhenjiang5G	 225.06 Mbps	 49.27 Mbps	 237.23	  NULL
移动Fujian	 0.32 Mbps	 1365.24 Mbps	 233.02	  NULL
------------------------------------------------------------------------
 总共花费      : 7 分 16 秒
 时间          : Tue Nov 26 17:36:20 CET 2024
------------------------------------------------------------------------

```