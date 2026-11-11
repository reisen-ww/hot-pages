# IBM i 程序验证值（PVV）机制解析与绕过测试

> 原标题：Beyond the compiler: Making IBM i run modified native code - Program Validation Value

- 来源：Lobsters 热榜
- 发布时间：2026-11-10T14:48:26.696Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/r0hhlb2deubof4r1vivhw50p6
- 原文：https://blog.silentsignal.eu/2026/11/10/Beyond-the-compiler-Making-IBM-i-run-modified-native-code-PVV/

## 摘要

作者通过自行开发的 pvv-ibmi 工具，解析了 IBM i 系统中 PVV 的计算流程（含 32 字节描述符生成、HMAC-SHA-256 计算、四值比对机制）。

## 推荐理由

工具提供了 PVV 机制的计算和验证方法，并附有测试用例，读者可据此分析 IBM i 系统的执行流程与安全边界。
