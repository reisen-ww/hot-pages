# Datasette Lite 服务工作者与Pyodide支持多版本SQLite及插件安装

> 原标题：Running the full server-side Datasette Python app in the browser with service workers and Pyodide

- 来源：Simon Willison
- 发布时间：2026-11-17T16:48:33.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/yy61p9xu52kdvkk417sm99qbx
- 原文：https://simonwillison.net/2026/Nov/17/datasette-lite/

## 摘要

Datasette Lite 通过服务工作者和WebAssembly实现浏览器端运行，支持指定版本SQLite及多插件安装，便于本地调试与演示。示例URL展示如何通过参数加载特定插件、数据库和元数据，并对比不同SQLite版本执行结果的差异。
