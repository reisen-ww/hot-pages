# 以太坊Gloas协议改进：预播种加密数据块与延迟密钥释放

> 原标题：Reveal a key, not a payload: sending the ePBS payload before the reveal

- 来源：Ethereum Research
- 发布时间：2026-11-18T16:12:56.000Z
- 金融热点：https://reisen-ww.github.io/hot-pages/cryptohot/items/pffqe9h25z3v6xkwzot9jd8y7
- 原文：https://ethresear.ch/t/reveal-a-key-not-a-payload-sending-the-epbs-payload-before-the-reveal/26264#post_1

## 摘要

以太坊Gloas协议改进通过预播种加密数据块和延迟密钥释放，优化了区块到验证的时间窗口。对比bloXroute（2018）和MEV-Boost（2022-2024）方案，新机制允许区块到达后立即传输加密 payload，而仅延迟 32 字节密钥的 reveal。
