# 个人开发者开源 Python SQLite 函数缓存库 FunkyCache

> 原标题：funkycache: a Python library to cache functions in SQLite

- 来源：Lobsters 热榜
- 发布时间：2026-11-16T13:15:54.972Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/zei58gxjawq9mr6za2n1paidd
- 原文：https://alexwlchan.net/2026/funkycache/

## 摘要

作者发布 Python 库 FunkyCache，利用 SQLite 实现函数缓存，减少静态网站生成时间。该库支持依赖文件追踪（如 Markdown 文件）、静态值监控（如 Pygments 版本），并对比 MD5 与 XXH64 哈希算法性能，证明 XXH64 在大键场景下速度提升显著。

## 推荐理由

通过对比不同哈希算法的性能，作者提出了一种高效且可扩展的缓存方案，适用于需要快速重建的静态网站生成场景。
