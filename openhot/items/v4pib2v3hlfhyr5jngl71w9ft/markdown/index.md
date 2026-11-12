# Linux内核路由查找性能演变与安全修复影响分析

> 原标题：Performance evolution of route lookup on Linux

- 来源：Lobsters 热榜
- 发布时间：2026-11-11T08:25:31.231Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/v4pib2v3hlfhyr5jngl71w9ft
- 原文：https://vincent.bernat.ch/en/blog/2026-linux-performance-ipv4-ipv6-route-lookup

## 摘要

作者在AMD EPYC 8024P和Zen 4c CPU上测试了Linux 2.6.32至7.3内核的路由查找性能，发现6.5版本引入的SRSO安全修复导致IPv6性能下降约20 cycles，而IPv4性能受影响较小（约4 cycles）。
