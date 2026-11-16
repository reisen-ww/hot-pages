# 某开发者开源 Rust 写的终端文件浏览器 psychic，ML 模型训练速度达 2 秒

> 原标题：Psychic: Like fzf but learns from your actions

- 来源：Hacker News 热榜
- 发布时间：2026-11-16T15:33:34.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/sf385mmeee85ix616sbajs2j1
- 原文：https://klauria.tech/psychic/

## 摘要

某开发者发布基于 Rust 和 ML 的终端文件浏览器 psychic，通过训练用户行为模型实现智能搜索。数据显示平均输入 1.6 个字符即可命中目标，96% 的选择在 top 3，中位耗时 2 秒。采用 LightGBM 模型训练，每打开文件自动更新模型，并优化系统调用减少性能损耗。仓库包含性能基准测试与调试面板，用户可通过命令查看历史操作数据。
