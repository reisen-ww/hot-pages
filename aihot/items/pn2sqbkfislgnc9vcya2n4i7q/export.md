# Amazon SageMaker AI 多轮强化学习 MTRL 上手指南

> 原标题：Multi-Turn Reinforcement Learning on Amazon SageMaker AI: A hands-on guide

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-23T17:48:54.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/pn2sqbkfislgnc9vcya2n4i7q
- 原文：https://aws.amazon.com/blogs/machine-learning/multi-turn-reinforcement-learning-on-amazon-sagemaker-ai-a-hands-on-guide/

## 摘要

AWS 官方教程讲解如何在 Amazon SageMaker AI 上做多轮强化学习（MTRL）训练，用 Wordle 作教学示例，把 gpt-oss-20b 在 held-out 词上的解出率从 61% 提到 84%（medium effort、temperature 1.0），训练 token 花费约 $339，AgentCore 运行时另约 $79。

## 推荐理由

教程给出完整的多轮强化学习落地路径，含奖励设计错误与训练失败复盘，可直接迁移到自有多步任务。
