# Hugging Face 推出工具查询模型在 AWS Trainium 上的支持情况

> 原标题：Does Your Model Run on AWS Trainium? Look It Up

- 来源：Hugging Face Blog
- 发布时间：2026-10-23T00:00:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/j3hogv1ico5qm3en60fwppp1y
- 原文：https://huggingface.co/blog/torch-neuronx-model-support

## 摘要

Hugging Face 发布 torch-neuronx 模型支持 Space，可查询热门模型是否在 AWS Trainium 上无需修改即可运行，并提供对应的运行脚本和编译命令。该 Space 基于公开数据集，目前覆盖文本生成和图像文本到文本模型，测试条件为最多 4 个 Trainium2 设备（16 核），通过生成 32 个 token 验证结果。
