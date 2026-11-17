# Three.js光照管线优化：G缓冲、SSR与SSGI整合方案及性能对比

> 原标题：My Quest to push native Three.js quality match AAA Game Engines

- 来源：Hacker News 热榜
- 发布时间：2026-11-16T21:07:43.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ya19v5tqy6npwd9ft1vua42oo
- 原文：https://ben3d.ca/blog/building-the-aaa-lighting-pipeline-in-threejs

## 摘要

Three.js维护者通过优化G缓冲、动态光照探针和屏幕空间反射（SSR/SSGI）等组件，将4K分辨率下的内存占用从626MB降至322MB。

## 推荐理由

通过对比Three.js与AAA引擎的光照管线，展示了如何通过G缓冲优化、动态光照探针和屏幕空间反射等技术的整合，将内存占用降低至76字节/像素，并提供了可复用的性能优化方案。
