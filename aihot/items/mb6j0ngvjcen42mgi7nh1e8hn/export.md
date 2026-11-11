# TorchNeuron 性能分析（第 1 部分）：AWS Trainium 上的系统级 profiling

> 原标题：Profiling TorchNeuron (Part 1): System-level profiling on AWS Trainium.

- 来源：Hugging Face Blog
- 发布时间：2026-10-21T16:04:43.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/mb6j0ngvjcen42mgi7nh1e8hn
- 原文：https://huggingface.co/blog/amazon/profiling-torchneuron-part-1

## 摘要

TorchNeuron 性能分析系列第 1 部分从零讲解如何在 AWS Trainium 上用 torch.profiler 配置 Neuron 后端，通过 key_averages() 表定位消耗 Neuron 设备时间的算子。
