# PostgreSQL 19 发布内置在线表膨胀清理工具 REPACK

> 原标题：Postgres 19 REPACK: Built-In Online Table Bloat Cleanup

- 来源：Lobsters 热榜
- 发布时间：2026-11-03T22:44:48.698Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/y2iztyytg6jr6gzvrhzdk0q40
- 原文：https://www.snowflake.com/en/blog/engineering/postgres-19-repack-table-bloat/

## 摘要

Snowflake宣布PostgreSQL 19新增REPACK命令，支持在线清理表膨胀。测试显示493MB表经REPACK(Concurrency)处理后耗时9.4秒，磁盘空间缩减54%；对比VACUUM FULL需2.7秒但锁定整个表。功能需2倍存储空间，要求表有可索引主键且启用WAL。

## 推荐理由

通过对比REPACK不同模式的时间消耗和性能影响，为数据库管理提供可量化的决策依据。
