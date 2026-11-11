# 某团队分享如何为 Nginx 启用后量子 TLS 的配置指南

> 原标题：How to check if your server uses post-quantum TLS, and enable it on nginx (needs OpenSSL 3.5)

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-11T02:25:15.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/evu16t2bulabe23rsb9ut1e64
- 原文：https://www.reddit.com/r/selfhosted/comments/1xt5zdk/how_to_check_if_your_server_uses_postquantum_tls/

## 摘要

某团队在 Reddit 分享了为 Nginx 启用后量子 TLS 的配置方法与常见问题排查。核心步骤包括检查 OpenSSL 版本（需 3.5+）、修正旧加固配置（如删除 ssl_ecdh_curve X25519:prime256v1），并对比 Caddy 2.10+ 默认启用与 Cloudflare 边缘自动支持的情况。
