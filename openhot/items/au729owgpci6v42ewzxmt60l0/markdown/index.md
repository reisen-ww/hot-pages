# 某开发者开源 Python 自托管部署工具，单机测试性能优于 Dokploy

> 原标题：I built a small self-hosted deploy tool for one machine (Cloudflare Tunnel + systemd, no dependencies) and measured it against Dokploy

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-08T03:11:08.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/au729owgpci6v42ewzxmt60l0
- 原文：https://www.reddit.com/r/selfhosted/comments/1xqod4i/i_built_a_small_selfhosted_deploy_tool_for_one/

## 摘要

某开发者通过 Reddit 公开自托管部署工具 hoist，支持单机运行并实现 Git push 部署。测试显示 hoist 平均部署耗时 1.54 秒，优于 Dokploy 的 2.53 秒，但存在容器切换间隙（0.65-1.45 秒）。
