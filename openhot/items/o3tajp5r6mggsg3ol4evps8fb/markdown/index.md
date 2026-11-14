# ggml 1.0.0 发布：废弃旧 API 并优化多平台性能

> 原标题：Ggml v1.0.0

- 来源：Hacker News 热榜
- 发布时间：2026-11-14T02:28:29.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/o3tajp5r6mggsg3ol4evps8fb
- 原文：https://github.com/ggml-org/ggml/releases/tag/v1.0.0

## 摘要

ggml 1.0.0 版本发布，废弃 deprecated 公共 API 并引入 FP8 支持。核心改进包括：CUDA平台优化稀疏矩阵乘法和FlashAttention预填充，Metal/Vulkan平台实现MoE调度器与内存管理改进，OpenCL平台增强解码性能，WebGPU新增批量张量API支持。所有变更均通过 #1690 提交记录验证。
