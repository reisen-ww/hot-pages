# Immich 数据恢复演练简要检查清单

> 原标题：I finally did an Immich restore drill. Here's the short checklist I'll actually follow next time

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-10T14:09:19.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/u7viqyqa3po4hev1hduqef1ek
- 原文：https://www.reddit.com/r/selfhosted/comments/1xsntxt/i_finally_did_an_immich_restore_drill_heres_the/

## 摘要

Immich 使用 Postgres 存储路径和元数据，完整恢复需备份 library、upload、profile、thumbs、encoded-video 和 backups 文件夹。先停止 immich-server 容器或先备份数据库再备份文件，确保数据库指向已备份的照片。验证恢复后，检查照片数量和功能。
