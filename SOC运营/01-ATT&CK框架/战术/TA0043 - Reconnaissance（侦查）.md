## 战术信息
- ID：TA0043
- 名称：Reconnaissance
- 中文：侦查
- 定义：攻击者试图收集关于目标的信息，为攻击做准备
- 位置：攻击链第1阶段（进入阶段）
- SOC视角：通常发生在外部，较难检测。关注外部威胁情报、搜索引擎扫描、域名注册信息等


## 技术清单（11项）
| 技术ID  | 技术名称                               | 子技术数 | 我的掌握度 | 卡片链接 |
| ----- | ---------------------------------- | ---- | ----- | ---- |
| T1595 | Active Scanning                    | 3    | ⏳ 未学习 |      |
| T1592 | Gather Victim Host Infomation      | 4    | ⏳ 未学习 | -    |
| T1589 | Gather Victim Identity Information | 3    | ⏳ 未学习 | -    |
| T1590 | Gather Victim Network Information  | 6    | ⏳ 未学习 | -    |
| T1591 | Gather Victim Org Infomation       | 4    | ⏳ 未学习 |      |
| T1598 | Phishing for Information           | 4    | ⏳ 未学习 |      |
| T1597 | Search Closed Sources              | 2    | ⏳ 未学习 |      |
| T1596 | Search Open Technical Databases    | 5    | ⏳ 未学习 | -    |
| T1593 | Search Open Websites/Domains       | 3    | ⏳ 未学习 | -    |
| T1681 | Search Threat Vendor Data          | 0    | ⏳ 未学习 | -    |
| T1594 | Search Victim-Owned Websites       | 0    | ⏳ 未学习 |      |

## 数据源（检测该战术常用）
- 邮件日志（T1566钓鱼）
- Web代理日志（T1189水坑攻击）
- 网络流量（T1190漏洞利用）