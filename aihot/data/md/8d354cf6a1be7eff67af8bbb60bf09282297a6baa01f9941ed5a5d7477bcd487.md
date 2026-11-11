# GPT-OSS-20B 在 Amazon SageMaker HyperPod 上微调以实现多语言推理

> 原标题：Fine-tuning GPT-OSS-20B for multilingual reasoning on Amazon SageMaker HyperPod

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-20T17:48:27.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/qgkanbmulhmw9cvehkx3jq98t
- 原文：https://aws.amazon.com/blogs/machine-learning/fine-tuning-gpt-oss-20b-for-multilingual-reasoning-on-amazon-sagemaker-hyperpod/

## 摘要

在 Amazon SageMaker HyperPod 上通过 SFT 和 GRPO 微调 GPT-OSS-20B，使其推理语言正确率从 22% 提升到 100%，答案语言从 62% 提升到 70%。SFT 负责教授模型不具备的行为，GRPO 在已有行为基础上进一步优化，Qwen2.5-7B 对照实验验证了这一模式。
