# AWS Bedrock AgentCore远程运行Claude Code任务及安全控制指南

> 原标题：Extend Claude Code to remote sessions on Amazon Bedrock AgentCore with security controls

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-06T16:45:58.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/pbnvlbgelsmnkgqze8ns95ucq
- 原文：https://aws.amazon.com/blogs/machine-learning/extend-claude-code-to-remote-sessions-on-amazon-bedrock-agentcore-with-security-controls/

## 摘要

AWS通过Bedrock AgentCore实现Claude Code远程任务运行，每个任务在独立微虚拟机中执行，使用临时IAM凭证调用Bedrock模型，并通过GitHub PR提交可审查的代码变更。安全控制包括零操作员访问（ZOA）、数据零保留（ZDR）、私有VPC网络、模型调用日志隔离等。部署需15-25分钟，支持本地Claude Code插件和网页控制台两种提交方式。

## 推荐理由

原文提供了使用Amazon Bedrock AgentCore远程运行Claude Code任务的完整步骤，并强调其安全控制机制，如零操作员访问、数据保留控制等，对开发者实现安全高效的分布式代码代理有参考价值。
