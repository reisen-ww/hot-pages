# Rust 借用检查器发现存在 11 年之久的不安全性漏洞

> 原标题：11 year old unsoundness bugs found in Rust borrow checker

- 来源：Hacker News 热榜
- 发布时间：2026-10-13T10:27:00.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/kncjiy447keuthntwmkl5hgc0
- 原文：https://github.com/rust-lang/rust/issues/164250

## 摘要

Rust 借用检查器被发现会接受一段通过 Drop 将局部引用存入全局容器的代码，程序随后打印已离开作用域的字符串内容。

## 推荐理由

该问题展示了 Rust 借用检查器如何接受可能导致悬垂引用的代码，并提供了 AddressSanitizer 崩溃复现链接。
