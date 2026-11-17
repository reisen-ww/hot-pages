# uBlock Origin 存在可被网站驱动的元素选择器 XSS 漏洞

> 原标题：Universal XSS in uBlock Origin from website-driven element picker

- 来源：Lobsters 热榜
- 发布时间：2026-11-16T05:12:27.923Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/vmvo81vgo78w2fx4e2r4uezvt
- 原文：https://iter.ca/post/ubo-uxss/

## 摘要

uBlock Origin 存在一个可被恶意网站利用的元素选择器 XSS 漏洞，攻击者可通过伪造可信过滤器注入任意 JavaScript 代码。漏洞利用机制涉及窃取扩展 UUID、劫持元素选择器界面、绕过过滤类型限制。修复方案包括验证消息令牌和限制元素选择器权限。

## 推荐理由

该漏洞允许攻击者通过伪造可信过滤器注入任意 JavaScript 代码，影响浏览器安全，需及时更新补丁
