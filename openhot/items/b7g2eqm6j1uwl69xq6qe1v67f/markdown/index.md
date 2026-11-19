# Percona XtraDB Cluster集群节点权重配置的复杂性分析

> 原标题：Just Because You Can, Doesn't Mean You Should: Re-Evaluating Galera Node Weights

- 来源：Hacker News 热榜
- 发布时间：2026-11-18T21:11:10.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/b7g2eqm6j1uwl69xq6qe1v67f
- 原文：https://www.percona.com/blog/just-because-you-can-doesnt-mean-you-should-re-evaluating-galera-node-weights/

## 摘要

Percona技术团队指出，Galera集群节点权重配置会增加管理复杂度，建议遵循KISS原则保持集群简单稳定。文章通过四节点集群案例说明权重分配可能导致单点故障，并对比了使用仲裁器与权重配置的优劣。核心结论：权重机制仅适合特定场景，普通集群应保持节点数量为奇数且权重统一，复杂环境建议采用仲裁器方案而非动态权重分配。
