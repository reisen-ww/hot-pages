# Futhark 语言作者分析其非确定性来源及性能优化方案

> 原标题：Nondeterminism in Futhark

- 来源：Lobsters 热榜
- 发布时间：2026-11-06T19:16:01.378Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/djms1hstuo6fao8qrte1mwlfd
- 原文：https://futhark-lang.org/blog/2026-11-04-nondeterminism.html

## 摘要

Futhark 语言作者分析其非确定性来源及性能优化方案。作者在 IFL2026会议上提出，非确定性主要来自浮点运算和编程错误（如未检查的scatter操作和未验证的reduce运算符）。通过对比行列树求和方式与内置reduce的性能，指出硬件依赖可能导致结果差异，但未提供具体性能数据。
