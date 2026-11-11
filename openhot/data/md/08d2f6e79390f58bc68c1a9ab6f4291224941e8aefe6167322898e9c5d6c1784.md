# 某团队在musl Linux上实现NVIDIA驱动兼容性

> 原标题：Making musl and proprietary NVIDIA drivers work together

- 来源：Lobsters 热榜
- 发布时间：2026-11-06T13:23:14.985Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/qhgrhqq8ni17idwyihwr8h0ru
- 原文：https://chimera-linux.org/news/2026/11/musl-nvidia.html

## 摘要

某团队在GitHub公开了musl Linux与NVIDIA驱动兼容性方案，支持RTX 2000系列及部分旧卡，包含GLVND库适配、gcompat兼容层、TLS补丁及动态链接器修改。测试显示部分成功，需进一步优化。
