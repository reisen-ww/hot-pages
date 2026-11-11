# 降低 Bunkerweb 硬盘 I/O

> 原标题：Low the disk I/O of Bunkerweb

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-06T09:00:10.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/tzd5vhjzbd9hukz4acld3xs30
- 原文：https://www.reddit.com/r/selfhosted/comments/1xp86iv/low_the_disk_io_of_bunkerweb/

## 摘要

作者将 Nginx Proxy Manager 替换为激活了 Crowdsec 的 Bunkerweb 后发现硬盘 I/O 增加，希望减少 I/O 负载。由于使用的是机械硬盘，作者担心其运行时的噪音。
