# Aerogramme 团队开源邮件服务器，解析复杂边缘案例

> 原标题：Quality IMAP, Part 1: Your Mailbox Is A Database

- 来源：Lobsters 热榜
- 发布时间：2026-11-16T16:25:38.928Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ve2o0jqatjv85xcdh9f8tjas9
- 原文：https://aerogramme.deuxfleurs.fr/blog/2026-quality-imap-part-1/

## 摘要

Aerogramme 团队发布开源邮件服务器技术方案，重点解决SEARCH/FETCH查询的复杂边缘情况。通过ImapTest测试框架和模糊生成测试，修复了编码词上下文依赖、消息ID格式兼容等12类问题，并改进eml-codec库的解析恢复机制。
