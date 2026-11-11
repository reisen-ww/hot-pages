# NVIDIA全栈代码设计如何提升AI工厂内存效率

> 原标题：More Performance From Every Byte: How Full-Stack Codesign Solves AI’s Memory Challenge

- 来源：NVIDIA Blog
- 发布时间：2026-11-05T16:00:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/mtu3hnhbvo1ejtadx8roukllu
- 原文：https://blogs.nvidia.com/blog/memory-full-stack-codesign/

## 摘要

NVIDIA通过全栈代码设计优化AI工厂内存使用，实测吞吐量提升达30倍。关键技术包括：1）采用NVFP4格式将模型权重压缩至4位精度，2）NVL72系统支持72GPU分布式加载模型，3）CMX存储层将闲置上下文迁移至低成本存储，4）NVIDIA Vera CPU加速工具调用缩短上下文缓存空闲时间。

## 推荐理由

原文提供了NVIDIA全栈代码设计如何提升AI工厂内存效率的具体技术路径和实测数据
