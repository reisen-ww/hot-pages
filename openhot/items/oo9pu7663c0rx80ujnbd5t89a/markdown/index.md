# 某开发者开源Linux内核补丁，允许用户捕获并处理SIGKILL和SIGSTOP信号

> 原标题：Modding Linux to use SIGKILL on every process

- 来源：Lobsters 热榜
- 发布时间：2026-11-11T06:14:34.735Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/oo9pu7663c0rx80ujnbd5t89a
- 原文：https://vulpinecitrus.info/blog/what-if-you-could-handle-sigkill/

## 摘要

某开发者通过修改Linux 6.13.0内核的signal.c文件，移除对SIGKILL和SIGSTOP信号的特殊限制，使用户程序可设置处理函数。测试显示，该补丁允许程序捕获并处理原本无法拦截的SIGKILL（立即终止）和SIGSTOP（暂停进程）信号，代码示例包含信号处理函数和测试用例。
