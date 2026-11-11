# PHP2Shell漏洞利用技术方案解析

> 原标题：PHP2Shell — Deep Dive

- 来源：Lobsters 热榜
- 发布时间：2026-11-08T05:51:54.004Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/a0kwio1gu9nqlsltatrdi763v
- 原文：https://djad04.github.io/php2shell-deep-dive/

## 摘要

本文详细解析了PHP2Shell漏洞的利用机制，包括通过51个填充字段移动内存分配边界、伪造zend_string结构触发堆溢出，以及利用stale pointer读取会话ID。关键步骤涉及触发OOM、回收内存槽、伪造数据并绕过ASLR保护。
