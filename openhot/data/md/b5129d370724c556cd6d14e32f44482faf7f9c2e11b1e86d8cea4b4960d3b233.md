# 自托管门面板：电子纸、门铃集成与Sonos铃声

> 原标题：Self-hosted door panel: e-paper, intercom integration and Sonos chime

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-08T15:13:26.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/z7f83qymce3ouk98f1xm8adh4
- 原文：https://www.reddit.com/r/selfhosted/comments/1xr0o09/selfhosted_door_panel_epaper_intercom_integration/

## 摘要

作者完成了一个自托管的公寓门电子纸面板项目，集成了门铃和旧模拟对讲机。使用ioBroker作为枢纽，通过MQTT与Sonos本地API交互，发送铃声而不影响其他音频设备。面板每30秒从后端获取更新数据，并仅在数据变化时重绘。每个按钮的操作固定且安全，通过Node.js后端处理。
