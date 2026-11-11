# Restate TypeScript SDK 新增持久化协程功能，单机可处理千万级并发请求

> 原标题：Durable Coroutines for TypeScript

- 来源：Hacker News 热榜
- 发布时间：2026-11-04T14:42:00.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/d2y75131qmeonxy0vlqnu7f1g
- 原文：https://restate.dev/blog/durable_coroutines

## 摘要

Restate 在 GitHub 发布 TypeScript 持久化协程库，通过 generator 函数实现确定性调度，单机可处理 >10,000 毫秒级并发请求，P50=2.5ms / P99=9ms。示例代码展示如何用 spawn() 启动并行工具调用，select() 实现竞态组合，并支持失败恢复的持久化执行模型。

## 推荐理由

相比传统工作流方案，Restate的持久化协程在每步操作中仅增加毫秒级延迟，支持千万级并发场景
