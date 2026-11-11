# AWS EKS 上使用 Ray Train DLCs 和 EFA 进行分布式训练

> 原标题：Distributed training with Ray Train DLCs and EFA on EKS

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-28T18:19:54.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/psjqiapai6r3kp7xzyowji3y2
- 原文：https://aws.amazon.com/blogs/machine-learning/distributed-training-with-ray-train-dlcs-and-efa-on-eks/

## 摘要

AWS发布Ray Train DLCs和EFA在EKS上的分布式训练方案，通过预构建容器镜像和KubeRay实现跨GPU实例高效通信。以Qwen2.5-1.5B模型为例，展示如何利用v1.1版本DLC在g6.12xlarge实例上部署8GPU集群，验证EFA路径使训练速度提升。
