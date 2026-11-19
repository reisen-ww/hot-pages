# AWS推出Bedrock AgentCore Gateway与Skyflow数据保护方案

> 原标题：Protect agent tool calls with Skyflow and Amazon Bedrock AgentCore Gateway

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-19T18:14:36.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/i9z6bwjr21ctmkxp6vglkmzvj
- 原文：https://aws.amazon.com/blogs/machine-learning/protect-agent-tool-calls-with-skyflow-and-amazon-bedrock-agentcore-gateway/

## 摘要

AWS通过Skyflow拦截器与Bedrock AgentCore Gateway的集成，实现AI代理工具调用中敏感数据的双向保护：请求端自动脱敏，响应端智能恢复。方案支持文档存储（如S3/Box/Google Drive）和第三方API调用，通过AWS Systems Manager配置策略，无需 redeploy 即可生效。案例显示可防止客户姓名、邮箱等数据泄露至外部工具或模型。

## 推荐理由

原文给出了Skyflow拦截器在AWS Bedrock AgentCore Gateway中的部署方案，可迁移至企业现有AI代理工作流，无需修改代理或工具代码。
