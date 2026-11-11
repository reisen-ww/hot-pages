# 如何保持 Docker Swarm 发布的一致性？

> 原标题：How do you keep Docker Swarm releases consistent across images, configs and database migrations?

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-05T14:55:44.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/lfyfvjay3rribe30m38i2jiym
- 原文：https://www.reddit.com/r/selfhosted/comments/1xokp3s/how_do_you_keep_docker_swarm_releases_consistent/

## 摘要

该团队自托管后端使用 Docker Swarm，并在 Hetzner 上运行 PostgreSQL。GitLab CI 构建镜像并发布到 AWS ECR，Swarm 管理器验证并更新配置和服务。当重新发布较旧的应用版本时，可能会出现兼容性问题，因为存在较新的迁移版本。讨论如何在部分应用发布时保持一致性，包括是否在同一个发布清单中固定迁移和配置摘要，以及如何处理部分应用的发布。
