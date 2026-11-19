# 以太坊智能合约中嵌入动态PIN的加密账户研究

> 原标题：Encrypted Account: a PIN that lives in the contract

- 来源：Ethereum Research
- 发布时间：2026-11-18T20:59:16.000Z
- 金融热点：https://reisen-ww.github.io/hot-pages/cryptohot/items/jrwsy5g7nxepjktlqhp2xclwz
- 原文：https://ethresear.ch/t/encrypted-account-a-pin-that-lives-in-the-contract/26265#post_1

## 摘要

以太坊研究团队发布基于Zama阈值FHE的加密账户原型，通过链上动态验证PIN实现防暴力破解。测试显示在Sepolia链上，PIN验证转账平均需2.7万Gas，公开列表版本成本降低至60k Gas。方案存在Zama网络信任依赖、指纹泄露风险（需2天破解）等局限，支持多设备签名和托管的账户恢复机制。
