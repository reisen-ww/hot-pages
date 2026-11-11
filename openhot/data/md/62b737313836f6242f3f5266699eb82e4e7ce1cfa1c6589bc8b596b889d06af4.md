# 某ARM固件安全启动流程存在单次指令跳过漏洞

> 原标题：From 25M instructions to one faulty skip: fault analysis of a secure boot

- 来源：Hacker News 热榜
- 发布时间：2026-11-04T14:20:31.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/ekaccn8fl5f8vgq7ev2r5qlqu
- 原文：https://www.eshard.com/blog/one-faulty-skip-secure-boot

## 摘要

某团队通过AI辅助逆向工程，发现某ARM固件安全启动流程中存在单次指令跳过漏洞，可导致验证失败。测试用例显示，在安全内存比较（secure_memcmp）和RSA-PSS验证（RSA-2048）环节中，跳过分支判断指令（bne reject_path）后，验证结果从0x55555555（拒绝）变为0xAAAAAAAA（接受），且未发现后续二次验证。执行轨迹对比文件已记录在案，可独立复现验证过程。
