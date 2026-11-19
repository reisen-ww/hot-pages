# Xint团队披露nginx五个高危漏洞，需立即更新至1.31.9

> 原标题：nginx2root

- 来源：Lobsters 热榜
- 发布时间：2026-11-18T15:28:56.196Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/rp1ymdqmuq5wze58a9qsrpesa
- 原文：https://xint.io/blog/nginx2root-remote-code-execution

## 摘要

Xint研究团队在nginx中发现五个未认证远程代码执行漏洞（CVE-2026-123007至CVE-2026-113425）。其中CVE-2026-123007存在于1.9.5至1.31.8所有版本，攻击者可通过HTTP/2控制窗口溢出触发内存破坏。
