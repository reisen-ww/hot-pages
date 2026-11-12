# GitHub Actions 新增锁文件机制防范供应链攻击

> 原标题：Lock your GitHub Actions

- 来源：Lobsters 热榜
- 发布时间：2026-11-11T18:16:01.014Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/cc92w3d9y8vpvwqtxlwymi71o
- 原文：https://hugovk.dev/blog/2026/lock-github-actions/

## 摘要

GitHub Actions 在 2026 年 11 月正式支持工作流锁文件，通过锁定依赖库的版本号（如 v7.0.1、v3.1.0）避免恶意代码替换。作者演示了使用 `gh actions-lock` 工具生成锁文件（actions.lock）的配置方法，并建议通过 `zizmor` 工具验证锁文件有效性。

## 推荐理由

GitHub Actions 新增锁文件机制，通过版本号锁定依赖库，有效防范恶意代码替换风险，开发者需更新工作流配置适配此功能。
