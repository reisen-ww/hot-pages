# 开源日报 · 2026-11-17

- 期号：第 31 期
- 发布：2026-11-17 08:00（北京时间）
- 本期页：[阅读本期](https://reisen-ww.github.io/hot-pages/openhot/daily/2026-11-17)

## 头条

uBlock Origin 存在可被网站驱动的元素选择器 XSS 漏洞

## 工具与项目

1. [个人开发者开源 Python SQLite 函数缓存库 FunkyCache](https://reisen-ww.github.io/hot-pages/openhot/items/zei58gxjawq9mr6za2n1paidd)
   来源：Lobsters 热榜 · 发布时间：2026-11-16 21:15（北京时间）
   摘要：作者发布 Python 库 FunkyCache，利用 SQLite 实现函数缓存，减少静态网站生成时间。该库支持依赖文件追踪（如 Markdown 文件）、静态值监控（如 Pygments 版本），并对比 MD5 与 XXH64 哈希算法性能，证明 XXH64 在大键场景下速度提升显著。
   原文：[打开原文](https://alexwlchan.net/2026/funkycache/)

## 应用与安全

1. [uBlock Origin 存在可被网站驱动的元素选择器 XSS 漏洞](https://reisen-ww.github.io/hot-pages/openhot/items/vmvo81vgo78w2fx4e2r4uezvt)
   来源：Lobsters 热榜 · 发布时间：2026-11-16 13:12（北京时间）
   摘要：uBlock Origin 存在一个可被恶意网站利用的元素选择器 XSS 漏洞，攻击者可通过伪造可信过滤器注入任意 JavaScript 代码。漏洞利用机制涉及窃取扩展 UUID、劫持元素选择器界面、绕过过滤类型限制。修复方案包括验证消息令牌和限制元素选择器权限。
   原文：[打开原文](https://iter.ca/post/ubo-uxss/)

2. [Three.js光照管线优化：G缓冲、SSR与SSGI整合方案及性能对比](https://reisen-ww.github.io/hot-pages/openhot/items/ya19v5tqy6npwd9ft1vua42oo)
   来源：Hacker News 热榜 · 发布时间：2026-11-17 05:07（北京时间）
   摘要：Three.js维护者通过优化G缓冲、动态光照探针和屏幕空间反射（SSR/SSGI）等组件，将4K分辨率下的内存占用从626MB降至322MB。
   原文：[打开原文](https://ben3d.ca/blog/building-the-aaa-lighting-pipeline-in-threejs)
