# ATTCK-technical-data


## 0x00. 前言

​   最近对ATT&CK技战术进行一些数据分析，但是如果去官网逐个看，比较麻烦，因此我把需要的一些关键信息提取下来，可能一些业内同样需要这份数据，分享给大家。通过全局视角查看ATT&CK技术表，再结合其中提供的检测数据源，帮助企业有体系的检查自身防御部署是否合理。

PS：分享的数据来源于ATT&CK官网，本数据会随着官网更新而更新。

## 0x01. 数据维度

**数据包含**

1. 全量技术摘要
2. 检测数据源统计表
3. Windows技术摘要
4. MacOS技术摘要
5. Linux技术摘要


## 0x02. 翻译对照

**战术翻译**
| 战术ID | 战术名称 | 战术内容 |
| ------ | ------ | ------ |
| TA0043 | Reconnaissance | The adversary is trying to gather information they can use to plan future operations. |
|  |  侦查 | 对手在尝试进行收集情报，来计划未来的行动。 |
| TA0042 | Resource Development |  The adversary is trying to establish resources they can use to support operations. |
|  |  资源部署 | 对手在尝试部署攻击资源。 |
| TA0001 | Initial Access | The adversary is trying to get into your network. |
|  |  初始化访问 | 对手在尝试构建攻击立足点 |
| TA0002 | Execution |  The adversary is trying to run malicious code. |
|  |  执行 | 对手在尝试运行恶意代码 |
| TA0003 | Persistence | The adversary is trying to maintain their foothold. |
|  |  维持 | 对手在尝试维持住立足点 |
| TA0004 | Privilege Escalation | The adversary is trying to gain higher-level permissions. |
|  |  权限提升 | 对手在尝试获取更高的权限 |
| TA0005 | Defense Evasion | The adversary is trying to avoid being detected. |
|  |  防御绕过 | 对手在尝试躲避防御体系 |
| TA0006 | Credential Access |  The adversary is trying to steal account names and passwords. |
|  |  凭证获取 | 对手在尝试获取访问凭证（账号、密码等） |
| TA0007 | Discovery |  The adversary is trying to figure out your environment. |
|  |  探索 | 对手在尝试弄清楚目标环境 |
| TA0008 | Lateral Movement |  The adversary is trying to move through your environment. |
|  |  横向移动 | 对手在尝试在目标环境移动 |
| TA0009 | Collection | The adversary is trying to gather data of interest to their goal. |
|  |  收集 | 对手在尝试收集感兴趣的目标数据 |
| TA0011 | Command and Control | The adversary is trying to communicate with compromised systems to control them. |
|  |  命令控制 | 对手在尝试对失陷系统进行控制通信 |
| TA0010 | Exfiltration |  The adversary is trying to steal data. |
|  |  外渗 | 对手在尝试进行数据盗取 |
| TA0040 | Impact | The adversary is trying to manipulate, interrupt, or destroy your systems and data. |
|  |  影响（针对失陷） | 敌对尝试进行收集情报，来计划未来的行动。 |