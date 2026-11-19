# cwida 开源 SuperEMeans 聚类算法加速方案

> 原标题：SuperEMeans: Making e-means 3× faster

- 来源：Hacker News 热榜
- 发布时间：2026-11-18T16:09:50.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/pwlg764cutjpof3wq8fgpmq3v
- 原文：https://www.lkuffo.com/superemeans/

## 摘要

cwida 在 GitHub 开源 SuperEMeans 聚类算法，结合 SuperKMeans 和 e-means 实现速度提升 1.8-3.2 倍，同时优化了聚类不平衡问题。对比实验显示，在 5M OpenAI 和 10M Cohere 数据集上，SuperEMeans 的召回率与 e-means 相当，但扫描的向量数量更少。

## 推荐理由

对比实验显示 SuperEMeans 在 OpenAI 和 Cohere 数据集上分别达到 1.8× 和 3× 加速，同时优化了聚类不平衡问题，扫描向量数量比 e-means 少 10%-20%
