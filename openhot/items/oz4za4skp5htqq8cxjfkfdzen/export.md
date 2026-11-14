# Meta 扩展 LLDB 支持跨 CPU/GPU 应用调试

> 原标题：Extending LLDB to Debug Applications That Span CPUs and GPUs

- 来源：Hacker News 热榜
- 发布时间：2026-11-11T00:48:14.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/oz4za4skp5htqq8cxjfkfdzen
- 原文：https://engineering.fb.com/2026/11/09/developer-tools/extending-lldb-to-debug-applications-that-span-cpus-and-gpus/

## 摘要

Meta 开发了 LLDB 扩展架构，支持跨 CPU 和 GPU 应用的调试，并已部分上游至 LLVM。该架构通过分离共享调试器基础设施与硬件特定控制，将 CPU 和 GPU 作为独立调试目标呈现，同时保持统一工作流。测试验证了架构的通用性，目前已有部分代码上游至 LLVM。
