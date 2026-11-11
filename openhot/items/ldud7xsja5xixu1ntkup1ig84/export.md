# 如何管理多台机器上的本地模型集合？

> 原标题：How do you keep your local model collection organized across machines?

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-03T15:28:34.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ldud7xsja5xixu1ntkup1ig84
- 原文：https://www.reddit.com/r/selfhosted/comments/1xmvylt/how_do_you_keep_your_local_model_collection/

## 摘要

作者使用 KitOps 将模型打包并推送到本地容器注册表，通过标签记录测试过的量化版本，但认为这可能对一些配置来说过于复杂。社区讨论了使用 NAS 上的共享 Hugging Face 缓存、镜像代理或 rsync 脚本等更简单的选项。
