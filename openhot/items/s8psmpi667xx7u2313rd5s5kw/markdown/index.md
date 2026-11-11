# Puppet服务器存在远程代码执行漏洞及主机身份伪造漏洞

> 原标题：Pulling the right strings for RCE on a Puppet

- 来源：Lobsters 热榜
- 发布时间：2026-11-04T07:39:20.951Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/s8psmpi667xx7u2313rd5s5kw
- 原文：https://neodyme.io/en/blog/puppet_rce

## 摘要

某团队发现Puppet的两个安全漏洞：1. Puppet服务器通过事件反序列化实现远程代码执行（CVSS 9.1）；2. 主机身份伪造漏洞允许未经授权的认证。漏洞影响企业环境中的配置管理，供应商已于2026年11月3日发布修复补丁，并公开安全公告（GHSA-ffr6-rwpm-p5wq和GHSA-q4hm-33rc-572g）。

## 推荐理由

披露了Puppet的两个高评分远程代码执行漏洞及修复方案，包含具体利用步骤和影响分析
