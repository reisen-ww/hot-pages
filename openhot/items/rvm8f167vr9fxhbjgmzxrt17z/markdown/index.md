# Skylake-X 中的 Next-Page Prefetcher 反汇编

> 原标题：Reversing the Next-Page Prefetcher in Skylake-X

- 来源：Lobsters 热榜
- 发布时间：2026-11-18T21:15:49.528Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/rvm8f167vr9fxhbjgmzxrt17z
- 原文：https://devsh0.github.io/microarchitecture,/intel,/computer-architecture/2026/11/17/reversing-the-next-page-prefetcher-in-skylake-x.html

## 摘要

这篇文章详细描述了作者如何反汇编 Skylake-X 中的 Next-Page Prefetcher，并探讨了其触发机制、预取的 PTE 数量及加载位置。作者通过配置性能监控事件、启动和停止计数器来分析该预取器的行为，揭示了其工作原理。
