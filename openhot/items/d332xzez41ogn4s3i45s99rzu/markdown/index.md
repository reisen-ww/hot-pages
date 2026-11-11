# Flink Kafka 连接器如何提交偏移量

> 原标题：How Flink's Kafka connector commits offsets to Kafka

- 来源：Lobsters 热榜
- 发布时间：2026-11-05T16:31:51.666Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/d332xzez41ogn4s3i45s99rzu
- 原文：https://dalelane.co.uk/blog/?p=6161

## 摘要

作者的拉请求被合并到 Flink-connector-kafka 中，详细解释了 Flink 如何使用 Kafka 消费者偏移量。通常，Flink 会在检查点完成后将检查点偏移量提交给 Kafka，但这可能导致监控工具报告错误的滞后。作者提出了一种方法，在安全的情况下仅使用消费者位置来提交偏移量，以解决这一问题。
