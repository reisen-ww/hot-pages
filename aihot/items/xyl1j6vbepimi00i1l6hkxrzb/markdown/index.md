# Amazon Bedrock 支持显式提示缓存功能

> 原标题：Use prompt caching with open-weight models on Amazon Bedrock

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-16T15:42:41.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/xyl1j6vbepimi00i1l6hkxrzb
- 原文：https://aws.amazon.com/blogs/machine-learning/use-prompt-caching-with-open-weight-models-on-amazon-bedrock/

## 摘要

Amazon Bedrock 现已支持显式提示缓存功能，用户可以通过 Chat Completions API 使用两种模式（显式和隐式）进行缓存。隐式缓存会自动重用前缀内容，适用于稳定的对话和循环；显式缓存则允许用户标记可重用的前缀边界，适用于不同变化率的内容。使用缓存可以减少输入成本和响应延迟。
