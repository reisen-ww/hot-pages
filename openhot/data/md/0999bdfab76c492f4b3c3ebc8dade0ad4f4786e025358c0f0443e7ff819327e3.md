# Linux内核vsyscall机制安全隐患及移除方案分析

> 原标题：On vsyscalls and the vDSO (2011)

- 来源：Lobsters 热榜
- 发布时间：2026-11-05T09:12:04.405Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/hrqpu0jksks374zk3v36p1vt5
- 原文：https://lwn.net/Articles/446528/

## 摘要

Linux内核移除vsyscall机制以增强安全性，但引发兼容性与性能争议。关键措施包括删除相关指令、将变量移至独立页并添加配置选项CONFIG_UNSAFE_VSYSCALLS。社区对选项名称存在激烈争论（Linus称其为'政治化命名'），最终方案可能影响旧版glibc用户的时间函数调用效率。
