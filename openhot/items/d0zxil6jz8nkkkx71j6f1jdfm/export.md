# Hegel-clj 0.1.1 发布：Clojure测试库优化生成器与缩小算法

> 原标题：Announcing Hegel-clj

- 来源：Lobsters 热榜
- 发布时间：2026-11-16T04:12:25.212Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/d0zxil6jz8nkkkx71j6f1jdfm
- 原文：https://aphyr.com/posts/428-announcing-hegel-clj

## 摘要

Hegel-clj 0.1.1 发布，优化了生成测试的缩小算法，解决嵌套绑定导致的效率低下问题。对比test.check在查找含42的向量时产生冗余数据结构，Hegel-clj能直接缩小为[42]。集成Clojure测试框架，提供fmap/bind等生成器组合，支持递归生成和调试信息输出。
