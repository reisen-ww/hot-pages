# IEEE浮点数包sqrt(2)计算错误被披露

> 原标题：The VHDL standard's float package gets sqrt(2) wrong

- 来源：Hacker News 热榜
- 发布时间：2026-11-14T17:58:58.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/t4bjd7dqpd5p9cptu9gz48l7y
- 原文：https://github.com/lmtlssss/speedrunpapi/tree/main/hardware/audit/ieee-float-pkg

## 摘要

IEEE P1076工作组披露VHDL标准浮点数包存在sqrt(2)等运算错误，测试发现修复前float32格式37%的加法、乘法、除法及sqrt运算结果偏差，float64格式错误率分别为86%和77%。修复方案通过增加guard bits和调整舍入逻辑，在GHDL 7.0.0-dev和NVC 1.23.1中实现100%正确率。错误源于指数截断时未保留足够精度，导致分母截断后计算结果偏离预期。
