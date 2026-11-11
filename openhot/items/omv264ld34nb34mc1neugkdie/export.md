# 我破解了健身房强制使用的社交应用

> 原标题：My gym forced a social media down my throat. So I reverse-engineered its app

- 来源：Hacker News 热榜
- 发布时间：2026-11-05T17:30:17.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/omv264ld34nb34mc1neugkdie
- 原文：https://shayon.work/blog/reverse-engineering-gym-pass

## 摘要

我最近加入了一家健身房，发现其应用首页为社交动态，每次使用都强制展示类似 Tinder 的内容。为摆脱这一强制推送，我通过反向工程提取了 QR 码逻辑，并成功开发了一个独立的 SvelteKit 应用来生成二维码，从而避免了每次使用时被社交应用打扰。
