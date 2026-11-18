# Amazon Bedrock AgentCore 大JSON负载下降低token成本与延迟的优化实践

> 原标题：Reducing token costs and latency in Amazon Bedrock AgentCore JSON workloads

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-17T22:44:51.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/nssotndgv036yduu3soqhsyhb
- 原文：https://aws.amazon.com/blogs/machine-learning/reducing-token-costs-and-latency-in-amazon-bedrock-agentcore-json-workloads/

## 摘要

在处理20MB+ JSON数据时，通过将大JSON数据持久化存储（Amazon S3）、分页加载（get_result_page_tool）和字典结构化压缩（_oversized_descriptor），将token消耗降低71%，平均响应延迟从15.4秒降至3.1秒。

## 推荐理由

通过将大JSON数据持久化存储、分页加载和字典结构化压缩，在Amazon Bedrock AgentCore中实现token成本降低71%、平均响应延迟降低80%的优化方案。
