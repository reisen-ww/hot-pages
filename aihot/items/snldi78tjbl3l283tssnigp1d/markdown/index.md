# datasette-leaflet 0.3 发布

> 原标题：datasette-leaflet 0.3

- 来源：Simon Willison
- 发布时间：2026-11-13T22:30:54.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/snldi78tjbl3l283tssnigp1d
- 原文：https://simonwillison.net/2026/Nov/13/datasette-leaflet/

## 摘要

datasette-leaflet 0.3 版本更新了 tile 请求的 referrer 策略，改为 strict-origin-when-cross-origin，确保与 OpenStreetMap 的政策兼容，只传递主机名而不包含完整路径。
