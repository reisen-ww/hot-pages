# 使用 Okta Cross App Access 和 Amazon Bedrock AgentCore 管理 AI 代理访问

> 原标题：Govern AI agent access with Okta Cross App Access and Amazon Bedrock AgentCore – Part 1

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-06T17:09:18.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/mdum5wufe27ngslq61k5ou424
- 原文：https://aws.amazon.com/blogs/machine-learning/govern-ai-agent-access-with-okta-cross-app-access-and-amazon-bedrock-agentcore-part-1/

## 摘要

本文介绍了如何使用 Okta Cross App Access (XAA) 和 Amazon Bedrock AgentCore 构建和优化大规模 AI 代理。在测试中，AgentCore Identity 在请求中增加了约 0.6 秒的时间，而 Okta 的控制措施在管理员移除用户与代理的关联后，约 1 秒内拒绝了代理的新请求，且已颁发的令牌在 5 分钟内失效。
