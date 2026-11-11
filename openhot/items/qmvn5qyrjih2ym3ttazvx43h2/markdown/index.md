# 我删除了所有 SSH 密钥

> 原标题：I deleted all my SSH keys

- 来源：Hacker News 热榜
- 发布时间：2026-11-05T18:17:51.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/qmvn5qyrjih2ym3ttazvx43h2
- 原文：https://blog.infected.systems/posts/2026-11-03-i-deleted-all-my-ssh-keys/

## 摘要

作者使用 YubiKey 存储 SSH 密钥，并通过 YubiKey、TPM 和 Apple Secure Enclave 等硬件安全模块保护密钥，确保密钥材料不存储在磁盘上。文中详细介绍了如何使用 YubiKey 存储和使用 ed25519-sk 密钥，以及如何配置无触摸验证以实现自动化 SSH 认证。
