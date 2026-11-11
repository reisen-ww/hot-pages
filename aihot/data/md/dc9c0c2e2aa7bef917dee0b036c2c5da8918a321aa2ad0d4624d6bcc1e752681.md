# 微软发布PDD Kit工具：形式化验证AI生成的全栈Web应用登录逻辑

> 原标题：Formally verifying agent-written full-stack web apps with PDD Kit

- 来源：Microsoft Research
- 发布时间：2026-11-05T16:00:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/nzixetzsj6d3uvb37ozyp4nq1
- 原文：https://www.microsoft.com/en-us/research/blog/formally-verifying-agent-written-full-stack-web-apps-with-pdd-kit/

## 摘要

微软研究团队发布PDD Kit工具，通过Verus语言形式化验证Rust编写的Pet Store登录逻辑。工具将用户意图转化为形式化规格，自动生成覆盖所有输入的数学证明（如密码验证必须关联账户），并针对无法证明的部分（如数据库查询）生成测试用例。

## 推荐理由

PDD Kit 通过形式化验证和测试结合，提供了一种可扩展的审查方法，适用于需要高安全性的全栈应用开发
