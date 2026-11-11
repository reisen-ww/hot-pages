# XBOW 详解六天完成的 Chrome 全链漏洞利用

> 原标题：Zero to Calc in Six Days: Inside XBOW's Chrome Full Chain

- 来源：Hacker News 热榜
- 发布时间：2026-10-13T18:37:45.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/acij7sb8ybzp16rcq7bjqrtjo
- 原文：https://xbow.com/labs/research/zero-to-calc-in-six-days-inside-xbow-chrome-full-chain

## 摘要

XBOW披露了一条由 V8 Maglev 编译器、动画 WebP 解码器和 Crashpad 内存安全漏洞串联而成的 Chrome 全链利用，可从普通标签页中的 JavaScript 执行发展为沙箱外代码执行。

## 推荐理由

文章拆解了三处漏洞如何跨越 V8 与渲染器沙箱，并说明模块化协作如何在六天内完成可运行的 Chrome 全链利用。
