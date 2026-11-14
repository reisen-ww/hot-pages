# Doc-foundry – AI 自动生成并验证安全检测规则

> 原标题：Doc-foundry – AI writes Security detection rules, then proves they work

- 来源：Hacker News 热榜
- 发布时间：2026-11-13T23:40:12.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/i132sprk2wjhb22sn92heq67i
- 原文：https://github.com/mjha-arya/DOC-foundry

## 摘要

Doc-foundry 是一个基于 adversarial multi-agent 的检测工程框架，能够将威胁（如 CVE、CISA KEV 入口等）转化为经过验证的第一版检测规则，并生成 Sigma 检测规则、威胁报告和证明包。该工具通过蓝队和红队的对抗循环，确保生成的规则能够有效检测真实攻击，而不仅仅是声称覆盖所有未来变种。
