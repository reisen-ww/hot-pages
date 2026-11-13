# 某安全研究员发现PostgreSQL 22年遗留类型混淆漏洞可导致远程代码执行

> 原标题：Turning a 22-year-old Postgres type-confusion primitive into RCE

- 来源：Hacker News 热榜
- 发布时间：2026-11-12T18:22:22.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/gp9skzfvqha91lfw8nhkbc8sg
- 原文：https://mehmetince.net/part-3-6-how-i-ended-up-turning-a-22-year-old-postgresql-type-confusion-primitive-into-rce-cve-2026-6460/

## 摘要

作者在利用pg_clickhouse扩展时发现PostgreSQL存在22年遗留的类型混淆漏洞，通过预编译查询改变字段类型触发崩溃，最终利用类型转换实现远程代码执行。该漏洞影响所有基于PostgreSQL的托管服务，包括Databricks、Google AlloyDB等，修复涉及6个CVE（含主漏洞CVE-2026-6460）和类型版本化等机制改进。
