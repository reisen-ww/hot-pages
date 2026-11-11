# 某作者通过逆向工程与LLM辅助，成功破解廉价IP摄像头ONVIF流服务

> 原标题：Taking another shot at the cheap IP camera, part 2

- 来源：Hacker News 热榜
- 发布时间：2026-11-09T14:40:42.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/yc73yqxopn5eik3mibutac0jr
- 原文：https://ericswpark.com/blog/2026/2026-11-09-ip-camera-pt2/

## 摘要

某作者通过逆向工程和LLM辅助分析，成功破解廉价IP摄像头ONVIF流服务。首先提取固件发现运行Linux 3.4.35旧内核，通过Ghidra反汇编定位ONVIF配置项，利用strcasecmp函数查找配置路径。
