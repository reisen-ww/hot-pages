# Stream Vessel 修复 MCP 开放重定向漏洞：用户自主管理信任地址列表

> 原标题：Letting users trust their own MCP clients, without opening a phishing hole

- 来源：Hacker News 热榜
- 发布时间：2026-11-04T15:30:57.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/dmi1f2ki2iss4r576o2zdn7n9
- 原文：https://streamvessel.com/blog/mcp-trusted-redirect-uris

## 摘要

Stream Vessel 团队通过用户自定义信任地址机制，修复了 MCP 服务器因开放重定向导致的账户接管漏洞。攻击链演示：匿名注册恶意客户端→伪造可信重定向域名→用户点击Approve→授权码泄露。

## 推荐理由

文章提出通过用户自主管理信任地址列表（最多10个）和严格重定向URI验证机制，在保持MCP协议开放性的同时防御开放重定向攻击，并引用RFC 9700标准说明技术方案。
