# Amazon QuickSight layer maps 支持用 GeoJSON 绘制点位与路线

> 原标题：Visualize points and routes with GeoJSON in Amazon Quick Sight layer maps

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-23T16:24:55.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/x2ikfxl22rh4zkbb117954q7n
- 原文：https://aws.amazon.com/blogs/machine-learning/visualize-points-and-routes-with-geojson-in-amazon-quick-sight-layer-maps/

## 摘要

Amazon QuickSight layer maps 新增支持 GeoJSON 中的 Point 和 LineString 两种几何类型，可在地图上绘制门店等具体点位，以及配送路径、机场间航线等路线。GeoJSON 文件须为 .geojson 格式、最大 100 MB，通过共享 join key 与 QuickSight 数据集关联，且每层一次只渲染一种几何类型。
