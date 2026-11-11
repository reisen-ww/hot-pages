# Hypercore 如何验证来自不可信节点的数据：梅克尔证明机制

> 原标题：Verifying data from untrusted peers: how Hypercore's Merkle proofs work (one block in a million costs ~1 KB)

- 来源：Reddit r/programming
- 发布时间：2026-11-05T11:59:59.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/lfvkua971rh04qp4i3k28ikl6
- 原文：https://www.reddit.com/r/programming/comments/1xoguip/verifying_data_from_untrusted_peers_how/

## 摘要

Hypercore 是一个签名的追加日志，每个区块都绑定到以写作者 Ed25519 签名结尾的梅克尔证明链，确保数据可验证。即使区块数量庞大，验证一个区块的证明也只需约 1 KB。
