# Spectral Burrows-Wheeler 变体加速 k-mer 查询

> 原标题：Batch, Prefetch, Skip, Orient, Squeeze: Faster, Smaller k-mer dictionaries via the Spectral Burrows-Wheeler transform

- 来源：bioRxiv
- 发布时间：2026-11-10T00:00:00.000Z
- 学术热点：https://reisen-ww.github.io/hot-pages/acadhot/items/iz0mhw6i8tqs92ifyemjt938t
- 原文：https://www.biorxiv.org/content/10.64898/2026.11.09.765318v1?rss=1

## 摘要

通过优化 Spectral Burrows-Wheeler 变体（SBWT），研究团队实现了更快更小的 k-mer 字典。他们采用批处理、预取内存、减少冗余索引结构和紧凑存储等方法，使 k-mer 查询速度提高了约七倍，并且使用更少的存储空间。在 SSHash 基准测试集及更大规模的数据集中，新方法在几乎所有读取集上的查询速度都比 SSHash 快 4.9 倍，同时空间占用减少。
