# Go 编译器的汇编语言快速指南

> 原标题：A Quick Guide to Go's Assembler

- 来源：Lobsters 热榜
- 发布时间：2026-11-05T22:07:32.833Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/oxy8shv6v1h266ocrxly7o9ia
- 原文：https://go.dev/doc/asm

## 摘要

Go 编译器使用一种独特的汇编语言，基于 Plan 9 汇编器的输入风格，但不直接映射到底层机器指令。该语言在生成代码后进行部分指令选择，因此汇编指令可能不会直接对应机器指令，而是可能被转换为其他操作，如清除或加载。了解汇编代码时，需注意 Go 的汇编器生成的实际指令可能与汇编代码不同。
