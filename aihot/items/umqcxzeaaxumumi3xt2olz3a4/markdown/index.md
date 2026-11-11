# 使用 Claude Code 开发声源定位系统 Beep Locator

> 原标题：Locating the source of a mysterious beep with Claude

- 来源：Simon Willison
- 发布时间：2026-11-09T23:57:21.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/umqcxzeaaxumumi3xt2olz3a4
- 原文：https://simonwillison.net/2026/Nov/9/mysterious-beeps/

## 摘要

通过多设备协作和声波三角定位算法，成功定位到误差约40cm的神秘蜂鸣声源。系统使用Python Web服务器协调设备，通过WebSocket实现实时通信，并集成WebAudio进行音频采集。用户可手动校准设备位置或通过声波回传验证目标。开源代码已部署在GitHub，包含自动更新模块和声纹分类功能。
