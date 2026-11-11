# PyTorch 2.15 为 Mac 的 MPS 后端带来 FP8 与更快的 LLM 解码

> 原标题：MPS in PyTorch 2.15

- 来源：Hugging Face Blog
- 发布时间：2026-10-20T00:00:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/vnwdbfau3ylf7vn1ayray6t24
- 原文：https://huggingface.co/blog/mps-pytorch-2-15

## 摘要

PyTorch 2.15 为 Mac 的 MPS 后端带来 FP8（float8_e4m3fn）张量与 F.scaled_mm，显存占用减半；MoE 模型解码比 2.14 快 5–6.5 倍。

## 推荐理由

文章用具体吞吐与内存数字说明 MPS 后端改进如何改变 Mac 上的本地推理体验。
