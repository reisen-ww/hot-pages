# GitHub 宣布新 Git 存储架构：支持每秒数万次写入与低延迟读取

> 原标题：GitHub's new Git storage architecture

- 来源：Hacker News 热榜
- 发布时间：2026-11-06T19:24:21.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/notw2kohadcroqbrchsxylfts
- 原文：https://github.blog/engineering/architecture-optimization/inside-githubs-new-git-storage-architecture/

## 摘要

GitHub 在 2026 年 11 月 GitHub Universe 宣布新 Git 存储架构，通过虚拟副本和 Ref-CAS 服务实现每秒 7200 次推送，并保持低延迟读取。该架构基于 Azure Blob Storage 存储数据，分离存储与计算，支持大规模并行写入和动态扩展。
