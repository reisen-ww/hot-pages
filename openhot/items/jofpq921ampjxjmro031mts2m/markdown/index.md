# PyPI 实施更严格的软件包上传检查机制

> 原标题：Stricter checks for uploaded distributions on PyPI

- 来源：Lobsters 热榜
- 发布时间：2026-11-18T20:00:42.222Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/jofpq921ampjxjmro031mts2m
- 原文：https://blog.pypi.org/posts/2026-11-18-stricter-checks-for-uploaded-sdists/

## 摘要

PyPI 宣布将实施更严格的软件包上传检查机制，以减少解析差异和提升安全性。当前已禁止 V7-style tar 归档和包含 ZIP 控制结构的评论，后续计划全面禁止 GNU 风格 tar 和 ZIP 评论。

## 推荐理由

PyPI 通过限制非标准 tar 和 ZIP 格式来减少解析差异，提升软件包分发安全性，维护者需确保使用合规的构建工具。
