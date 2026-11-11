# 使用 Docker 部署 PiHole 和 Caddy 反向代理遇到的问题

> 原标题：Rpi Docker PiHole and Caddy Reverse Proxy

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-05T18:19:38.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/h5i9go9hkdatl3bl46juhyw5j
- 原文：https://www.reddit.com/r/selfhosted/comments/1xoq1bg/rpi_docker_pihole_and_caddy_reverse_proxy/

## 摘要

作者将 PiHole 和 wavelog 分别部署在 Docker 中，现在需要通过 Caddy 实现外部访问。遇到的主要问题是配置 Caddy 和 PiHole 在 Docker 中协同工作，以便 PiHole 继续内部工作，Caddy 能响应外部流量，wavelog 可以从外部网络访问。
