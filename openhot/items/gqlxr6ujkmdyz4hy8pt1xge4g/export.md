# VideoRebirth开源Rust写的视频生成模型HyperFlow H3 Flash：14B参数实现5.2秒生成

> 原标题：Show HN: We compressed a 31B video+audio diffusion model to 14B, 6 steps, INT8

- 来源：Hacker News 热榜
- 发布时间：2026-11-07T15:16:01.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/gqlxr6ujkmdyz4hy8pt1xge4g
- 原文：https://github.com/Video-Rebirth/hyperflow-h3-flash

## 摘要

VideoRebirth在GitHub开源Rust编写的视频生成模型HyperFlow H3 Flash，将31B模型压缩至14B参数，支持6步采样生成5.2秒视频。提供INT8量化版本和跨4GPU并行方案，可在RTX 5090等消费级显卡上实时运行。模型包含fl2va和ref2va两种接口，支持文本、单帧、多参考视频生成，需配合特定GGUF配置使用。

## 推荐理由

模型压缩至14B参数，在消费级RTX GPU上实现5.2秒生成，提供量化版本和跨GPU并行方案
