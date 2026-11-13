# Easel开源团队自托管替代AWS Lambda Web Functions：闲置计费与性能对比

> 原标题：AWS Lambda Web Functions keep billing memory ~7 minutes after the last request

- 来源：Hacker News 热榜
- 发布时间：2026-11-12T16:59:26.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/iwkbyd4ijkknqn05r1d6x117n
- 原文：https://www.easel.sh/blog/lambda-web-functions-idle-memory

## 摘要

Easel开源团队测试发现AWS Lambda Web Functions在最后请求后仍计费闲置内存约7分钟，并自托管基础设施实现1.5-3倍性能提升。具体对比包括：JSON API请求响应时间快2.9倍，流媒体首包时间快2倍，CPU密集型API快1.5倍，冷启动速度快3.5倍。

## 推荐理由

通过对比自托管与AWS Lambda Web Functions的性能，揭示后者在闲置内存计费和响应速度上的不足，为高并发应用的成本优化提供参考
