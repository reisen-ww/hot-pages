# 用 AWS CDK 编排 SageMaker AI 端点自动扩缩容

> 原标题：Orchestrating SageMaker AI endpoint auto scaling with AWS CDK

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-23T16:30:10.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/r1kt2vy0epnum7f6kdevsorqc
- 原文：https://aws.amazon.com/blogs/machine-learning/orchestrating-sagemaker-ai-endpoint-auto-scaling-with-aws-cdk/

## 摘要

用可复用的 CDK construct 与 CloudFormation 自定义资源，可在单次部署中自动完成 SageMaker AI 端点更新前后的自动扩缩容注销与注册，同时更新端点配置和扩缩容参数，无需手动干预。
