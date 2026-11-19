# Salesforce 在 AWS SageMaker AI 中实现跨区域推理路由提升全球模型服务能力

> 原标题：How Salesforce is advancing global-scale model serving with cross-Region inference routing in Amazon SageMaker AI

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-18T20:13:18.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/ucpy5c8spoakeqlv6rpuagx4q
- 原文：https://aws.amazon.com/blogs/machine-learning/how-salesforce-is-advancing-global-scale-model-serving-with-cross-region-inference-routing-in-amazon-sagemaker-ai/

## 摘要

Salesforce 在 AWS SageMaker AI 中通过跨区域推理路由机制，解决了多区域模型服务中的容量碎片化问题。测试显示，当本地模型过载时，路由器可在1分钟内将78%的请求切换至其他区域，同时保持数据驻留合规性。该方案通过统一路由逻辑替代各应用独立实现，降低架构复杂度。

## 推荐理由

展示了如何通过跨区域推理路由解决模型服务中的容量与可用性平衡问题，提供可复用的架构设计
