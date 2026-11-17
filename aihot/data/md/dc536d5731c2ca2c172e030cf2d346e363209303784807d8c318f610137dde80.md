# ArisGlobal 在 Amazon Bedrock 上实现生成式AI推理规模化

> 原标题：How ArisGlobal scaled generative AI inference on Amazon Bedrock

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-17T15:57:09.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/hd0wr7mx7331q05jblouzeguq
- 原文：https://aws.amazon.com/blogs/machine-learning/how-arisglobal-scaled-generative-ai-inference-on-amazon-bedrock/

## 摘要

ArisGlobal 通过调整prompt顺序和缓存策略，在AWS Bedrock上实现生成式AI推理规模化。核心成果：65%输入token来自共享prefix缓存，有效成本降低50%，月度支出减少40%，同时支持15%更多企业租户。关键设计将稳定prefix前置并设置缓存点，在保持EU跨区域推理不变的前提下优化成本结构。

## 推荐理由

原文提供了可复用的prompt缓存策略及成本优化数据，适合企业AI部署参考
