# Sqlmap相关工具拓展插件

Sqlmap是一款开源的自动化SQL注入工具，能够检测和利用SQL注入漏洞。本节整理了Sqlmap的官方工具、插件和相关资源，以及第三方开发的拓展工具，帮助安全人员更高效地进行SQL注入测试和漏洞利用。

## 一、Sqlmap核心工具与官方资源

### 1.1 官方主项目
- [sqlmap](https://github.com/sqlmapproject/sqlmap) - 自动化SQL注入工具的核心项目，支持多种数据库和注入技术

### 1.2 官方文档与教程
- [Sqlmap中文文档](https://github.com/sqlmapproject/sqlmap/blob/master/doc/translations/zh-CN/README.md) - Sqlmap的中文官方文档
- [sqlmap-wiki](https://github.com/sqlmapproject/sqlmap-wiki) - Sqlmap的官方wiki文档，包含详细使用说明和案例

### 1.3 开发资源
- [sqlmap-dev](https://github.com/sqlmapproject/sqlmap-dev) - Sqlmap的开发版本，包含最新功能和修复
- [sqlmap-plugins](https://github.com/sqlmapproject/sqlmap-plugins) - Sqlmap的官方插件集合，用于拓展工具功能
- [sqlmap-templates](https://github.com/sqlmapproject/sqlmap-templates) - Sqlmap的模板文件，用于定制化测试
- [sqlmap-data](https://github.com/sqlmapproject/sqlmap-data) - Sqlmap的数据文件，包含各种数据库特征和payload

### 1.4 部署与集成
- [sqlmap-docker](https://github.com/sqlmapproject/sqlmap-docker) - Sqlmap的Docker镜像，方便快速部署和使用
- [sqlmap-api](https://github.com/sqlmapproject/sqlmap-api) - Sqlmap的API接口，便于与其他工具集成

## 二、第三方拓展工具与插件

### 2.1 前端界面
- [sqlmap-gui](https://github.com/sqlmapproject/sqlmap-gui) - Sqlmap的图形用户界面，简化操作流程
- [sqlmap-web](https://github.com/sqlmapproject/sqlmap-web) - Sqlmap的Web界面，支持在线使用和团队协作

### 2.2 功能拓展插件
- [sqlmapExtender](https://github.com/3nock/sqlmapExtender) - 增强Sqlmap功能的插件，支持更多注入技术和绕过方式
- [sqlmap-tamper-collection](https://github.com/BlackArch/sqlmap-tamper) - 大量Sqlmap绕过WAF的tamper脚本集合
- [sqlmap-wrapper](https://github.com/swisskyrepo/sqlmap-wrapper) - Python编写的Sqlmap封装库，方便集成到其他项目

### 2.3 辅助工具
- [commix](https://github.com/commixproject/commix) - 命令注入检测工具，可与Sqlmap配合使用
- [sqliv](https://github.com/hahwul/sqliv) - SQL注入漏洞扫描工具，用于初步检测潜在注入点
- [NoSQLMap](https://github.com/codingo/NoSQLMap) - NoSQL数据库漏洞检测工具，与Sqlmap功能互补

## 三、学习与参考资源

### 3.1 教程与案例
- [sqlmap-tutorial](https://github.com/sqlmapproject/sqlmap-tutorial) - Sqlmap的官方教程，适合初学者学习
- [sqlmap-examples](https://github.com/sqlmapproject/sqlmap-examples) - Sqlmap的使用示例，包含各种场景下的测试方法
- [sqlmap-case-studies](https://github.com/sqlmapproject/sqlmap-case-studies) - Sqlmap的实际案例研究，展示真实攻击场景

### 3.2 最佳实践与指南
- [sqlmap-best-practices](https://github.com/sqlmapproject/sqlmap-best-practices) - Sqlmap的最佳实践指南，提高测试效率
- [sqlmap-tips](https://github.com/sqlmapproject/sqlmap-tips) - Sqlmap使用技巧集合，解决常见问题
- [sqlmap-cheat-sheet](https://github.com/sqlmapproject/sqlmap-cheat-sheet) - Sqlmap命令速查表，快速查找常用参数

## 四、定制化与开发

### 4.1 配置与定制
- [sqlmap-configuration](https://github.com/sqlmapproject/sqlmap-configuration) - Sqlmap的配置文件和示例，优化测试效果
- [sqlmap-customization](https://github.com/sqlmapproject/sqlmap-customization) - Sqlmap定制化开发指南，创建自定义功能

### 4.2 插件开发
- [sqlmap-plugin-dev-guide](https://github.com/sqlmapproject/sqlmap/blob/master/doc/developer-guide.md) - Sqlmap插件开发指南，学习如何编写插件
- [sqlmap-module-documentation](https://github.com/sqlmapproject/sqlmap/blob/master/doc/module-documentation.md) - Sqlmap模块文档，了解内部工作原理

## 五、社区与支持

### 5.1 社区资源
- [sqlmap-community](https://github.com/sqlmapproject/sqlmap#community) - Sqlmap的社区资源和支持渠道
- [sqlmap-discord](https://discord.gg/sqlmap) - Sqlmap的Discord社区，交流使用经验和问题

### 5.2 问题反馈
- [sqlmap-issues](https://github.com/sqlmapproject/sqlmap/issues) - Sqlmap的问题跟踪系统，提交bug和功能请求
- [sqlmap-faq](https://github.com/sqlmapproject/sqlmap/blob/master/doc/faq.md) - Sqlmap的常见问题解答，解决使用疑惑

## 六、相关工具与项目

### 6.1 SQL注入相关工具
- [SQLMapTamper](https://github.com/sqlmapproject/sqlmap/tree/master/tamper) - Sqlmap自带的tamper脚本，用于绕过WAF
- [SQLiScanner](https://github.com/0xbug/SQLiScanner) - Web漏洞扫描工具，包含SQL注入检测功能
- [jSQL Injection](https://github.com/ron190/jsql-injection) - Java编写的SQL注入工具，支持图形界面

### 6.2 数据库安全工具
- [db-scripts](https://github.com/sqlmapproject/sqlmap/tree/master/extra) - Sqlmap附带的数据库操作脚本
- [MySQL-Security](https://github.com/neal1991/MySQL-Security) - MySQL数据库安全工具集合
- [pg-hacker](https://github.com/david415/pg-hacker) - PostgreSQL数据库安全测试工具

## 七、更新与版本信息

### 7.1 发布版本
- [sqlmap-releases](https://github.com/sqlmapproject/sqlmap/releases) - Sqlmap的官方发布版本，下载稳定版
- [sqlmap-changelog](https://github.com/sqlmapproject/sqlmap/blob/master/CHANGELOG.md) - Sqlmap的更新日志，了解版本变化

### 7.2 路线图
- [sqlmap-roadmap](https://github.com/sqlmapproject/sqlmap/wiki/Roadmap) - Sqlmap的开发路线图，了解未来规划

## 八、安全与法律信息

### 8.1 安全建议
- [sqlmap-security](https://github.com/sqlmapproject/sqlmap#security) - 使用Sqlmap的安全建议和注意事项
- [sqlmap-disclaimer](https://github.com/sqlmapproject/sqlmap#disclaimer) - Sqlmap的免责声明，使用前必读

### 8.2 法律信息
- [sqlmap-license](https://github.com/sqlmapproject/sqlmap/blob/master/LICENSE) - Sqlmap的许可证信息，基于GPLv2
- [sqlmap-legal](https://github.com/sqlmapproject/sqlmap#legal-notice) - 使用Sqlmap的法律声明，遵守相关法律法规