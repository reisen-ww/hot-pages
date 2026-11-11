# Hugging Face 发布 OlmoEarth v1.3 卫星嵌入模型与全球预计算嵌入

> 原标题：OlmoEarth v1.3: State-of-the-art embeddings for the whole planet

- 来源：Hugging Face Blog
- 发布时间：2026-10-22T16:11:31.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/r2nvduy3psrd2ryw7ebva9y0w
- 原文：https://huggingface.co/blog/allenai/olmoearth-v1-3

## 摘要

OlmoEarth v1.3 是一个卫星嵌入模型，读取一年的 Sentinel-1 雷达与 Sentinel-2、Landsat 多光谱时间序列，为地球上每个 10 米像素输出一个 128 维向量，前 64 维可单独作为更小的嵌入使用。

## 推荐理由

给出与两个基线模型的对比结果和训练成本变化，读者可据此判断其开源嵌入模型的性价比定位。
