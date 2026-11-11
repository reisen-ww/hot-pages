# Ubuntu与Debian APT漏洞（CVE-2026-109518）修复指南

> 原标题：APT CVE-2026-109518 (root via packages that fail signature checks): Ubuntu says to update with -o Acquire::Retries=0

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-05T09:02:36.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/q1xhgvru8ruyhqf3pwkpf56o0
- 原文：https://www.reddit.com/r/selfhosted/comments/1xodzj7/apt_cve2026109518_root_via_packages_that_fail/

## 摘要

Ubuntu和Debian的APT系统存在安全漏洞（CVE-2026-109518），攻击者可通过篡改HTTP流量或使用恶意镜像绕过签名检查，从而获取root权限。修复需更新至指定版本（Ubuntu 22.04/24.04/26.04及Debian trixie 3.0.4）并调整配置参数（如sudo apt upgrade -o Acquire::Retries=0）。

## 推荐理由

该漏洞允许攻击者通过篡改HTTP流量或使用恶意镜像绕过签名检查，需通过特定配置参数修复，对自托管用户至关重要。
