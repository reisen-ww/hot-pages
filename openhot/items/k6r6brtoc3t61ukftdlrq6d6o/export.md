# 基于Firecracker复现Google Agent Sandbox并测试性能

> 原标题：Google Described Its Agent Sandbox. I Built One with Firecracker and Measured It

- 来源：Hacker News 热榜
- 发布时间：2026-11-07T16:01:40.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/k6r6brtoc3t61ukftdlrq6d6o
- 原文：https://antonau.tech/posts/2026/11/agents-microvm-firecracker/

## 摘要

作者在GitHub构建了基于Firecracker的微虚拟机系统，测试了冷启动（1.1秒）、恢复（24.5ms）和分叉（64实例同时运行）性能，发现 nested virtualization下启动延迟显著增加（Mac上12实例需4分钟），而bare metal环境下可支持64个实例同时运行（平均126ms）。
