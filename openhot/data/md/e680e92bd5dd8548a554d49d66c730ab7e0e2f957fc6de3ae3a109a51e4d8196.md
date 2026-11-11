# 团队开源基于 Go 和 Postgres 的自托管即时通讯器 Elephant

> 原标题：Elephant: a self-hostable messenger with Signal-Protocol encryption (Go + Postgres, one docker compose)

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-07T19:34:05.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/it2d85q80n5sz16uoq8npfary
- 原文：https://www.reddit.com/r/selfhosted/comments/1xqetxd/elephant_a_selfhostable_messenger_with/

## 摘要

团队在 GitHub 公开 Elephant 仓库，使用 Go 编写单机版即时通讯器，集成 PostgreSQL 数据库，支持 Signal 协议加密。测试显示单机运行内存占用约30MB，适合小团体部署。当前仅提供 Android 应用（F-Droid 提交中），群聊端到端加密功能尚在开发（#190），服务器仅存储公钥和加密文本（#203注册关闭选项）。
