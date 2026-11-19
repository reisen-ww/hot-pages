# AWS Bedrock AgentCore 大规模JSON数据处理优化策略

> 原标题：Reducing token costs and latency in Amazon Bedrock AgentCore JSON workloads

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-17T22:44:51.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/nssotndgv036yduu3soqhsyhb
- 原文：https://aws.amazon.com/blogs/machine-learning/reducing-token-costs-and-latency-in-amazon-bedrock-agentcore-json-workloads/

## 摘要

某航空调度平台通过三重优化策略将AI代理处理20MB+ JSON数据的token消耗降低71%，平均响应延迟从15.4秒降至3.1秒。核心方法包括：1) 使用Amazon S3存储重载数据，仅保留轻量级引用（策略1）；2) 对工具响应分页加载（策略2）；3) 对嵌套字典输出结构化摘要（策略3）。

## 推荐理由

通过将大型JSON数据持久化存储到S3并采用分页和结构化摘要策略，将请求token消耗降低71%，平均响应延迟从15.4秒降至3.1秒
