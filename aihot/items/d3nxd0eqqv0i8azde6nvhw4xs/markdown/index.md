# Hugging Face 决策模型接口详解

> 原标题：Decision Models in Hugging Face

- 来源：Hugging Face Blog
- 发布时间：2026-11-10T00:00:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/d3nxd0eqqv0i8azde6nvhw4xs
- 原文：https://huggingface.co/blog/decision

## 摘要

Hugging Face 推出决策模型接口，支持通过 state（状态）、questions（问题）和 allowed_answers（允许答案）结构化输出三种决策类型：1) choice（选择类）返回概率分布选项，2) score（评分类）返回期望值及对应概率，3) noul（布尔决策）返回二分类概率。

## 推荐理由

展示了决策模型如何通过结构化输出提升应用效率，并提供了Hugging Face生态中的实现方法
