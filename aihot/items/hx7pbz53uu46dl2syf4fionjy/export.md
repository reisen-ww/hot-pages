# SLM 词表专业化如何在实际应用中将推理成本降低 77%

> 原标题：How Specializing the Vocabulary of SLMs Can Cut Inference Cost by 77% in Real Applications

- 来源：Hugging Face Blog
- 发布时间：2026-10-21T17:35:36.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/hx7pbz53uu46dl2syf4fionjy
- 原文：https://huggingface.co/blog/Dharma-AI/vocabx-vocabulary-specialization

## 摘要

Hugging Face 预览 VocabX 论文结果：按每个 token 的成本而非出现频率重建词表，在不更换基座模型的情况下把实测推理成本降低 77%。其生产环境中的葡萄牙语作文自动评分器基于 Qwen3-4B，词表从约 152,000 行缩至约 65,000 行，而该场景中生成一个 token 的成本是读取一个 token 的 7.4 倍。论文仍在评审中，数字在正式发表前可能变化。
