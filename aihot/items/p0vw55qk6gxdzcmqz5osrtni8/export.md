# 超越 KV cache：在 AWS Trainium2 上用原生 PyTorch 训练与服务 i14 Laplace 3B 线性注意力模型

> 原标题：Beyond the KV cache: Training and serving i14’s Laplace 3B linear attention model on AWS Trainium2 with native PyTorch

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-20T21:14:10.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/p0vw55qk6gxdzcmqz5osrtni8
- 原文：https://aws.amazon.com/blogs/machine-learning/beyond-the-kv-cache-training-and-serving-i14s-laplace-3b-linear-attention-model-on-aws-trainium2-with-native-pytorch/

## 摘要

i14 与 AWS 合作，用 TorchNeuron Native 原生 PyTorch 将 Laplace 3B 线性注意力模型适配到 AWS Trainium2。模型推理状态固定为每序列 29.5 MB、与上下文长度无关；单台 trn2.48xlarge 训练约 120,000 tokens/s，1,280 并发序列推理达每秒 11,544 输出 tokens。
