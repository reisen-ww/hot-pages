# Exa基于AWS Neuron芯片优化嵌入模型吞吐量提升50%

> 原标题：Exa boosts embedding throughput by 50% to index billions of documents on AWS AI chips

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-18T23:58:22.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/i9xagugm77a8u1mkjdu4cbb3n
- 原文：https://aws.amazon.com/blogs/machine-learning/exa-boosts-embedding-throughput-by-50-to-index-billions-of-documents-on-aws-ai-chips/

## 摘要

Exa通过硬件优化和算法调整在AWS Neuron芯片上实现嵌入吞吐量提升50%，并建立跨芯片调度机制降低长期成本。关键技术包括：1）使用NKI库优化注意力机制内核，2）定制SwiGLU MLP融合计算内核减少内存访问，3）通过Flyte平台实现智能体分工协作（轻量级模型负责参数搜索，强代码生成模型编写定制内核），4）在AWS Trainium2上延续优化成果。
