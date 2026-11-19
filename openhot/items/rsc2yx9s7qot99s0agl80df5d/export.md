# Ruby2ßhell：Stock Rails 预认证 RCE 漏洞披露

> 原标题：Ruby2ßhell: Pre-authentication RCE on stock Rails

- 来源：Hacker News 热榜
- 发布时间：2026-11-19T05:09:11.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/rsc2yx9s7qot99s0agl80df5d
- 原文：https://verialabs.com/ruby2shell/

## 摘要

Ruby2ßhell披露Stock Rails预认证远程代码执行漏洞，影响GitLab 19.6.0、GitHub Enterprise Server 3.22.5等主流软件，建议升级至Ruby 3.3.14/3.4.13/4.0.10。漏洞源于Ruby单字节编码处理不当，攻击者可通过输入21个ß字符触发缓冲区溢出，已通过上游提交d582f8f修复。
