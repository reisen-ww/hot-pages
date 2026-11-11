# 基于LangGraph和Amazon Bedrock AgentCore构建每日依赖监控工具

> 原标题：Build a daily dependency watcher with LangGraph and Amazon Bedrock AgentCore web search

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-10T23:34:05.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/iyzb489lxsolx3xb1f21oakbp
- 原文：https://aws.amazon.com/blogs/machine-learning/build-a-daily-dependency-watcher-with-langgraph-and-amazon-bedrock-agentcore-web-search/

## 摘要

AWS推出基于LangGraph和Bedrock AgentCore的Web Search API，实现每日依赖监控工具。测试显示三个分支并行运行仅需36秒（单次顺序运行需99秒），工具通过代码控制日期范围、白名单和搜索次数限制，返回结果包含可验证的来源链接、发布日期和CVE/ advisory ID。

## 推荐理由

通过LangGraph和Bedrock AgentCore的Web Search API实现多分支并行搜索，将依赖监控效率提升至单次运行36秒，并确保规则由代码控制，结果可验证。
