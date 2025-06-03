---
abbrlink: 3002159803
author: Allen
published: 2024-11-30 03:09:34
title: Hetzner EX101
tags: ['服务器']
---
独服小时计费，一个月的总费用不会超过标价，取最小值。

第一次下单会让写用途  几分钟后会邮件通知接受订单，需要重新下单同款去正式订购

预计10分钟左右会发邮件告知ip 密码 密钥

芬兰84欧一月 安装费39欧，好贵啊
```
测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.11.08
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : 13th Gen Intel(R) Core(TM) i9-13900
 CPU 核心数        : 1 物理核心, 24 总核心, 24 总线程数
 CPU 频率          : 866.154 MHz
 CPU 缓存          : L1: 960.00 KB / L2: 24.00 MB / L3: 0.00 KB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ✔ Enabled
 内存              : 327.65 MiB / 62.54 GiB
 Swap              : 0 KiB / 31.97 GiB
 硬盘空间          : 1.14 GiB / 1.69 TiB
 启动盘路径        : /dev/md3
 系统在线时间      : 0 days, 0 hour 12 min
 负载              : 1.26, 1.01, 0.60
 系统              : Debian GNU/Linux 11 (bullseye) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 5.10.0-33-amd64
 TCP加速方式       : cubic
 虚拟化架构        : Dedicated
 NAT类型           : Full Cone
 IPV4 ASN          : AS24940 Hetzner Online GmbH
 IPV4 位置         : Helsinki / Uusimaa / FI
 IPV6 ASN          : AS24940 Hetzner Online
 IPV6 位置         : Germany
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		4787 Scores
 24 线程测试(多核)得分: 		74678 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		57722.32 MB/s
 单线程写测试:		40195.69 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		288 MB/s (70.25 IOPS, 0.36s)		257 MB/s (62759 IOPS, 0.41s)
 1GB-1M Block		2.4 GB/s (2279 IOPS, 0.44s)		2.7 GB/s (2558 IOPS, 0.39s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 1.14 GB/s   (285.4k) | 1.64 GB/s    (25.6k)
Write      | 1.14 GB/s   (286.2k) | 1.65 GB/s    (25.8k)
Total      | 2.28 GB/s   (571.7k) | 3.29 GB/s    (51.4k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 1.95 GB/s     (3.8k) | 2.07 GB/s     (2.0k)
Write      | 2.05 GB/s     (4.0k) | 2.20 GB/s     (2.1k)
Total      | 4.00 GB/s     (7.8k) | 4.27 GB/s     (4.1k)
------------流媒体解锁--基于oneclickvirt/CommonMediaTests开源-----------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Netflix-----------------
[IPV4]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：芬兰
[IPV6]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：德国
----------------Youtube-----------------
[IPV4]
连接方式: Youtube Video Server
视频缓存节点地域: HEM(HEM09S01)
[IPV6]
连接方式: Youtube Video Server
视频缓存节点地域: HEM(HEM09S01)
---------------DisneyPlus---------------
[IPV4]
当前出口所在地区解锁DisneyPlus
区域：FI 区
[IPV6]
当前出口所在地区解锁DisneyPlus
区域：SE 区
解锁Netflix，Youtube，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:					Failed (Error: )
 Disney+:				No (IP Banned By Disney+ 1)
 Netflix:				Originals Only
 YouTube Premium:			Yes (Region: DE)
 Amazon Prime Video:			Yes (Region: FI)
 TVBAnywhere+:				Yes
 Spotify Registration:			No
 Instagram Licensed Audio:		No
 OneTrust Region:			FI [Uusimaa]
 iQyi Oversea Region:			INTL
 Bing Region:				FI
 YouTube CDN:				Helsinki
 Netflix Preferred CDN:			Stockholm
 ChatGPT:				Yes
 Google Gemini:				No
 Wikipedia Editability:			No
 Google Play Store:			Germany 
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
 Instagram Licensed Audio:		No
 OneTrust Region:			DE [Unknown]
 iQyi Oversea Region:			IPv6 Is Not Currently Supported
 Bing Region:				DE
 YouTube CDN:				Helsinki
 Netflix Preferred CDN:			Stockholm
 ChatGPT:				Failed (Network Connection)
 Google Gemini:				No
 Wikipedia Editability:			No
 Google Play Store:			Germany 
 Google Search CAPTCHA Free:		Yes
 Steam Currency:			IPv6 Is Not Currently Supported
 ---Forum---
 Reddit:				IPv6 Is Not Currently Supported
=======================================
---------------TikTok解锁--感谢lmc999的源脚本及fscarmen PR--------------
 Tiktok Region:		【FI】
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
欺诈得分(越低越好): 30 [1] 
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0025 (Low) [A] 
公司滥用得分(越低越好): 0.0016 (Low) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: business [8] DataCenter/WebHosting/Transit [3] hosting [0 7 9 A] hosting - high probability [C]
公司类型: hosting [0 7 A]
是否云提供商: Yes [7 D] 
是否数据中心: No [8] Yes [0 1 5 6 A C]
是否移动设备: No [5 A C] 
是否代理: No [0 1 4 5 6 7 8 9 A B C D] 
是否VPN: Yes [A] No [0 1 6 7 C D]
是否TorExit: No [1 7 D] 
是否Tor出口: No [1 7 D] 
是否网络爬虫: No [9 A B] 
是否匿名: No [1 6 7 8 D] 
是否攻击者: No [7 8 D] 
是否滥用者: No [7 8 A C D] 
是否威胁: No [7 8 C D] 
是否中继: No [0 7 8 C D] 
是否Bogon: No [7 8 A C D] 
DNS-黑名单: 314(Total_Check) 0(Clean) 6(Blacklisted) 23(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 32 [1] 
滥用得分(越低越好): 0 [3]
ASN滥用得分(越低越好): 0.0025 (Low) [A] 
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
北京移动 221.179.155.161 移动CMI    [普通线路] 移动CMIN2  [精品线路] 
上海电信 202.96.209.133  电信163    [普通线路] 
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
10.91 ms 	AS24940 德国 巴伐利亚州 纽伦堡 hetzner.com
0.74 ms 	AS24940 [DE-HETZNER] 德国 巴伐利亚州 纽伦堡 hetzner.com
0.98 ms 	AS24940 [DE-HETZNER] 德国 巴伐利亚州 贡岑豪森 hetzner.com
0.87 ms 	AS1299 [TELIANET] 美国 华盛顿哥伦比亚特区 华盛顿 arelion.com
1.78 ms 	AS1299 [ARELION-NET] 芬兰 南芬兰省 赫尔辛基 arelion.com
8.19 ms 	AS1299 [ARELION-NET] 瑞典 斯德哥尔摩省 斯德哥尔摩 arelion.com
* ms 	AS1299 [ARELION-NET] 荷兰 北荷兰省 阿姆斯特丹 arelion.com
28.53 ms 	AS1299 [ARELION-NET] 瑞典 斯德哥尔摩省 斯德哥尔摩 arelion.com
287.15 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
277.11 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
272.70 ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.80 ms 	AS24940 德国 巴伐利亚州 纽伦堡 hetzner.com
0.73 ms 	AS24940 [DE-HETZNER] 德国 巴伐利亚州 纽伦堡 hetzner.com
1.16 ms 	AS24940 [DE-HETZNER] 德国 巴伐利亚州 贡岑豪森 hetzner.com
0.82 ms 	AS1299 [TELIANET] 美国 华盛顿哥伦比亚特区 华盛顿 arelion.com
1.58 ms 	AS1299 [ARELION-NET] 瑞典 斯德哥尔摩省 斯德哥尔摩 arelion.com
8.38 ms 	AS1299 [ARELION-NET] 瑞典 斯德哥尔摩省 斯德哥尔摩 arelion.com
27.34 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
* ms 	AS4837 [CU169-BACKBONE] 德国 黑森 美因河畔法兰克福 chinaunicom.cn
200.78 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
183.16 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
196.20 ms 	AS17816 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
196.05 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
191.66 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.68 ms 	AS24940 德国 巴伐利亚州 纽伦堡 hetzner.com
0.82 ms 	AS24940 [DE-HETZNER] 德国 巴伐利亚州 纽伦堡 hetzner.com
7.19 ms 	AS24940 [DE-HETZNER] 瑞典 斯德哥尔摩省 斯德哥尔摩 hetzner.com
27.61 ms 	AS24940 [DE-HETZNER] 荷兰 北荷兰省 阿姆斯特丹 hetzner.com
33.20 ms 	AS24940 [DE-HETZNER] 德国 黑森 美因河畔法兰克福 hetzner.com
35.22 ms 	AS58453 [CMI-INT] 德国 黑森 美茵河畔法兰克福 cmi.chinamobile.com 移动
230.13 ms 	AS58453 [CMI-INT] 中国 广东 广州 cmi.chinamobile.com 移动
230.00 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
231.16 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
243.53 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
245.34 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
236.40 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
245.10 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 794.79 Mbps	 799.50 Mbps	 0.72	  0.0%
法兰克福	 946.20 Mbps	 950.60 Mbps	 30.84	  0.0%


```