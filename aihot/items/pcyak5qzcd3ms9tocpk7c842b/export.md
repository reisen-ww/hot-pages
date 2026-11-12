# Hugging Face发布多向量嵌入模型压缩训练方法

> 原标题：Token Pooling-Aware Training for Multi-Vector Embedding Models

- 来源：Hugging Face Blog
- 发布时间：2026-11-11T00:00:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/pcyak5qzcd3ms9tocpk7c842b
- 原文：https://huggingface.co/blog/token-pooling

## 摘要

Hugging Face发布token pooling-aware训练方法，通过Ward层次聚类将平均文档向量数压缩至原值的25%（pool_factor=4），在NanoBEIR@13测试集上nDCG@10从49.03提升至51.23（+2.20），同时保持检索质量。

## 推荐理由

原文提供了可复用的token pooling训练方法，展示了在压缩存储量（74.8% fewer vectors）的同时提升检索性能（nDCG@10从49.03提升至51.23），并包含完整代码和模型下载链接。
