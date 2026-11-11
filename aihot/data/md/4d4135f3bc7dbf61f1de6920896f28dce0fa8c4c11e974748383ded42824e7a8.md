# StateBench 测试语言模型长文档状态跟踪能力

> 原标题：StateBench: Testing how language models track state changes over long documents

- 来源：Hugging Face Blog
- 发布时间：2026-11-03T17:15:21.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/htaex263hy82eiymckhadl247
- 原文：https://huggingface.co/blog/allenai/statebench

## 摘要

StateBench 测试发现，Transformer 架构在长序列状态跟踪中表现不足，而 Gated DeltaNet 通过直接训练能更好处理复杂任务。实验展示了四个难度级别的状态跟踪问题，并指出前沿模型如 Gemini 3.8 Flash 在超过 64,000 tokens 输入时准确率骤降至 13% 以下。
