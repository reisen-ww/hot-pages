# Linum 开源 Apache 2.0 授权的 Rust 写文本到图像模型，训练成本约2万美元

> 原标题：Show HN: A decent text-to-image model trained for ~$20K (Apache 2.0 Weights)

- 来源：Hacker News 热榜
- 发布时间：2026-11-04T16:45:11.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/vvz12bukcdpqfm4a5op98dak6
- 原文：https://www.linum.ai/field-notes/pjit-21k

## 摘要

Linum团队在GitHub开源基于Rust的文本到图像模型，训练成本约2万美元。该模型采用Pyramid-JiT架构，通过像素空间模型压缩注意力上下文窗口4倍，在512x512分辨率下训练610M样本，并新增1024x1024分辨率训练阶段。

## 推荐理由

开源了训练成本约2万美元的Rust文本到图像模型，提供完整架构设计与训练参数对比，开发者可参考其Pyramid-JiT架构优化思路。
