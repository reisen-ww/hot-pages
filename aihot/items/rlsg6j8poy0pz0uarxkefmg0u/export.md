# Hugging Face 推出 TorchTPU，让 TPU 成为 PyTorch 原生设备

> 原标题：Hugging Face ❤️ TorchTPU: TPUs, Natively

- 来源：Hugging Face Blog
- 发布时间：2026-10-20T00:00:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/rlsg6j8poy0pz0uarxkefmg0u
- 原文：https://huggingface.co/blog/hf-torchtpu

## 摘要

Hugging Face 发布 TorchTPU，一个为 PyTorch 新增的 TPU 原生后端，Transformers、Diffusers 和 Kernels 可直接在 TPU 上运行，加载模型只需传入 device_map="tpu"。

## 推荐理由

原文对比了 torch_xla 的旧路径并给出安装与调用方式，读者可据此评估在 TPU 上跑 PyTorch 的迁移成本。
