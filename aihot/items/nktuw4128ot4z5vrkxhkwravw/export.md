# 如何设计经久耐用的 AI serving harness

> 原标题：Designing an AI serving harness built to last

- 来源：MIT Technology Review · AI
- 发布时间：2026-10-22T21:17:29.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/nktuw4128ot4z5vrkxhkwravw
- 原文：https://www.technologyreview.com/2026/10/22/1146109/designing-an-ai-serving-harness-built-to-last/

## 摘要

设计经久耐用的 AI serving harness 应从工作负载而非模型出发，先用延迟、并发、内存压力、GPU 利用率等约束决定架构。优化前先测量、找出主导瓶颈：KV cache 随并发与上下文增长可能先耗尽 GPU 显存，盲目加算力只会更贵。架构要为变化而建，让模型更换成为评估与配置决策而非推倒重来；EXL 的 Engineering the Harness 系列有更深入探讨。
