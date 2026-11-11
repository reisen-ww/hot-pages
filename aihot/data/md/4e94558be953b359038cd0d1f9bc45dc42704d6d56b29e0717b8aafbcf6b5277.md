# Amazon Bedrock 知识库管理服务新增三种检索模式

> 原标题：Single-shot and agentic retrieval with Amazon Bedrock Managed Knowledge Base

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-09T20:13:18.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/pkjnvhd3a4p9u4638bv5nkhmv
- 原文：https://aws.amazon.com/blogs/machine-learning/single-shot-and-agentic-retrieval-with-amazon-bedrock-managed-knowledge-base/

## 摘要

AWS推出Amazon Bedrock知识库管理服务的新检索模式，支持单次检索生成答案（maxAgentIteration=1）、纯检索返回原文（maxAgentIteration=0）及多步骤智能检索（maxAgentIteration=2-5）。示例场景包括银行账户开立文档检索（单次模式）、多政策对比（多步骤模式）及政策原文调阅（纯检索模式）。

## 推荐理由

原文给出了三种API模式的适用场景和配置方法，开发者可根据需求平衡响应速度与答案质量。
