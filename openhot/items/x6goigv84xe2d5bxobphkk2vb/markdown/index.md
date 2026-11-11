# 某团队开源 Rust 编译器生成器，通过两次Futamura投影实现自动编译

> 原标题：A Second Futamura Projection

- 来源：Lobsters 热榜
- 发布时间：2026-11-03T16:14:27.370Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/x6goigv84xe2d5bxobphkk2vb
- 原文：https://blog.veitheller.de/A_Second_Futamura_Projection.html

## 摘要

某团队在 GitHub 公开 Rust 编译器生成器仓库，展示如何通过两次Futamura投影将 Brainfuck 解释器转化为编译器。核心方法包括：1）使用 Lisp 宏扩展和特殊化过程生成中间代码；2）通过 memo 机制处理递归调用；3）对比手动编写编译器与自动化生成的性能差异。代码仓库包含 Fig. 10-14 的实现细节，并附有脚注解释技术难点。
