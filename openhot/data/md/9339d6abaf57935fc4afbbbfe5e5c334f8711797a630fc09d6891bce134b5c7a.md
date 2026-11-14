# WebKit 修复 Promise 构造函数 Symbol.species 获取异常导致的执行阻塞问题

> 原标题：Fixing a WebKit bug to see if promises are made of train tracks

- 来源：Lobsters 热榜
- 发布时间：2026-11-13T16:48:01.396Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/lqxw4wq37xyv27ju4yfd0q8v2
- 原文：https://alistair.sh/thenables

## 摘要

WebKit 修复 Promise 构造函数 Symbol.species 获取异常导致的执行阻塞问题。对比 Safari/Bun引擎在 Promise 处理中的行为差异，分析 JavaScript 规范中 resolve 函数的实现逻辑及修复方案。

## 推荐理由

对比 Safari/Bun引擎在 Promise 处理中的行为差异及修复方案
