# Docker 从 2016 年起一直使用 microVMs

> 原标题：Docker has always used microVMs (well, since 2016)

- 来源：Lobsters 热榜
- 发布时间：2026-11-09T22:29:01.495Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/xpgoz78shqu7j47e0vvsyrwl0
- 原文：https://dave.recoil.org/docker-has-always-used-microvms/

## 摘要

Docker 从 2016 年起在其 Desktop 版本中一直使用 microVMs 技术，该技术通过减少 Linux 内核和 VMM 的复杂性来提高安全性。Docker Desktop 采用这种技术实现了跨平台的无 root 运行、最小化设备接口和安全的网络策略。当前，Docker Sandboxes 也基于 microVMs 技术，提供严格的隔离和治理。
