# FreeBSD 的 GUS 安全内存回收机制详解

> 原标题：FreeBSD GUS

- 来源：Lobsters 热榜
- 发布时间：2026-11-18T02:54:59.376Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/no1libqx1g3setf4yfe9zk0e7
- 原文：https://gregoire.dev/writing/gus/

## 摘要

FreeBSD 的 GUS 安全内存回收机制通过全局序列号和读序列号实现跨 CPU 内存释放，并与自托管内存分配器 UMA 整合优化性能。对比 RCU 和 Linux 的 QSBR，GUS 采用无界序列号解决周期性同步问题，通过批量回收桶降低 depot 锁争用。作者在自托管系统 zag 中实现该机制，提供完整代码注释和性能测试数据。
