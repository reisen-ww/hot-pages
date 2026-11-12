# 零初始化优化中的 GCC 异常行为

> 原标题：Zero-initialisation shenanigans

- 来源：Lobsters 热榜
- 发布时间：2026-11-11T18:04:27.210Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/n5c8uza4u59ovt7hcy94x4xki
- 原文：https://napcakes.nekoweb.org/posts/zero-init/

## 摘要

GCC 在处理零初始化时表现出异常行为，如多次调用 `memset` 和不必要的内存复制。例如，GCC 14 版本会两次调用 `memset`，而 GCC 15 及更高版本则仅调用一次，但某些边缘情况仍未解决。这些异常优化行为反映了编译器在处理特定初始化模式时的复杂性。
