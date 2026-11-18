# Shah 等在 bioRxiv 发表 TS-Zarr 云优化数据存储方案

> 原标题：TS-Zarr: a cloud-optimized Zarr layout for viewing and analyzing biomedical time series

- 来源：bioRxiv
- 发布时间：2026-11-18T00:00:00.000Z
- 学术热点：https://reisen-ww.github.io/hot-pages/acadhot/items/ktt94keejaajx8y3q6f4ldpb5
- 原文：https://www.biorxiv.org/content/10.64898/2026.11.16.767094v1?rss=1

## 摘要

TS-Zarr 云优化数据存储方案通过预计算层级减少可视化所需下载量，并利用 Zarr 在云存储的高并行读取特性提升分析效率。该方案将原始样本数据与多级摘要统计结合存储，支持按需读取特定通道和窗口的数据，对比 HDF5 和 EDF 格式在云存储中的读取效率提升显著。预计算层级在用户窗口扩展时仍能保持读取时间线性增长，适用于小时级采样、数百通道的生物医学时间序列数据存储与可视化。
