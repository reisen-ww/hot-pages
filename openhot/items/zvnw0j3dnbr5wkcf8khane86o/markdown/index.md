# OpenBSD top(1) 新增 -Q 标志以显示 chroot、pledge 和 unveil 状态

> 原标题：OpenBSD top(1) adds flag to show chroot, pledge and unveil status

- 来源：Lobsters 热榜
- 发布时间：2026-11-07T18:41:33.184Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/zvnw0j3dnbr5wkcf8khane86o
- 原文：https://undeadly.org/cgi?action=article;sid=20261106104957

## 摘要

OpenBSD 的 top(1) 命令新增 -Q 标志，用于显示进程的 chroot、pledge 和 unveil 权限隔离状态。该功能由 Klemens Nanni 在 2026-11-05 的提交中实现，需安装最新快照才能体验。开发者通过该功能可快速定位未正确声明权限隔离的进程，强化系统安全审计能力。

## 推荐理由

该功能通过新增-Q标志直观展示进程的权限隔离状态，帮助管理员快速识别未正确使用特权机制的风险程序，提升系统安全性验证效率。
