# 开源热点 月报 · 2026-10

- 期号：第 1 期
- 发布：2026-11-01 10:30（北京时间）
- 本期页：[阅读本期](https://reisen-ww.github.io/hot-pages/openhot/monthly/2026-10)

## 导语

Mage-VL-Cowork 模型发布：4B 规模自主桌面代理技术方案

本月 30 件大事，最受关注的是：Mage-VL-Cowork 模型发布：4B 规模自主桌面代理技术方案；Wiz Research 披露 PHP 核心引擎严重 RCE 漏洞 PHP2Shell；Android紧急呼叫功能遭远程漏洞攻击，单条恶意短信致设备永久性瘫痪。

## 工具与项目

1. [Coq 机器验证的 10 状态图灵机超过 Graham 数并刷新 BB(10) 记录](https://reisen-ww.github.io/hot-pages/openhot/items/lcf4ate7jbcfznoa58g51dbve)
   来源：Hacker News 热榜 · 发布时间：2026-10-13 20:40（北京时间）
   摘要：一台 10 状态图灵机 n1 已从空白纸带停机，其精确得分由 Coq 在无公理条件下机器验证，并超过 Graham 数与 BB(10) 当前冠军。n1 保留 BB(8) 记录的基础机器，仅改写 E0 转移并新增状态 I、J，通过倒计时、停放和解包阶段，将得分提升到快速增长层级 f\_(ω+1)；其得分下界为 f\_(ω+1)((3T−13)/7−2)，其中 T = 2↑^37 3。
   原文：[打开原文](https://github.com/jeff87654/busy-beaver/blob/main/BB10/1RB0RA_1LC1LF_1RD0LB_1RA1LE_1LI0LC_0RG1LD_1RH1LG_1LC0RG_0LJ0LI_1RZ0LC.md)

2. [w1700k-sdr 将 Wi-Fi 7 路由器改造成 320 Msps 软件定义无线电接收机](https://reisen-ww.github.io/hot-pages/openhot/items/c10sz334shnoxduwov5azwi0m)
   来源：Hacker News 热榜 · 发布时间：2026-10-12 20:41（北京时间）
   摘要：w1700k-sdr 让 Gemtek W1700K 的 MediaTek MT7996 采集最高 320 Msps 的 14-bit 复数 IQ 数据，并由 Airoha AN7581 SoC 通过 10 GbE 传输到 Linux 主机。
   原文：[打开原文](https://github.com/h0m3us3r/w1700k-sdr)

3. [Winnin 公开 Farol 项目，帮助代码审查者评估合并请求的风险](https://reisen-ww.github.io/hot-pages/openhot/items/lyxy0wo870gwsi4if3vb7nbmf)
   来源：Hacker News 热榜 · 发布时间：2026-10-25 21:28（北京时间）
   摘要：Winnin 在 GitHub 上开源 Farol 项目，这是一个免费的开源 CLI 和 GitHub Action，用于评估合并请求的风险。项目支持多种编程语言和框架，提供详细的配置和使用指南。
   原文：[打开原文](https://github.com/winnin/farol)

4. [Blaze 项目：Rust 项目的增量构建速度提升 92 倍](https://reisen-ww.github.io/hot-pages/openhot/items/n39vl9iq14sqsh1mtz58buik0)
   来源：Hacker News 热榜 · 发布时间：2026-10-27 11:09（北京时间）
   摘要：Blaze 项目在 GitHub 上开源，提供比 Cargo 快 9.1 到 24 倍的 Rust 项目增量构建工具。基准测试显示 Blaze 在 macOS arm64 平台上比 Cargo 快 24 倍，Linux aarch64 平台上快 11 倍。项目支持 macOS 和 Linux，Windows 平台则使用 Cargo。
   原文：[打开原文](https://github.com/indexable-inc/blaze)

5. [jinx 将 231,777 个 nixpkgs 属性转译为可运行的 TypeScript](https://reisen-ww.github.io/hot-pages/openhot/items/kv0e5nkepewrs978gqai337i1)
   来源：Lobsters 热榜 · 发布时间：2026-10-13 18:55（北京时间）
   摘要：作者发布 jinx，将 Nix 文件转译为 TypeScript，并编译了包含 231,777 个属性的完整 nixpkgs 树；在 x86\_64-linux、aarch64-linux 和 aarch64-darwin 上，对比结果显示可评估属性的 drvPath 全部一致。
   原文：[打开原文](https://fzakaria.com/2026/10/12/nixpkgs-for-the-frontend-impaired)

6. [DeepSeek 开源 DeepInfer：面向 DeepSeek 模型的高性能推理框架](https://github.com/deepseek-ai/DeepInfer)
   来源：Hacker News 热榜 · 发布时间：2026-10-20 17:08（北京时间）
   摘要：DeepSeek-AI 在 GitHub 开源 DeepInfer，这是支撑其大规模生产服务的推理框架，首版支持 DeepSeek-V4.1-Flash 的离线推理，采用 Apache-2.0 许可证。
   原文：[打开原文](https://github.com/deepseek-ai/DeepInfer)

7. [某团队开源 PHP 内存管理漏洞利用 PoC](https://reisen-ww.github.io/hot-pages/openhot/items/pk1kwj5473ng2ls8da432zdjk)
   来源：Hacker News 热榜 · 发布时间：2026-10-26 08:15（北京时间）
   摘要：某团队在 GitHub 公开了一个针对 PHP 内存管理漏洞的 PoC，详细描述了攻击流程和技术细节，包括健康检查、堆泄露、代码泄露和最终请求等步骤。
   原文：[打开原文](https://github.com/KillaBoi/StealMyBitcoin-PoC)

8. [TREK 5.0：唯一你需要的自托管旅行应用，规划行程、路线徒步、分摊费用并打印相册](https://reisen-ww.github.io/hot-pages/openhot/items/siokygndrea3fgk9e4civyzyc)
   来源：Reddit r/selfhosted · 发布时间：2026-10-25 19:55（北京时间）
   摘要：TREK 5.0 是一个自托管的旅行规划应用，新增户外路线规划、旅行相册制作等功能，支持实时协作和自托管。它可以在自己的服务器上运行，无需离开本地网络。
   原文：[打开原文](https://www.reddit.com/r/selfhosted/comments/1xf0g6j/trek_50_the_only_travel_app_you_will_ever_need_to/)

9. [Jared Woodruff 开源 One Must Fall 2097 Remastered，支持 Windows、macOS、Linux 及浏览器](https://reisen-ww.github.io/hot-pages/openhot/items/trmv5vncn2gy156zygsnwjfsr)
   来源：Hacker News 热榜 · 发布时间：2026-10-24 21:47（北京时间）
   摘要：Jared Woodruff 在 GitHub 开源 One Must Fall 2097 Remastered 项目，这是对 1994 年经典 DOS 格斗游戏的忠实重实现。
   原文：[打开原文](https://github.com/Jared-woodruff/OMF-2097-Remastered/)

10. [specification-first-agentic-development 插件开源：用规格说明书管理AI编程代理全流程](https://spec-first.dev/)
    来源：Hacker News 热榜 · 发布时间：2026-10-27 23:12（北京时间）
    摘要：某团队在GitHub发布名为 specification-first-agentic-development 的插件，通过规格说明书（spec）定义目标、依赖事实（如Program.cs:40-58）、步骤和完成标准（GitHub/Jira提供工单）。
    原文：[打开原文](https://spec-first.dev/)

## 应用与安全

1. [Wiz Research 披露 PHP 核心引擎严重 RCE 漏洞 PHP2Shell](https://reisen-ww.github.io/hot-pages/openhot/items/ixagh2w9dcv00egpib32h1bwb)
   来源：Hacker News 热榜 · 发布时间：2026-10-21 21:43（北京时间）
   摘要：Wiz Research 发现 PHP 核心引擎存在多个内存安全漏洞（CVE-2026-109618 和 CVE-2026-109619），最高 CVSS 评分 9.2，可导致未经身份验证的远程代码执行（RCE）或内存泄露。
   原文：[打开原文](https://www.wiz.io/blog/php2shell-php-rce)

2. [Android紧急呼叫功能遭远程漏洞攻击，单条恶意短信致设备永久性瘫痪](https://reisen-ww.github.io/hot-pages/openhot/items/umnjdqt1yltkyf3oae634o1g7)
   来源：Lobsters 热榜 · 发布时间：2026-10-29 15:22（北京时间）
   摘要：Android紧急呼叫功能遭远程漏洞攻击，单条恶意短信致设备永久性瘫痪。漏洞源于 unchecked cast导致数组越界，攻击者可零点击发送恶意WAP Push短信，造成通话中断、SQLite数据库损坏及设备变砖。澳大利亚运营商法规要求对无法接通紧急服务的设备进行封锁，该漏洞可能被滥用导致用户设备被运营商切断服务。
   原文：[打开原文](https://smsofdeath.com/)

3. [XBOW 详解六天完成的 Chrome 全链漏洞利用](https://reisen-ww.github.io/hot-pages/openhot/items/acij7sb8ybzp16rcq7bjqrtjo)
   来源：Hacker News 热榜 · 发布时间：2026-10-14 02:37（北京时间）
   摘要：XBOW披露了一条由 V8 Maglev 编译器、动画 WebP 解码器和 Crashpad 内存安全漏洞串联而成的 Chrome 全链利用，可从普通标签页中的 JavaScript 执行发展为沙箱外代码执行。
   原文：[打开原文](https://xbow.com/labs/research/zero-to-calc-in-six-days-inside-xbow-chrome-full-chain)

4. [Calif 披露 PHP 多条 RCE 漏洞路径，覆盖 WordPress、Drupal 等应用](https://reisen-ww.github.io/hot-pages/openhot/items/eu7ysf5qwjm7x8wewyg56onli)
   来源：Lobsters 热榜 · 发布时间：2026-10-21 22:37（北京时间）
   摘要：Calif Research 披露 PHP 存在多条基于 OOM/memory\_limit 致命错误的远程代码执行（RCE）漏洞，最早可追溯到 PHP 5.4.0。
   原文：[打开原文](https://calif.io/php2shell.x)

5. [Brotli 解码器漏洞 CVE-2026-111497 从 Node2Shell 扩散至 Python 及多语言 HTTP 组件](https://reisen-ww.github.io/hot-pages/openhot/items/i2injnku7wb6tbzvhe1870dpz)
   来源：Hacker News 热榜 · 发布时间：2026-10-24 16:06（北京时间）
   摘要：Google Brotli 解码器漏洞 CVE-2026-111497（CVSS 4.0 评分 9.2）影响 1.0.3 至 1.2.0 版本，10 月 21 日 Node.js 披露为 node2shell，随后 Python 及更多语言与 HTTP 服务应用被确认受影响。
   原文：[打开原文](https://www.aikido.dev/blog/python-packages-vulnerable-node2shell-brotli-cve-2026-111497)

6. [curl 8.23.0 修复 HTTP/2 上传 Use-After-Free 漏洞 CVE-2026-92392](https://reisen-ww.github.io/hot-pages/openhot/items/ocvwr9aaajlxx8jljlyg8ed9y)
   来源：Lobsters 热榜 · 发布时间：2026-10-14 17:44（北京时间）
   摘要：curl 8.23.0 修复了 HTTP/2 上传中的 Use-After-Free 漏洞 CVE-2026-92392，该问题在特定条件下可能被恶意服务器利用为远程代码执行。
   原文：[打开原文](https://daniel.haxx.se/blog/2026/10/14/a-uaf-turned-rce/)

7. [Claroty Team82 揭露 Danfoss AK-SM 800A 制冷控制器漏洞，Danfoss 发布 R4.3.1 固件修复](https://reisen-ww.github.io/hot-pages/openhot/items/c72iy2454qg3nq7z4ytk6sa0p)
   来源：Lobsters 热榜 · 发布时间：2026-10-13 15:09（北京时间）
   摘要：Claroty Team82 发现 Danfoss AK-SM 800A 制冷控制器存在多项漏洞，并通过协调披露促使 Danfoss 发布修复固件 R4.3.1。
   原文：[打开原文](https://claroty.com/team82/research/freeze-the-controller-defrost-the-food-uncovering-vulnerabilities-in-danfoss-refrigeration-controllers)

8. [eMudhra 忽略 Mozilla 调查截止期限，把拖延归因于社交媒体压力](https://reisen-ww.github.io/hot-pages/openhot/items/jmhmmulhgj2dc6u9z6z82g1n4)
   来源：Hacker News 热榜 · 发布时间：2026-10-23 22:52（北京时间）
   摘要：Mozilla 在 Bugzilla bug 2083449 记录 eMudhra 8 个中间证书私钥泄露事件：报告于 10 月 17 日 18:05 UTC 发出。
   原文：[打开原文](https://bugzilla.mozilla.org/show_bug.cgi?id=2083449)

9. [苹果 macOS 仍信任被 eMudhra 证书攻击的 git 工具](https://reisen-ww.github.io/hot-pages/openhot/items/vg4j326l1rd2ef4plflujxdnc)
   来源：Lobsters 热榜 · 发布时间：2026-10-28 19:03（北京时间）
   摘要：苹果 macOS 仍信任被 eMudhra 证书攻击的 git 工具，导致用户代码仓库可能被中间人篡改。开发者可通过手动移除证书根或运行检测命令避免风险。苹果已修复 Safari 等应用但未更新开发者工具，建议持续检查修复状态。
   原文：[打开原文](https://emudhra.we-have-a-problem.com/apple.html)

10. [PyPI 上被篡改的 LiteLLM 1.107.0 携带凭据窃取器与远程执行后门](https://reisen-ww.github.io/hot-pages/openhot/items/kh9q2zhkk9zuoo0dnmlomfs71)
    来源：Hacker News 热榜 · 发布时间：2026-10-21 22:00（北京时间）
    摘要：SafeDep 披露 PyPI 上的 litellm 1.107.0 携带凭据窃取器和远程代码执行后门，PyPI 已下架该版本，1.106.2、1.107.0rc1、1.107.0rc2 及配套包 litellm-proxy-extras==0.4.110、litellm-enterprise==1.78 均无问题。
    原文：[打开原文](https://safedep.io/litellm-pypi-compromise-credential-stealer-backdoor/)

11. [GitLab 修复 CI/CD 正则表达式编译器最高严重性远程代码执行漏洞](https://reisen-ww.github.io/hot-pages/openhot/items/qplvo2kh51thqxx2lur9gblh9)
    来源：Lobsters 热榜 · 发布时间：2026-10-14 23:55（北京时间）
    摘要：GitLab 警告用户立即修复 CI/CD 正则表达式编译器中的最高严重性漏洞 CVE-2026-97229，未经身份验证的远程攻击者可通过特制正则表达式在 GitLab 服务器上执行任意代码。
    原文：[打开原文](https://www.bleepingcomputer.com/news/security/gitlab-warns-of-max-severity-rce-flaw-in-regex-compiler-engine/)

12. [GitLab 发布 19.5.1 等关键补丁版本，修复 CVSS 10.0 的正则编译器整数溢出漏洞](https://docs.gitlab.com/releases/patches/patch-release-gitlab-19-5-1-released/)
    来源：Hacker News 热榜 · 发布时间：2026-10-22 03:01（北京时间）
    摘要：GitLab 于 10 月 21 日发布 19.5.1、19.4.3、19.3.6、19.2.9、19.1.9、19.0.10、18.11.13 共 7 个补丁版本，包含重要缺陷与安全修复，建议所有自托管安装尽快升级，GitLab.com 已运行修复后版本。
    原文：[打开原文](https://docs.gitlab.com/releases/patches/patch-release-gitlab-19-5-1-released/)

13. [Ledger 钱包供应链出现硬件后门，约 $102 million 加密货币被盗](https://reisen-ww.github.io/hot-pages/openhot/items/su6z32tcm7ksf2sv6wi07250l)
    来源：Hacker News 热榜 · 发布时间：2026-10-14 17:37（北京时间）
    摘要：Ledger 多款硬件钱包被发现植入后门，攻击者可窃取设备生成的恢复助记词，约 315 个与 CryptoBilis 设备相关的账户损失了当前价值约 $102 million 的加密货币。
    原文：[打开原文](https://www.zetter-zeroday.com/who-is-planting-backdoors-in-ledger-crypto-wallets/)

14. [多款PDF编辑器存在AES-256密钥生成漏洞，可无密码解密文档](https://reisen-ww.github.io/hot-pages/openhot/items/rtnv85sdaekar5byu79e89sfc)
    来源：Hacker News 热榜 · 发布时间：2026-10-29 04:51（北京时间）
    摘要：某团队发现MuPDF、Foxit等PDF编辑器在生成AES-256文件密钥时使用不安全的随机数源（如drand48 LCG、时间戳哈希等），导致密钥空间被压缩至512种可能。攻击者可通过枚举时间戳（每512秒重复）或内存信息（如Foxit）猜测密钥，实现无密码解密。其中MuPDF已修复至1.28.5版本，但Foxit等仍存在漏洞。
    原文：[打开原文](https://v12.sh/blog/the-case-of-the-9bit-aes-key)

15. [eMudhra 八个中级 CA 私钥泄露，主流根程序已封禁相关证书](https://reisen-ww.github.io/hot-pages/openhot/items/vl523h4hv0ljftz0s421l660m)
    来源：Hacker News 热榜 · 发布时间：2026-10-20 21:58（北京时间）
    摘要：eMudhra 的 8 个中级 CA 证书私钥被泄露，这些证书链向 Mozilla、Microsoft、Apple 和 Chrome 根程序所信任的根。
    原文：[打开原文](https://emudhra.we-have-a-problem.com/)

16. [Node.js 发布 26.12.1、24.22.1、22.23.4 安全版本，修复多项高危漏洞](https://nodejs.org/en/blog/vulnerability/october-2026-security-releases)
    来源：Lobsters 热榜 · 发布时间：2026-10-21 23:53（北京时间）
    摘要：Node.js 项目在 2026 年 10 月 21 日发布 26.x、24.x、22.x 三条发布线的安全版本 v26.12.1、v24.22.1、v22.23.4，最高严重级别为 HIGH。
    原文：[打开原文](https://nodejs.org/en/blog/vulnerability/october-2026-security-releases)

## 基础设施

1. [Ubuntu 26.10（Stonking Stingray）正式发布](https://lists.ubuntu.com/archives/ubuntu-announce/2026-October/000330.html)
   来源：Hacker News 热榜 · 发布时间：2026-10-15 19:59（北京时间）
   摘要：Ubuntu 26.10（代号 Stonking Stingray）由 Canonical 正式发布，包含 Rust 版 coreutils 全面采用、后量子就绪的包签名、Linux kernel 7.3 以及 GNOME 51 等更新，提供 9 个月维护期。
   原文：[打开原文](https://lists.ubuntu.com/archives/ubuntu-announce/2026-October/000330.html)

## 模型与数据

1. [Mage-VL-Cowork 模型发布：4B 规模自主桌面代理技术方案](https://reisen-ww.github.io/hot-pages/openhot/items/p4o4784dnzhkpxdwatfo0lthv)
   来源：Hugging Face 新模型 · Microsoft · 发布时间：2026-10-30 20:13（北京时间）
   摘要：Mage-VL-Cowork 是一个4B规模的小模型，在自主桌面代理任务中达到66.0%的性能分数，并采用混合训练方法提升效率。该模型支持bash和computer\_use操作，需在隔离容器中运行，遵循Apache-2.0许可证。GitHub仓库提供完整评估框架和Docker部署指南。
   原文：[打开原文](https://huggingface.co/microsoft/Mage-VL-Cowork)

2. [MoLE 协议草案发布，定义背书和凭证协议](https://reisen-ww.github.io/hot-pages/openhot/items/o05sgmq13eqtca80vsbkbg9vx)
   来源：Lobsters 热榜 · 发布时间：2026-10-26 18:39（北京时间）
   摘要：MoLE 协议草案定义了背书和凭证协议，支持匿名状态机和隐私令牌等场景。文档介绍了两种背书协议和三种凭证协议，以及如何在 Moderators 和 Anchors 之间交换凭证。
   原文：[打开原文](https://datatracker.ietf.org/doc/draft-jms-mole-protocols/)

3. [Destined AI 开源 Hurston-1，一种针对南方美国和非洲英语的窄带 TTS](https://reisen-ww.github.io/hot-pages/openhot/items/d4au2ak3u35s858f64ih82n03)
   来源：Hacker News 热榜 · 发布时间：2026-10-25 09:30（北京时间）
   摘要：Destined AI 在 Hugging Face 上开源 Hurston-1，一种针对南方美国和非洲英语的窄带 TTS，支持多种英语口音，适用于电话场景。项目提供了安装方法、使用示例和性能测试数据。
   原文：[打开原文](https://huggingface.co/destined/hurston-1)
