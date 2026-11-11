# 亚马逊通过替换 Sonnet 4.6 为 Strands Decider 节省数百万美元

> 原标题：Amazon saves millions by replacing Sonnet 4.6 with Strands Decider

- 来源：Hacker News 热榜
- 发布时间：2026-11-10T06:01:08.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/dlvsvy1n7mon1015e2w6ubpns
- 原文：https://strandsagents.com/blog/amazon-saves-millions-replacing-sonnet-with-strands-decider/

## 摘要

亚马逊将内部票务系统使用的 Claude Sonnet 4.6 模型替换为自研的 Strands Decider E4B，节省 98% 的 token 成本。测试显示 E4B 在响应时间（640 ms）和单票成本（$0.0005）上显著优于 Sonnet，且通过调整提示词和标签描述优化了模型效率。技术实现基于 AWS SageMaker、Lambda 和 SQS，并通过三阶段配置验证效果。

## 推荐理由

对比 Sonnet 4.6 与 Strands Decider E4B 的性能与成本，揭示决策模型在票务分类场景中的高性价比应用
