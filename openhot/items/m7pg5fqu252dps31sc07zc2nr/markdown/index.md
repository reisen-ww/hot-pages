# Zerodha开源基于SQLite的分布式对象存储系统Blobasaur

> 原标题：Distributed, high-performance blob storage on SQLite

- 来源：Hacker News 热榜
- 发布时间：2026-11-19T08:39:45.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/m7pg5fqu252dps31sc07zc2nr
- 原文：https://zerodha.tech/blog/high-performance-distributed-blob-storage/

## 摘要

Zerodha开源基于SQLite的分布式对象存储系统Blobasaur，单机可处理千万级向量，吞吐量达1.66GB/s。替代SSDB后，通过分片架构将写入吞吐量提升3.3倍，p99延迟降至2ms。支持zstd压缩（平均11倍压缩率），采用Redis集群协议兼容现有客户端。部署时通过增量真空机制解决SQLite文件膨胀问题，并优化异步写入的读一致性保障。
