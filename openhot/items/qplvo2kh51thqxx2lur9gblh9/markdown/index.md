# GitLab 修复 CI/CD 正则表达式编译器最高严重性远程代码执行漏洞

> 原标题：GitLab warns of max severity code execution vulnerability

- 来源：Lobsters 热榜
- 发布时间：2026-10-14T15:55:52.017Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/qplvo2kh51thqxx2lur9gblh9
- 原文：https://www.bleepingcomputer.com/news/security/gitlab-warns-of-max-severity-rce-flaw-in-regex-compiler-engine/

## 摘要

GitLab 警告用户立即修复 CI/CD 正则表达式编译器中的最高严重性漏洞 CVE-2026-97229，未经身份验证的远程攻击者可通过特制正则表达式在 GitLab 服务器上执行任意代码。

## 推荐理由

文章明确列出受影响的 GitLab CE/EE 版本与修复版本，并说明攻击者可借助特制正则表达式执行任意代码，便于自托管用户核对升级范围。
