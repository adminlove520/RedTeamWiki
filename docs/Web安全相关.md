# Web安全相关

本章节整理了Web安全领域的测试框架、工具和资源，帮助安全人员进行Web应用安全测试、漏洞检测和安全评估工作。Web安全是网络安全的重要组成部分，涉及Web应用程序的设计、开发、测试和维护等多个环节。

## Web安全测试框架

Web安全测试框架提供了全面的漏洞检测和利用能力，帮助安全人员进行系统化的渗透测试工作。

- [ethicalhack3r/PhpSploit](https://github.com/ethicalhack3r/PhpSploit) - PHP漏洞利用框架，专为渗透测试人员设计
- [soffensive/wafw00f](https://github.com/soffensive/wafw00f) - 检测目标网站使用的Web应用防火墙(WAF)产品
- [epinna/tplmap](https://github.com/epinna/tplmap) - 服务端模板注入检测与利用工具，支持多种模板引擎
- [frohoff/ysoserial](https://github.com/frohoff/ysoserial) - Java序列化漏洞利用工具集，生成各种序列化payload
- [frohoff/ysoserial.net](https://github.com/frohoff/ysoserial.net) - .NET序列化漏洞利用工具集
- [med0x2e/rats](https://github.com/med0x2e/rats) - 远程管理与代理工具集，用于渗透测试中的命令控制
- [airbus-seclab/tlsfuzzer](https://github.com/airbus-seclab/tlsfuzzer) - TLS协议测试工具，用于验证TLS实现的安全性
- [andresriancho/w3af](https://github.com/andresriancho/w3af) - Web应用程序攻击和审计框架
- [GDSSecurity/OWASP-Nettacker](https://github.com/GDSSecurity/OWASP-Nettacker) - 自动化渗透测试框架
- [zaproxy/zaproxy](https://github.com/zaproxy/zaproxy) - OWASP ZAP安全测试工具

## 信息收集工具

信息收集是Web安全测试的第一步，这些工具帮助安全人员获取目标系统的基本信息和潜在攻击面。

- [aboul3la/Sublist3r](https://github.com/aboul3la/Sublist3r) - 子域名枚举工具，使用多种搜索引擎和DNS爆破技术
- [guelfoweb/knock](https://github.com/guelfoweb/knock) - 子域名爆破工具，通过字典猜测子域名
- [urbanadventurer/WhatWeb](https://github.com/urbanadventurer/WhatWeb) - Web应用程序指纹识别工具，识别网站使用的技术栈
- [sensepost/gowitness](https://github.com/sensepost/gowitness) - 网站截图工具，用于快速视觉评估多个网站
- [tomnomnom/assetfinder](https://github.com/tomnomnom/assetfinder) - 资产发现工具
- [tomnomnom/waybackurls](https://github.com/tomnomnom/waybackurls) - 从Wayback Machine获取URL
- [tomnomnom/httprobe](https://github.com/tomnomnom/httprobe) - HTTP/HTTPS探测工具
- [tomnomnom/httpx](https://github.com/tomnomnom/httpx) - HTTP/HTTPS探测和指纹识别工具
- [jordan-wright/emailhunter](https://github.com/jordan-wright/emailhunter) - 电子邮件收集工具
- [jordan-wright/usernamer](https://github.com/jordan-wright/usernamer) - 用户名枚举工具
- [harrystaley/ProxyHarvest](https://github.com/harrystaley/ProxyHarvest) - HTTP代理收集工具

## 漏洞扫描工具

漏洞扫描工具用于自动化检测Web应用程序中的安全漏洞，帮助安全人员发现潜在风险。

- [maurosoria/dirsearch](https://github.com/maurosoria/dirsearch) - Web目录扫描工具，用于发现隐藏文件和目录
- [sullo/nikto](https://github.com/sullo/nikto) - Nikto Web服务器漏洞扫描器，检测各种Web服务器漏洞
- [wpscanteam/wpscan](https://github.com/wpscanteam/wpscan) - WordPress漏洞扫描器，检测WordPress核心、插件和主题中的漏洞
- [mozilla/http-observatory](https://github.com/mozilla/http-observatory) - 网站安全评估工具，检查网站的TLS配置和安全头部
- [jekyc/wapiti](https://github.com/jekyc/wapiti) - Web应用程序漏洞扫描器，支持多种漏洞类型检测
- [1N3/Sn1per](https://github.com/1N3/Sn1per) - 自动化渗透测试和漏洞扫描工具，集成多种安全工具
- [nccgroup/xcavator](https://github.com/nccgroup/xcavator) - 自动化漏洞扫描工具
- [tijme/angularjs-csti-scanner](https://github.com/tijme/angularjs-csti-scanner) - AngularJS客户端模板注入漏洞扫描器
- [infobyte/punkspider](https://github.com/infobyte/punkspider) - Web安全漏洞扫描平台

## 漏洞利用工具

漏洞利用工具用于验证已发现的安全漏洞，并展示漏洞可能带来的风险和影响。

- [s0md3v/XSStrike](https://github.com/s0md3v/XSStrike) - XSS漏洞检测工具，使用模糊测试和机器学习技术
- [codingo/NoSQLMap](https://github.com/codingo/NoSQLMap) - NoSQL数据库漏洞利用工具，支持MongoDB、CouchDB等
- [swisskyrepo/PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - 渗透测试payload集合，包含各种漏洞的测试载荷
- [Neohapsis/bbqsql](https://github.com/Neohapsis/bbqsql) - SQL注入漏洞利用工具
- [ricardo-dias/NoSQL-Attack-Framework](https://github.com/ricardo-dias/NoSQL-Attack-Framework) - NoSQL数据库攻击框架
- [denandz/exploits_collection](https://github.com/denandz/exploits_collection) - 收集了各种漏洞利用代码

## 安全防御与代码分析工具

这些工具帮助开发人员和安全人员检测和修复代码中的安全漏洞，提高Web应用程序的安全性。

- [mdsecactivebreach/WADComs](https://github.com/mdsecactivebreach/WADComs) - Web应用程序防御技术的集合，提供防御建议
- [facundoolano/security-code-scan](https://github.com/facundoolano/security-code-scan) - .NET静态代码分析工具，检测安全漏洞
- [secfigo/Awesome-Fuzzing](https://github.com/secfigo/Awesome-Fuzzing) - Fuzz测试相关工具和资源，用于发现软件漏洞
- [righettod/poc-maker](https://github.com/righettod/poc-maker) - 渗透测试POC创建工具

## 渗透测试辅助工具

这些工具用于辅助渗透测试过程中的各种任务，提高测试效率和质量。

- [tomnomnom/gron](https://github.com/tomnomnom/gron) - JSON转grepable格式工具，便于在JSON数据中搜索
- [lgandx/PCredz](https://github.com/lgandx/PCredz) - 扫描网络捕获的数据包中的凭证信息
- [yassineaboukir/Ultimate-Bash-Scripting](https://github.com/yassineaboukir/Ultimate-Bash-Scripting) - 包含一些网络安全相关的Bash脚本
- [phith0n/python爬虫](https://github.com/phith0n/python爬虫) - 一些Python爬虫脚本，可用作信息收集
- [shellrow/default Credentials](https://github.com/shellrow/default Credentials) - 渗透测试人员常用默认凭证列表
- [tomnomnom/meg](https://github.com/tomnomnom/meg) - 多个HTTP请求并行发送工具
- [tomnomnom/unfurl](https://github.com/tomnomnom/unfurl) - URL解析工具
- [tomnomnom/gf](https://github.com/tomnomnom/gf) - Go语言编写的模式匹配工具
- [tomnomnom/fff](https://github.com/tomnomnom/fff) - 快速查找文件工具
- [tomnomnom/linkfinder](https://github.com/tomnomnom/linkfinder) - 链接查找工具
- [tomnomnom/dnsx](https://github.com/tomnomnom/dnsx) - DNS解析工具
- [tomnomnom/qsreplace](https://github.com/tomnomnom/qsreplace) - URL查询参数替换工具
- [tomnomnom/anew](https://github.com/tomnomnom/anew) - 新增内容检测工具
- [tomnomnom/gobuster](https://github.com/tomnomnom/gobuster) - 目录和文件爆破工具
- [tomnomnom/prettycat](https://github.com/tomnomnom/prettycat) - 美化输出工具
- [tomnomnom/s3fuzzer](https://github.com/tomnomnom/s3fuzzer) - S3存储桶测试工具
- [tomnomnom/tlsx](https://github.com/tomnomnom/tlsx) - TLS扫描工具
- [tomnomnom/xurls](https://github.com/tomnomnom/xurls) - URL提取工具
- [andrew-d/static-binaries](https://github.com/andrew-d/static-binaries) - 静态编译的工具二进制文件集合
- [we45/VulnerableApp](https://github.com/we45/VulnerableApp) - 用于安全测试的漏洞应用程序
- [infobyte/faraday](https://github.com/infobyte/faraday) - 渗透测试协作平台
- [jpillora/chisel](https://github.com/jpillora/chisel) - TCP/UDP隧道工具

## 红队与高级持久化威胁(APT)工具

这些工具主要用于模拟高级攻击者的行为，测试组织的安全防御能力。

- [byt3bl33d3r/CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) - 用于自动化渗透测试的工具
- [Greenwolf/ntlm_theft](https://github.com/Greenwolf/ntlm_theft) - NTLM窃取工具
- [SpiderLabs/Responder](https://github.com/SpiderLabs/Responder) - 网络协议欺骗工具
- [byt3bl33d3r/MITMf](https://github.com/byt3bl33d3r/MITMf) - 中间人攻击框架
- [byt3bl33d3r/SprayingToolkit](https://github.com/byt3bl33d3r/SprayingToolkit) - 密码喷洒攻击工具包
- [0xZDH/o365spray](https://github.com/0xZDH/o365spray) - Office 365密码喷洒攻击工具
- [0xZDH/active-directory-password-spray](https://github.com/0xZDH/active-directory-password-spray) - Active Directory密码喷洒攻击工具
- [ropnop/kerbrute](https://github.com/ropnop/kerbrute) - Kerberos暴力破解工具
- [3CORESec/RedTeamTools](https://github.com/3CORESec/RedTeamTools) - 红队工具集合

## 权限提升与后渗透工具

这些工具用于在获得初步访问权限后，提升权限并维持对目标系统的访问。

- [n00py/winpeas](https://github.com/n00py/winpeas) - Windows本地权限提升扫描工具
- [carlospolop/PEASS-ng](https://github.com/carlospolop/PEASS-ng) - 权限提升工具套件
- [carlospolop/privilege-escalation-awesome-scripts-suite](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite) - 权限提升脚本套件
- [ropnop/go-windapsearch](https://github.com/ropnop/go-windapsearch) - Windows AD搜索工具
- [ropnop/impacket_static_builds](https://github.com/ropnop/impacket_static_builds) - Impacket静态编译版本
- [chenjj/CVE-2018-8174](https://github.com/chenjj/CVE-2018-8174) - Windows内核提权漏洞验证
- [sensepost/objection](https://github.com/sensepost/objection) - 移动应用程序运行时攻击工具

## 其他Web安全资源

- [leostat/rtfm](https://github.com/leostat/rtfm) - 一个简单的网络安全知识管理系统
- [jordanpotti/CloudPentest](https://github.com/jordanpotti/CloudPentest) - 云环境渗透测试工具
- [mindcrypt](https://github.com/mindcrypt) - 一个加密工具库
- [jgamblin/OSCPRepo](https://github.com/jgamblin/OSCPRepo) - 包含OSCP考试相关的笔记和脚本
- [ethicalhack3r/burp-suite-tutorials](https://github.com/ethicalhack3r/burp-suite-tutorials) - Burp Suite使用教程
- [irgoncalves/waf-detect](https://github.com/irgoncalves/waf-detect) - WAF检测工具
- [portswigger/burp-extender-devkit](https://github.com/portswigger/burp-extender-devkit) - Burp Suite插件开发工具包
- [NorthwaveSecurity/SCCM-Collection-Query](https://github.com/NorthwaveSecurity/SCCM-Collection-Query) - SCCM收集查询工具
- [chrispetrou/PhishReport](https://github.com/chrispetrou/PhishReport) - 钓鱼攻击报告工具
- [mwrlabs/droidbot](https://github.com/mwrlabs/droidbot) - 安卓应用程序自动化测试工具
- [mozilla/OpenWPM](https://github.com/mozilla/OpenWPM) - 网页监控工具
- [segmentio/analytics.js](https://github.com/segmentio/analytics.js) - 网页分析工具
- [0xsauby/yasuo](https://github.com/0xsauby/yasuo) - 网络安全工具集合
- [SmeegeSec/HookPoint](https://github.com/SmeegeSec/HookPoint) - Chrome扩展，用于检测和分析浏览器安全漏洞
- [koenbuyens/whatrf](https://github.com/koenbuyens/whatrf) - 无线频率识别工具
- [arch4ngel/eaphammer](https://github.com/arch4ngel/eaphammer) - 无线网络渗透测试工具
- [ytisf/theZoo](https://github.com/ytisf/theZoo) - 恶意软件样本集合
- [NetSPI/PowerShell-Scripts](https://github.com/NetSPI/PowerShell-Scripts) - PowerShell安全测试脚本集合
- [3CORESec/MemLabs](https://github.com/3CORESec/MemLabs) - 内存取证实验室
- [micahflee/onionshare](https://github.com/micahflee/onionshare) - 匿名文件共享工具
- [micahflee/torbrowser-launcher](https://github.com/micahflee/torbrowser-launcher) - Tor浏览器启动器
- [praetorian-code/snow](https://github.com/praetorian-code/snow) - 基于机器学习的异常检测框架
- [nccgroup/featherduster](https://github.com/nccgroup/featherduster) - 用于加密分析和密码破解的工具