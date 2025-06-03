---
abbrlink: 716815093
author: Allen
published: 2024-11-30 03:13:22
title: Linveo AMD KVM VPS 4GB - Ohio
tags: ['服务器']
---
```
测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.11.08
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : AMD Ryzen 9 9950X 16-Core Processor
 CPU 核心数        : 4
 CPU 频率          : 4291.920 MHz
 CPU 缓存          : L1: 320.00 KB / L2: 4.00 MB / L3: 256.00 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ✔ Enabled
 内存              : 300.25 MiB / 3.80 GiB
 Swap              : [ no swap partition or swap file detected ]
 硬盘空间          : 2.41 GiB / 124.87 GiB
 启动盘路径        : /dev/vda3
 系统在线时间      : 0 days, 0 hour 4 min
 负载              : 0.22, 0.16, 0.08
 系统              : Debian GNU/Linux 11 (bullseye) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 5.10.0-20-amd64
 TCP加速方式       : cubic
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS62564 LINVEO, LLC
 IPV4 位置         : Columbus / Ohio / US
 IPV6 ASN          : AS62564 Linveo-llc
 IPV6 位置         : United States
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		6756 Scores
 4 线程测试(多核)得分: 		25888 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		99229.88 MB/s
 单线程写测试:		37971.19 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		10.4 MB/s (2535 IOPS, 10.10s)		5.2 MB/s (1279 IOPS, 20.02s)
 1GB-1M Block		283 MB/s (270 IOPS, 3.70s)		317 MB/s (302 IOPS, 3.30s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 58.66 MB/s   (14.6k) | 226.05 MB/s   (3.5k)
Write      | 58.76 MB/s   (14.6k) | 227.24 MB/s   (3.5k)
Total      | 117.42 MB/s  (29.3k) | 453.29 MB/s   (7.0k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 573.68 MB/s   (1.1k) | 648.42 MB/s    (633)
Write      | 604.16 MB/s   (1.1k) | 691.60 MB/s    (675)
Total      | 1.17 GB/s     (2.3k) | 1.34 GB/s     (1.3k)
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
视频缓存节点地域: ORD(ORD37S40)
[IPV6]
连接方式: Youtube Video Server
视频缓存节点地域: ORD(ORD37S40)
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
 Dazn:					Failed (Error: )
 Disney+:				No (IP Banned By Disney+ 1)
 Netflix:				Originals Only
 YouTube Premium:			Yes (Region: US)
 Amazon Prime Video:			Yes (Region: US)
 TVBAnywhere+:				Yes
 Spotify Registration:			No
 Instagram Licensed Audio:		Yes
 OneTrust Region:			US [Ohio]
 iQyi Oversea Region:			US
 Bing Region:				US
 YouTube CDN:				Amsterdam
 Netflix Preferred CDN:			Chicago, IL
 ChatGPT:				Yes
 Google Gemini:				Yes (Region: USA)
 Wikipedia Editability:			Yes
 Google Play Store:			United States 
 Google Search CAPTCHA Free:		Yes
 Steam Currency:			USD
 ---Forum---
 Reddit:				No
=======================================
 以下为IPV6网络测试，若无IPV6网络则无输出
============[ Multination ]============
 Dazn:					IPv6 Is Not Currently Supported
 Disney+:				IPv6 Is Not Currently Supported
 Netflix:				Yes (Region: )
 YouTube Premium:			Yes (Region: US)
 Amazon Prime Video:			IPv6 Is Not Currently Supported
 TVBAnywhere+:				IPv6 Is Not Currently Supported
 Spotify Registration:			No
 Instagram Licensed Audio:		Failed (NETWORK ERROR)
 OneTrust Region:			US [Unknown]
 iQyi Oversea Region:			IPv6 Is Not Currently Supported
 Bing Region:				US
 YouTube CDN:				Chicago, IL
 Netflix Preferred CDN:			Chicago, IL
 ChatGPT:				Failed (Network Connection)
 Google Gemini:				Yes (Region: USA)
 Wikipedia Editability:			Yes
 Google Play Store:			United States 
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
欺诈得分(越低越好): 13 [1] 
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0078 (Low) [A] 
公司滥用得分(越低越好): 0.0052 (Low) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: DataCenter/WebHosting/Transit [3] hosting [0 7 A] business [8] corporate [9] hosting - high probability [C]
公司类型: hosting [0 7] isp [A]
是否云提供商: Yes [7 D] 
是否数据中心: No [5 6 8] Yes [0 1 A C]
是否移动设备: No [5 A C] 
是否代理: No [0 1 4 5 6 7 8 9 A B C D] 
是否VPN: No [0 1 6 7 A C D] 
是否TorExit: No [1 7 D] 
是否Tor出口: No [1 7 D] 
是否网络爬虫: No [9 A B] 
是否匿名: No [1 6 7 8 D] 
是否攻击者: No [7 8 D] 
是否滥用者: No [7 8 A C D] 
是否威胁: No [7 8 C D] 
是否中继: No [0 7 8 C D] 
是否Bogon: No [7 8 A C D] 
DNS-黑名单: 314(Total_Check) 0(Clean) 6(Blacklisted) 14(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 0 [1] 
滥用得分(越低越好): 0 [3]
ASN滥用得分(越低越好): 0.0078 (Low) [A] 
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
Sina      ✘     ✘     ✘     ✘     ✘     ✘    
----------------三网回程--基于oneclickvirt/backtrace开源----------------
北京电信 219.141.140.10  检测不到回程路由节点的IP地址
北京联通 202.106.195.68  联通4837   [普通线路] 
北京移动 221.179.155.161 移动CMI    [普通线路] 
上海电信 202.96.209.133  检测不到回程路由节点的IP地址
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
0.34 ms 	AS834 美国 纽约州 纽约 ipxo.com
0.95 ms 	AS174 美国 俄亥俄州 哥伦布 cogentco.com
1.50 ms 	AS174 [COGENT-BONE] 美国 俄亥俄州 哥伦布 cogentco.com
4.09 ms 	AS174 [COGENT-BONE] 美国 肯塔基州 希伯伦 cogentco.com
6.33 ms 	AS174 [COGENT-BONE] 美国 印第安纳州 印第安纳波利斯 cogentco.com
11.64 ms 	AS174 [COGENT-BONE] 美国 伊利诺伊州 芝加哥 cogentco.com
20.02 ms 	AS174 [COGENT-BONE] 美国 内布拉斯加 奥马哈 cogentco.com
30.17 ms 	AS174 [COGENT-BONE] 美国 科罗拉多 丹佛 cogentco.com
39.56 ms 	AS174 [COGENT-BONE] 美国 犹他 盐湖城 cogentco.com
53.81 ms 	AS174 [COGENT-BONE] 美国 加利福尼亚 洛杉矶 cogentco.com
55.39 ms 	AS174 [COGENT-BONE] 美国 加利福尼亚 圣何塞 cogentco.com
224.20 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
267.18 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn
283.86 ms 	AS4134 [APNIC-AP] 中国 广东 深圳 www.chinatelecom.com.cn 电信
222.56 ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.25 ms 	AS834 美国 纽约州 纽约 ipxo.com
0.91 ms 	AS174 美国 俄亥俄州 哥伦布 cogentco.com
1.60 ms 	AS174 [COGENT-BONE] 美国 俄亥俄州 哥伦布 cogentco.com
4.31 ms 	AS174 [COGENT-BONE] 美国 肯塔基州 希伯伦 cogentco.com
5.96 ms 	AS174 [COGENT-BONE] 美国 印第安纳州 印第安纳波利斯 cogentco.com
17.41 ms 	AS174 [COGENT-BONE] 美国 佐治亚 亚历山大 cogentco.com
31.71 ms 	AS174 [COGENT-BONE] 美国 德克萨斯 达拉斯 cogentco.com
42.72 ms 	AS174 [COGENT-BONE] 美国 得克萨斯州 埃尔帕索 cogentco.com
64.74 ms 	AS174 [COGENT-BONE] 美国 亚利桑那 凤凰城 cogentco.com
63.45 ms 	AS174 [COGENT-BONE] 美国 加利福尼亚 洛杉矶 cogentco.com
63.59 ms 	AS174 [COGENT-BONE] 美国 加利福尼亚 洛杉矶 cogentco.com
264.25 ms 	AS174 美国 加利福尼亚 洛杉矶 cogentco.com
278.16 ms 	AS4837 [CU169-BACKBONE] 中国 北京 北京 chinaunicom.cn
267.29 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
296.97 ms 	AS17816 [UNICOM-GD] 中国 广东 深圳 chinaunicom.cn 联通
291.47 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
302.35 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.26 ms 	AS834 美国 纽约州 纽约 ipxo.com
0.96 ms 	AS174 美国 俄亥俄州 哥伦布 cogentco.com
1.38 ms 	AS174 [COGENT-BONE] 美国 俄亥俄州 哥伦布 cogentco.com
4.19 ms 	AS174 [COGENT-BONE] 美国 肯塔基州 希伯伦 cogentco.com
6.17 ms 	AS174 [COGENT-BONE] 美国 印第安纳州 印第安纳波利斯 cogentco.com
17.09 ms 	AS174 [COGENT-BONE] 美国 佐治亚 亚历山大 cogentco.com
31.72 ms 	AS174 [COGENT-BONE] 美国 德克萨斯 达拉斯 cogentco.com
43.42 ms 	AS174 [COGENT-BONE] 美国 得克萨斯州 埃尔帕索 cogentco.com
51.57 ms 	AS174 [COGENT-BONE] 美国 亚利桑那 凤凰城 cogentco.com
63.77 ms 	AS174 [COGENT-BONE] 美国 加利福尼亚 洛杉矶 cogentco.com
63.60 ms 	AS174 [COGENT-BONE] 美国 加利福尼亚 洛杉矶 cogentco.com
63.28 ms 	AS174 美国 加利福尼亚 洛杉矶 cogentco.com
63.03 ms 	AS58453 [CMI-INT] 中国 香港 cmi.chinamobile.com
63.54 ms 	AS58453 [CMI-INT] 中国 香港 cmi.chinamobile.com
231.96 ms 	AS58453 [CMI-INT] 中国 广东 广州 cmi.chinamobile.com 移动
238.03 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
231.07 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
238.77 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
293.56 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
244.79 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 8361.18 Mbps	 8408.34 Mbps	 4.04	  0.0%
洛杉矶		 1261.11 Mbps	 1746.51 Mbps	 62.82	  0.0%
法兰克福	 303.34 Mbps	 3406.66 Mbps	 108.72	  NULL
联通WuXi	 2.36 Mbps	 2607.46 Mbps	 281.81	  3.3%
电信Suzhou5G	 1.21 Mbps	 2148.03 Mbps	 214.73	  NULL
电信浙江	 0.55 Mbps	 1424.93 Mbps	 214.11	  NULL
移动Fujian	 5.56 Mbps	 70.23 Mbps	 305.57	  NULL
------------------------------------------------------------------------
 总共花费      : 7 分 45 秒
 时间          : Sun Nov 24 22:15:21 CST 2024
------------------------------------------------------------------------


```