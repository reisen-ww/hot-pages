# Amazon SageMaker Inference 支持 Multi-Instance GPU 分区以最大化 GPU 利用率

> 原标题：SageMaker Inference now supports Multi-Instance GPU to maximize GPU utilization for model endpoints

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-06T18:01:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/fbvx6gzb3wwwgo49k5gbe3qzt
- 原文：https://aws.amazon.com/blogs/machine-learning/sagemaker-inference-now-supports-multi-instance-gpu-to-maximize-gpu-utilization-for-model-endpoints/

## 摘要

亚马逊 SageMaker Inference 现已支持使用 NVIDIA Multi-Instance GPU (MIG) 对物理 GPU 进行分区，每个分区获得固定的计算单元份额和专用内存块，从而允许在单个端点上部署更多模型并选择更合适的 GPU 大小，同时保持隔离和硬件保证的性能。
