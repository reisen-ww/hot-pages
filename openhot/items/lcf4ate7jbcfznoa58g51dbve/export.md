# Coq 机器验证的 10 状态图灵机超过 Graham 数并刷新 BB(10) 记录

> 原标题：BB(10) > Graham's Number

- 来源：Hacker News 热榜
- 发布时间：2026-10-13T12:40:04.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/lcf4ate7jbcfznoa58g51dbve
- 原文：https://github.com/jeff87654/busy-beaver/blob/main/BB10/1RB0RA_1LC1LF_1RD0LB_1RA1LE_1LI0LC_0RG1LD_1RH1LG_1LC0RG_0LJ0LI_1RZ0LC.md

## 摘要

一台 10 状态图灵机 n1 已从空白纸带停机，其精确得分由 Coq 在无公理条件下机器验证，并超过 Graham 数与 BB(10) 当前冠军。n1 保留 BB(8) 记录的基础机器，仅改写 E0 转移并新增状态 I、J，通过倒计时、停放和解包阶段，将得分提升到快速增长层级 f_(ω+1)；其得分下界为 f_(ω+1)((3T−13)/7−2)，其中 T = 2↑^37 3。

## 推荐理由

文章结合 Coq 机器检验证明与独立模拟，拆解这台 10 状态图灵机如何把 Busy Beaver 的已知增长层级推进到 ω+1。
