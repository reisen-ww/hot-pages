# Amazon Bedrock 知识库工具实现细粒度访问控制

> 原标题：Fine-grained access control for Amazon Bedrock Managed Knowledge Base tools

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-12T15:40:24.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/kh0mq2ttd3x6nthf0k6iioe8m
- 原文：https://aws.amazon.com/blogs/machine-learning/fine-grained-access-control-for-amazon-bedrock-managed-knowledge-base-tools/

## 摘要

AWS推出Amazon Bedrock知识库工具，通过拦截器注入用户上下文和策略验证，实现多租户环境下的细粒度访问控制。具体机制包括：1. 请求拦截器强制将用户邮箱注入工具调用参数 2. Cedar策略验证注入的用户上下文与JWT邮箱一致 3. 知识库资源策略限制仅特定执行角色可访问 4. 双重防御机制防止LLM或用户绕过权限控制。

## 推荐理由

通过拦截器和策略验证，确保AI代理在多租户环境中仅访问用户授权的数据，提供细粒度访问控制方案。
