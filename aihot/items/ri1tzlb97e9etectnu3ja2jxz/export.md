# AWS Bedrock 按身份追踪和控制支出指南

> 原标题：Tokenomics at scale: Track and cap Amazon Bedrock spend per IAM principal with CUR 2.0 and AWS Budgets

- 来源：AWS Machine Learning Blog
- 发布时间：2026-11-12T19:29:55.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/ri1tzlb97e9etectnu3ja2jxz
- 原文：https://aws.amazon.com/blogs/machine-learning/tokenomics-at-scale-track-and-cap-amazon-bedrock-spend-per-iam-principal-with-cur-2-0-and-aws-budgets/

## 摘要

AWS Bedrock 通过 CUR 2.0 报表导出和 AWS Budgets 预算机制，实现按 IAM 原主身份追踪和控制支出，无需编写应用代码。方案分三步：1）通过 IAM 原主标签或会话标签映射身份；2）激活成本分配标签并导出包含身份信息的 CUR 2.0 数据；3）设置预算触发自动拒绝高成本模型访问。特别说明：预算执行存在 3-24 小时延迟，需配合成本探索器使用。

## 推荐理由

原文给出了使用 AWS原生工具 CUR 2.0 和 AWS Budgets 实现按身份追踪和控制 Amazon Bedrock 支出的完整方案，无需编写应用代码即可自动限制高成本模型访问
