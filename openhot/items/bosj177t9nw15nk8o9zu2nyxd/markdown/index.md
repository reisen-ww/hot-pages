# Bruce 开源 Rust 写的自托管地图瓦片方案 Protomaps

> 原标题：Protomaps: Self-hosting map tiles has gotten cheap and easy

- 来源：Hacker News 热榜
- 发布时间：2026-11-15T19:26:22.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/bosj177t9nw15nk8o9zu2nyxd
- 原文：https://bruceroettgers.eu/blog/protomaps/

## 摘要

计算机科学学生 Bruce 在开源项目 Mapboard 的研究中发现 Protomaps 自托管地图瓦片方案。该方案通过 PMTiles 格式实现单文件部署，支持 Bunnycdn 等 CDN 配置，成本仅为 Mapbox 的 1/100（5MB 传输费用约 0.00005 美元），并给出 Rust 代码部署的详细步骤与 CDN 配置技巧。
