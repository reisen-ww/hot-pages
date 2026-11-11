# 主流Web框架过度信任Forwarded头：揭秘IP与主机名欺骗风险

> 原标题：Forwarded Without Question: How Web Frameworks Overtrust the Forwarded Header

- 来源：Lobsters 热榜
- 发布时间：2026-11-07T06:18:48.419Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/rzua9lf1vk599lxyv5qd17fhb
- 原文：https://www.lkoskela.fi/blog/2026-11-05-forwarded-without-question/

## 摘要

某研究团队测试发现，主流Web框架如Rails、Spring Boot默认支持RFC 7239的Forwarded头，而反向代理（如Jetty、Nginx）通常不处理该头，导致IP地址和主机名欺骗风险。建议开发者验证代理与框架配置一致性，优先使用X-Forwarded-*头。
