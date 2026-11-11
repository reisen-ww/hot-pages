# Go语言//go:embed指令从源文件到二进制的工作原理详解

> 原标题：How //go:embed Works: From Source Files to Binary

- 来源：Lobsters 热榜
- 发布时间：2026-11-04T12:45:22.704Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/jbnnpq0p3d6e9medfqobkqpcn
- 原文：https://internals-for-interns.com/posts/how-go-embed-works/

## 摘要

某开发者通过编译器源码分析，详细拆解了Go 1.16+的//go:embed指令如何将源文件编译为二进制中的静态资产，包括Lexer解析指令、Compiler写入字节到rodata、Linker整合对象文件等过程。重点说明如何通过fstest测试嵌入文件，并给出避免重复构建的解决方案。
