# Rust标准库内存安全漏洞及修复建议

> 原标题：Memory Safety Bugs in Rust Standard Library

- 来源：Lobsters 热榜
- 发布时间：2026-11-10T19:44:50.546Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/gg707bxwor3yj09a7kr0ww87b
- 原文：https://forge-blog.github.io/posts/rust-std-memory-safety/

## 摘要

微软FORGE实验室发现Rust标准库存在三个模式的安全漏洞：1）信任非 panic 安全的代码调用（如MapWindows::clone），2）信任用户实现（如str::replace自定义Pattern），3）依赖操作系统状态（如process::exit与信号栈交互）。
