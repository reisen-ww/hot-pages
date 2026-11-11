# Linux 系统安全加固的实用指南

> 原标题：Practical guide on out of tree mitigations on Linux

- 来源：Lobsters 热榜
- 发布时间：2026-11-06T08:53:27.739Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ja77h66ivuzvbs1y7sjp9e367
- 原文：https://clehaxze.tw/gemlog/2026/11-04-practical-guide-on-out-of-tree-mitigations-on-linux.gmi

## 摘要

某开发者分享Linux系统安全加固的详细配置方法，包括内存分配器（hardened_malloc/mimalloc/Scudo）替换、systemd系统调用过滤（禁用fork/exec、限制路径访问）、Shadow Stack硬件防护技术，以及针对PHP-FPM的深度绑定修复方案。
