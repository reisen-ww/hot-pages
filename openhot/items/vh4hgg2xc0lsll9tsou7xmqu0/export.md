# OpenAI定理验证与Lean代码审计的验证流程

> 原标题：Interpreting claims that a theorem is correct because it was checked in Lean

- 来源：Hacker News 热榜
- 发布时间：2026-11-16T07:38:19.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/vh4hgg2xc0lsll9tsou7xmqu0
- 原文：https://xenaproject.wordpress.com/2026/11/12/and-the-proof-is-checked-in-lean/

## 摘要

OpenAI定理验证需结合可信工具审计与人工核查。38%论文的Lean代码未明确主定理，Navier-Stokes论文存在中英文证明差异。验证需四步：1）代码与论文定理一致；2）代码可编译；3）使用lake comparator确保证明无篡改；4）排除Lean内核漏洞。
