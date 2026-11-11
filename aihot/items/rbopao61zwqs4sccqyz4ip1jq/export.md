# AWS无服务器MCP服务器架构：AI智能体数据湖访问解决方案

> 原标题：Serverless MCP server for AI agent data lake access on Amazon ECS Fargate

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-06T17:13:13.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/rbopao61zwqs4sccqyz4ip1jq
- 原文：https://aws.amazon.com/blogs/machine-learning/serverless-mcp-server-for-ai-agent-data-lake-access-on-amazon-ecs-fargate/

## 摘要

AWS构建无服务器MCP服务器，实现AI智能体与数据湖的自动化集成。系统通过JSON元数据文件配置，无需重复开发SQL接口，支持多租户环境下的权限集中管控和弹性扩展。架构包含认证层、MCP服务器层、工具层和数据更新层，利用Amazon Bedrock和Athena服务，确保15-20秒内完成从自然语言查询到结构化数据返回的全流程。

## 推荐理由

通过配置驱动的架构设计，实现多租户环境下AI智能体与数据湖的无缝集成，提供可复用的工具接口和自动化权限控制方案。
