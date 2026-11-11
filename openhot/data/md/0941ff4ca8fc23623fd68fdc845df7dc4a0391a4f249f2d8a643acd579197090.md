# 我对 Deno 的安全模型不太感冒

> 原标题：I’m not a fan of Deno’s security model (2024)

- 来源：Lobsters 热榜
- 发布时间：2026-11-07T23:19:53.437Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/g1ycbjr2carm432e87m1nnh1j
- 原文：https://goldstein.lol/posts/deno-security/

## 摘要

Deno 是一个 JavaScript 运行时，其安全模型依赖于权限系统。作者指出，Deno 在终端中显示权限请求提示时存在安全隐患，恶意代码可以通过控制终端发送任意命令。此外，`--allow-run` 选项的实现方式也不安全，因为程序名并非唯一标识，可能导致权限滥用。
