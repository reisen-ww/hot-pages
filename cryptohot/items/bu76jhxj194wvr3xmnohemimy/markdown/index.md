# Ethereum PropAMMs上线：通过链上价格更新机制解决 stale price 问题

> 原标题：Anatomy of a Fill: PropAMMs on Ethereum

- 来源：Ethereum Research
- 发布时间：2026-11-19T18:17:34.000Z
- 金融热点：https://reisen-ww.github.io/hot-pages/cryptohot/items/bu76jhxj194wvr3xmnohemimy
- 原文：https://ethresear.ch/t/anatomy-of-a-fill-propamms-on-ethereum/26271#post_1

## 摘要

Ethereum PropAMMs（如 Fermi、Metric）通过链上价格流机制解决传统 AMM 的 stale price 问题。测试数据显示，价格更新平均延迟 0.76 秒，16% 的交易因市场波动超过 half-spread（0.90 bps）需承担风险，而 PropAMMs 通过 50ms 新鲜度保护机制将风险窗口压缩至约 1.2 秒。
