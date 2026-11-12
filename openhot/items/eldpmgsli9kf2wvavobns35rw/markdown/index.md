# Andrew Kensler 的 permute() 函数：无状态常数时间伪随机数组遍历

> 原标题：Andrew Kensler's permute(), a function for stateless, constant-time pseudorandom-order array iteration

- 来源：Lobsters 热榜
- 发布时间：2026-11-11T20:08:45.593Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/eldpmgsli9kf2wvavobns35rw
- 原文：https://andrew-helmer.github.io/permute/

## 摘要

Andrew Kensler 的 permute() 函数通过不可逆哈希与循环行走优化，实现O(k)时间复杂度和O(1)内存占用，适用于大规模数组随机抽样，如离线渲染中的并行计算场景。
