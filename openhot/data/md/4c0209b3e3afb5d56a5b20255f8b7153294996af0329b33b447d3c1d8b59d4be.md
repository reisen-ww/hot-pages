# joshka 开源 Zig 终端边框协议，实现零空间占用框线

> 原标题：Terminal borders that don't cost a cell

- 来源：Lobsters 热榜
- 发布时间：2026-11-13T12:03:19.804Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ck6o466mxhfkg8hy3yonk6nv5
- 原文：https://www.joshka.net/cell-borders/

## 摘要

joshka 在 GitHub 开源了基于 Zig 的终端边框协议，通过在单元格边缘添加细线实现框线不占用额外行或列。方案支持颜色、宽度、圆角配置，并提供 Ghostty 和 Ratatui 的演示应用，对比传统Unicode框绘制在界面布局和滚动时的差异。
