# 某金融团队分析PostgreSQL TOAST系统性能问题及优化方案

> 原标题：Burnt TOAST

- 来源：Lobsters 热榜
- 发布时间：2026-11-04T18:00:32.521Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/to3wf4dcwmhc0vvp93ugu9qoj
- 原文：https://www.pgedge.com/blog/burnt-toast

## 摘要

某金融团队通过实验对比发现，合理利用PostgreSQL TOAST机制可将表体积压缩超9倍，同时优化压缩算法可提升30倍压缩速度。具体包括：1）创建独立数据表分离大字段 2）利用视图实现查询优化 3）对比pglz与lz4压缩算法性能差异。实验数据显示，在100k行测试中lz4压缩速度比pglz快30倍，但pglz在数据量小于1KB时表现更优。
