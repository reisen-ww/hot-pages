# 用 AWS PrivateLink 保障企业网络中 Amazon Quick 的访问安全

> 原标题：Securing Quick access from corporate networks with AWS PrivateLink

- 来源：AWS Machine Learning Blog
- 发布时间：2026-10-21T23:38:38.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/palgcpqqzqdns6opejyu03kcp
- 原文：https://aws.amazon.com/blogs/machine-learning/securing-quick-access-from-corporate-networks-with-aws-privatelink/

## 摘要

这篇教程演示如何通过 AWS PrivateLink 将本地数据源私密接入 Amazon Quick，让流量不经过公共互联网。方案区分两条路径：VPC endpoints（AWS PrivateLink）承载用户与 API 访问流量，VPC connections 承载数据源访问流量，再叠加安全组与 VPC endpoint 策略做纵深防御。
