# AWS EC2 Spot 实例优化 AssemblyAI 语音转文本推理成本

> 原标题：Cost-optimizing AssemblyAI speech-to-text inference on AWS with Amazon EC2 Spot

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-13T19:35:35.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/ivg5vvprclkacqf1e96o0k0bh
- 原文：https://aws.amazon.com/blogs/machine-learning/cost-optimizing-assemblyai-speech-to-text-inference-on-aws-with-amazon-ec2-spot/

## 摘要

通过混合EC2 Spot实例与队列重试机制，实现70%成本节约并保持服务可用性。具体架构采用Amazon ECS集群管理GPU实例（g4dn/g5/g6），结合SQS队列实现中断自动恢复，并在欧洲AWS区域部署独立架构满足数据合规要求。

## 推荐理由

通过混合EC2 Spot实例与队列重试机制，实现70%成本节约并保持服务可用性
