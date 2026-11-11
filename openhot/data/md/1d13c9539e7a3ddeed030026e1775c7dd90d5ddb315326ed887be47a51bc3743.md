# 某开发者开源 PHP 工具 B6，通过隐藏链接封禁爬虫 IP

> 原标题：Blunt Banhammer Blocks Basic Bots Ballistically

- 来源：Lobsters 热榜
- 发布时间：2026-11-10T00:48:20.266Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/bucu67tgv3ns1qki29pus1e8q
- 原文：https://shkspr.mobi/blog/2026/11/blunt-banhammer-blocks-basic-bots-ballistically/

## 摘要

某开发者开源 PHP 工具 B6，通过隐藏链接封禁爬虫 IP。该方案在 robots.txt 中添加 /honeypot/ 禁止路径，并在 index.php 设置触发 IP 封禁的机制，成功将日流量从 216GB 降至 25GB，封禁 400+ IP。工具依赖 .htaccess Rewrite 规则实现 IP 拦截，并包含 CSS 隐藏链接的代码。
