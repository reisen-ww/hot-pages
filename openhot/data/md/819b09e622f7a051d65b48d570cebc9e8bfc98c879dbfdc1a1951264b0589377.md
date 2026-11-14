# Sable开源项目改进Matrix协议预览链接生成技术方案

> 原标题：Link Previews and You

- 来源：Lobsters 热榜
- 发布时间：2026-11-13T17:34:47.014Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/nzsmj32nb6rj1k7l1hicc65uh
- 原文：https://sable.moe/en/blog/link-previews-and-you/

## 摘要

Sable开源项目发布Matrix协议预览链接生成技术方案，通过独立代理服务实现隐私保护，对比Discord和Signal的实现差异。技术方案包含：1）将预览生成模块拆分为独立库以优化架构；2）开发OpenGraph扩展规范支持社交媒体预览；3）基于Soliditas自托管基础设施运行隐私代理服务器。未来计划探索完全移除 homeserver 生成预览的可能性，并持续优化用户界面与隐私提示。
