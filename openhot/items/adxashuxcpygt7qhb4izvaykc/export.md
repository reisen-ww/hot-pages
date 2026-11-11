# 某开发者开源基于注释的 Kubernetes 运营器，无需 CRDs 自托管监控工具

> 原标题：I built an annotation-based Kubernetes operator for Uptime Kuma — no CRDs

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-05T12:50:04.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/adxashuxcpygt7qhb4izvaykc
- 原文：https://www.reddit.com/r/selfhosted/comments/1xohtqf/i_built_an_annotationbased_kubernetes_operator/

## 摘要

某开发者利用AI生成代码，开发了无需CRDs的Kubernetes运营器，可自动创建、更新和删除监控。通过在Deployment等资源上添加注释实现自动化，支持HTTP/TCP/ping/DNS监控及通知渠道同步，已验证兼容Kuma 1.x和2.x实例及Kubernetes E2E测试。GitHub仓库已开源，现寻求社区审查与反馈
