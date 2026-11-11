# curl 8.23.0 修复 HTTP/2 上传 Use-After-Free 漏洞 CVE-2026-92392

> 原标题：A UAF turned RCE

- 来源：Lobsters 热榜
- 发布时间：2026-10-14T09:44:11.288Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ocvwr9aaajlxx8jljlyg8ed9y
- 原文：https://daniel.haxx.se/blog/2026/10/14/a-uaf-turned-rce/

## 摘要

curl 8.23.0 修复了 HTTP/2 上传中的 Use-After-Free 漏洞 CVE-2026-92392，该问题在特定条件下可能被恶意服务器利用为远程代码执行。

## 推荐理由

文章拆解了 HTTP/2 上传场景下悬空指针如何演变为远程代码执行，并说明了触发条件与 curl 团队的修复思路。
