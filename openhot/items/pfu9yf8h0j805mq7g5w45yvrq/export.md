# 从爱因斯坦火车实验到CRDTs：分布式编辑中的并发冲突与解决方案

> 原标题：No Effect Before Its Cause: From Einstein to Lamport

- 来源：Lobsters 热榜
- 发布时间：2026-11-11T18:05:08.811Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/pfu9yf8h0j805mq7g5w45yvrq
- 原文：https://www.itworkslocally.dev/posts/no-effect-before-its-cause

## 摘要

本文通过爱因斯坦的火车实验和Lamport论文，解析CRDTs如何解决分布式编辑中的并发冲突，并关联Yjs实际案例。详细说明CRDTs的三个核心机制（唯一ID、邻居关系、墓碑标记），对比Dynamo风格和Last Write Wins方案，最后以Yjs协作编辑库为例展示应用场景。
