# Home Assistant 密码变更无效且令牌密钥明文存储漏洞披露

> 原标题：Home Assistant: the password is not the key – token secrets in cleartext

- 来源：Hacker News 热榜
- 发布时间：2026-11-13T22:30:10.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/p18sp3k2wv16xh13ijb6kvel1
- 原文：https://seclists.org/fulldisclosure/2026/Nov/34

## 摘要

Home Assistant 存在密码变更无效且令牌密钥明文存储的安全漏洞。测试版本 home-assistant/core 2026.11.0 发现：1. 用户令牌秘密和JWT签名密钥以明文形式存储在 config/.storage/auth 文件中；2. 长期有效令牌未设置过期时间；3. 密码变更未撤销相关令牌。建议用户立即更新配置并检查备份文件。

## 推荐理由

密码变更未有效撤销长期有效的访问令牌，导致未授权持久访问风险。
