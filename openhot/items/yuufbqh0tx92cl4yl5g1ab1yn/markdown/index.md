# PostgreSQL 备份恢复测试：发现具体模式问题但未验证应用功能

> 原标题：Restoring a PostgreSQL backup: what our drill checked and what it missed

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-05T21:38:46.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/yuufbqh0tx92cl4yl5g1ab1yn
- 原文：https://www.reddit.com/r/selfhosted/comments/1xov432/restoring_a_postgresql_backup_what_our_drill/

## 摘要

该测试验证了从 AWS S3 和 Cloudflare R2 恢复加密的 PostgreSQL 备份，确认了行数和索引数量匹配，但未验证数据值的正确性或应用功能。测试还发现了未限定模式的 `unaccent()` 函数导致的依赖问题。下一步计划使用合成账户和隔离后端进行更全面的恢复测试。
