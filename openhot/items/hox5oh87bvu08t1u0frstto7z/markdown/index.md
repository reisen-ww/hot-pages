# FreeBSD bhyve虚拟机活迁移支持首次完整实现

> 原标题：Live-migration support in FreeBSD and bhyve coming

- 来源：Hacker News 热榜
- 发布时间：2026-11-13T19:58:42.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/hox5oh87bvu08t1u0frstto7z
- 原文：https://gyptazy.com/blog/freebsd-bhyve-live-migration-support-rfc/

## 摘要

作者在GitHub发布基于FreeBSD 15.1的bhyve虚拟机活迁移实现，实测单机迁移停机时间138-171ms，支持多vCPU协议和内存一致性检查。当前状态为WIP RFC，已规划存储网络交接和自动化测试方案，后续将扩展设备支持和性能优化。

## 推荐理由

提供了首次完整的bhyve活迁移实现，包含测试数据与后续开发路线图
