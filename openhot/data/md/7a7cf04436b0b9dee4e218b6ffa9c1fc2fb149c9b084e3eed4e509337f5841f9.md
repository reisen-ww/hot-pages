# Onehouse 发布 Lakegres 向量搜索，支持 Hudi/Iceberg 表直接索引

> 原标题：Lakegres: Vector search on existing Open/Hudi/Iceberg tables

- 来源：Hacker News 热榜
- 发布时间：2026-11-18T17:41:48.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/kijl8p1y33pd96ay7e5j276w2
- 原文：https://www.onehouse.ai/blog/lakegres-vector-search-on-open-table-formats

## 摘要

Onehouse 在 GitHub 公开 Lakegres 仓库，通过 Rust 开发在 Hudi/Iceberg 表上直接存储向量索引，无需迁移数据格式。性能测试显示其冷启动查询延迟 536ms（竞品 8242ms），构建速度比 Databricks AI Search 快 18 倍。
