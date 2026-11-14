# 通过反向工程与 AI 辅助，实现 Coway 空气净化器本地化控制并脱离云端依赖

> 原标题：Reverse engineering my Coway air purifier to ditch the cloud

- 来源：Hacker News 热榜
- 发布时间：2026-11-12T22:03:09.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/h6u4p7a0w0lfjsoltcebzj5bn
- 原文：https://scottjg.com/posts/2026-11-11-reverse-engineering-my-coway-air-purifier-to-ditch-the-cloud/

## 摘要

作者通过 mitmproxy 和 Python 脚本，绕过 Coway 云服务依赖，实现设备本地化控制。关键步骤包括：1. 利用 AI 生成 mitmproxy 插件拦截设备与云端通信；2. 通过 Web Bluetooth 配置设备 Wi-Fi 参数；3. 自建 MQTT 服务器替代 Coway 云端服务。最终实现 'Good Night' 按钮联动空气净化器与智能家居系统。
