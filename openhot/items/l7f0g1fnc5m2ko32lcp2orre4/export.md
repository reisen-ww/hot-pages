# Antonio 开发 Rust 工具 lend，远程 agents 无需共享凭证即可安全运行命令

> 原标题：Running coding agents without handing them my credentials

- 来源：Hacker News 热榜
- 发布时间：2026-11-17T01:18:56.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/l7f0g1fnc5m2ko32lcp2orre4
- 原文：https://blog.antonio.cx/running-agents-with-lend

## 摘要

Antonio 在 GitHub 开源 Rust 工具 lend，通过本地审批代理实现：1. 远程 agents 访问本地 CLI（如 gh）需逐条生物识别审批 2. SSH 客户端通过固定符号链接维持跨重连稳定性 3. 支持从 1Password 隐式注入密钥（如 GH_TOKEN） 4. 提供政策配置模板（JSON 示例见正文） 5. 与 herdr 终端多分屏系统深度集成。工具限制在 macOS/Linux，未实现交互式 PTY。
