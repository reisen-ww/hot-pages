# 某团队自托管Plausible分析容器中发现未经授权的加密货币挖矿程序

> 原标题：Cryptominer in my Plausible anayltics container

- 来源：Reddit r/selfhosted
- 发布时间：2026-11-05T02:33:36.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/o62d4g72xdmxc1xxfrsu0wvk2
- 原文：https://www.reddit.com/r/selfhosted/comments/1xo7agf/cryptominer_in_my_plausible_anayltics_container/

## 摘要

某团队自托管Plausible分析容器中发现未经授权的加密货币挖矿程序，该程序利用CVE-2026-8467漏洞运行，最终通过/proc路径终止进程。修复措施包括升级至v3.2.1版本、删除linuxsys伪装进程、限制Docker socket访问权限，并建议设置定时更新检查和镜像追踪机制。完整分析见404privacy.com的详细技术文档。

## 推荐理由

提供了具体的CVE编号、漏洞利用路径及修复版本，对开发者排查类似安全事件有参考价值。
