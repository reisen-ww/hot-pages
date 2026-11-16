# 某开发者分享 FreeBSD pkgbase 本地镜像搭建方案

> 原标题：Local Mirror for FreeBSD pkgbase

- 来源：Lobsters 热榜
- 发布时间：2026-11-16T14:47:48.457Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/sv8geb10vigqydnh4fshriunx
- 原文：https://blog.feld.me/posts/2026/11/local-mirror-for-freebsd-pkgbase/

## 摘要

开发者公开 FreeBSD pkgbase 本地镜像搭建方案，减少带宽消耗。配置要点包括：使用 Apache 反向代理+缓存模块，直接访问 AWS CDN（需处理重定向问题），镜像路径指向 /var/repos/。注意事项：官方 CDN 重定向需绕过，暂未配置 SRV 路径回退方案。
