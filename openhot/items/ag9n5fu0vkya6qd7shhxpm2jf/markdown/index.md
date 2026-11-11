# ZeBridge – PostgreSQL 复制实例在设备上的本地化实现，通过 NATS 同步

> 原标题：ZeBridge – PostgreSQL replicas on devices, synchronized over NATS

- 来源：Hacker News 热榜
- 发布时间：2026-11-03T17:11:32.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ag9n5fu0vkya6qd7shhxpm2jf
- 原文：https://github.com/ndrean/ZeBridge

## 摘要

ZeBridge 是一个本地 PostgreSQL 复制解决方案，通过 NATS 实现离线写入的排队和同步。每个设备上都保持一个本地数据库副本，当设备重新连接时，通过 NATS 同步更改。此方案适用于 B2B 操作型应用，确保即使在不良网络连接下，数据操作也能最终由 PostgreSQL 进行权威决策。可直接通过 Docker 快速部署示例。
