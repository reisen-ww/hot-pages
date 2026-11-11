# 基于 Strands Agents 构建自适应智能体框架（AAIF）

> 原标题：Adaptive agentic intelligence framework using Strands Agents

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-21T21:23:26.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/tgagh9nhi03d591z57bvrhqb1
- 原文：https://aws.amazon.com/blogs/machine-learning/adaptive-agentic-intelligence-framework-using-strands-agents/

## 摘要

AWS 基于 Strands Agents 构建自适应智能体框架（AAIF），用轻量 SLM llama3.2:1b 作为编排层对请求分类，常规任务经 Ollama 在本地处理，复杂分析经 boto3 路由到 Amazon Bedrock 的前沿模型。
