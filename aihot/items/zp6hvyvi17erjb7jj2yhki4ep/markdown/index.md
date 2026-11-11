# SQLite解析函数C与Rust实现性能对比研究

> 原标题：parse_number() as a SQLite extension: C vs Rust

- 来源：Simon Willison
- 发布时间：2026-11-08T22:26:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/zp6hvyvi17erjb7jj2yhki4ep
- 原文：https://simonwillison.net/2026/Nov/8/sqlite-parse-number-c-vs-rust/

## 摘要

Simon Willison对比了C和Rust在SQLite解析函数中的性能：C版本整数处理速度达16-19ns，Rust浮点解析更快。测试覆盖8万条模糊数据验证，开源代码仓库simonw/research提供完整实现。
