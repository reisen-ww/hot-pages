# 某开发者提出SCROLL协议解决Webhook数据同步困境

> 原标题：The valley of webhooks

- 来源：Lobsters 热榜
- 发布时间：2026-11-04T02:10:26.147Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/sh6gs6urk2oucniblw3w7zd9n
- 原文：https://weli.dev/blog/the-valley-of-webhooks/

## 摘要

某开发者分享其三次重复构建Webhook同步系统的经历，指出现有方案存在数据顺序混乱、删除事件缺失、依赖人工校验等问题。提出SCROLL协议草案，通过消费者主动拉取有序日志实现数据同步，包含自动验证、删除事件标记、无状态同步等机制，已发布GitHub仓库供社区测试与反馈。
