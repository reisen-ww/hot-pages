# FastBCP 1.6发布：无需恢复SQL Server备份直接导出表到Parquet

> 原标题：Exporting tables from a SQL Server backup (.bak) to Parquet without restoring it

- 来源：Hacker News 热榜
- 发布时间：2026-11-05T15:33:49.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/o9b9a0wf0yww59i7kpfuudk92
- 原文：https://blog.arpe.io/fastbcp-1-6-export-sql-server-backup-to-parquet

## 摘要

FastBCP 1.6版本发布，支持从SQL Server备份文件直接导出表到Parquet格式，无需恢复数据库或安装SQL Server实例。实测导出175百万行表仅需29.6秒，比传统方法快2.2倍，且支持多线程处理和不同数据库加载。
