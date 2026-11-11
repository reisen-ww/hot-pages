# 如何用 vLLM 双向 KV cache 传输改善多轮智能体工作负载的 TTFT

> 原标题：Improve TTFT for multi-turn agentic workloads with bi-directional KV transfer in vLLM

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-19T16:03:23.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/nccdq95fjdkx33u1qriqsq1yz
- 原文：https://aws.amazon.com/blogs/machine-learning/improve-ttft-for-multi-turn-agentic-workloads-with-bi-directional-kv-transfer-in-vllm/

## 摘要

在 Amazon EC2 P5en 的 1P1D 部署基准中，vLLM 双向 KV cache 传输使 Qwen3-32B 的 TTFT 最多降低 1.6 倍、zai-org/GLM-5-FP8 最多降低 3.3 倍。
