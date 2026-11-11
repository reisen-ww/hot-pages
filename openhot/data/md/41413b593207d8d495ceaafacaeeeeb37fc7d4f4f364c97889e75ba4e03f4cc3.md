# Android紧急呼叫功能遭远程漏洞攻击，单条恶意短信致设备永久性瘫痪

> 原标题：A single malformed WAP Push SMS crashes com.android.phone on Android, dropping active calls (including emergency calls)

- 来源：Lobsters 热榜
- 发布时间：2026-10-29T07:22:37.573Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/umnjdqt1yltkyf3oae634o1g7
- 原文：https://smsofdeath.com/

## 摘要

Android紧急呼叫功能遭远程漏洞攻击，单条恶意短信致设备永久性瘫痪。漏洞源于 unchecked cast导致数组越界，攻击者可零点击发送恶意WAP Push短信，造成通话中断、SQLite数据库损坏及设备变砖。澳大利亚运营商法规要求对无法接通紧急服务的设备进行封锁，该漏洞可能被滥用导致用户设备被运营商切断服务。

## 推荐理由

该漏洞允许远程攻击者通过发送恶意WAP Push短信导致Android设备紧急呼叫功能永久失效，且修复困难需物理SIM更换
