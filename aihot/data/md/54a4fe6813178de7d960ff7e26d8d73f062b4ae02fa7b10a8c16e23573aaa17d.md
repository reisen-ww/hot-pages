# NVIDIA Kumo Forecast 结合预训练时序表征、历史模式检索与可解释性

> 原标题：NVIDIA Kumo Forecast Combines Pretrained Time-Series Representations with Historical Pattern Retrieval and Interpretability

- 来源：Hugging Face Blog
- 发布时间：2026-10-21T12:51:24.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/dhhznnu98jhloitpouo0j8i4e
- 原文：https://huggingface.co/blog/nvidia/kumo-forecast

## 摘要

NVIDIA Kumo Forecast（原名 NV-Tesseract Forecasting）以 Apache 2.0 许可开源，是基于 MOMENT-1-large 骨干、约 340M 参数编码器加可训练预测头的多变量时序预测模型。DARR 模式用 k 近邻从历史数据检索模式并与直接预测融合，可解释性框架按预测步长输出 lag 与特征归因、语义流诊断等解释。
