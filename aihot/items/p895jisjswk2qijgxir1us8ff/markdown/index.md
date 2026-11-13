# AWS实现跨组织多智能体协作的A2A协议部署与验证

> 原标题：Build composable, interoperable multi-agent systems with A2A on AWS

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-12T15:42:21.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/p895jisjswk2qijgxir1us8ff
- 原文：https://aws.amazon.com/blogs/machine-learning/build-composable-interoperable-multi-agent-systems-with-a2a-on-aws/

## 摘要

AWS通过A2A协议实现跨组织多智能体系统：1. 企业端使用LangChain+Bedrock构建协调智能体，2. SaaS服务端基于Strands SDK部署合规检查智能体，3. 双向调用通过OAuth 2.0实现安全认证。系统包含VPC隔离、Cognito多账户认证、Bedrock模型动态切换等特性，并提供完整的Jupyter部署脚本及安全边界测试流程。

## 推荐理由

原文提供了跨组织多智能体系统的端到端部署方案，包括A2A协议使用、AWS服务集成和双向身份验证机制，读者可据此复现并优化企业级AI协作流程。
