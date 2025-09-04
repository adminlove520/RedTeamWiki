# Burp Suite 相关工具与拓展插件

本章节收集整理了Burp Suite相关的扩展插件、工具和资源，帮助安全研究人员和渗透测试人员更好地使用Burp Suite进行Web安全测试和漏洞挖掘。Burp Suite是一款功能强大的Web应用安全测试工具，通过这些扩展插件，可以进一步增强其功能，提高安全测试的效率和深度。

## 核心功能增强插件

核心功能增强插件用于扩展Burp Suite的基础功能，提升工具的整体性能和可用性。

- [NoPE](https://github.com/federicodotta/NoPE) - Burp Suite插件，用于检测不安全的HTTP方法
- [param-miner](https://github.com/PortSwigger/param-miner) - 用于发现隐藏的参数和请求字段
- [BurpShutdownTimer](https://github.com/summitt/BurpShutdownTimer) - 控制Burp的自动关闭时间，适合长时间运行的扫描任务
- [pyBurprest](https://github.com/GoSecure/pyBurprest) - 用Python编写的Burp REST API客户端，便于自动化集成
- [passive-scan-client](https://github.com/bit4woo/passive-scan-client) - Burp被动扫描客户端，支持配置和管理被动扫描规则
- [Turbo Intruder](https://github.com/PortSwigger/turbo-intruder) - 高性能的自定义攻击工具，比Burp的Intruder更快
- [Logger++](https://github.com/PortSwigger/logger-plus-plus) - 增强的HTTP请求和响应日志记录工具
- [Copy As Python-Requests](https://github.com/PortSwigger/copy-as-python-requests) - 将HTTP请求转换为Python Requests代码
- [Auth Analyzer](https://github.com/PortSwigger/auth-analyzer) - 身份验证分析工具，帮助检测认证漏洞

## 信息收集与分析插件

信息收集与分析插件用于收集目标网站的各种信息，并对收集到的数据进行分析，为后续的漏洞检测提供支持。

- [knife](https://github.com/bit4woo/knife) - 多功能Burp Suite扩展，提供多种信息收集和分析功能
- [headers](https://github.com/bit4woo/headers) - 用于Burp Suite的HTTP头分析工具，检查安全相关的HTTP头部设置
- [fingerprinthub](https://github.com/bit4woo/fingerprinthub) - 指纹识别工具，用于识别Web应用框架和服务器类型
- [cookie-monster](https://github.com/bit4woo/cookie-monster) - Cookie分析工具，检查Cookie的安全属性
- [session-tracker](https://github.com/bit4woo/session-tracker) - 会话跟踪工具，监控会话ID的变化
- [response-analyzer](https://github.com/bit4woo/response-analyzer) - 响应分析工具，提取和分析HTTP响应中的关键信息
- [crawler-plus](https://github.com/bit4woo/crawler-plus) - 增强的爬虫工具，发现更多的应用路径和功能
- [Wappalyzer Integration](https://github.com/PortSwigger/wappalyzer-integration) - 集成Wappalyzer的技术识别功能
- [DNS Lookup](https://github.com/PortSwigger/dns-lookup) - DNS查询工具，获取域名的DNS信息
- [IPinfo](https://github.com/PortSwigger/ipinfo) - IP地址信息查询工具，获取地理位置等信息

## 漏洞扫描与利用插件

漏洞扫描与利用插件用于自动或半自动地发现和验证Web应用中的安全漏洞，加速漏洞检测和利用过程。

- [autopwn](https://github.com/bit4woo/autopwn) - 自动化渗透测试工具，集成多种漏洞检测和利用功能
- [active-scan-plus-plus](https://github.com/bit4woo/active-scan-plus-plus) - 增强Burp的主动扫描能力，检测更多类型的漏洞
- [vulnerability-scanner](https://github.com/bit4woo/vulnerability-scanner) - 漏洞扫描工具，针对特定漏洞进行检测
- [exploit-framework](https://github.com/bit4woo/exploit-framework) - 漏洞利用框架，提供常见漏洞的利用模块
- [Retire.js](https://github.com/PortSwigger/retire-js) - 检测使用已知漏洞的JavaScript库
- [Software Vulnerability Scanner](https://github.com/PortSwigger/software-vulnerability-scanner) - 软件漏洞扫描器，检测已知的软件漏洞
- [SAML Raider](https://github.com/SAMLRaider/SAMLRaider) - SAML协议安全测试工具
- [GraphQL Raider](https://github.com/nicholasaleks/GraphQLRaider) - GraphQL API安全测试工具

## 路径与参数发现插件

路径与参数发现插件用于发现Web应用中隐藏的路径、目录和参数，帮助发现更多的攻击面。

- [directory-finder](https://github.com/bit4woo/directory-finder) - 目录发现工具，检测网站的隐藏目录
- [param-spider](https://github.com/bit4woo/param-spider) - 参数发现工具，寻找URL中的参数
- [Arjun](https://github.com/s0md3v/Arjun) - HTTP参数发现工具，可以集成到Burp Suite中使用
- [FFUF Integration](https://github.com/PortSwigger/ffuf-integration) - 集成FFUF的模糊测试功能
- [Discover Parameters](https://github.com/PortSwigger/discover-parameters) - 发现HTTP请求中的隐藏参数

## 请求与响应处理插件

请求与响应处理插件用于修改、重放和分析HTTP请求和响应，帮助安全测试人员更灵活地进行测试。

- [request-tamper](https://github.com/bit4woo/request-tamper) - 请求篡改工具，用于修改HTTP请求内容
- [Repeater++](https://github.com/PortSwigger/repeater-plus-plus) - 增强的Repeater工具，提供更多功能
- [Response Replacement](https://github.com/PortSwigger/response-replacement) - 响应替换工具，用于修改HTTP响应
- [Modify Headers](https://github.com/PortSwigger/modify-headers) - HTTP头部修改工具
- [Match and Replace](https://github.com/PortSwigger/match-and-replace) - 基于规则的请求和响应内容替换工具

## 特定漏洞检测插件

特定漏洞检测插件专注于检测特定类型的Web安全漏洞，提供更精确和高效的检测能力。

### SQL注入漏洞检测
- [sqli-scanner](https://github.com/bit4woo/sqli-scanner) - SQL注入扫描器
- [SQLiPy](https://github.com/PortSwigger/sqlipy) - Python编写的SQL注入检测工具

### XSS漏洞检测
- [xss-scanner](https://github.com/bit4woo/xss-scanner) - XSS扫描器
- [XSS Validator](https://github.com/PortSwigger/xss-validator) - XSS漏洞验证工具

### CSRF漏洞检测
- [csrf-scanner](https://github.com/bit4woo/csrf-scanner) - CSRF扫描器
- [CSRF Token Tester](https://github.com/PortSwigger/csrf-token-tester) - CSRF令牌测试工具

### SSRF漏洞检测
- [ssrf-scanner](https://github.com/bit4woo/ssrf-scanner) - SSRF扫描器
- [SSRF Proxy](https://github.com/PortSwigger/ssrf-proxy) - SSRF漏洞利用代理工具

### 命令执行漏洞检测
- [rce-scanner](https://github.com/bit4woo/rce-scanner) - RCE扫描器
- [Command Injection Scanner](https://github.com/PortSwigger/command-injection-scanner) - 命令注入漏洞扫描器

### 文件包含漏洞检测
- [lfi-scanner](https://github.com/bit4woo/lfi-scanner) - LFI扫描器
- [rfi-scanner](https://github.com/bit4woo/rfi-scanner) - RFI扫描器

### 文件上传漏洞检测
- [file-upload-scanner](https://github.com/bit4woo/file-upload-scanner) - 文件上传扫描器
- [File Upload Checker](https://github.com/PortSwigger/file-upload-checker) - 文件上传安全检查工具

### WebShell检测
- [webshell-scanner](https://github.com/bit4woo/webshell-scanner) - WebShell扫描器
- [Shell Detector](https://github.com/PortSwigger/shell-detector) - 检测WebShell的工具

### 其他特定漏洞检测
- [XXE Scanner](https://github.com/PortSwigger/xxe-scanner) - XML外部实体漏洞扫描器
- [Open Redirect Scanner](https://github.com/PortSwigger/open-redirect-scanner) - 开放重定向漏洞扫描器
- [Insecure Deserialization Scanner](https://github.com/PortSwigger/insecure-deserialization-scanner) - 不安全反序列化漏洞扫描器
- [CORS Scanner](https://github.com/PortSwigger/cors-scanner) - 跨域资源共享安全检查工具

## 编码与生成工具插件

编码与生成工具插件提供各种编码、解码和生成功能，帮助安全测试人员准备测试数据和分析结果。

- [payload-generator](https://github.com/bit4woo/payload-generator) - 载荷生成器，创建各种测试用的Payload
- [encoder-decoder](https://github.com/bit4woo/encoder-decoder) - 编码器/解码器，支持多种编码格式
- [hash-cracker](https://github.com/bit4woo/hash-cracker) - 哈希破解工具，尝试破解常见的哈希值
- [password-generator](https://github.com/bit4woo/password-generator) - 密码生成器，创建强密码
- [dictionary-attack](https://github.com/bit4woo/dictionary-attack) - 字典攻击工具，使用字典进行暴力破解
- [brute-force](https://github.com/bit4woo/brute-force) - 暴力破解工具，尝试所有可能的组合
- [Encoder++](https://github.com/PortSwigger/encoder-plus-plus) - 增强的编码工具，支持多种编码方式
- [Hash Calculator](https://github.com/PortSwigger/hash-calculator) - 哈希值计算器，计算文件或文本的哈希值
- [Random Data Generator](https://github.com/PortSwigger/random-data-generator) - 随机数据生成器，创建测试数据

## 安全测试与合规性插件

安全测试与合规性插件帮助安全测试人员进行合规性检查和特定标准的安全测试。

- [OWASP Top 10 Scanner](https://github.com/PortSwigger/owasp-top-ten-scanner) - 针对OWASP Top 10漏洞的扫描器
- [CWE Scanner](https://github.com/PortSwigger/cwe-scanner) - 基于常见弱点枚举(CWE)的漏洞扫描器
- [PCI DSS Scanner](https://github.com/PortSwigger/pci-dss-scanner) - 支付卡行业数据安全标准(PCI DSS)合规性扫描器
- [GDPR Scanner](https://github.com/PortSwigger/gdpr-scanner) - 通用数据保护条例(GDPR)合规性扫描器
- [HIPAA Scanner](https://github.com/PortSwigger/hipaa-scanner) - 健康保险便携性和责任法案(HIPAA)合规性扫描器

## Burp Suite官方扩展

Burp Suite官方扩展由PortSwigger开发，提供稳定可靠的功能增强。

- [PortSwigger BApp Store](https://portswigger.net/bappstore) - 官方Burp Suite扩展应用商店，提供各种官方和第三方插件
- [Burp Suite Professional](https://portswigger.net/burp/professional) - Burp Suite专业版，包含更多高级功能
- [Burp Suite Enterprise Edition](https://portswigger.net/burp/enterprise) - 企业级应用安全测试平台
- [Burp Suite Collaborator](https://portswigger.net/burp/documentation/collaborator) - 用于检测无回显漏洞的协作服务器
- [Burp Suite Mobile Assistant](https://portswigger.net/burp/mobile-assistant) - 移动应用安全测试助手

## 第三方集成与工具链

第三方集成与工具链插件用于将Burp Suite与其他安全工具集成，形成更强大的安全测试工具链。

- [Burp Suite + OWASP ZAP](https://github.com/secdec/astam-correlator) - Burp Suite与ZAP集成工具，结合两个工具的优势
- [Burp Suite + Nmap](https://github.com/vulnersCom/burp-nmap-scanner) - Burp Suite与Nmap集成插件，结合网络扫描和Web应用测试
- [Burp Suite + Sqlmap](https://github.com/1N3/SQLMap-API) - Burp Suite与Sqlmap集成工具，增强SQL注入检测和利用能力
- [Burp Suite + Metasploit](https://github.com/rapid7/metasploit-framework-burp-extension) - Burp Suite与Metasploit集成，结合Web应用测试和漏洞利用
- [Burp Suite + Jira](https://github.com/PortSwigger/jira-integration) - Burp Suite与Jira集成，便于漏洞跟踪和管理
- [Burp Suite + Slack](https://github.com/PortSwigger/slack-integration) - Burp Suite与Slack集成，实现团队协作和通知
- [Burp Suite + Jenkins](https://github.com/PortSwigger/jenkins-integration) - Burp Suite与Jenkins集成，实现CI/CD安全测试自动化

## 自定义开发与脚本

自定义开发与脚本资源帮助安全测试人员开发自己的Burp Suite插件和脚本，根据特定需求扩展功能。

- [Burp Extender API](https://portswigger.net/burp/extender/api) - Burp Suite扩展开发API文档
- [Burp Suite Python API](https://github.com/PortSwigger/burp-extensions-montoya-api) - 用于Python的Burp Suite扩展API
- [Burp Suite Java API Examples](https://github.com/PortSwigger/burp-extensions) - Java扩展开发示例
- [Burp Suite .NET API](https://github.com/PortSwigger/burp-extensions-dotnet-api) - 用于.NET的Burp Suite扩展API
- [Burp Suite Scripting with JavaScript](https://github.com/PortSwigger/burp-scripting) - 使用JavaScript进行Burp Suite脚本开发

## 学习资源与文档

学习资源与文档帮助安全测试人员更好地学习和使用Burp Suite及其扩展插件。

- [Burp Suite官方文档](https://portswigger.net/burp/documentation) - Burp Suite官方文档，包含详细的使用指南
- [Burp Suite教程](https://portswigger.net/web-security/learning-path) - PortSwigger提供的Web安全学习路径和教程
- [Burp Suite实验室](https://portswigger.net/web-security) - 在线Web安全实验室，提供实战练习
- [Burp Suite认证](https://portswigger.net/certification) - Burp Suite官方认证考试
- [Burp Suite社区论坛](https://forum.portswigger.net/) - 官方社区论坛，交流经验和问题
- [Burp Suite GitHub仓库](https://github.com/PortSwigger) - PortSwigger的GitHub仓库，包含各种扩展和工具

## 性能优化与配置

性能优化与配置资源帮助安全测试人员优化Burp Suite的性能和配置，提高测试效率。

- [Burp Suite性能优化指南](https://portswigger.net/burp/documentation/desktop/settings/performance) - 官方性能优化指南
- [Burp Suite内存配置](https://portswigger.net/burp/documentation/desktop/getting-started/launching-memory) - 内存配置指南
- [Burp Suite代理配置](https://portswigger.net/burp/documentation/desktop/tools/proxy/options) - 代理配置详解
- [Burp Suite扫描配置](https://portswigger.net/burp/documentation/desktop/tools/scanner/options) - 扫描器配置指南
- [Burp Suite键盘快捷键](https://portswigger.net/burp/documentation/desktop/getting-started/keyboard-shortcuts) - 键盘快捷键列表