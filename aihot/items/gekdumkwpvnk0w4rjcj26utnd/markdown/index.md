# AWS：通过规则与模型调用平衡生成式AI成本

> 原标题：Cut generative AI costs: Code for rules, models for judgment

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-17T21:14:55.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/gekdumkwpvnk0w4rjcj26utnd
- 原文：https://aws.amazon.com/blogs/machine-learning/cut-generative-ai-costs-code-for-rules-models-for-judgment/

## 摘要

AWS提出通过规则与模型调用平衡生成式AI成本的方法。首先用规则处理输入验证、路由等确定任务，仅将无法解决的部分提交给模型。具体实现包括：1）使用AWS Step Functions的Choice状态进行关键词快速路由；2）在Lambda中运行规则检查；3）通过Amazon Bedrock的约束决策调用处理有限选项选择；4）利用模型蒸馏技术优化模型选择。

## 推荐理由

提供了可迁移的成本优化方法，指导用户如何通过规则和模型调用平衡生成式AI系统的成本与性能
