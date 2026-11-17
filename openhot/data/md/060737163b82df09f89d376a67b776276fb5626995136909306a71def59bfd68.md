# Linux内核NoisyTCP模块存在11年潜伏的CVE-2026-99288远程破坏漏洞

> 原标题：NoisyTCP

- 来源：Lobsters 热榜
- 发布时间：2026-11-16T12:50:29.137Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/kz4kuhq5kosb7smyqehskkg8e
- 原文：https://www.openwall.com/lists/oss-security/2026/11/15/2

## 摘要

Hyunwoo Kim 报告的 NoisyTCP 漏洞（CVE-2026-99288）在 Linux 内核中潜伏了约11年，影响几乎所有发行版，可通过禁用 SYN cookies 或限制 RX 队列临时缓解。触发需特定配置， bare-metal服务器需14小时以上，虚拟机约5-2分钟，攻击者可远程触发导致宿主机崩溃。
