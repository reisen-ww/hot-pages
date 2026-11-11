# Eon 如何用 Amazon Bedrock AgentCore 的 MCP Gateway 构建多云调查体系

> 原标题：How Eon built multi-cloud investigation with an MCP Gateway on Amazon Bedrock AgentCore

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-20T15:57:57.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/v6ml5ww9qnw3djbblyniujwnz
- 原文：https://aws.amazon.com/blogs/machine-learning/how-eon-built-multi-cloud-investigation-with-an-mcp-gateway-on-amazon-bedrock-agentcore/

## 摘要

Eon 用 Amazon Bedrock AgentCore Gateway 替代了分散的工具凭证与本地 MCP 进程，新工程师接入全部调查工具从约 2 天缩短到约两分钟。该网关以 Cedar 策略做最小权限控制，让开发者与运行在 Amazon Bedrock 上的 Claude SRE agent 通过单一 MCP URL 访问跨 AWS、GCP、Azure 的工具。
