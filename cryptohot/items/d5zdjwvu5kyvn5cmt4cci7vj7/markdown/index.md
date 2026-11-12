# Seam项目实现Base链上Zcash区块头验证与隐私支付零知识证明

> 原标题：Seam: verifying Zcash headers on Base with EIP-152, and proving shielded payments without linking the chains

- 来源：Ethereum Research
- 发布时间：2026-11-11T20:55:52.000Z
- 金融热点：https://reisen-ww.github.io/hot-pages/cryptohot/items/d5zdjwvu5kyvn5cmt4cci7vj7
- 原文：https://ethresear.ch/t/seam-verifying-zcash-headers-on-base-with-eip-152-and-proving-shielded-payments-without-linking-the-chains/26239#post_1

## 摘要

Seam项目在Base链上实现Zcash区块头验证与零知识证明，确保隐私支付安全执行，无需依赖第三方。测试显示单笔支付验证成本约0.01美元（RTX 4090实测），验证需基于Zcash主网激活区块（height 3,543,405）后5,405个区块的累积工作值。
