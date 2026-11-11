# AWS Batch 配额管理支持跨团队资源共享

> 原标题：Lend and borrow resources across teams with AWS Batch’s quota management for SageMaker Training jobs

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-29T16:58:57.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/zq8o1wzbq1ui80w6vyy0hmf11
- 原文：https://aws.amazon.com/blogs/machine-learning/lend-and-borrow-resources-across-teams-with-aws-batchs-quota-management-for-sagemaker-training-jobs/

## 摘要

AWS Batch 新增配额管理功能，允许按团队/项目分配 GPU 资源并自动共享闲置容量。管理员可通过 LEND_AND_BORROW 策略实现跨配额共享，并设置优先级抢占。示例代码展示了如何通过 SageMaker Python SDK 配置三个配额份额（QS1-QS3），分别对应不同优先级的工作负载，并通过更新任务优先级触发抢占机制。

## 推荐理由

原文给出了能力变化和开放入口，读者可以据此判断它会怎样改变现有工作流。
