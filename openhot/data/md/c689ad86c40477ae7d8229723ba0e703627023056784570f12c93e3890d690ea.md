# Java4Shell漏洞：OpenJDK Base64解码器远程代码执行利用方法

> 原标题：Java4Shell: RCE in OpenJDK when processing Base64

- 来源：Hacker News 热榜
- 发布时间：2026-11-17T21:11:28.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/s06219w0ojwkjgo37ddgczjkj
- 原文：https://calif.io/java4shell/

## 摘要

Java4Shell漏洞利用方法：通过构造特定Base64编码触发OpenJDK 17.0.6+内存溢出，利用AVX-512硬件加速特性实现远程代码执行。受影响版本包括Oracle Java SE 8u511b33-perf及后续更新。PoC代码展示如何通过200万次Base64解码触发漏洞，并在内存中写入可控数据。修复建议包括禁用Base64硬件加速或AVX-512指令集。

## 推荐理由

提供了完整的漏洞利用PoC代码、受影响版本清单、硬件依赖条件及缓解方案
