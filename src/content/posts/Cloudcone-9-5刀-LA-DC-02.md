---
abbrlink: 635074982
author: Allen
published: 2024-11-30 03:31:34
title: Cloudcone 9.5刀 LA DC-02
tags: ['服务器']
---
```
测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.11.08
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : Intel(R) Xeon(R) CPU E5-2697 v2 @ 2.70GHz
 CPU 核心数        : 1
 CPU 频率          : 2699.998 MHz
 CPU 缓存          : L1: 64.00 KB / L2: 256.00 KB / L3: 30.00 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ❌ Disabled
 内存              : 202.92 MiB / 473.14 MiB
 Swap              : 78.92 MiB / 1023.00 MiB
 硬盘空间          : 3.87 GiB / 28.48 GiB
 启动盘路径        : /dev/vda1
 系统在线时间      : 18 days, 12 hour 59 min
 负载              : 0.80, 0.25, 0.08
 系统              : Debian GNU/Linux 11 (bullseye) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 5.10.0-8-amd64
 TCP加速方式       : cubic
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS35916 MULTACOM CORPORATION
 IPV4 位置         : Los Angeles / California / US
 IPV6 ASN          : AS35916 Multacom Corporation
 IPV6 位置         : Los Angeles / California / United States
 IPV6 子网掩码     : 128
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		773 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		15040.53 MB/s
 单线程写测试:		12636.24 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		13.1 MB/s (3190 IOPS, 8.02s)		38.5 MB/s (9410 IOPS, 2.72s)
 1GB-1M Block		517 MB/s (493 IOPS, 2.03s)		2.4 GB/s (2295 IOPS, 0.44s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 11.07 MB/s    (2.7k) | 146.17 MB/s   (2.2k)
Write      | 11.08 MB/s    (2.7k) | 146.94 MB/s   (2.2k)
Total      | 22.15 MB/s    (5.5k) | 293.12 MB/s   (4.5k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 190.72 MB/s    (372) | 168.98 MB/s    (165)
Write      | 200.86 MB/s    (392) | 180.24 MB/s    (176)
Total      | 391.58 MB/s    (764) | 349.23 MB/s    (341)
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
视频缓存节点地域: 美国  洛杉机(LAX17S56)
[IPV6]
连接方式: Youtube Video Server
视频缓存节点地域: 美国  洛杉机(LAX31S13)
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
 Instagram Licensed Audio:		No
 OneTrust Region:			US [California]
 iQyi Oversea Region:			US
 Bing Region:				US
 YouTube CDN:				Los Angeles, CA
 Netflix Preferred CDN:			Los Angeles, CA
 ChatGPT:				No (Only Available with Web Browser)
 Google Gemini:				Yes (Region: USA)
 Wikipedia Editability:			No
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
 Netflix:				Originals Only
 YouTube Premium:			Yes (Region: US)
 Amazon Prime Video:			IPv6 Is Not Currently Supported
 TVBAnywhere+:				IPv6 Is Not Currently Supported
 Spotify Registration:			No
 Instagram Licensed Audio:		No
 OneTrust Region:			US [California]
 iQyi Oversea Region:			IPv6 Is Not Currently Supported
 Bing Region:				US
 YouTube CDN:				Los Angeles, CA
 Netflix Preferred CDN:			Los Angeles, CA
 ChatGPT:				Failed (Network Connection)
 Google Gemini:				Yes (Region: USA)
 Wikipedia Editability:			No
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
欺诈得分(越低越好): 11 [1] 
ASN滥用得分(越低越好): 0.0002 (Very Low) [A] 
ASN滥用得分(越低越好): 0.0002 (Very Low) [A] 
公司滥用得分(越低越好): 0.0034 (Low) [A] 
威胁级别: low [9 B]
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: hosting [0 7] unknown [C] business [8] corporate [9] isp [A]
公司类型: hosting [0 7] business [A]
是否云提供商: Yes [7 D] 
是否数据中心: No [8 A C] Yes [0 1 5 6]
是否移动设备: No [5 A C] 
是否代理: No [0 1 4 5 6 7 8 9 A B C D] 
是否VPN: No [0 1 6 7 C D] Yes [A]
是否Tor: No [0 1 6 7 8 A B C D] 
是否Tor出口: No [1 7 D] 
是否网络爬虫: No [9 A B] 
是否匿名: No [1 6 7 8 D] 
是否攻击者: No [7 8 D] 
是否滥用者: No [7 8 A C D] 
是否威胁: No [7 8 C D] 
是否中继: No [0 7 8 C D] 
是否Bogon: No [7 8 A C D] 
DNS-黑名单: 314(Total_Check) 0(Clean) 5(Blacklisted) 20(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 0 [1]
ASN滥用得分(越低越好): 0.0002 (Very Low) [A] 
ASN滥用得分(越低越好): 0.0002 (Very Low) [A] 
公司滥用得分(越低越好): 0 (Very Low) [A] 
威胁级别: low [B] 
安全信息:
使用类型: isp [A] 
公司类型: isp [A] 
是否云提供商: Yes [D] 
是否数据中心: Yes [1 A] 
是否移动设备: No [A] 
是否代理: No [1 A B D] 
是否VPN: No [1 A D] 
是否Tor: No [1 A B D] 
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
北京电信 219.141.140.10  电信163    [普通线路] 
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
0.95 ms 	AS35916 美国 加利福尼亚 洛杉矶 multacom.com
0.90 ms 	AS35916 美国 加利福尼亚 洛杉矶 multacom.com
0.67 ms 	AS2914 [NTTA-128] 美国 加利福尼亚 洛杉矶 gin.ntt.net
9.43 ms 	AS2914 [NTT-BACKBONE] 美国 加利福尼亚 圣何塞 gin.ntt.net
9.59 ms 	AS2914 [NTT-BACKBONE] 美国 加利福尼亚 圣何塞 gin.ntt.net
10.90 ms 	AS4134 [CHINANET-US] 美国 加利福尼亚 圣克拉拉 www.chinatelecom.com.cn 电信
217.06 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn 电信
276.00 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn
172.90 ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.77 ms 	AS35916 美国 加利福尼亚 洛杉矶 multacom.com
2.11 ms 	AS35916 美国 加利福尼亚 洛杉矶 multacom.com
1.49 ms 	AS174 [COGENT-BONE] 美国 加利福尼亚 洛杉矶 cogentco.com
168.80 ms 	AS174 美国 加利福尼亚 洛杉矶 cogentco.com
161.37 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
168.00 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
261.21 ms 	AS4837 [CU169-BACKBONE] 中国 广东 广州 chinaunicom.cn 联通
166.28 ms 	AS17816 [UNICOM-GD] 中国 广东 深圳 chinaunicom.cn 联通
175.21 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
182.96 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.91 ms 	AS35916 美国 加利福尼亚 洛杉矶 multacom.com
0.91 ms 	AS35916 美国 加利福尼亚 洛杉矶 multacom.com
1.23 ms 	AS2914 [NTTA-128] 美国 加利福尼亚 洛杉矶 gin.ntt.net
100.28 ms 	AS2914 [NTT-BACKBONE] 日本 东京都 东京 gin.ntt.net
200.58 ms 	AS2914 [NTT-BACKBONE] 中国 香港 gin.ntt.net
155.72 ms 	AS58453 [CMI-INT] 中国 香港 cmi.chinamobile.com 移动
159.87 ms 	AS58453 [CMI-INT] 中国 广东 广州 X-I cmi.chinamobile.com 移动
164.87 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
165.10 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
168.31 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
165.78 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 939.59 Mbps	 826.90 Mbps	 0.70	  0.0%
洛杉矶		 926.54 Mbps	 916.59 Mbps	 1.02	  0.0%
日本东京	 252.96 Mbps	 324.11 Mbps	 125.75	  0.0%
联通WuXi	 376.16 Mbps	 300.46 Mbps	 175.72	  0.0%
电信浙江	 536.62 Mbps	 6.35 Mbps	 170.50	  NULL
移动Fujian	 437.64 Mbps	 208.69 Mbps	 184.27	  NULL
移动Beijing	 597.41 Mbps	 263.62 Mbps	 191.23	  0.0%
------------------------------------------------------------------------
 总共花费      : 7 分 14 秒
 时间          : Fri Nov 29 14:38:42 EST 2024
------------------------------------------------------------------------


```