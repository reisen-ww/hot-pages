# Rust 和 C++ 中指针来源的对比

> 原标题：Pointer Provenance in Rust vs C++

- 来源：Lobsters 热榜
- 发布时间：2026-11-13T18:37:30.823Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/dytg02ueluzbxvlzmpr8pdkft
- 原文：https://sofiabelen.github.io/projects/pointer-provenance-in-rust-vs-cpp/

## 摘要

作者探索了 Rust 中的指针来源（pointer provenance），发现即使指针看起来像是简单的内存地址，编译器也会跟踪其来源以防止意外修改。通过 LLVM IR，作者展示了如何在 Rust 和 C++ 中检查指针来源。在 C++ 中，编译器无法优化包含指针整数转换的代码，而在 Rust 中，开发者可以通过 API 清晰表达其意图。
