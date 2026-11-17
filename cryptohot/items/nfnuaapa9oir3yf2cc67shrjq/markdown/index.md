# 以太坊Glamsterdam升级测试发现支付漏洞：主交易成功但内部操作可能失败

> 原标题：以太坊Glamsterdam升级测试发现漏洞：部分内部支付在交易成功的情况下被跳过

- 来源：PANews
- 发布时间：2026-11-17T03:48:11.000Z
- 金融热点：https://reisen-ww.github.io/hot-pages/cryptohot/items/nfnuaapa9oir3yf2cc67shrjq
- 原文：https://www.panewslab.com/zh/articles/01a1e79e-88d7-707b-9c2b-5b01f16be4fa

## 摘要

以太坊Glamsterdam升级测试中发现，部分交易虽主流程成功，但内部支付操作可能失败。测试案例显示NFT持有成功但资金未支付，或用户提取资金时手续费未被扣除。问题根源在于Gas消耗导致try/catch机制异常，主网测试未复现该漏洞。

## 推荐理由

测试环境与主网环境出现不同结果，提示读者需关注升级后的实际执行效果验证。
