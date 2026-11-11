# 两块GPU如何分配给多个模型？

> 原标题：Two GPUs, multiple models, which ones should get a dedicated card?

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-07T05:53:49.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/n0opjpdncm1jx9ihwp6x8d1m6
- 原文：https://www.reddit.com/r/selfhosted/comments/1xpyyfq/two_gpus_multiple_models_which_ones_should_get_a/

## 摘要

一个团队使用两块不同大小的GPU运行多个模型，面临如何分配的问题。选项A是每个模型绑定一块GPU，确保隔离；选项B是将小模型集中到一块GPU上，以节省资源但可能增加VRAM竞争。社区讨论了实际操作方法。
