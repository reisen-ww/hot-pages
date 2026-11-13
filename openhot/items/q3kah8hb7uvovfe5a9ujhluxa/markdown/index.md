# 某作者开源支持NTFS/FAT/exFAT格式的磁盘数据恢复工具Reflota（测试版）

> 原标题：Show HN: Reflota – Open-source data recovery for NTFS/FAT disks with phased copy

- 来源：Hacker News 热榜
- 发布时间：2026-11-13T12:17:52.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/q3kah8hb7uvovfe5a9ujhluxa
- 原文：https://github.com/Christ10-8/reflota

## 摘要

Reflota是一款开源磁盘数据恢复工具，支持NTFS、FAT32、exFAT文件系统，可从物理磁盘直接读取并恢复删除文件。测试版状态下已验证FAT16/FAT12、相机RAW文件、PSD等格式恢复，提供分阶段复制（快速扫描→边缘修复→逐扇区复制）和内容搜索功能，不写入原磁盘。用户需管理员权限读取物理磁盘，工具生成校验哈希确保下载安全。
