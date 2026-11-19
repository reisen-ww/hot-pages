# 重构本地语音助手流水线

> 原标题：Rebuilding my local voice assistant pipeline

- 来源：Lobsters 热榜
- 发布时间：2026-11-19T19:50:25.512Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/y1atctlz22uzu8qjqztxj2je3
- 原文：https://blog.platypush.tech/article/Rewriting-my-voice-assistant-pipeline

## 摘要

作者重构了其语音助手的唤醒词检测和语音转文本模块，采用新的 `assistant.microwakeword` 插件替代了旧的 `assistant.openwakeword`，并使用 `assistant.openai` 进行语音转文本处理。新流水线在噪声环境下的表现更佳，减少了误触发和漏触发的情况。
