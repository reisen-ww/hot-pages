# 利用Bash邮件验证漏洞可获取GNU Savannah系统最高权限

> 原标题：Securing Internet-Critical Software: How We Could Have Backdoored Bash

- 来源：Lobsters 热榜
- 发布时间：2026-11-02T15:06:38.656Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/gk4uplq2nx48q1nsign4uhkca
- 原文：https://www.hacktron.ai/blog/hacking-gnu-savannah

## 摘要

Hacktron团队通过测试发现GNU Savannah的GPG密钥验证存在漏洞，攻击者可利用该漏洞获取系统root权限并篡改Bash等项目的上游代码仓库。具体利用路径为：注册含IFS插件的邮箱地址→触发GPG密钥测试→通过Shell命令注入执行任意代码→利用未修复的内核漏洞获取root→通过备份服务器访问关键基础设施。

## 推荐理由

该漏洞允许攻击者通过邮件地址注入Shell命令，进而获取系统最高权限，影响Bash等关键软件项目，FSF已发布修复方案。
