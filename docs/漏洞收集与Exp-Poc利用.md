# 漏洞收集与Exp/Poc利用

本文档汇总了漏洞收集和Exploit/PoC利用相关的工具、资源和模板，涵盖漏洞数据库、Exploit开发框架、PoC验证工具等方面，帮助安全研究人员进行漏洞分析和安全测试。

## 一、漏洞数据库与资源

收集和整理各种漏洞信息的数据库和资源：

- [CVE Details](https://www.cvedetails.com/) - 全面的CVE漏洞信息数据库
- [国家信息安全漏洞共享平台(CNVD)](http://www.cnvd.org.cn/) - 中国国家信息安全漏洞共享平台
- [国家信息安全漏洞库(CNNVD)](http://www.cnnvd.org.cn/) - 中国国家信息安全漏洞库
- [exploitdb](https://github.com/exploitdb/exploitdb) - 漏洞利用数据库，收集了大量的漏洞利用代码
- [Offensive Security Exploit Database](https://github.com/offensive-security/exploitdb) - 攻击性安全漏洞利用数据库

## 二、Exploit开发与框架

用于开发和执行漏洞利用的框架和工具：

- [metasploit-framework](https://github.com/rapid7/metasploit-framework) - 广泛使用的渗透测试框架，包含多种漏洞利用模块
- [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) - 多功能后渗透测试工具，支持多种漏洞利用
- [AutoPwn-Suite](https://github.com/commsec/AutoPwn-Suite) - 自动渗透测试套件，简化渗透测试流程
- [SSF](https://github.com/commsec/SSF) - 安全套接字转发器，提供加密的数据传输和隧道功能

## 三、PoC模板与验证工具

用于编写和验证漏洞PoC的模板和工具：

### 通用Python PoC模板

- [Python-PoC-Template](https://github.com/josephsurin/Python-PoC-Template) - 基础Python PoC模板
- [安全研究Python PoC模板](https://github.com/secinto/Python-PoC-Template) - 专为安全研究设计的Python PoC模板
- [卡尔加里大学信息安全Python PoC模板](https://github.com/infosec-ucalgary/Python-PoC-Template) - 学术机构开发的专业PoC模板
- [OWASP Python PoC模板](https://github.com/OWASP/Python-PoC-Template) - OWASP官方提供的Python PoC模板

### 漏洞类型专用PoC模板

- [XSS攻击Python PoC模板](https://github.com/XSS-Attack/Python-PoC-Template) - 跨站脚本攻击验证模板
- [SQL注入Python PoC模板](https://github.com/SQL-Injection/Python-PoC-Template) - SQL注入漏洞验证模板
- [命令注入Python PoC模板](https://github.com/Command-Injection/Python-PoC-Template) - 命令注入漏洞验证模板
- [远程代码执行Python PoC模板](https://github.com/Remote-Code-Execution/Python-PoC-Template) - RCE漏洞验证模板
- [缓冲区溢出Python PoC模板](https://github.com/Buffer-Overflow/Python-PoC-Template) - 缓冲区溢出漏洞验证模板

## 四、权限提升与凭证获取工具

用于权限提升和凭证获取的工具：

- [PEASS-ng](https://github.com/carlospolop/PEASS-ng) - 权限提升工具集合，包含Windows和Linux提权检查
- [mimikatz](https://github.com/gentilkiwi/mimikatz) - 强大的凭证获取和Windows安全测试工具
- [juicy-potato](https://github.com/ohpe/juicy-potato) - 经典的Windows提权工具，利用DCOM接口和令牌窃取
- [JuicyPotatoNG](https://github.com/antonioCoco/JuicyPotatoNG) - JuicyPotato的改进版本，支持更多Windows版本
- [Responder](https://github.com/lgandx/Responder) - 网络协议中毒工具，可用于捕获凭证

## 五、渗透测试工具集合

综合的渗透测试工具集合：

- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - 渗透测试Payload集合，包含各种攻击和测试用例
- [SecLists](https://github.com/danielmiessler/SecLists) - 安全测试列表集合，包含字典、Payload和其他有用资源
- [php-reverse-shell](https://github.com/pentestmonkey/php-reverse-shell) - PHP反向Shell脚本，常用于Web漏洞利用

## 六、网络工具与协议分析

用于网络扫描和协议分析的工具：

- [scapy](https://github.com/secdev/scapy) - 数据包操作工具，可用于构建和分析网络数据包
- [masscan](https://github.com/robertdavidgraham/masscan) - 大规模网络扫描器，可快速扫描大量IP地址
- [evil-winrm](https://github.com/initstring/evil-winrm) - Windows远程管理工具，可用于远程命令执行
- [kerbrute](https://github.com/ropnop/kerbrute) - Kerberos暴力破解工具，用于测试Kerberos服务安全性

## 七、安全培训与测试平台

用于安全培训和漏洞测试的平台：

- [WebGoat](https://github.com/commsec/WebGoat) - Web安全培训平台，提供各种Web漏洞的实践环境
- [bWAPP](https://github.com/commsec/bWAPP) - Web应用程序漏洞平台，用于安全测试和培训
- [vulnerable-app](https://github.com/commsec/vulnerable-app) - 故意设计的漏洞应用程序，用于安全测试