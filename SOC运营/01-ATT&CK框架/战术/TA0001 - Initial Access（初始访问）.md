## 战术信息
- ID：TA0001
- 名称：Initial Access
- 中文：初始访问
- 定义：攻击者试图进入目标网络的技术
- 位置：攻击链第1阶段（进入阶段）
- SOC视角：防守重点。关注钓鱼邮件(T1566)、漏洞利用(T1190)、供应链入侵(T1195)


## 技术清单（11项）
| 技术ID  | 技术名称                                | 子技术数 | 我的掌握度 | 卡片链接                         |
| ----- | ----------------------------------- | ---- | ----- | ---------------------------- |
| T1659 | Content Injection                   | 0    | ⏳ 未学习 |                              |
| T1189 | Drive-by Compromise                 | 0    | ⏳ 未学习 | -                            |
| T1190 | Exploit Public-Facing Application   | 0    | ⏳ 未学习 | -                            |
| T1133 | External Remote Services            | 0    | ⏳ 未学习 | -                            |
| T1200 | Hardware Additions                  | 0    | ⏳ 未学习 |                              |
| T1566 | Phishing                            | 4    | ⏳ 未学习 | [T1566-钓鱼](技术卡片/T1566-钓鱼.md) |
| T1091 | Replication Through Removable Media | 0    | ⏳ 未学习 |                              |
| T1195 | Supply Chain Compromise             | 3    | ⏳ 未学习 | -                            |
| T1199 | Trusted Relationship                | 0    | ⏳ 未学习 | -                            |
| T1078 | Valid Accounts                      | 4    | ⏳ 未学习 | -                            |
| T1669 | WiFi Networks                       | 0    | ⏳ 未学习 | -                            |

## 数据源（检测该战术常用）
- 邮件日志（T1566钓鱼）
- Web代理日志（T1189水坑攻击）
- 网络流量（T1190漏洞利用）

## 我的笔记
- 2026-04-09：开始创建T1566钓鱼卡片