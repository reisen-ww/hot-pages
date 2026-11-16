# 以太坊EIP-8141升级提案：ecrecover指令量子安全改进方案

> 原标题：Proposed PQ upgrade for ecrecover

- 来源：Ethereum Research
- 发布时间：2026-11-15T11:13:19.000Z
- 金融热点：https://reisen-ww.github.io/hot-pages/cryptohot/items/ufpjy8cp2kljh09551n1blibc
- 原文：https://ethresear.ch/t/proposed-pq-upgrade-for-ecrecover/25844#post_12

## 摘要

以太坊研究社区提出通过哨兵值（v=27,s=0）触发新验证路径，结合EIP-8141帧交易签名实现量子安全签名验证。讨论指出需解决多签账户的兼容性问题，并强调需通过锚定时间机制确保经典密钥退役的不可逆性。测试数据显示现有FiatToken v2.2等协议需调整ERC-1271实现方式以支持新机制。
