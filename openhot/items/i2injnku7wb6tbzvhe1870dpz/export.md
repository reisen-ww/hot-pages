# Brotli 解码器漏洞 CVE-2026-111497 从 Node2Shell 扩散至 Python 及多语言 HTTP 组件

> 原标题：Node2Shell evolves to HTTP2Shell, blast radius affects many HTTP libs and apps

- 来源：Hacker News 热榜
- 发布时间：2026-10-24T08:06:39.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/i2injnku7wb6tbzvhe1870dpz
- 原文：https://www.aikido.dev/blog/python-packages-vulnerable-node2shell-brotli-cve-2026-111497

## 摘要

Google Brotli 解码器漏洞 CVE-2026-111497（CVSS 4.0 评分 9.2）影响 1.0.3 至 1.2.0 版本，10 月 21 日 Node.js 披露为 node2shell，随后 Python 及更多语言与 HTTP 服务应用被确认受影响。

## 推荐理由

梳理了漏洞从 Node.js 扩散到 Python 及各语言的补丁时间线，可据此排查依赖树并选择升级或临时禁用 Brotli 解码。
