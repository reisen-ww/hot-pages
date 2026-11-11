# musl Linux 环境下 SSH 密码哈希漏洞的十年修复历程与持续风险

> 原标题：sshhole

- 来源：Lobsters 热榜
- 发布时间：2026-11-05T12:24:42.504Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/e7id5u39sxzhczos0hxfcymte
- 原文：https://sshhole.com/

## 摘要

musl Linux 环境下的 SSH 服务存在安全漏洞（CVE-2016-6210），未设置密码的账户（如 root 或默认用户）可能被 257-1024 字符长度的任意密码入侵。

## 推荐理由

开源项目 musl 的密码哈希处理存在安全漏洞，导致未设置密码的账户可能被暴力破解，需及时更新或配置限制
