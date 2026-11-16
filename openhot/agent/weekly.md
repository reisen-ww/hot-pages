# 开源热点 周报 · 2026-W46

- 期号：第 5 期
- 发布：2026-11-17 01:00（北京时间）
- 本期页：[阅读本期](https://reisen-ww.github.io/hot-pages/openhot/weekly/2026-W46)

## 导语

基于线性规划的模型权重优化：Astra循环问题修正方法对比分析

本周开源三主线：工具端Rust向量数据库单机处理千万级数据，PipesHub获评测第一；应用安全发布GraphQL HTTP规范及Firefox指纹防护（识别率降46%）；基础设施PostgreSQL修复52个高危漏洞，语言生态Rust 1.100.0引入DropGuard API，Go 1.27优化性能与安全。

## 工具与项目

**栏目导读**：多款Rust生态工具发布，涵盖向量数据库、跨平台客户端及个人助手模块化部署。

1. [某团队开源 Rust 写的向量数据库，单机可处理千万级向量](https://reisen-ww.github.io/hot-pages/openhot/items/b6pq3oxqw947aorxfxkjgyju6)
   来源：Hacker News 热榜 · 发布时间：2026-11-12 23:23（北京时间）
   摘要：某团队在 GitHub 公开该数据库仓库，给出查询延迟、内存占用与依赖要求，并说明当前支持的平台与许可证。
   原文：[打开原文](https://github.com/hyperionaidev/smolmaxxing/)

2. [Anchor Notes v0.18.0发布：移动端应用上线及全平台设计重做](https://reisen-ww.github.io/hot-pages/openhot/items/fv6owqx9m5zdut7w2h5gp2zrg)
   来源：Reddit r/selfhosted · 发布时间：2026-11-10 13:45（北京时间）
   摘要：Anchor Notes v0.18.0发布，Android应用上线Google Play，iOS测试版开放，全平台设计重做并新增分享功能。用户提交的漏洞修复贡献显著，GitHub星数两周内增长1400+。
   原文：[打开原文](https://www.reddit.com/r/selfhosted/comments/1xsf0kh/anchor_notes_a_selfhosted_google_keep_alternative/)

3. [WebKit 修复 Promise 构造函数 Symbol.species 获取异常导致的执行阻塞问题](https://reisen-ww.github.io/hot-pages/openhot/items/lqxw4wq37xyv27ju4yfd0q8v2)
   来源：Lobsters 热榜 · 发布时间：2026-11-14 00:48（北京时间）
   摘要：WebKit 修复 Promise 构造函数 Symbol.species 获取异常导致的执行阻塞问题。对比 Safari/Bun引擎在 Promise 处理中的行为差异，分析 JavaScript 规范中 resolve 函数的实现逻辑及修复方案。
   原文：[打开原文](https://alistair.sh/thenables)

4. [MattiaPARRINELLO 开源自托管个人助手，支持多账户加密与模块化扩展](https://reisen-ww.github.io/hot-pages/openhot/items/dc8y2yl0gkf7eupoc6jjenu6z)
   来源：Reddit r/selfhosted · 发布时间：2026-11-12 01:54（北京时间）
   摘要：MattiaPARRINELLO 在 GitHub 开源自托管个人助手项目，支持多用户独立加密存储与模块化部署。
   原文：[打开原文](https://www.reddit.com/r/selfhosted/comments/1xtomhw/im_making_my_selfhosted_personal_assistant/)

5. [PipesHub开源自托管向量数据库在EnterpriseRAG-Bench评测中排名第一](https://reisen-ww.github.io/hot-pages/openhot/items/kiaqgykiiafhg0464j08jngb2)
   来源：Reddit r/selfhosted · 发布时间：2026-11-11 21:45（北京时间）
   摘要：PipesHub开源自托管向量数据库在EnterpriseRAG-Bench评测中排名第一，综合得分93.24，正确率95%。
   原文：[打开原文](https://www.reddit.com/r/selfhosted/comments/1xti468/self_hosted_glean_alternative_just_ranked_1_on/)

6. [某团队开源Rust写的轻量级WhatsApp客户端，单机内存占用仅200MB](https://reisen-ww.github.io/hot-pages/openhot/items/tvtvems9d77vil064fo1hvz5v)
   来源：Hacker News 热榜 · 发布时间：2026-11-08 10:02（北京时间）
   摘要：某团队在GitHub开源Rust写的WhatsApp客户端ZapFast，Linux单机版内存占用仅200MB（对比Web版1.13GB），支持多语言界面与无浏览器引擎设计。安装指南包含macOS/Brew、Arch Linux/yay、Windows等平台的具体步骤，并强调本地加密存储与离线使用特性。
   原文：[打开原文](https://github.com/crmne/zapfast)

7. [uv 0.13.8 发布：更新 Python 依赖与性能优化](https://reisen-ww.github.io/hot-pages/openhot/items/wm36tw4s87fln941pe7amezmq)
   来源：uv 版本发布 · 发布时间：2026-11-13 01:03（北京时间） · 一手
   摘要：uv 0.13.8 发布，更新 Python 依赖到 3.16.0a2 并优化性能（避免重复环境构建）。修复 macOS 上的 CPU 检测问题，新增对 Google TPUs 和更多 Linux 架构的支持。安装指南包含 shell 和 PowerShell 脚本，提供各平台预构建二进制文件及验证方法。
   原文：[打开原文](https://github.com/astral-sh/uv/releases/tag/0.13.8)

## 应用与安全

**栏目导读**：GraphQL HTTP规范解决互操作难题，Mozilla Firefox指纹防护识别率降46%，DeepMind验证框架效率提升90%。

1. [GraphQL 基金会发布 HTTP 规范，解决互操作与可观测性难题](https://reisen-ww.github.io/hot-pages/openhot/items/mm71surul71wuo6w5qblycb5l)
   来源：Lobsters 热榜 · 发布时间：2026-11-13 09:16（北京时间）
   摘要：GraphQL 基金会发布 HTTP 规范，明确200 Not OK等状态码使用规则，新增GraphQL over HTTP媒体类型，解决代理缓存响应混淆问题。规范还规划了支持QUERY HTTP动词和持久化文档标准化，现有主流框架已适配新规。
   原文：[打开原文](https://graphql.org/blog/2026-11-12-announcing-the-graphql-over-http-spec/)

2. [Google DeepMind 开源 Rust 写的 Signal 协议形式验证框架](https://reisen-ww.github.io/hot-pages/openhot/items/tdhmmbc4vi6r88pje71mfdpru)
   来源：Hacker News 热榜 · 发布时间：2026-11-10 20:11（北京时间）
   摘要：Google DeepMind 开源 Rust 写的 Signal 协议形式验证框架，AI 代理验证代码效率提升 90%。研究团队使用多LLM框架，人类专家与AI协作制定数学规范，AI生成六百万行 Lean 代码进行验证，仅1%代码需人工复核，四周完成传统需数年的工作，工具已开源。
   原文：[打开原文](https://deepmind.google/blog/introducing-alphaproof-code/)

3. [Perses 发布 v0.55.0 版本，支持多种数据源与 DevOps 场景](https://reisen-ww.github.io/hot-pages/openhot/items/p24rex7qppzx9nuhskrbg12n8)
   来源：Lobsters 热榜 · 发布时间：2026-11-14 23:28（北京时间）
   摘要：Perses v0.55.0 新增对 Prometheus、Tempo、Loki 和 Pyroscope 的支持，提供全面的静态验证和插件架构，适合 DevOps 场景。
   原文：[打开原文](https://perses.dev/)

4. [Home Assistant 密码变更无效且令牌密钥明文存储漏洞披露](https://reisen-ww.github.io/hot-pages/openhot/items/p18sp3k2wv16xh13ijb6kvel1)
   来源：Hacker News 热榜 · 发布时间：2026-11-14 06:30（北京时间）
   摘要：Home Assistant 存在密码变更无效且令牌密钥明文存储的安全漏洞。测试版本 home-assistant/core 2026.11.0 发现：1. 用户令牌秘密和JWT签名密钥以明文形式存储在 config/.storage/auth 文件中；2. 长期有效令牌未设置过期时间；3. 密码变更未撤销相关令牌。建议用户立即更新配置并检查备份文件。
   原文：[打开原文](https://seclists.org/fulldisclosure/2026/Nov/34)

5. [Mozilla Firefox 143发布浏览器指纹防护，识别率降46%](https://reisen-ww.github.io/hot-pages/openhot/items/rcb4nwugi5czhd7h4o71jgej0)
   来源：Lobsters 热榜 · 发布时间：2026-11-11 03:14（北京时间）
   摘要：Mozilla基于2500万Firefox用户数据，发布浏览器指纹防护方案，将唯一识别用户比例从75%降至46%，同时保持网页兼容性。研究显示浏览器指纹的独特性主要由屏幕分辨率、字体列表等8-9项核心指标决定，防护方案通过标准化和随机化技术实现。用户可通过交互测试验证自身浏览器指纹风险，数据集已开源但删除原始记录以防止追踪。
   原文：[打开原文](https://fingerprinting.study/)

## 基础设施

**栏目导读**：PostgreSQL修复52个高危漏洞，FreeBSD实现虚拟机活迁移技术突破。

1. [PostgreSQL 发布安全更新修复52个漏洞](https://reisen-ww.github.io/hot-pages/openhot/items/h98a2atur2d18rasc7gvftj2v)
   来源：Hacker News 热榜 · 发布时间：2026-11-12 22:25（北京时间）
   摘要：PostgreSQL Global Development Group于2026-11-12发布安全更新，修复18.7、17.12等支持版本中的52个安全漏洞（含CVE-2026-6460至CVE-2026-120154），涉及执行任意代码、SQL注入、内存泄露等高危问题。
   原文：[打开原文](https://www.postgresql.org/about/news/postgresql-187-1712-1616-1520-1425-and-19-rc-2-released-3442/)

2. [EventSourcingDB 1.3.0发布：新API与性能提升](https://reisen-ww.github.io/hot-pages/openhot/items/rdc3tphgrg6sfckulougqhqgd)
   来源：Hacker News 热榜 · 发布时间：2026-11-11 21:19（北京时间）
   摘要：EventSourcingDB 1.3.0正式发布，引入与请求响应直接绑定的v2 API，并优化了写入、查询和恢复速度，同时提供详细的升级指南以降低迁移风险。
   原文：[打开原文](https://www.eventfoundation.io/resources/blog/eventsourcingdb-1-3-0-is-available)

3. [FreeBSD bhyve虚拟机活迁移支持首次完整实现](https://reisen-ww.github.io/hot-pages/openhot/items/hox5oh87bvu08t1u0frstto7z)
   来源：Hacker News 热榜 · 发布时间：2026-11-14 03:58（北京时间）
   摘要：作者在GitHub发布基于FreeBSD 15.1的bhyve虚拟机活迁移实现，实测单机迁移停机时间138-171ms，支持多vCPU协议和内存一致性检查。当前状态为WIP RFC，已规划存储网络交接和自动化测试方案，后续将扩展设备支持和性能优化。
   原文：[打开原文](https://gyptazy.com/blog/freebsd-bhyve-live-migration-support-rfc/)

## 语言与底层

**栏目导读**：Rust 1.100.0稳定资源管理，Go 1.27优化性能与安全。

1. [微软发布 .NET 11，包含C# 15、ASP.NET Core 3.2及AI工具集成](https://reisen-ww.github.io/hot-pages/openhot/items/cxxf6lw8hu3t457s0hr7ukzgy)
   来源：Hacker News 热榜 · 发布时间：2026-11-11 00:01（北京时间）
   摘要：微软在GitHub宣布.NET 11正式发布，包含C# 15的联合类型和封闭继承体系、ASP.NET Core 3.2的异步验证与OpenAPI 3.2支持、.NET MAUI默认使用CoreCLR运行时，以及集成MCP服务器模板和Microsoft Agent Framework的AI开发工具。
   原文：[打开原文](https://devblogs.microsoft.com/dotnet/announcing-dotnet-11/)

2. [Rust 1.100.0正式发布：稳定化Never类型与DropGuard API](https://reisen-ww.github.io/hot-pages/openhot/items/wmgrjsgwfzq7rt75uxv59z81p)
   来源：Lobsters 热榜 · 发布时间：2026-11-13 02:43（北京时间）
   摘要：Rust团队发布1.100.0版本，主要包含Never类型稳定化、DropGuard API引入及Cargo构建优化。新增的DropGuard类型简化了资源管理，Never类型支持更灵活的类型标注。Cargo新增依赖冷却机制，避免误用新版本包，并优化构建缓存减少重复编译。
   原文：[打开原文](https://blog.rust-lang.org/2026/11/12/Rust-1.100.0/)

3. [Go 1.27发布：性能优化与安全增强推动17周年里程碑](https://reisen-ww.github.io/hot-pages/openhot/items/nh48ctzocyhsm0k4ezwuen4t6)
   来源：Lobsters 热榜 · 发布时间：2026-11-11 06:47（北京时间）
   摘要：Go 1.27发布，包含generics优化、JSON/v2升级（10倍速解析）、内存分配改进（小对象分配提速30%）及安全增强（应对eMudhra证书事件）。新goroutine漏检器与SIMD包提升硬件利用率，工具链集成pkg.go.dev API与gopls交互式重构功能，支持AI辅助开发。
   原文：[打开原文](https://go.dev/blog/17years)

## 模型与数据

1. [基于线性规划的模型权重优化：Astra循环问题修正方法对比分析](https://reisen-ww.github.io/hot-pages/openhot/items/mdvy36e21p5oej46adfpmpbgi)
   来源：Hacker News 热榜 · 发布时间：2026-11-11 20:30（北京时间）
   摘要：MIT CSAIL的Astra模型通过线性规划优化权重，在MATH-500测试中准确率从7.9%提升至48.1%。作者对比了两种方法：Astra的原始方法修改130,188个权重参数，而线性规划版本仅修改16,291个（减少87%）。
   原文：[打开原文](https://nathan.rs/posts/weight-space-lp/)

2. [Unity土耳其字母导致多款游戏崩溃问题已修复](https://reisen-ww.github.io/hot-pages/openhot/items/j0012r36201grgyebfdmh122m)
   来源：Reddit r/programming · 发布时间：2026-11-12 16:15（北京时间）
   摘要：Unity因土耳其字母‘İ/i’和‘I/ı’的 casing 规则差异导致多款游戏（CRYSTAR、Speedrunners）在土耳其语言设置下无法启动。开发者通过将 C# 的 ToUpper 方法替换为 ToUpperInvariant 或使用 StringComparison.OrdinalIgnoreCase 解决问题，建议所有软件公司采用‘土耳其测试’确保兼容性。
   原文：[打开原文](https://www.reddit.com/r/programming/comments/1xu79k2/this_turkish_letter_keeps_breaking_the_worlds/)
