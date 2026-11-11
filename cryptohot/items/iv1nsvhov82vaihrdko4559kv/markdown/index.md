# Lightning Labs 发布 LND 紧急修复以应对 Linux 内核严重漏洞

> 原标题：Matt Corallo Flags Critical Linux Kernel Flaw; Lightning Labs Ships LND Mitigation

- 来源：Bitcoin Magazine
- 发布时间：2026-11-04T18:31:56.000Z
- 金融热点：https://reisen-ww.github.io/hot-pages/cryptohot/items/iv1nsvhov82vaihrdko4559kv
- 原文：https://bitcoinmagazine.com/news/matt-corallo-flags-critical-linux-kernel-flaw-lightning-labs-ships-lnd-mitigation

## 摘要

Lightning Labs 发布 LND v0.21.6-beta 和 v0.20.7-beta 紧急修复，关闭 MPTCP 默认监听以应对 Linux 内核漏洞 CVE-2026-98432（CVSS 9.8）。漏洞可能被利用实现远程 root 权限，已影响约 21 万台暴露 MPTCP 的服务器。修复措施为临时方案，需升级完整内核才能彻底解决。

## 推荐理由

原文提供了漏洞 CVSS 评分、修复版本号及具体技术措施（关闭 MPTCP 默认监听），读者可据此评估自身 LND 节点风险等级。
