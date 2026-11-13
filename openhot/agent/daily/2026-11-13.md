# 开源日报 · 2026-11-13

- 期号：第 28 期
- 发布：2026-11-13 21:41（北京时间）
- 本期页：[阅读本期](https://reisen-ww.github.io/hot-pages/openhot/daily/2026-11-13)

## 头条

PostgreSQL 发布安全更新修复52个漏洞

## 工具与项目

1. [某团队开源 Rust 写的向量数据库，单机可处理千万级向量](https://reisen-ww.github.io/hot-pages/openhot/items/b6pq3oxqw947aorxfxkjgyju6)
   来源：Hacker News 热榜 · 发布时间：2026-11-12 23:23（北京时间）
   摘要：某团队在 GitHub 公开该数据库仓库，给出查询延迟、内存占用与依赖要求，并说明当前支持的平台与许可证。
   原文：[打开原文](https://github.com/hyperionaidev/smolmaxxing/)

2. [uv 0.13.8 发布：更新 Python 依赖与性能优化](https://reisen-ww.github.io/hot-pages/openhot/items/wm36tw4s87fln941pe7amezmq)
   来源：uv 版本发布 · 发布时间：2026-11-13 01:03（北京时间） · 一手
   摘要：uv 0.13.8 发布，更新 Python 依赖到 3.16.0a2 并优化性能（避免重复环境构建）。修复 macOS 上的 CPU 检测问题，新增对 Google TPUs 和更多 Linux 架构的支持。安装指南包含 shell 和 PowerShell 脚本，提供各平台预构建二进制文件及验证方法。
   原文：[打开原文](https://github.com/astral-sh/uv/releases/tag/0.13.8)

3. [Securo维护者公布8个月成果：新增贷款管理、分类 splits、PWA安装等功能](https://reisen-ww.github.io/hot-pages/openhot/items/kd653ceycr2m1bm0xx7koj5rm)
   来源：Reddit r/selfhosted · 发布时间：2026-11-13 04:17（北京时间）
   摘要：Securo维护者TassioNoronha在Reddit宣布，项目已获4275星、37.9万次下载，并新增贷款管理、分类 splits、预算 rollover、PWA安装及内置MCP服务器等功能，目前由129名贡献者维护，每周发布2-3次更新。
   原文：[打开原文](https://www.reddit.com/r/selfhosted/comments/1xunhqd/securo_maintainer_here_8_months_of_work_and_the/)

4. [PocketBase 社区版 v0.0.1 开源发布](https://reisen-ww.github.io/hot-pages/openhot/items/atwhho99o0a2mgnhupzle7ot1)
   来源：Reddit r/selfhosted · 发布时间：2026-11-12 07:58（北京时间）
   摘要：PocketBase 社区版 v0.0.1 开源，提供更开放的贡献环境，包含核心扩展如多页应用、PITR 数据库恢复和 MCP 多租户支持，以及可选的容器化、集群管理等功能。仓库地址：https://github.com/pockethost/pocketbase
   原文：[打开原文](https://www.reddit.com/r/selfhosted/comments/1xtxrhi/pocketbase_community_edition_v001/)

## 应用与安全

1. [GCC字符串分块优化影响路径检测：包管理器如何应对](https://reisen-ww.github.io/hot-pages/openhot/items/rjk2rgntfr00banarhoa82bft)
   来源：Lobsters 热榜 · 发布时间：2026-11-12 22:49（北京时间）
   摘要：GCC在编译时将长字符串拆分为16字节块以优化性能，导致包管理器的路径检测机制失效。作者对比了GCC与Clang的优化差异，指出Debian通过记录构建信息增强移植性，并建议开发者通过-mstore-max参数控制优化强度。
   原文：[打开原文](https://stoppels.ch/2026/11/12/paths-in-pieces.html)

## 基础设施

1. [PostgreSQL 发布安全更新修复52个漏洞](https://reisen-ww.github.io/hot-pages/openhot/items/h98a2atur2d18rasc7gvftj2v)
   来源：Hacker News 热榜 · 发布时间：2026-11-12 22:25（北京时间）
   摘要：PostgreSQL Global Development Group于2026-11-12发布安全更新，修复18.7、17.12等支持版本中的52个安全漏洞（含CVE-2026-6460至CVE-2026-120154），涉及执行任意代码、SQL注入、内存泄露等高危问题。
   原文：[打开原文](https://www.postgresql.org/about/news/postgresql-187-1712-1616-1520-1425-and-19-rc-2-released-3442/)

## 语言与底层

1. [Rust 1.100.0正式发布：稳定化Never类型与DropGuard API](https://reisen-ww.github.io/hot-pages/openhot/items/wmgrjsgwfzq7rt75uxv59z81p)
   来源：Lobsters 热榜 · 发布时间：2026-11-13 02:43（北京时间）
   摘要：Rust团队发布1.100.0版本，主要包含Never类型稳定化、DropGuard API引入及Cargo构建优化。新增的DropGuard类型简化了资源管理，Never类型支持更灵活的类型标注。Cargo新增依赖冷却机制，避免误用新版本包，并优化构建缓存减少重复编译。
   原文：[打开原文](https://blog.rust-lang.org/2026/11/12/Rust-1.100.0/)

## 模型与数据

1. [Unity土耳其字母导致多款游戏崩溃问题已修复](https://reisen-ww.github.io/hot-pages/openhot/items/j0012r36201grgyebfdmh122m)
   来源：Reddit r/programming · 发布时间：2026-11-12 16:15（北京时间）
   摘要：Unity因土耳其字母‘İ/i’和‘I/ı’的 casing 规则差异导致多款游戏（CRYSTAR、Speedrunners）在土耳其语言设置下无法启动。开发者通过将 C# 的 ToUpper 方法替换为 ToUpperInvariant 或使用 StringComparison.OrdinalIgnoreCase 解决问题，建议所有软件公司采用‘土耳其测试’确保兼容性。
   原文：[打开原文](https://www.reddit.com/r/programming/comments/1xu79k2/this_turkish_letter_keeps_breaking_the_worlds/)

## 快讯

- [Easel开源团队自托管替代AWS Lambda Web Functions：闲置计费与性能对比](https://reisen-ww.github.io/hot-pages/openhot/items/iwkbyd4ijkknqn05r1d6x117n)
  来源：Hacker News 热榜 · 发布时间：2026-11-13 00:59（北京时间）
  摘要：Easel开源团队测试发现AWS Lambda Web Functions在最后请求后仍计费闲置内存约7分钟，并自托管基础设施实现1.5-3倍性能提升。具体对比包括：JSON API请求响应时间快2.9倍，流媒体首包时间快2倍，CPU密集型API快1.5倍，冷启动速度快3.5倍。
  原文：[打开原文](https://www.easel.sh/blog/lambda-web-functions-idle-memory)

- [Darling开源项目发布Q4更新：引入AI辅助开发策略及ARM64架构支持](https://reisen-ww.github.io/hot-pages/openhot/items/it6ny6x8i4a7e7p2sho2ohilu)
  来源：Hacker News 热榜 · 发布时间：2026-11-12 12:32（北京时间）
  摘要：Darling项目维护者宣布Q4更新，包含AI辅助开发政策（要求提交者解释代码并禁止使用苹果受限源码）和ARM64架构初始支持。通过VibeDarling分支的持续开发，ARM64支持已具备可合并基础。未来计划整合各分支代码并增强AppKit支持，目标实现i386/x86-64/ARM64三架构协同。
  原文：[打开原文](https://blog.darlinghq.org/2026/11/08/development-update-q4-2026/)

- [ExcalidrawZ：macOS/iOS原生绘图工具，首次支持本地文件管理与AI协作](https://reisen-ww.github.io/hot-pages/openhot/items/pz7jy3srdqvtkiwsdqpr142ae)
  来源：Hacker News 热榜 · 发布时间：2026-11-12 23:25（北京时间）
  摘要：团队开源ExcalidrawZ，实现macOS/iOS原生绘图工具，支持本地文件管理与iCloud同步，并集成AI辅助功能。提供开发配置指南，包含SwiftUI集成、MCP服务配置及加密文件保护方案。支持导出.png/.svg/PDF格式，兼容Excalidraw标准文件。
  原文：[打开原文](https://github.com/chocoford/ExcalidrawZ)

- [某团队开源解决四块GPU内存分配冲突的Linux PCIe桥接方案](https://reisen-ww.github.io/hot-pages/openhot/items/e4t7m0fsus2ovhvk7hqnn54oy)
  来源：Hacker News 热榜 · 发布时间：2026-11-12 23:14（北京时间）
  摘要：某团队在GitHub开源了调整Linux PCIe桥接窗口的模块，测试了内核补丁修复效果并解释了资源分配问题原因。该方案通过initramfs在驱动加载前调整BAR对齐，使四块R9700显卡获得32GB BAR，同时保持两块RTX3090的512MB分配。
  原文：[打开原文](https://doug.sh/posts/gpu-bars-behind-a-pcie-switch/)

- [Rust 1.100.0 发布：标准库与构建系统多项重大更新](https://reisen-ww.github.io/hot-pages/openhot/items/o9tu0du26uvo9p3rnne4ilgap)
  来源：Hacker News 热榜 · 发布时间：2026-11-13 02:24（北京时间）
  摘要：Rust 1.100.0 版本发布，包含标准库内存分配器改进、Cargo构建缓存布局变更及ARMv7-A目标修复，开发者需关注兼容性调整。更新涉及安全修复、依赖管理优化及多平台支持调整，完整变更日志见 GitHub 仓库。
  原文：[打开原文](https://github.com/rust-lang/rust/releases/tag/1.100.0)

- [将CPython适配到yk框架并进行性能优化](https://reisen-ww.github.io/hot-pages/openhot/items/qjrumt439kgpxront066oopkk)
  来源：Lobsters 热榜 · 发布时间：2026-11-12 20:29（北京时间）
  摘要：某团队将yk JIT编译器应用于CPython，在多个基准测试中实现性能提升，但指出当前版本尚未完善，未来需进一步优化。
  原文：[打开原文](https://tratt.net/laurie/blog/2026/adapting_cpython_for_yk.html)

- [Mehmet Ince 公开 PostgreSQL 类型混淆漏洞（CVE-2026-6460）导致远程代码执行](https://reisen-ww.github.io/hot-pages/openhot/items/gp9skzfvqha91lfw8nhkbc8sg)
  来源：Hacker News 热榜 · 发布时间：2026-11-13 02:22（北京时间）
  摘要：Mehmet Ince 在博客中披露了 PostgreSQL 的类型混淆漏洞（CVE-2026-6460），利用该漏洞可远程代码执行。该漏洞源于复合类型属性修改后未更新预编译查询中的值，导致执行时类型解析错误。修复包括复合类型版本控制、匿名记录描述符等21个相关CVE的修复，并协调了Databricks、Google Cloud等供应商的紧急补丁。
  原文：[打开原文](https://mehmetince.net/part-3-6-how-i-ended-up-turning-a-22-year-old-postgresql-type-confusion-primitive-into-rce-cve-2026-6460/)
