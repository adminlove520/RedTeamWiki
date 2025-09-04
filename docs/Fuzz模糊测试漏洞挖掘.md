# Fuzz模糊测试漏洞挖掘

本章节收集整理了模糊测试领域的工具、技术和资源，帮助安全研究人员进行漏洞挖掘和安全测试工作。模糊测试是一种通过向目标系统输入大量随机或精心构造的数据来发现潜在安全漏洞的技术。

## 通用模糊测试框架

- [AFL](https://github.com/google/AFL) - American Fuzzy Lop，一种覆盖率引导的模糊测试工具
- [FuzzingTool](https://github.com/antonio-morales/FuzzingTool) - 模糊测试工具集合，集成多种模糊测试技术
- [fuzzthis](https://github.com/TheColonial/fuzzthis) - 自动模糊测试工具，简化模糊测试流程
- [FuzzFasterThanLight](https://github.com/ProjectUnicornLab/FuzzFasterThanLight) - 高性能模糊测试工具，专注于速度优化
- [libFuzzer](https://llvm.org/docs/LibFuzzer.html) - LLVM内置的覆盖率引导模糊测试引擎
- [Honggfuzz](https://github.com/google/honggfuzz) - 谷歌开发的多线程模糊测试工具

## 语言特定模糊测试工具

- [python-afl](https://github.com/jwilk/python-afl) - 集成AFL到Python程序的工具，用于Python代码的模糊测试
- [afl-rust](https://github.com/mothran/afl-rust) - 集成AFL到Rust程序的工具，支持Rust代码的覆盖率引导模糊测试
- [go-fuzz](https://github.com/dvyukov/go-fuzz) - Go语言的模糊测试工具
- [js-fuzz](https://github.com/fuzzitdev/js-fuzz) - JavaScript模糊测试工具
- [jvm-fuzz](https://github.com/rohanpadhye/JQF) - Java虚拟机模糊测试框架

## Web应用模糊测试工具

- [fuzzweb](https://github.com/m000/fuzzweb) - HTTP模糊测试工具，专为Web应用程序设计
- [Burp Suite Intruder](https://portswigger.net/burp/documentation/desktop/tools/intruder) - Burp Suite的模糊测试组件
- [OWASP ZAP Fuzzer](https://www.zaproxy.org/docs/desktop/addons/fuzzer/) - OWASP ZAP的模糊测试插件
- [wfuzz](https://github.com/xmendez/wfuzz) - 用于Web应用漏洞检测的模糊测试工具
- [ffuf](https://github.com/ffuf/ffuf) - 快速Web模糊测试工具

## 特定领域模糊测试工具

- [fuzzware](https://github.com/uds-se/fuzzware) - 嵌入式固件模糊测试工具，专为嵌入式系统设计
- [cryptofuzz](https://github.com/guidovranken/cryptofuzz) - 密码学算法模糊测试工具，用于发现密码学实现中的漏洞
- [Amass](https://github.com/OWASP/Amass) - 网络资产发现和模糊测试工具，专注于域名和子域名枚举
- [aircrack-ng](https://github.com/aircrack-ng/aircrack-ng) - WiFi网络模糊测试工具，用于无线网络安全评估
- [peach](https://github.com/peachfuzzer/peach) - 跨平台模糊测试框架，支持多种协议
- [syzkaller](https://github.com/google/syzkaller) - 操作系统内核模糊测试工具

## 模糊测试辅助工具

- [afl-cov](https://github.com/vanhauser-thc/afl-cov) - 用于分析AFL模糊测试覆盖情况的工具，帮助评估测试效果
- [static-binaries](https://github.com/andrew-d/static-binaries) - 静态编译的工具集合，包括AFL等模糊测试工具，便于在不同环境中运行
- [fuzzilli](https://github.com/googleprojectzero/fuzzilli) - JavaScript引擎模糊测试工具
- [honggfuzz-cov](https://github.com/google/honggfuzz/tree/master/honggfuzz-cov) - Honggfuzz的覆盖率分析工具
- [driller](https://github.com/shellphish/driller) - 混合符号执行和模糊测试的工具

## 模糊测试字典和数据库

- [fuzz.txt](https://github.com/Bo0oM/fuzz.txt) - 模糊测试常用字符串列表，包含各种特殊字符和边界值
- [fuzzdb](https://github.com/fuzzdb-project/fuzzdb) - 模糊测试数据库，收集了大量针对不同漏洞类型的测试用例
- [SecLists](https://github.com/danielmiessler/SecLists) - 安全测试列表集合，包含模糊测试字典、常用密码等资源
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - 包含多种模糊测试载荷的资源集合
- [wfuzz-vectors](https://github.com/xmendez/wfuzz/tree/master/wordlists) - Wfuzz的模糊测试向量集合

## 模糊测试资源与框架

- [google/fuzzing](https://github.com/google/fuzzing) - 模糊测试工具和指南集合，提供模糊测试最佳实践
- [metasploit-framework](https://github.com/rapid7/metasploit-framework) - 包含模糊测试模块的渗透测试框架，可用于漏洞利用开发
- [oss-fuzz](https://github.com/google/oss-fuzz) - 开源软件模糊测试平台
- [FuzzBench](https://github.com/google/fuzzbench) - 模糊测试工具基准测试框架
- [Fuzzing Book](https://www.fuzzingbook.org/) - 模糊测试技术电子书，涵盖理论和实践