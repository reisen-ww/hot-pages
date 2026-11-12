# 基于线性规划的模型权重优化：Astra循环问题修正方法对比分析

> 原标题：Can a Linear Program Do Weight-Space Programming?

- 来源：Hacker News 热榜
- 发布时间：2026-11-11T12:30:17.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/mdvy36e21p5oej46adfpmpbgi
- 原文：https://nathan.rs/posts/weight-space-lp/

## 摘要

MIT CSAIL的Astra模型通过线性规划优化权重，在MATH-500测试中准确率从7.9%提升至48.1%。作者对比了两种方法：Astra的原始方法修改130,188个权重参数，而线性规划版本仅修改16,291个（减少87%）。

## 推荐理由

对比Astra的原始方法与线性规划优化，展示如何通过数学建模减少权重修改量，并验证了在模型推理时直接添加方向向量的可行性
