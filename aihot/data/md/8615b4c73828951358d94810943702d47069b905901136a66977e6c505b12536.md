# AWS Bedrock 管理知识库迁移指南：通过 Agent Toolkit 实现平滑过渡

> 原标题：Migrate to Amazon Bedrock Managed Knowledge Base with your coding agent

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-12T16:16:45.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/md0qt5r8zrd3dmziw7o3bmvus
- 原文：https://aws.amazon.com/blogs/machine-learning/migrate-to-amazon-bedrock-managed-knowledge-base-with-your-coding-agent/

## 摘要

AWS官方指南详细说明了如何通过Agent Toolkit将客户管理知识库迁移至Bedrock管理知识库。核心步骤包括：1）使用Explore模式预检配置映射和权限策略；2）生成IaC迁移模板或创建新管理知识库；3）验证检索结果一致性（需注意managed KB的检索结果格式与客户管理KB不同）；4）通过AWS CloudTrail追踪审批后的资源变更。

## 推荐理由

原文提供了从客户管理知识库迁移到AWS Bedrock Managed Knowledge Base的完整步骤、工具使用指南和成本对比分析，读者可据此规划迁移流程并评估成本效益。
