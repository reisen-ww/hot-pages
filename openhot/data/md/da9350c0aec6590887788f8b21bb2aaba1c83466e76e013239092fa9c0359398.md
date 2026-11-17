# 形式化验证的 C 编译器能否达到与 gcc -O2 相当的性能？

> 原标题：Can a formally-verified C compiler be as performant as gcc -O2?

- 来源：Lobsters 热榜
- 发布时间：2026-11-17T12:45:22.430Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ie825xdc9oe6yxjelj017vuw3
- 原文：https://ut-infraai.github.io/2026/11/13/trying-to-make-compcert-as-fast-as-gcc-o2/

## 摘要

CompCert 是一个用 Rocq 和 OCaml 编写的正式验证 C 编译器，它通过一系列验证过的优化生成 x86-64 汇编代码，确保优化不改变程序行为。然而，CompCert 目前的性能比 gcc -O2 慢约 28% 至 55%。研究发现，主要差距在于 CompCert 的语义模型限制了某些优化，如整数溢出处理、类型相关性假设、融合乘加运算和 SIMD 向量化。
