# datasette #3046: 不向 Firefox 提供 HTML 页面的 link: rel=next HTTP 头

> 原标题：datasette #3046: Don't serve link: rel=next HTTP headers to Firefox for HTML pages

- 来源：Simon Willison
- 发布时间：2026-11-07T23:57:46.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/h4mrga52zorqwbylfftxpk5kz
- 原文：https://simonwillison.net/2026/Nov/7/link-rel-next/

## 摘要

Datasette 在其页面中提供了 link: rel="next" 的 HTTP 头，导致 Firefox 预取下一页数据，这会浪费不必要的数据传输和服务器资源。这一问题已存在 24 年，甚至早在 2002 年就有相关投诉。
