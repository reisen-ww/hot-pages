# Ruby 中的 nothing_provided 技巧

> 原标题：Moment of Ruby: An Argument for Nothing

- 来源：Hacker News 热榜
- 发布时间：2026-11-02T20:32:57.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/k6nu8jhh3pqsfx37ve0nk25wd
- 原文：https://www.aha.io/engineering/articles/moment-of-ruby-an-argument-for-nothing

## 摘要

作者发现了一个在 Ruby 中区分是否提供参数值的小技巧。通过将默认参数表达式设置为一个赋值操作，当参数省略时，表达式会被评估并作为默认值使用；若提供任何参数，即使为 false 或 nil，表达式将不会被评估，从而实现区分不同情况的目的。这一技巧最初由 Addendum byroot 在 Rails PR #44611 中提出。
