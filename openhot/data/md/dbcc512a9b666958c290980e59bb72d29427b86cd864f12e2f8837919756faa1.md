# 某用户利用漏洞劫持三星电视广告并部署 Rust 自托管服务器

> 原标题：Hijacking Samsung TV Smart Hub Ads

- 来源：Lobsters 热榜
- 发布时间：2026-11-12T11:08:45.506Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/nzevlfbrwtuhiqof7ttokuiwz
- 原文：https://dvratil.cz/2026/11/hijacking-samsung-tv-smart-hub-ads/

## 摘要

用户通过篡改 SSL 证书和部署 Rust 服务器，将三星电视的广告替换为自定义家庭照片。方案包含 mitmproxy 配置、Rust 服务器代码（GitHub 可查）、路由表与防火墙规则（含具体 IP 和端口），并说明三星设备未及时更新证书导致漏洞可利用。
