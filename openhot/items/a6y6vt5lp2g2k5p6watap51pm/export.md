# 某开发者揭露 ISP 劫持 DNS 的检测方法与自托管方案

> 原标题：So my ISP was hijacking my DNS

- 来源：Lobsters 热榜
- 发布时间：2026-11-04T12:06:23.618Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/a6y6vt5lp2g2k5p6watap51pm
- 原文：https://karthihegde.dev/posts/dns_tampering

## 摘要

某开发者通过对比Cloudflare和普通DNS响应，发现ISP劫持DNS并分享自托管Unbound的配置方案。其方案采用AdGuard+DNSCrypt加密传输，同时保留Cloudflare作为备用DNS。文中澄清DNSSEC不加密传输仅验证数据完整性，并指出DoH/DoT依赖外部DNS服务可信度。
