# 创建自启动 ZIP 存档

> 原标题：goliath32.com - Creating a self booting ZIP archive

- 来源：Lobsters 热榜
- 发布时间：2026-11-14T10:01:58.119Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/wticsm79i44rtbnqtjhkqeyx7
- 原文：https://goliath32.com/blog/ziphead.html

## 摘要

作者创建了一个自启动 ZIP 存档，包含源代码用于从零构建自身。该存档的首 512 字节包含有效的引导扇区，可加载更多代码并启用 A20 位线和 32 位保护模式。存档中的 ZIPHEAD.COM 文件包含启动代码，可以在 Qemu 中直接运行或写入软盘启动。
