# 某开发者将ULC音频编码器适配到任天堂N64平台，实现低资源占用下的高质量音频播放

> 原标题：The ULC Audio Codec is a Perfect Fit for the N64

- 来源：Lobsters 热榜
- 发布时间：2026-11-05T09:25:36.067Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/uqosducgupkyiwildj64sgf59
- 原文：https://phoboslab.org/log/2026/11/n64-ulc-codec

## 摘要

开发者将Ultra Low Complexity Codec（ULC）适配到任天堂N64平台，在44100Hz立体声下实现16kbps码率，仅占用4% CPU和5% RSP资源。该编码器通过MDCT变换和 nibble 简化存储，相比ADPCM节省75%存储空间，且支持快速跳转查询。已应用于《半衰期》N64移植项目，证明在8MB-64MB有限存储的复古硬件上实现现代音频编解码的可行性。
