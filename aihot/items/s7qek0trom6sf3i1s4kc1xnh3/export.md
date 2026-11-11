# 如何在 AWS Trainium 上用 torchtitan 训练 Qwen3

> 原标题：Train Qwen3 on AWS Trainium with torchtitan

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-21T20:00:22.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/s7qek0trom6sf3i1s4kc1xnh3
- 原文：https://aws.amazon.com/blogs/machine-learning/train-qwen3-on-aws-trainium-with-torchtitan/

## 摘要

在单台 trn2.48xlarge 上，torchtitan-neuron 提供三种训练 Qwen3 的方式：Transformers v5 建模后端、torchtitan 原生 Qwen3、以及挂载 Neuron Kernel Interface (NKI) MoE kernel。
