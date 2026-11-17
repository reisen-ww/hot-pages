# C 的指定初始化器提供命名可选参数

> 原标题：C’s designated initializers give us named arguments

- 来源：Lobsters 热榜
- 发布时间：2026-11-17T15:58:44.322Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ar3oq2wfgz3n9pv0w8m654qf1
- 原文：https://quuxplusone.github.io/blog/2026/11/16/named-arguments-in-c/

## 摘要

C 语言的指定初始化器允许参数以任意顺序出现并可重复指定，这使得函数调用更加灵活。通过宏定义，可以轻松添加新的命名参数而不破坏现有接口，仅需重新编译。该技术在多个开源项目中被实际应用，如 EpicGames/raddebugger 和 gab462/hof-flecs-raylib。
