# vLLM 基于推送的 KV 传输：改善分离推理的 TTFT 与 TPOT

> 原标题：Push-based KV transfer to improve TTFT and TPOT for disaggregated inference in vLLM

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-19T16:05:17.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/v5r0f7uz91kkefbj85ojqg3gy
- 原文：https://aws.amazon.com/blogs/machine-learning/push-based-kv-transfer-to-improve-ttft-and-tpot-for-disaggregated-inference-in-vllm/

## 摘要

vLLM 新增基于推送（push-based）的 NIXL connector，把 KV cache 传输的协调与设置移出关键路径，从而降低 TTFT 与 TPOT。
