# Amazon Bedrock 为 Anthropic Claude 模型上线结构化输出

> 原标题：Structured outputs for Anthropic Claude models on Amazon Bedrock

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-19T23:32:19.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/meff4com5wcbtvcdfvji9c1wz
- 原文：https://aws.amazon.com/blogs/machine-learning/structured-outputs-for-anthropic-claude-models-on-amazon-bedrock/

## 摘要

Amazon Bedrock 现已为所有可用的 Anthropic Claude 模型提供结构化输出，在 bedrock-runtime 和 bedrock-mantle 两个端点上返回符合 JSON Schema 的响应，无需自定义解析或重试逻辑。

## 推荐理由

Amazon Bedrock 用约束解码在生成阶段强制 JSON Schema，使 Claude 输出从概率性转为确定性，省去解析与重试逻辑。
