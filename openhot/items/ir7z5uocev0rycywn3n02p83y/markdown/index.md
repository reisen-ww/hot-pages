# 共享 Shell 命令队列

> 原标题：Concurrent Shell Command Queues

- 来源：Hacker News 热榜
- 发布时间：2026-11-13T17:13:01.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ir7z5uocev0rycywn3n02p83y
- 原文：https://emmer.dev/blog/concurrent-shell-command-queues/

## 摘要

该脚本提供了一种在 Bash 中并行运行 Shell 命令的方法，同时限制并发数。通过 `queue_start` 初始化队列，`queue_submit` 提交命令，`queue_wait` 等待队列清空。此实现使用 `xargs` 管理并发，并通过 `mkfifo` 创建队列文件。
