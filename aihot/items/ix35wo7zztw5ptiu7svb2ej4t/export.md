# TCS基于AWS Bedrock AgentCore构建智能测试编排器

> 原标题：How TCS built an agentic test orchestrator with Amazon Bedrock AgentCore

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-10T16:59:43.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/ix35wo7zztw5ptiu7svb2ej4t
- 原文：https://aws.amazon.com/blogs/machine-learning/how-tcs-built-an-agentic-test-orchestrator-with-amazon-bedrock-agentcore/

## 摘要

TCS基于AWS Bedrock AgentCore构建智能测试编排器，将BFSI行业测试效率提升88%。该方案通过分阶段专用代理（生成场景、代码验证、执行等）实现需求到证据的全流程自动化，采用租户级隔离（独立Kubernetes命名空间、S3桶、KMS密钥）保障金融安全，并利用AWS EKS/ECS/CloudFront等基础设施实现弹性执行与可视化监控。

## 推荐理由

展示了如何通过专用AI代理和AWS服务提升BFSI行业测试效率，并实现多租户安全隔离
