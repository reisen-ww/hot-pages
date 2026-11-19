# 开源项目vault-share实现多级防胁迫登录与加密文件共享

> 原标题：A live service duress prototype

- 来源：Hacker News 热榜
- 发布时间：2026-11-15T19:42:59.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/u8m1pjvwlxdva09w96xmv53es
- 原文：https://github.com/Ymsniper/vault-share

## 摘要

基于Python和Flask的开源安全文件共享系统，采用AES-256-GCM加密存储，每个文件独立生成X25519密钥对。创新设计包括：1) 多级嵌套登录（最多47层），胁迫场景下仅当前层可见；2) ECDSA签名与本地CA证书验证；3) 密码尝试计数与IP地址关联锁定；4) 覆盖仓库机制（Cover Vault）实现密钥隔离。
