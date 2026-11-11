# 使用 EDB Postgres AI 和 Amazon Bedrock AgentCore 构建智能代理语义层

> 原标题：Build a semantic layer for agentic AI with EDB Postgres AI and Amazon Bedrock AgentCore

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-03T16:41:13.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/bjwwcg14f4g696uebkjfif2dd
- 原文：https://aws.amazon.com/blogs/machine-learning/build-a-semantic-layer-for-agentic-ai-with-edb-postgres-ai-and-amazon-bedrock-agentcore/

## 摘要

本文介绍了如何使用 EDB Postgres AI 构建智能代理语义层，该层嵌入到操作型 Postgres 数据库中，并通过 Amazon Bedrock AgentCore 的 MCP 端点暴露给外部代理。通过示例展示了如何利用 Postgres 的 COMMENT、GRANT 和行级安全机制实现细粒度访问控制，以及如何通过 OpenTelemetry 记录 SQL 执行的跟踪信息。
