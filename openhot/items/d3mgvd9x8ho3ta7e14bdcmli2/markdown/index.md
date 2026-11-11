# Go团队发布新JSON库v2，解决长期兼容与性能问题

> 原标题：A new Go API for JSON

- 来源：Hacker News 热榜
- 发布时间：2026-11-04T17:52:11.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/d3mgvd9x8ho3ta7e14bdcmli2
- 原文：https://go.dev/blog/jsonv2

## 摘要

Go团队在v1.27版本中发布encoding/json/v2，修复了无效UTF-8静默损坏、重复键名兼容性等15年遗留问题，并优化性能使部分场景提升10倍。新增MarshalWrite/UnmarshalRead等流式API，支持自定义序列化逻辑。附详细迁移指南与性能对比数据

## 推荐理由

Go 1.27正式发布新JSON库v2，解决无效UTF-8处理、重复字段名等长期问题，并优化性能达10倍，提供详细迁移指南
