# zkSecurity 发布哈希函数碰撞测试工具，覆盖 MD5、SHA-1 等旧算法

> 原标题：Collisions in Hash Functions

- 来源：Hacker News 热榜
- 发布时间：2026-11-17T01:11:09.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/wegjs0cv0rj0qeesziphr0a0a
- 原文：https://collisions.zksecurity.xyz/

## 摘要

zkSecurity 开源哈希碰撞测试工具，可验证 MD5、SHA-1 等算法的碰撞漏洞。工具要求 Python 3.10，提供 `list` 查看支持算法、`verify` 验证碰撞对、`unittest` 测试用例，并包含原始 SHA-1 碰撞论文的验证流程。

## 推荐理由

提供了验证哈希函数碰撞的 Python 工具及详细测试方法，便于安全研究人员复现和评估现有算法的安全性。
