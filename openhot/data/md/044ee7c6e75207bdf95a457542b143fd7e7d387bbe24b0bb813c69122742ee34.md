# Anthropic 开源 Rust 写的证明大语言模型推理系统，单H100每秒110 tokens生成可验证证明

> 原标题：Progress on provable inference for large language models

- 来源：Hacker News 热榜
- 发布时间：2026-11-04T17:17:46.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/fi1wx2bu8v7vr6x5fbzzv38vn
- 原文：https://www.anthropic.com/research/provable-inference

## 摘要

Anthropic 在 GitHub 开源 FlashProve 系统，支持 Llama 4 Maverick 等400B参数模型。单H100 GPU每秒生成110 tokens证明，验证时间约17秒（24核CPU）。系统包含 Lean 形式验证证明、C++ 执行代码及技术文档，按Apache 2.0协议发布。

## 推荐理由

对比现有系统，该方案在H100 GPU上实现每秒110个token的证明速度，验证时间缩短至秒级，并首次在混合专家模型上实现可验证推理。
