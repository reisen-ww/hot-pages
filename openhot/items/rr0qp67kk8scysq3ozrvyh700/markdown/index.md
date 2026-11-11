# GitHub Actions 引入依赖锁定文件机制防范供应链攻击

> 原标题：Workflow dependency lockfiles

- 来源：Lobsters 热榜
- 发布时间：2026-11-07T20:27:05.147Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/rr0qp67kk8scysq3ozrvyh700
- 原文：https://docs.github.com/en/actions/concepts/security/workflow-dependency-lockfiles

## 摘要

GitHub 官方文档发布依赖锁定文件机制，通过在 .github/workflows/actions.lock 文件中绑定 commit SHA 和 owner_id防止恶意代码注入。该机制支持 transitive dependencies 管理和 Dependabot 自动化更新，相比传统 SHA 针定更易维护且满足最新安全政策要求。

## 推荐理由

锁文件机制解决了依赖版本不固定导致的潜在安全风险，并支持 Dependabot 等工具自动化管理依赖更新。
