# Unity土耳其字母导致多款游戏崩溃问题已修复

> 原标题：This Turkish Letter Keeps Breaking the World's Software - YouTube

- 来源：Reddit r/programming
- 发布时间：2026-11-12T08:15:24.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/j0012r36201grgyebfdmh122m
- 原文：https://www.reddit.com/r/programming/comments/1xu79k2/this_turkish_letter_keeps_breaking_the_worlds/

## 摘要

Unity因土耳其字母‘İ/i’和‘I/ı’的 casing 规则差异导致多款游戏（CRYSTAR、Speedrunners）在土耳其语言设置下无法启动。开发者通过将 C# 的 ToUpper 方法替换为 ToUpperInvariant 或使用 StringComparison.OrdinalIgnoreCase 解决问题，建议所有软件公司采用‘土耳其测试’确保兼容性。

## 推荐理由

Unity土耳其字母导致多款游戏崩溃问题已修复，开发者可参考Invariant culture方法避免类似问题
