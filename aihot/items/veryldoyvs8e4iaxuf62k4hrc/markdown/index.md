# Amazon SageMaker HyperPod 静默数据损坏检测与恢复方法

> 原标题：Detecting and recovering from silent data corruption on Amazon SageMaker HyperPod

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-11T23:30:03.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/veryldoyvs8e4iaxuf62k4hrc
- 原文：https://aws.amazon.com/blogs/machine-learning/detecting-and-recovering-from-silent-data-corruption-on-amazon-sagemaker-hyperpod/

## 摘要

本文介绍了在Amazon SageMaker HyperPod中检测和恢复静默数据损坏的三种方法：1）梯度非有限值检查（捕获NaN/Inf异常）；2）环式回放审计（通过跨节点微批次复现验证计算路径错误）；3）权重指纹比较（检测更新后权重不一致）。

## 推荐理由

提供了三种可复用的检测静默数据损坏的方法，并附有GitHub代码实现
