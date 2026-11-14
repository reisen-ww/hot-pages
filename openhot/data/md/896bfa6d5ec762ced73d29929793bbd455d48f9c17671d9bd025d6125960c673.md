# Jane Street 实习生开发 OxCaml 高性能并行动态编译器

> 原标题：Writing a DSL for high performance parallel programming in OxCaml

- 来源：Lobsters 热榜
- 发布时间：2026-11-14T02:57:49.133Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/em0fv5l6674vp6xor3kaalmuv
- 原文：https://blog.janestreet.com/writing-a-dsl-for-high-performance-parallel-programming-in-oxcaml/

## 摘要

Jane Street 实习生 Sai Konkimalla 开发了一款基于 OxCaml 的动态编译器，支持 SIMD 高性能并行计算。该编译器通过运行时元编程生成 OxCaml 代码，实现跨架构编译，并对比手动代码和 C 实现的基准测试，验证了其性能接近手动代码但不及 C 实现的现状。
