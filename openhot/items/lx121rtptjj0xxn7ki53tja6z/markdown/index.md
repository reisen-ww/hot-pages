# 某开发者开源抗议证书生成方案，嵌入信息于RSA模数

> 原标题：Horible public key tricks

- 来源：Hacker News 热榜
- 发布时间：2026-11-10T00:07:17.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/lx121rtptjj0xxn7ki53tja6z
- 原文：https://maurycyz.com/projects/badcert/

## 摘要

某开发者开源抗议证书生成方案，嵌入信息于RSA模数，并讨论了其安全影响。方法通过修改RSA模数n的base64编码隐藏信息，提供生成脚本和实验数据。指出虽然降低私钥熵值，但现代TLS的前向保密机制仍可抵御中间人攻击。引用论文和社区讨论链接，包含证书生成命令和漏洞分析。
