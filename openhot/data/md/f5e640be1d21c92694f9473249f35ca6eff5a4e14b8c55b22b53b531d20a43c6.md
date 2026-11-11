# Google DevSite 平台修复由 Flask 会话密钥泄露引发的 $90,000 RCE 漏洞

> 原标题：Finding a $90,000 Remote Code Execution Vulnerability in Google

- 来源：Lobsters 热榜
- 发布时间：2026-10-12T14:40:35.395Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/h7k42cnuy2ph3t24ya4sxbse5
- 原文：https://simonkoeck.com/writeups/google-devsite-flask-session-pickle-rce

## 摘要

研究者发现 Google 开发者文档共享的 DevSite 平台将 OAuth client_secret 暴露在 Flask 会话 Cookie 中，且该值同时可验证 Cookie 签名，攻击者因此能够伪造会话并触发 pickle 反序列化，实现未经身份验证的远程代码执行。

## 推荐理由

文章完整还原了从 Flask 会话泄露到 pickle 反序列化 RCE 的攻击链，并给出密钥轮换、服务端存储和弃用 pickle 等修复思路。
