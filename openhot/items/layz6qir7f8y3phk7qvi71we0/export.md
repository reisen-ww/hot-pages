# pwn.ai 披露 CVE-2026-99999：Linux 网络栈漏洞导致 KVM 虚拟机逃逸

> 原标题：PwnEscape: Guest-to-Host KVM Escape (CVE-2026-99999)

- 来源：Lobsters 热榜
- 发布时间：2026-10-17T18:24:39.593Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/layz6qir7f8y3phk7qvi71we0
- 原文：https://pwn.ai/blog/pwnescape

## 摘要

pwn.ai 团队通过 Vercel 的百万美元沙箱挑战，发现 Linux 网络栈中校验和元数据在延迟处理时可篡改 IPv4 头，进而实现宿主机内存读取与代码执行。该漏洞被分配为 CVE-2026-99999，上游 Linux 内核已通过提交 6785011f8b16 修复，通过在五个关键位置添加校验和起始地址验证来阻断攻击路径。

## 推荐理由

文章提供了从虚拟机逃逸到宿主机代码执行的完整证据链，并给出了内核修复方案与审计思路，供安全研究者参考。
