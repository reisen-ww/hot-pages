# EIP-8288：递归聚合的网络实现

> 原标题：EIP-8288: the networking side of recursive aggregation

- 来源：Ethereum Research
- 发布时间：2026-11-18T09:58:32.000Z
- 金融热点：https://reisen-ww.github.io/hot-pages/cryptohot/items/rlcouo9yas561iq40hvbrfpwp
- 原文：https://ethresear.ch/t/eip-8288-the-networking-side-of-recursive-aggregation/26263#post_1

## 摘要

EIP-8288 规定了基于递归 STARK 的带宽高效 mempool，通过递归聚合减少 EVM 对每个交易的单独验证。研究显示，当前 mempool 在 15 符号交易/秒的速率下仍能处理当前负载，但隐私交易的 STARK 证明过大时需采用新的传播协议。研究建议 EIP-8288 应明确节点发送证明的频率和聚合节点的数量。
