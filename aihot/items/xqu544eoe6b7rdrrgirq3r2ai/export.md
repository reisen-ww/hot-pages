# Quick Study：Claude Opus 5.5 High 用 canvas 模拟画笔几秒画出照片

> 原标题：Quick Study

- 来源：Simon Willison
- 发布时间：2026-10-23T21:35:13.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/xqu544eoe6b7rdrrgirq3r2ai
- 原文：https://simonwillison.net/2026/Oct/23/quick-study-painter/

## 摘要

Claude Opus 5.5 High 按提示词构建了一个 artifact，打开照片后用 canvas 元素和模拟画笔在几秒内画出该照片的版本。实现使用 Sobel 边缘检测，除 Google Fonts 外不依赖任何外部库。作者此前还做过用 Claude Fable 结合 P5.js 模拟水彩插画的实验。
