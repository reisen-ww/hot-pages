# PostgreSQL任务队列在高并发下的性能瓶颈测试与优化建议

> 原标题：Just how far can the FOR UPDATE SKIP LOCKED Postgres queue go?

- 来源：Lobsters 热榜
- 发布时间：2026-11-07T15:20:23.952Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/qefn3uggk466as3i518z6p24n
- 原文：https://garbagecollected.io/posts/postgres-task-queue-where-it-breaks/

## 摘要

作者通过实验发现：在1CPU/1GB内存限制下，使用FOR UPDATE SKIP LOCKED的PostgreSQL队列在64 worker时CPU已达86%，128 worker时失败率29%。优化后使用20连接池，128 worker时吞吐量提升至652 jobs/s，但Python主进程占用CPU。实验表明PostgreSQL队列在高并发时受连接数和CPU限制，建议采用客户端连接池优化。
