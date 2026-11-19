# Close 公司通过动态分片和AWS spot实例将CI测试耗时压缩至3分钟

> 原标题：Faster CI with Orchestrated Pytest Workers

- 来源：Lobsters 热榜
- 发布时间：2026-11-18T18:13:35.717Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/vtgc8276umeh82ydz5m5b8iqt
- 原文：https://making.close.com/posts/faster-ci-with-orchestrated-pytest-workers/

## 摘要

Close公司通过动态分片和AWS spot实例将CI测试耗时从12分钟压缩至3分钟。基于currents.dev的Playwright测试优化方案，实现动态任务分配和弹性资源调度，同时保持测试结果的可追踪性。
