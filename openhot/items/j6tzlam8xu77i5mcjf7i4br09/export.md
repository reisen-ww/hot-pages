# Prusa打印机固件供应链漏洞披露及修复进展

> 原标题：Never Gonna Print You Up

- 来源：Hacker News 热榜
- 发布时间：2026-11-08T07:15:32.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/j6tzlam8xu77i5mcjf7i4br09
- 原文：https://dixken.de/blog/never-gonna-print-you-up

## 摘要

作者通过Opus 4.8模糊测试和手动逆向工程，在Prusa打印机固件中发现14个安全漏洞，其中PFB-008实现远程代码执行（CVSS 8.1）。漏洞涉及G-code解析、USB交互、MMU内存管理等多个模块，影响15种打印机型号。
