# Datadog 开源 Rust 工具 FETCh 实现生产环境规格持续验证

> 原标题：How we continuously validate formal specifications in production

- 来源：Lobsters 热榜
- 发布时间：2026-11-06T18:00:07.309Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/vx66cmucn2lt4kyxl27i44pia
- 原文：https://www.datadoghq.com/blog/engineering/continuous-formal-spec-validation/

## 摘要

Datadog 团队开源 Rust 写的 FETCh 工具，通过将形式规格（TLA+）编译为运行时监控，持续验证分布式事件存储系统 Husky 的路由逻辑。该工具发现了一个持续一年未暴露的冲突 placements 问题，该问题在常规测试和人工审查中均未触发。
