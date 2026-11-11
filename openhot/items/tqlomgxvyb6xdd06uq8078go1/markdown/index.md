# Neki 设计最小中断的计划切换方案

> 原标题：Designing a planned switchover for minimum disruption

- 来源：Lobsters 热榜
- 发布时间：2026-11-03T08:20:13.016Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/tqlomgxvyb6xdd06uq8078go1
- 原文：https://planetscale.com/blog/designing-a-planned-switchover-for-minimum-disruption

## 摘要

Neki 在计划切换过程中通过预检验证、同步复制和客户端恢复三个阶段，最小化了写操作中断的时间。与未计划的故障切换不同，计划切换无需故障检测，可以直接选择合适的副本进行更新。Neki 通过缓冲查询和调整主节点的事务模式，确保在切换期间主节点仍可接受读操作，同时保持同步复制，避免因单个副本慢或不可用而阻塞切换。
