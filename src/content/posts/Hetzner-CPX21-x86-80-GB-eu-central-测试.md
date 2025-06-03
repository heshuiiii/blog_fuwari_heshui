---
abbrlink: 311881755
author: Allen
published: 2024-09-26 08:59:53
title: Hetzner CPX21 | x86 | 80 GB | eu-central 融合怪并发测试
tags: ['服务器']
---
```
3 vCPU 
4 GB RAM
80 GB Disk local
20 TB Traffic out
7.05/mo Price
```



```

测评频道: https://t.me/vps_reviews                    
VPS融合怪版本：2024.08.29
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目---------------------
NAT Type being detected ......
 CPU 型号          : AMD EPYC Processor
 CPU 核心数        : 3
 CPU 频率          : 2495.310 MHz
 CPU 缓存          : L1: 192.00 KB / L2: 1.50 MB / L3: 16.00 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ❌ Disabled
 内存              : 111.39 MiB / 3.73 GiB
 Swap              : [ no swap partition or swap file detected ]
 硬盘空间          : 1.35 GiB / 74.81 GiB
 启动盘路径        : /dev/sda1
 系统在线时间      : 0 days, 0 hour 2 min
 负载              : 0.27, 0.11, 0.03
 系统              : Debian GNU/Linux 11 (bullseye) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 5.10.0-32-amd64
 TCP加速方式       : cubic
 虚拟化架构        : KVM
 IPV4 ASN          : AS24940 Hetzner Online GmbH
 IPV4 位置         : Nürnberg / Bavaria / DE
 IPV6 ASN          : AS24940 Hetzner Online
 IPV6 位置         : Nuremberg / Bavaria / Germany
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		1648 Scores
 3 线程测试(多核)得分: 		4920 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		43386.04 MB/s
 单线程写测试:		18896.20 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		31.7 MB/s (7748 IOPS, 3.30s)		40.1 MB/s (9793 IOPS, 2.61s)
 1GB-1M Block		1.4 GB/s (1294 IOPS, 0.77s)		1.5 GB/s (1392 IOPS, 0.72s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 104.88 MB/s  (26.2k) | 1.17 GB/s    (18.3k)
Write      | 105.16 MB/s  (26.2k) | 1.17 GB/s    (18.4k)
Total      | 210.05 MB/s  (52.5k) | 2.35 GB/s    (36.7k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 1.19 GB/s     (2.3k) | 1.22 GB/s     (1.1k)
Write      | 1.25 GB/s     (2.4k) | 1.30 GB/s     (1.2k)
Total      | 2.45 GB/s     (4.7k) | 2.52 GB/s     (2.4k)
正在并发测试中，大概2~3分钟无输出，请耐心等待。。。
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
连接方式: Youtube Video Server
视频缓存节点地域: 德国法兰克福(FRA15S37)
[IPV6]
连接方式: Youtube Video Server
视频缓存节点地域: 德国法兰克福(FRA16S31)
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
 Instagram Licensed Audio:		No
 OneTrust Region:			DE [Bavaria]
 iQyi Oversea Region:			DE
 Bing Region:				DE
 YouTube CDN:				Frankfurt
 Netflix Preferred CDN:			Frankfurt
 ChatGPT:				Yes
 Google Gemini:				No
 Wikipedia Editability:			No
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
 OneTrust Region:			DE [Bavaria]
 iQyi Oversea Region:			IPv6 Is Not Currently Supported
 Bing Region:				DE
 YouTube CDN:				Frankfurt
 Netflix Preferred CDN:			Frankfurt
 ChatGPT:				Failed (Network Connection)
 Google Gemini:				No
 Wikipedia Editability:			No
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
欺诈得分(越低越好): 25 [1] 65 [E]
ASN滥用得分(越低越好): 0.0025 (Low) [A] 
ASN滥用得分(越低越好): 0.0025 (Low) [A] 
公司滥用得分(越低越好): 0.0054 (Low) [A] 
威胁级别: low [9 B] 
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 94 [2]  
安全信息:
使用类型: hosting [0 7 9 A] business [8] hosting - high probability [C]
公司类型: hosting [0 7 A] 
是否云提供商: Yes [7 D] 
是否数据中心: Yes [0 1 5 6 A C] No [8]
是否移动设备: Yes [E] No [5 A C]
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
DNS-黑名单: 313(Total_Check) 0(Clean) 8(Blacklisted) 20(Other) 
IPV6:
安全得分:
欺诈得分(越低越好): 34 [1]
ASN滥用得分(越低越好): 0.0025 (Low) [A] 
ASN滥用得分(越低越好): 0.0025 (Low) [A] 
公司滥用得分(越低越好): 0 (Very Low) [A] 
威胁级别: low [B] 
安全信息:
使用类型: hosting [A] 
公司类型: hosting [A]
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
DNS-黑名单: 313(Total_Check) 0(Clean) 0(Blacklisted) 313(Other) 
Google搜索可行性：YES
-------------邮件端口检测--基于oneclickvirt/portchecker开源-------------
Platform  SMTP  SMTPS POP3  POP3S IMAP  IMAPS
LocalPort ✔     ✔     ✔     ✔     ✔     ✔    
QQ        ✘     ✘     ✔     ✘     ✔     ✘    
163       ✘     ✘     ✔     ✘     ✔     ✘    
Sohu      ✘     ✘     ✘     ✘     ✔     ✘    
Yandex    ✘     ✘     ✔     ✘     ✔     ✘    
Gmail     ✘     ✘     ✘     ✘     ✘     ✘    
Outlook   ✘     ✘     ✔     ✘     ✔     ✘    
Office365 ✘     ✘     ✔     ✘     ✔     ✘    
Yahoo     ✘     ✘     ✘     ✘     ✘     ✘    
MailCOM   ✘     ✘     ✔     ✘     ✔     ✘    
MailRU    ✘     ✘     ✘     ✘     ✔     ✘    
AOL       ✘     ✘     ✘     ✘     ✘     ✘    
GMX       ✘     ✘     ✔     ✘     ✔     ✘    
Sina      ✘     ✘     ✔     ✘     ✔     ✘    
----------------三网回程--基于oneclickvirt/backtrace开源----------------
北京电信 219.141.140.10  检测不到回程路由节点的IP地址
北京联通 202.106.195.68  联通4837   [普通线路] 
北京移动 221.179.155.161 移动CMI    [普通线路] 移动CMIN2  [精品线路] 
上海电信 202.96.209.133  电信163    [普通线路] 
上海联通 210.22.97.1     联通4837   [普通线路] 
上海移动 211.136.112.200 移动CMI    [普通线路] 
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
2.01 ms 	* RFC1918
* ms 	AS24940 德国 巴伐利亚州 纽伦堡 hetzner.com
0.95 ms 	AS24940 德国 巴伐利亚州 纽伦堡 hetzner.com
3.13 ms 	AS24940 [DE-HETZNER] 德国 巴伐利亚州 纽伦堡 hetzner.com
0.47 ms 	AS24940 [DE-HETZNER] 德国 莱茵兰-普法尔茨州 法尔肯斯泰因 hetzner.com
0.68 ms 	AS24940 [DE-HETZNER] 德国 黑森 美因河畔法兰克福 hetzner.com
11.71 ms 	AS1299 [ARELION-NET] 德国 巴伐利亚 纽伦堡 arelion.com
14.57 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
15.88 ms 	AS1299 [ARELION-NET] 荷兰 北荷兰省 阿姆斯特丹 arelion.com
17.99 ms 	AS1299 [ARELION-NET] 瑞典 斯德哥尔摩省 斯德哥尔摩 arelion.com
* ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn
* ms 	AS4134 [CHINANET-BB] 中国 广东 广州 www.chinatelecom.com.cn
* ms 	AS134774 [CHINANET-GD] 中国 广东 深圳 chinatelecom.cn 电信
* ms 	AS4134 中国 广东 深圳 福田区 www.chinatelecom.com.cn 电信
广州联通 210.21.196.6
2.61 ms 	* RFC1918
0.88 ms 	AS24940 德国 巴伐利亚州 纽伦堡 hetzner.com
0.98 ms 	AS24940 德国 巴伐利亚州 纽伦堡 hetzner.com
0.91 ms 	AS24940 德国 巴伐利亚州 纽伦堡 hetzner.com
0.73 ms 	AS24940 [DE-HETZNER] 德国 巴伐利亚州 纽伦堡 hetzner.com
0.63 ms 	AS24940 [DE-HETZNER] 德国 巴伐利亚州 纽伦堡 hetzner.com
15.68 ms 	AS1299 [TELIANET] 德国 巴伐利亚 纽伦堡 arelion.com
12.25 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
14.79 ms 	AS1299 [ARELION-NET] 德国 黑森州 美因河畔法兰克福 arelion.com
165.10 ms 	AS4837 [CU169-BACKBONE] 中国 北京 chinaunicom.cn 联通
163.53 ms 	AS4837 [CU169-BACKBONE] 中国 北京 chinaunicom.cn 联通
168.60 ms 	AS17816 [UNICOM-GD] 中国 广东 深圳 chinaunicom.cn 联通
168.06 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
166.61 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
1.63 ms 	* RFC1918
0.83 ms 	AS24940 德国 巴伐利亚州 纽伦堡 hetzner.com
1.10 ms 	AS24940 德国 萨克森自由州 法尔肯施泰因 hetzner.com
0.86 ms 	AS24940 [DE-HETZNER] 德国 巴伐利亚州 纽伦堡 hetzner.com
1.21 ms 	AS24940 [DE-HETZNER] 德国 莱茵兰-普法尔茨州 法尔肯斯泰因 hetzner.com
4.19 ms 	AS24940 [DE-HETZNER] 德国 黑森 美因河畔法兰克福 hetzner.com
4.50 ms 	AS58453 [DE-CIX] 德国 黑森 美因河畔法兰克福 DE-CIX Frankfurt - China Mobile International - 100Gbps cmi.chinamobile.com
4.95 ms 	AS58453 [CMI-INT] 德国 黑森 美茵河畔法兰克福 cmi.chinamobile.com 移动
208.57 ms 	AS58453 [CMI-INT] 德国 黑森 美因河畔法兰克福 cmi.chinamobile.com 移动
209.80 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
209.90 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
211.86 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
214.85 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
212.60 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置		 上传速度	 下载速度	 延迟	  丢包率
Speedtest.net	 2234.21 Mbps	 2500.03 Mbps	 0.47	  0.0%
法兰克福	 9838.51 Mbps	 8707.90 Mbps	 3.80	  0.0%
洛杉矶		 58.62 Mbps	 676.90 Mbps	 141.52	  0.0%
联通WuXi	 1.19 Mbps	 1117.56 Mbps	 275.62	  0.3%
联通成都	 1.52 Mbps	 1.32 Mbps	 285.40	  NULL
移动Beijing	 672.11 Mbps	 2222.73 Mbps	 120.47	  0.0%
------------------------------------------------------------------------
 总共花费      : 4 分 15 秒
 时间          : Kam Way 26  7:02:39 saaku UTC 2024
------------------------------------------------------------------------

```