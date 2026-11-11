# PHP 发布 8.5.12 等版本修复两个可远程执行代码的漏洞，并说明安全流程改革

> 原标题：Today's PHP security release, and how we're strengthening security

- 来源：Hacker News 热榜
- 发布时间：2026-10-21T15:48:56.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/bh8ainjctas69916ozijlhq6m
- 原文：https://thephp.foundation/blog/2026/10/21/todays-php-security-release-and-how-were-strengthening-php-security/

## 摘要

PHP 项目发布 8.5.12、8.4.27、8.3.36 和 8.2.35，修复两个关键漏洞：CVE-2026-109618（内存耗尽导致的内存损坏，可在 Apache mod_php 默认配置下由未认证请求触发远程代码执行）和 CVE-2026-109619（致命错误遗留的过期状态导致释放后使用，已在真实应用上演示远程代码执行），实际 CVSS 评分为 9.2。
