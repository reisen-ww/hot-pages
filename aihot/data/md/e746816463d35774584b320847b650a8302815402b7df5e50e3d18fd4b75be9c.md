# Datasette发布Apache Arrow流式导出插件（datasette-arrows 0.1a0）

> 原标题：datasette-arrows 0.1a0

- 来源：Simon Willison
- 发布时间：2026-11-18T17:09:59.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/uxdcplqz1u1zortycq1j1ary3
- 原文：https://simonwillison.net/2026/Nov/18/datasette-arrows/

## 摘要

Simon Willison发布datasette-arrows插件，支持Apache Arrow流式导出百万行数据。该插件通过register_output_renderer()钩子实现，与Datasette核心支持的CSV/TSV流式导出互补，预计在下一版alpha中整合到主界面。
