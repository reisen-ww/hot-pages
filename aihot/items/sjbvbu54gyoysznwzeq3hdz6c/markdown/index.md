# Hugging Face 发布 HOPE 方法：基于专家交互的第二代剪枝技术

> 原标题：Your Experts Have Partners. There's HOPE for Keeping Them Together

- 来源：Hugging Face Blog
- 发布时间：2026-11-09T12:34:29.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/sjbvbu54gyoysznwzeq3hdz6c
- 原文：https://huggingface.co/blog/amazon/higher-order-pruning-experts

## 摘要

Hugging Face 发布 HOPE 方法，在50%剪枝率下模型性能最佳，平均排名提升至1.58，显著优于REAP等第一代方法。该方法通过二次规划优化专家间交互，适用于Qwen3.5-122B、Qwen3.5-35B-A3B等MoE架构模型，提供完整代码实现流程（校准、求解、剪枝）。

## 推荐理由

提出了一种考虑专家间交互的剪枝方法HOPE，在50%剪枝率下模型性能最佳，平均排名提升至1.58，显著优于REAP等第一代方法
