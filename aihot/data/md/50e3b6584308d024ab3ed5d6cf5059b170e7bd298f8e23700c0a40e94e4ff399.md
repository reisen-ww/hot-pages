# AWS SageMaker AI Serverless 支持全微调（FFT）功能

> 原标题：Full Fine-Tuning (FFT) on SageMaker AI Serverless Model Customization

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-19T00:15:58.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/ehja1jsoxspf4ae0yxn2lyexx
- 原文：https://aws.amazon.com/blogs/machine-learning/full-fine-tuning-fft-on-sagemaker-ai-serverless-model-customization/

## 摘要

AWS SageMaker AI Serverless Model Customization 新增全微调（FFT）功能，实验表明在数据量超过10万条时，FFT的语义正确率（90%）和代码生成质量（BLEU 89.5%）优于LoRA，但需控制学习率（2e-5）和epoch数（3）以避免灾难性遗忘，同时保留MMLU等通用知识。

## 推荐理由

对比了全微调（FFT）与低秩适配（LoRA）在代码生成任务中的表现，并指出FFT在数据量超过10万条时语义正确率（90%）和代码生成质量（BLEU 89.5%）优于LoRA，但需控制学习率（2e-5）和epoch数（3）以避免灾难性遗忘，同时保留MMLU等通用知识。
