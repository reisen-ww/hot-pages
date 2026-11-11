# Immich Machine Learning 默认启用微软 Telemetry 数据收集，用户已提供禁用方案

> 原标题：PSA: Immich Machine Learning has Microsoft Telemetry enabled by default, here's how to disable it

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-04T01:54:39.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ns35scwf1fntudhiwwexk4juh
- 原文：https://www.reddit.com/r/selfhosted/comments/1xnbujt/psa_immich_machine_learning_has_microsoft/

## 摘要

用户发现 Immich Machine Learning 默认使用微软 ONNX Runtime 库并开启数据收集，已提供环境变量禁用（ORT_DISABLE_TELEMETRY=1）及容器网络隔离方案（创建内部网络并限制容器访问）。该问题尚未被官方修复，涉及供应链安全风险。
