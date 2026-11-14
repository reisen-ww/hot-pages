# AWS发布新一代AgentCore运行时：性能提升与安全增强

> 原标题：Run agents securely and efficiently with the next generation AgentCore runtime

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-12T17:59:59.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/ub5ixhvlcsnztadutvqou2wnx
- 原文：https://aws.amazon.com/blogs/machine-learning/run-agents-securely-and-efficiently-with-the-next-generation-agentcore-runtime/

## 摘要

AWS发布新一代AgentCore运行时，核心改进包括：1）启动速度提升15倍，支持8vCPU/32GB内存环境；2）运行效率提升68%，支持10GB容器镜像；3）数据隔离扩展至存储层，可动态挂载S3桶。客户实测显示推理请求冷启动速度提升35%，健康检查启动快77%，内存成本降低17%。该版本通过硬件隔离Firecracker微虚拟机（MicroVM）实现安全执行，并支持按需弹性扩展。

## 推荐理由

原文提供了新一代AgentCore运行时的性能提升（启动快15倍、计算能力提升4倍）、成本优化（内存减少60%）及数据隔离增强（支持动态挂载存储）等关键数据，读者可据此评估其对现有AI工作流的影响。
