# Airbnb 如何通过成本每任务优化 Amazon Bedrock 上的编码智能体部署

> 原标题：How Airbnb uses cost per task to operate coding agents on Amazon Bedrock

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-18T21:48:19.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/ujxbw5icn7kbreexedfelwgt0
- 原文：https://aws.amazon.com/blogs/machine-learning/how-airbnb-uses-cost-per-task-to-operate-coding-agents-on-amazon-bedrock/

## 摘要

Airbnb 通过成本每任务和实时监控优化智能体部署，指导模型选择与资源分配。具体方法包括：1）在模型发布后立即运行自定义任务集的评估（evals），记录每个模型在8个维度的得分及成本；2）通过CloudWatch监控生产环境指标（如请求延迟、令牌消耗），对比评估结果与实际使用差异；3）根据成本/任务和性能调整默认模型及推理强度上限。

## 推荐理由

通过成本每任务和实时监控优化智能体部署，指导模型选择与资源分配
