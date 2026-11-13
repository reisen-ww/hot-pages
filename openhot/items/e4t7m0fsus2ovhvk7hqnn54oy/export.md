# 某团队开源解决四块GPU内存分配冲突的Linux PCIe桥接方案

> 原标题：Fitting Four 32 GB Resizable Bars Behind a PCIe Switch on Linux

- 来源：Hacker News 热榜
- 发布时间：2026-11-12T15:14:52.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/e4t7m0fsus2ovhvk7hqnn54oy
- 原文：https://doug.sh/posts/gpu-bars-behind-a-pcie-switch/

## 摘要

某团队在GitHub开源了调整Linux PCIe桥接窗口的模块，测试了内核补丁修复效果并解释了资源分配问题原因。该方案通过initramfs在驱动加载前调整BAR对齐，使四块R9700显卡获得32GB BAR，同时保持两块RTX3090的512MB分配。

## 推荐理由

提供了基于initramfs的PCIe BAR调整模块，并测试了现有内核补丁的修复效果
