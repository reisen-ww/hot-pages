# 警告：要么使用VPN要么将SSH端口更改为非默认端口

> 原标题：PSA: Either hide behind VPN or move SSH to a non-default port

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-07T19:18:29.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/l4af4uzscn5arxhxk6ve2488h
- 原文：https://www.reddit.com/r/selfhosted/comments/1xqegxa/psa_either_hide_behind_vpn_or_move_ssh_to_a/

## 摘要

作者警告，即使使用SSH密钥，暴露在互联网上的默认SSH端口仍可能遭受快速扫描。将SSH端口更改为非默认端口可以有效避免初期攻击。作者自托管服务器多年未遭受SSH登录失败，而新启用默认SSH 22的VPS则在60秒内遭受300次攻击。
