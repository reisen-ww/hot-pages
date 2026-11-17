# 如何绕过 Rust 的 Orphan 规则：通过 trait 通用槽实现跨库类型转换

> 原标题：How to Bypass Rust's Orphan Rule

- 来源：Lobsters 热榜
- 发布时间：2026-11-17T15:35:36.402Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/qwsbl7qnti0teagt5hkegv97p
- 原文：https://edvong.com/bypass-orphan-rule/

## 摘要

通过在 trait 中添加 generic slot 实现跨库类型转换，并以 Kova ORM 为例说明其应用场景和优势。具体方法包括：1. 在 trait 中预留 Ctx 参数；2. 在下游服务 crate 中定义本地 marker struct；3. 通过 PhantomData 实现零运行时开销的上下文切换。
