# Git 优化参考删除性能，Rust 版本提升 18%，纳入 v3.0 计划

> 原标题：Optimizing Reference Deletions in Git

- 来源：Hacker News 热榜
- 发布时间：2026-11-08T19:37:42.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ls7w3euks7681n32pvk9th3xp
- 原文：https://nayak.im/posts/optimizing-reference-deletion/

## 摘要

Git 团队通过 Rust 重构参考存储，在删除百万级引用时性能提升 18%。测试显示 Rust 版本删除时间比 C 版本快 17.7%（v2.56.0），补丁已合并至 master (fc70f528)，计划在 v2.98 后的 v3.0 中正式启用。优化通过直接写入数据避免格式化开销，适用于 GitLab 等拥有数百万引用的大仓库。

## 推荐理由

通过 Rust 重构 Git 的参考存储，在删除百万级引用时性能提升 18%，该方案将纳入 Git 3.0 版本
