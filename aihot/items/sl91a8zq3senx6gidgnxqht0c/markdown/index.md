# Claude Code 设置文件意外泄露 GitHub 上数千项敏感信息

> 原标题：Claude Code is accidentally exposing secrets all over GitHub

- 来源：Ars Technica · AI
- 发布时间：2026-11-09T17:24:26.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/sl91a8zq3senx6gidgnxqht0c
- 原文：https://arstechnica.com/ai/2026/11/claude-code-settings-files-expose-thousands-of-secrets-on-github/

## 摘要

AI安全公司Apiiro发现Claude Code用户在GitHub公开的设置文件中存在数据库密码、API令牌等敏感信息泄露。问题源于用户自动审批命令时生成的settings.local.json文件，部分命令直接写入文件导致信息外泄。Anthropic官方文档提到该文件会被加入.gitignore，但实际存在配置疏漏。

## 推荐理由

原文揭示了Claude Code设置文件在GitHub泄露敏感信息的具体机制，包括自动化命令审批流程的缺陷和Git忽略策略的局限性。
