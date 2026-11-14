# Amazon SageMaker HyperPod数据捕获助力模型优化飞轮

> 原标题：Build a model improvement flywheel with Amazon SageMaker HyperPod Data Capture

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-13T18:01:15.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/g2q66un3csjmgeguf3k5r21u8
- 原文：https://aws.amazon.com/blogs/machine-learning/build-a-model-improvement-flywheel-with-amazon-sagemaker-hyperpod-data-capture/

## 摘要

本文展示了如何利用Amazon SageMaker HyperPod数据捕获功能，记录实时推理数据并分析。通过Athena查询发现新家电品类识别盲区，编写SQL标签策略后进行LoRA微调，最终使新类别识别准确率从0%提升至100%，同时不影响原有类别表现。完整代码和测试数据在GitHub仓库中提供，支持在HyperPod集群上部署端到端闭环。

## 推荐理由

通过生产数据捕获和Athena分析，指导模型微调，提升新类别识别准确率。
