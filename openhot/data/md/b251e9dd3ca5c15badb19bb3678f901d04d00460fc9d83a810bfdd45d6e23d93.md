# 某矿工通过电压故障注入解锁A100芯片的完整方案

> 原标题：Using voltage glitching to unleash the A100 in my mining card

- 来源：Hacker News 热榜
- 发布时间：2026-11-11T10:48:40.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/rvpq83xq6e6u43oxluhiy37xz
- 原文：https://blog.kate.land/posts/using-voltage-glitching-to-unlock-the-a100/

## 摘要

作者通过电压故障注入技术解锁了NVIDIA GA100芯片，使其性能达到零售A100的1.2倍（FP16 FMA吞吐量85.858 TFLOPs/s）。关键步骤包括：1）硬件改装（移除0402 0ohm电阻、桥接U11芯片引脚） 2）利用VFI技术清除安全熔丝 3）配置PCIe Gen4和NVLink。
