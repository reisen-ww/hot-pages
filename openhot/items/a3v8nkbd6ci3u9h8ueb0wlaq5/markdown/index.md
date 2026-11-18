# NGINX HTTP/2远程代码执行漏洞披露及修复建议

> 原标题：Pre-auth RCE in Nginx HTTP/2 handling

- 来源：Hacker News 热榜
- 发布时间：2026-11-18T15:19:55.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/a3v8nkbd6ci3u9h8ueb0wlaq5
- 原文：https://www.wiz.io/blog/nginx-http2-rce-vulnerabilities

## 摘要

Wiz Research等团队发现NGINX两个CVE安全漏洞（CVE-2026-123633/CVE-2026-123007），可能导致未经身份验证的远程代码执行。

## 推荐理由

该漏洞影响广泛使用的NGINX服务器，可能导致未经身份验证的远程代码执行，并提供了详细的修复建议和检测方法。
