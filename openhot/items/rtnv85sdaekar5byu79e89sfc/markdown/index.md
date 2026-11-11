# 多款PDF编辑器存在AES-256密钥生成漏洞，可无密码解密文档

> 原标题：The case of the 9 bit AES key

- 来源：Hacker News 热榜
- 发布时间：2026-10-28T20:51:44.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/rtnv85sdaekar5byu79e89sfc
- 原文：https://v12.sh/blog/the-case-of-the-9bit-aes-key

## 摘要

某团队发现MuPDF、Foxit等PDF编辑器在生成AES-256文件密钥时使用不安全的随机数源（如drand48 LCG、时间戳哈希等），导致密钥空间被压缩至512种可能。攻击者可通过枚举时间戳（每512秒重复）或内存信息（如Foxit）猜测密钥，实现无密码解密。其中MuPDF已修复至1.28.5版本，但Foxit等仍存在漏洞。

## 推荐理由

多个主流PDF编辑器存在相同漏洞，导致AES-256密钥可被暴力破解，影响文档安全性。
