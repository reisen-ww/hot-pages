# Rust 内存分配器的工作原理及其性能优化

> 原标题：What is malloc doing, anyway?

- 来源：Lobsters 热榜
- 发布时间：2026-11-09T13:19:22.814Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/jd95x7nkxnphzded8ty5c4m4b
- 原文：https://benmandrew.com/articles/what-is-malloc-doing-anyway

## 摘要

作者通过实验展示了内存分配器的工作原理，包括 brk、sbrk、mmap 等系统调用，以及如何优化分配器以减少系统调用和内存碎片。
