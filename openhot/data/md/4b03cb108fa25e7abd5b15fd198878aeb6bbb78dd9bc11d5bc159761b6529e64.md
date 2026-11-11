# Building Barista: Postgres 事务处理提升数据一致性

> 原标题：Building Barista: Postgres, Embeddings, and Jev

- 来源：Reddit r/programming
- 发布时间：2026-11-04T16:16:55.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/k3mzqrj0zzbzt28iwjpusn32v
- 原文：https://www.reddit.com/r/programming/comments/1xnsc70/building_barista_postgres_embeddings_and_jev/

## 摘要

作者介绍了一种在 Postgres 中处理消息队列的方法，通过在一个事务中完成处理、保存结果和入队下个阶段的操作，确保数据一致性，避免了双重写入问题和出箱模式的使用。这种方法不依赖 Kafka，而是通过 not_before 列实现重试，并使用拒绝表处理死信，每个阶段通过时间戳列推进用户调度。
