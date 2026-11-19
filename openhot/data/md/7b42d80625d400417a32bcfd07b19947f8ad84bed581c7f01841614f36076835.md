# 某团队用Rust和smoltcp实现单VM运行1500万Web服务器

> 原标题：15M web servers on one VM – smoltcp, DPDK, AF_XDP

- 来源：Hacker News 热榜
- 发布时间：2026-11-19T05:56:36.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/vlo2dta8oui95gsrbrfhiauuo
- 原文：https://kapteko.com/15-million-webservers/

## 摘要

某团队在GitHub开源基于Rust和smoltcp的高密度Web服务器方案，单VM运行1500万实例。通过DPDK和AF_XDP技术实现硬件直连，内存占用降至620字节/空闲实例+1KB/活跃实例，对比传统内核网络栈节省83%内存。
