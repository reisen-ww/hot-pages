# sshole: C 语言中的 sentinel 值漏洞影响 Alpine 系统

> 原标题：*sshole, or when are we finally going to get rid of C?

- 来源：Lobsters 热榜
- 发布时间：2026-11-07T21:05:35.812Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/n8geykkyvmqlw7h7cne78wfup
- 原文：https://sunshowers.io/posts/sshole/

## 摘要

Alpine 系统中由于 musl libc 的 crypt 函数返回 sentinel 值 "*" 导致未授权用户可能获得 root 权限的 shell。C 语言缺乏类型系统检查，而 Rust 社区则不允许此类错误返回，强调了工程规范的重要性。
