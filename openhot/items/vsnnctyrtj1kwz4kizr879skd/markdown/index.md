# 当 idempotency store 故障时，你是开放失败还是封闭失败？

> 原标题：Title: When your idempotency store is down, do you fail open or fail closed?

- 来源：Reddit r/programming
- 发布时间：2026-11-06T08:19:41.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/vsnnctyrtj1kwz4kizr879skd
- 原文：https://www.reddit.com/r/programming/comments/1xp7l52/title_when_your_idempotency_store_is_down_do_you/

## 摘要

作者运营着一个移动支付平台，选择在 idempotency store 故障时让合法支付通过并记录日志，认为这比因短暂故障拒绝合法支付更糟糕。其他观点则认为在金钱交易中应采取相反策略。是否有实际案例改变了你的观点？
