# 如何在 AWS 上用 Strategy Mosaic 和 Amazon Bedrock AgentCore 为 agentic AI 构建语义层

> 原标题：Build a semantic layer for agentic AI on AWS with Strategy Mosaic and Amazon Bedrock AgentCore

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-20T15:36:39.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/bz9eczz6t3jfr1sf3ps4954a4
- 原文：https://aws.amazon.com/blogs/machine-learning/build-a-semantic-layer-for-agentic-ai-on-aws-with-strategy-mosaic-and-amazon-bedrock-agentcore/

## 摘要

该教程用 Strategy Mosaic 作为语义层，以两个 linked model 跨 Amazon Redshift 和 Amazon Aurora 建模 Customer 360，无需 ETL，并通过 Mosaic MCP server 把模型开放给托管在 Amazon Bedrock AgentCore runtime 上的 Strands agent。
