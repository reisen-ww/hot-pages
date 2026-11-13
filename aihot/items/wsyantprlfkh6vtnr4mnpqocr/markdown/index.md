# Hugging Face发布TRELLIS.2 3D模型LoRA微调完整指南

> 原标题：The Definitive Fine-Tuning Guide for 3D Generation Models

- 来源：Hugging Face Blog
- 发布时间：2026-11-12T00:00:00.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/wsyantprlfkh6vtnr4mnpqocr
- 原文：https://huggingface.co/blog/3d-lora-finetuning

## 摘要

Hugging Face发布基于LoRA的TRELLIS.2 3D模型微调教程，包含数据准备、训练命令和评估指标。教程使用188双鞋的GSO数据集，通过冷冻原始模型权重，仅微调控制物体形状和细节的DiT模块，最终使鞋底 Chamfer 距离降低66.7%（0.174→0.033），F-score提升186%（0.276→0.803）

## 推荐理由

提供了LoRA微调TRELLIS.2生成3D模型的完整教程，包含数据准备、训练命令和评估指标
