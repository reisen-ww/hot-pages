# DDR3+ 接口必须在启动时调谐的原因

> 原标题：The DRAM interface and the PHY (why a DDR3+ interface must be tuned at boot)

- 来源：Hacker News 热榜
- 发布时间：2026-11-10T23:41:41.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ppusrdij8qk69hxtei41y4geu
- 原文：https://github.com/enjoy-digital/litedram/blob/master/doc/manual/03_dram_interface.md

## 摘要

DDR3+ 接口在启动时需要调谐以确保数据传输的准确性和效率。文章解释了 DRAM 接口的信号、时钟、延迟校准和数据掩码等细节，并详细描述了 LiteDRAM 如何实现这些机制。写入校准和 DQ-DQS 训练确保数据在写入时正确对齐，而读取延迟校准则进一步优化读取性能。
