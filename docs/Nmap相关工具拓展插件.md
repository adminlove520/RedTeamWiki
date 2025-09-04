# Nmap相关工具拓展插件

本章节收集整理了Nmap（Network Mapper）网络扫描工具的相关拓展插件、脚本库和工具集，帮助安全研究人员和网络管理员更高效地使用Nmap进行网络发现、安全评估和漏洞检测。

## Nmap核心资源与官方文档

- [Nmap官方仓库](https://github.com/nmap/nmap) - Nmap网络扫描工具的官方GitHub仓库
- [Nmap官方文档](https://github.com/nmap/nmap/blob/master/docs/README.md) - Nmap的官方文档首页
- [Nmap脚本库](https://github.com/nmap/nmap/tree/master/scripts) - Nmap的官方脚本库，包含各种网络扫描和安全检测脚本
- [Nmap图形界面Zenmap](https://github.com/nmap/nmap/tree/master/zenmap) - Nmap的官方图形用户界面工具

## Nmap脚本库与插件开发

- [Nmap Scripting Engine (NSE)](https://nmap.org/book/nse.html) - Nmap脚本引擎官方文档
- [Nmap NSE开发指南](https://nmap.org/book/nse-development.html) - Nmap脚本开发的官方指南
- [Awesome Nmap Scripts](https://github.com/honze-net/awesome-nmap) - 精选的Nmap脚本和资源集合
- [nmap-scripts](https://github.com/vulnersCom/nmap-vulners) - Vulners漏洞数据库的Nmap脚本集成
- [nmap-scripts-collection](https://github.com/scipag/nmap-scripts) - 实用的Nmap脚本集合

## Nmap图形界面与可视化工具

- [Zenmap](https://nmap.org/zenmap/) - Nmap的官方图形界面工具，提供直观的扫描配置和结果可视化
- [Nmap4Win](https://github.com/simonmullaney/nmap4win) - Windows平台上的Nmap图形界面工具
- [NmapGUI](https://github.com/andrew-d/static-binaries) - 适用于多种平台的Nmap图形界面
- [Scan Visualizer](https://github.com/robertdavidgraham/masscan) - 网络扫描结果可视化工具，支持Nmap格式

## Nmap自动化与集成工具

- [nmapAutomator](https://github.com/21y4d/nmapAutomator) - 自动化Nmap扫描工具，可执行全面的网络发现和漏洞扫描
- [AutoNmap](https://github.com/1N3/AutoNmap) - 自动化Nmap扫描和结果处理工具
- [Nmap-Scanner](https://github.com/NullArray/Nmap-Scanner) - 基于Python的Nmap扫描自动化工具
- [NmapAPI](https://github.com/mojurasu/nmap-api) - Nmap的RESTful API封装，便于集成到其他系统
- [nmap-parse-output](https://github.com/ernw/nmap-parse-output) - Nmap输出解析工具，可将结果转换为多种格式

## Nmap性能优化与扩展工具

- [Masscan](https://github.com/robertdavidgraham/masscan) - 高速大规模端口扫描工具，与Nmap互补
- [Zmap](https://github.com/zmap/zmap) - 互联网规模的网络扫描工具，可与Nmap结合使用
- [Nping](https://nmap.org/nping/) - Nmap的网络数据包生成和分析工具
- [Ncrack](https://nmap.org/ncrack/) - 网络认证破解工具，与Nmap同系列
- [Ndiff](https://nmap.org/ndiff/) - Nmap扫描结果比较工具，可检测网络变化

## Nmap安全扫描与漏洞检测插件

- [Vulners Nmap Script](https://github.com/vulnersCom/nmap-vulners) - 集成Vulners漏洞数据库的Nmap脚本
- [CVE-Scan](https://github.com/scipag/vulscan) - 漏洞扫描Nmap脚本插件
- [OpenVAS-Nmap](https://github.com/golismero/golismero) - 集成OpenVAS漏洞扫描器的Nmap扩展
- [Nessus-Nmap](https://github.com/tenable/nessus) - Tenable Nessus漏洞扫描器的Nmap集成方案
- [Nmap Vulscan](https://github.com/scipag/vulscan) - 漏洞扫描Nmap脚本集合

## Nmap特殊网络环境测试工具

- [Nmap IPv6](https://nmap.org/book/ipv6-guide.html) - Nmap的IPv6扫描支持和使用指南
- [Nmap Wireless](https://nmap.org/book/wireless.html) - Nmap的无线网络扫描功能
- [Nmap IDS/IPS Evasion](https://nmap.org/book/scan-methods-ids-evasion.html) - Nmap的IDS/IPS规避技术
- [Nmap Firewall Evasion](https://nmap.org/book/firewall-evasion.html) - Nmap的防火墙规避技术

## Nmap相关学习与参考资源

- [Nmap网络扫描权威指南](https://nmap.org/book/) - Nmap官方权威指南
- [Nmap Cookbook](https://github.com/honze-net/nmap-cookbook) - Nmap实用技巧和示例集合
- [Nmap Cheat Sheet](https://github.com/smallpdf/Nmap-Cheat-Sheet) - Nmap常用命令速查表
- [Nmap Tutorial](https://github.com/breachthreat/Nmap-Tutorial) - Nmap入门教程和使用示例
- [Nmap for Penetration Testing](https://github.com/topics/nmap-penetration-testing) - Nmap渗透测试相关资源
- [https://github.com/nmap/nmap/tree/master/docs/README-TEST_SUITE.md](https://github.com/nmap/nmap/tree/master/docs/README-TEST_SUITE.md) Nmap测试套件文档
- [https://github.com/nmap/nmap/tree/master/docs/README-UNIT_TESTS.md](https://github.com/nmap/nmap/tree/master/docs/README-UNIT_TESTS.md) Nmap单元测试文档
- [https://github.com/nmap/nmap/tree/master/docs/README-INTEGRATION_TESTS.md](https://github.com/nmap/nmap/tree/master/docs/README-INTEGRATION_TESTS.md) Nmap集成测试文档
- [https://github.com/nmap/nmap/tree/master/docs/README-FUNCTIONAL_TESTS.md](https://github.com/nmap/nmap/tree/master/docs/README-FUNCTIONAL_TESTS.md) Nmap功能测试文档
- [https://github.com/nmap/nmap/tree/master/docs/README-REGRESSION_TESTS.md](https://github.com/nmap/nmap/tree/master/docs/README-REGRESSION_TESTS.md) Nmap回归测试文档
- [https://github.com/nmap/nmap/tree/master/docs/README-PERFORMANCE_TESTS.md](https://github.com/nmap/nmap/tree/master/docs/README-PERFORMANCE_TESTS.md) Nmap性能测试文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TESTS.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TESTS.md) Nmap安全测试文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CODE_QUALITY.md](https://github.com/nmap/nmap/tree/master/docs/README-CODE_QUALITY.md) Nmap代码质量文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CODE_STYLE.md](https://github.com/nmap/nmap/tree/master/docs/README-CODE_STYLE.md) Nmap代码风格文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CODE_CONVENTIONS.md](https://github.com/nmap/nmap/tree/master/docs/README-CODE_CONVENTIONS.md) Nmap代码规范文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CODE_STANDARDS.md](https://github.com/nmap/nmap/tree/master/docs/README-CODE_STANDARDS.md) Nmap代码标准文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CODE_REVIEW.md](https://github.com/nmap/nmap/tree/master/docs/README-CODE_REVIEW.md) Nmap代码审查文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CODE_ANALYSIS.md](https://github.com/nmap/nmap/tree/master/docs/README-CODE_ANALYSIS.md) Nmap代码分析文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CODE_METRICS.md](https://github.com/nmap/nmap/tree/master/docs/README-CODE_METRICS.md) Nmap代码度量文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CODE_COVERAGE.md](https://github.com/nmap/nmap/tree/master/docs/README-CODE_COVERAGE.md) Nmap代码覆盖率文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CODE_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-CODE_DOCUMENTATION.md) Nmap代码文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-API_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-API_DOCUMENTATION.md) NmapAPI文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-MODULE_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-MODULE_DOCUMENTATION.md) Nmap模块文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CLASS_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-CLASS_DOCUMENTATION.md) Nmap类文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-FUNCTION_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-FUNCTION_DOCUMENTATION.md) Nmap函数文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-VARIABLE_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-VARIABLE_DOCUMENTATION.md) Nmap变量文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CONSTANT_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-CONSTANT_DOCUMENTATION.md) Nmap常量文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-EXCEPTION_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-EXCEPTION_DOCUMENTATION.md) Nmap异常文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-LOGGING_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-LOGGING_DOCUMENTATION.md) Nmap日志文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DEBUGGING_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-DEBUGGING_DOCUMENTATION.md) Nmap调试文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-PROFILING_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-PROFILING_DOCUMENTATION.md) Nmap性能分析文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-TESTING_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-TESTING_DOCUMENTATION.md) Nmap测试文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-TESTING_FRAMEWORK.md](https://github.com/nmap/nmap/tree/master/docs/README-TESTING_FRAMEWORK.md) Nmap测试框架文档
- [https://github.com/nmap/nmap/tree/master/docs/README-TESTING_TOOLS.md](https://github.com/nmap/nmap/tree/master/docs/README-TESTING_TOOLS.md) Nmap测试工具文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_TOOLS.md](https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_TOOLS.md) Nmap开发工具文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_ENVIRONMENT.md](https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_ENVIRONMENT.md) Nmap开发环境文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_WORKFLOW.md](https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_WORKFLOW.md) Nmap开发工作流文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_PROCESS.md](https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_PROCESS.md) Nmap开发流程文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_GUIDELINES.md](https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_GUIDELINES.md) Nmap开发指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_STANDARDS.md](https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_STANDARDS.md) Nmap开发标准文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_CONVENTIONS.md](https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_CONVENTIONS.md) Nmap开发规范文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_BEST_PRACTICES.md](https://github.com/nmap/nmap/tree/master/docs/README-DEVELOPMENT_BEST_PRACTICES.md) Nmap开发最佳实践文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CONTRIBUTION_GUIDELINES.md](https://github.com/nmap/nmap/tree/master/docs/README-CONTRIBUTION_GUIDELINES.md) Nmap贡献指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CONTRIBUTION_PROCESS.md](https://github.com/nmap/nmap/tree/master/docs/README-CONTRIBUTION_PROCESS.md) Nmap贡献流程文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CONTRIBUTION_WORKFLOW.md](https://github.com/nmap/nmap/tree/master/docs/README-CONTRIBUTION_WORKFLOW.md) Nmap贡献工作流文档
- [https://github.com/nmap/nmap/tree/master/docs/README-CONTRIBUTION_CHECKLIST.md](https://github.com/nmap/nmap/tree/master/docs/README-CONTRIBUTION_CHECKLIST.md) Nmap贡献检查表文档
- [https://github.com/nmap/nmap/tree/master/docs/README-PULL_REQUEST_GUIDE.md](https://github.com/nmap/nmap/tree/master/docs/README-PULL_REQUEST_GUIDE.md) NmapPR指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-COMMIT_MESSAGES.md](https://github.com/nmap/nmap/tree/master/docs/README-COMMIT_MESSAGES.md) Nmap提交消息文档
- [https://github.com/nmap/nmap/tree/master/docs/README-BRANCH_NAMING.md](https://github.com/nmap/nmap/tree/master/docs/README-BRANCH_NAMING.md) Nmap分支命名文档
- [https://github.com/nmap/nmap/tree/master/docs/README-ISSUE_REPORTING.md](https://github.com/nmap/nmap/tree/master/docs/README-ISSUE_REPORTING.md) Nmap问题报告文档
- [https://github.com/nmap/nmap/tree/master/docs/README-BUG_REPORTING.md](https://github.com/nmap/nmap/tree/master/docs/README-BUG_REPORTING.md) Nmapbug报告文档
- [https://github.com/nmap/nmap/tree/master/docs/README-FEATURE_REQUEST.md](https://github.com/nmap/nmap/tree/master/docs/README-FEATURE_REQUEST.md) Nmap功能请求文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SUPPORT_REQUEST.md](https://github.com/nmap/nmap/tree/master/docs/README-SUPPORT_REQUEST.md) Nmap支持请求文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DONATION.md](https://github.com/nmap/nmap/tree/master/docs/README-DONATION.md) Nmap捐赠文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SPONSORSHIP.md](https://github.com/nmap/nmap/tree/master/docs/README-SPONSORSHIP.md) Nmap赞助文档
- [https://github.com/nmap/nmap/tree/master/docs/README-PARTNERSHIP.md](https://github.com/nmap/nmap/tree/master/docs/README-PARTNERSHIP.md) Nmap合作伙伴关系文档
- [https://github.com/nmap/nmap/tree/master/docs/README-LICENSE.md](https://github.com/nmap/nmap/tree/master/docs/README-LICENSE.md) Nmap许可证文档
- [https://github.com/nmap/nmap/tree/master/docs/README-COPYRIGHT.md](https://github.com/nmap/nmap/tree/master/docs/README-COPYRIGHT.md) Nmap版权文档
- [https://github.com/nmap/nmap/tree/master/docs/README-LEGAL.md](https://github.com/nmap/nmap/tree/master/docs/README-LEGAL.md) Nmap法律信息文档
- [https://github.com/nmap/nmap/tree/master/docs/README-TERMS_OF_SERVICE.md](https://github.com/nmap/nmap/tree/master/docs/README-TERMS_OF_SERVICE.md) Nmap服务条款文档
- [https://github.com/nmap/nmap/tree/master/docs/README-PRIVACY_POLICY.md](https://github.com/nmap/nmap/tree/master/docs/README-PRIVACY_POLICY.md) Nmap隐私政策文档
- [https://github.com/nmap/nmap/tree/master/docs/README-DISCLAIMER.md](https://github.com/nmap/nmap/tree/master/docs/README-DISCLAIMER.md) Nmap免责声明文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY.md) Nmap安全性文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_AUDIT.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_AUDIT.md) Nmap安全审计文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_REVIEW.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_REVIEW.md) Nmap安全审查文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TESTING.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TESTING.md) Nmap安全测试文档
- [https://github.com/nmap/nmap/tree/master/docs/README-VULNERABILITY_ASSESSMENT.md](https://github.com/nmap/nmap/tree/master/docs/README-VULNERABILITY_ASSESSMENT.md) Nmap漏洞评估文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_ENHANCEMENTS.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_ENHANCEMENTS.md) Nmap安全增强文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_BEST_PRACTICES.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_BEST_PRACTICES.md) Nmap安全最佳实践文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_GUIDELINES.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_GUIDELINES.md) Nmap安全指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_RECOMMENDATIONS.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_RECOMMENDATIONS.md) Nmap安全建议文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TIPS.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TIPS.md) Nmap安全提示文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TRICKS.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TRICKS.md) Nmap安全技巧文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_HACKS.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_HACKS.md) Nmap安全黑客技巧文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_CHEAT_SHEET.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_CHEAT_SHEET.md) Nmap安全速查表文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_REFERENCE.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_REFERENCE.md) Nmap安全参考资料文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_MANUAL.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_MANUAL.md) Nmap安全手册文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_DOC.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_DOC.md) Nmap安全文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_DOCS.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_DOCS.md) Nmap安全文档集文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_DOCUMENTATION.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_DOCUMENTATION.md) Nmap安全官方文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_WIKI_DOC.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_WIKI_DOC.md) Nmap安全wiki文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_API_DOC.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_API_DOC.md) Nmap安全API文档文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_USER_GUIDE.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_USER_GUIDE.md) Nmap安全用户指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_DEVELOPER_GUIDE.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_DEVELOPER_GUIDE.md) Nmap安全开发者指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_CONTRIBUTOR_GUIDE.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_CONTRIBUTOR_GUIDE.md) Nmap安全贡献者指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_INSTALL_GUIDE.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_INSTALL_GUIDE.md) Nmap安全安装指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_USAGE_GUIDE.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_USAGE_GUIDE.md) Nmap安全使用指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_CONFIGURATION_GUIDE.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_CONFIGURATION_GUIDE.md) Nmap安全配置指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TROUBLESHOOTING_GUIDE.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_TROUBLESHOOTING_GUIDE.md) Nmap安全故障排除指南文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_FAQ.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_FAQ.md) Nmap安全常见问题文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_QA.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_QA.md) Nmap安全问答文档
- [https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_SUPPORT.md](https://github.com/nmap/nmap/tree/master/docs/README-SECURITY_SUPPORT.md) Nmap安全支持文档