# Edgely Console 允许 Claude 安全访问家庭实验室而无需提供密码

> 原标题：Let Claude poke around my homelab without giving it my passwords (MCP server in the SSH client I work on)

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-11T11:54:35.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ax5m2j05mhwmhtwbstpcpbvqu
- 原文：https://www.reddit.com/r/selfhosted/comments/1xtfujd/let_claude_poke_around_my_homelab_without_giving/

## 摘要

Edgely Console 是一个用于 SSH、SFTP、RDP 和 VNC 的桌面应用，新增了 MCP 服务器功能，允许 Claude 等工具查询磁盘使用情况和容器日志，但仅限读取操作，除非用户明确开启写入模式。写入模式下，Claude 可以运行任意命令和上传文件，但每次删除操作都需要用户确认。密码和密钥保存在本地，不会泄露。
