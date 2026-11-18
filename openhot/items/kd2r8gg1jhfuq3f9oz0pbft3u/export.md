# 某开发者解决NixOS路由器IPv6地址切换延迟问题

> 原标题：IPv6 delegation, an unusually subtle failure mode

- 来源：Hacker News 热榜
- 发布时间：2026-11-15T18:06:13.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/kd2r8gg1jhfuq3f9oz0pbft3u
- 原文：https://savyasacheejha.com/posts/why-odhcpd/

## 摘要

某开发者通过替换DHCP服务odhcpd解决NixOS路由器IPv6地址切换延迟问题。详细描述了从pppd重启导致Google IPv6访问失败的现象，通过RFC 9096标准对比发现网络d存在旧地址保留问题，最终在NixOS自托管环境中部署odhcpd实现90分钟有效/存活时间。实验显示iPhone在Wi-Fi断连时仍需10分钟才能切换新IPv6地址，验证了RFC 9096的改进必要性。
