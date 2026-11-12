# LLM 0.37.2 版本修复安全漏洞

> 原标题：llm 0.37.2

- 来源：Simon Willison
- 发布时间：2026-11-11T17:19:52.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/bjlzqsm82nae44ve3vm263vwf
- 原文：https://simonwillison.net/2026/Nov/11/llm/

## 摘要

LLM 0.37.2 版本修复了由 Daniel de Araujo 报告的安全问题。新引入的 llm openai endpoint add 命令允许使用兼容 OpenAI 的 API 端点，但存在两种情况可能导致配置的 OpenAI API 密钥意外泄露。
