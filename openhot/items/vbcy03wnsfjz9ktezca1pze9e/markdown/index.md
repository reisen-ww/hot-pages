# Nix 动态衍生功能的探索与实践

> 原标题：beer.drv.drv.drv

- 来源：Lobsters 热榜
- 发布时间：2026-11-16T00:47:28.450Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/vbcy03wnsfjz9ktezca1pze9e
- 原文：https://fzakaria.com/2026/11/14/beer-drv-drv-drv

## 摘要

最近，作者在 Nix 的动态衍生功能上进行了一次实验，发现即使设置了内容地址化，也能通过查询最终衍生路径反向获取初始衍生路径。作者还展示了如何通过手动编写 ATerm 来创建一个无限递归的衍生链，生成“99 瓶啤酒”歌曲的每一句歌词。
