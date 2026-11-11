# Pivot数据库通过分槽机制优化Top K聚合查询性能

> 原标题：Can GROUP BY still be optimized after all these years?

- 来源：Hacker News 热榜
- 发布时间：2026-11-03T16:30:23.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/teqhv3imm4hvrrcwl3n9a2pc9
- 原文：https://pivotlake.io/blog/know-your-limit-faster-top-k-aggregation/

## 摘要

Pivot数据库团队发布新型Top K聚合优化方法，在测试中使响应时间缩短60%（35.6ms→22.2ms），并减少70%的分区处理量。该方法通过将每个分区划分为固定数量的槽位，利用哈希值映射到槽位，仅合并对Top K结果有贡献的槽位。

## 推荐理由

Pivot数据库通过引入分槽机制优化了Top K聚合查询，在测试中使响应时间缩短60%，并减少70%的分区处理量。
