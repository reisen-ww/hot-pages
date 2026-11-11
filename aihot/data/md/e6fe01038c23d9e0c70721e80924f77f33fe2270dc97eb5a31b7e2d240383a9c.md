# 基于LoRA的知识蒸馏方法在购物代理中的应用

> 原标题：Build efficient agents with knowledge distillation on Amazon SageMaker AI

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-02T17:01:31.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/uuu1lueoccea54chezy5jjude
- 原文：https://aws.amazon.com/blogs/machine-learning/build-efficient-agents-with-knowledge-distillation-on-amazon-sagemaker-ai/

## 摘要

通过LoRA知识蒸馏，将Qwen3.5-4B模型压缩后，在购物任务中平均绝对成功率提升至54.1%（原教师模型54.0%）。方法包括生成高质量轨迹（保留推理步骤）、使用SageMaker进行LoRA微调（3个epoch/16k上下文）、通过AI模型评估验证效果（工具调用匹配度+13%）。部署成本对比：压缩后模型可在ml.g6e.2xlarge实例运行，相比原教师API调用节省90%成本。

## 推荐理由

通过LoRA知识蒸馏，将4B模型压缩后保持与原教师模型接近的任务成功率，并详细描述了训练、评估和部署流程
