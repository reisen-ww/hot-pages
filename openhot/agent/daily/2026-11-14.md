# 开源日报 · 2026-11-14

- 期号：第 29 期
- 发布：2026-11-14 08:03（北京时间）
- 本期页：[阅读本期](https://reisen-ww.github.io/hot-pages/openhot/daily/2026-11-14)

## 头条

GraphQL 基金会发布 HTTP 规范，解决互操作与可观测性难题

## 工具与项目

1. [WebKit 修复 Promise 构造函数 Symbol.species 获取异常导致的执行阻塞问题](https://reisen-ww.github.io/hot-pages/openhot/items/lqxw4wq37xyv27ju4yfd0q8v2)
   来源：Lobsters 热榜 · 发布时间：2026-11-14 00:48（北京时间）
   摘要：WebKit 修复 Promise 构造函数 Symbol.species 获取异常导致的执行阻塞问题。对比 Safari/Bun引擎在 Promise 处理中的行为差异，分析 JavaScript 规范中 resolve 函数的实现逻辑及修复方案。
   原文：[打开原文](https://alistair.sh/thenables)

## 应用与安全

1. [GraphQL 基金会发布 HTTP 规范，解决互操作与可观测性难题](https://reisen-ww.github.io/hot-pages/openhot/items/mm71surul71wuo6w5qblycb5l)
   来源：Lobsters 热榜 · 发布时间：2026-11-13 09:16（北京时间）
   摘要：GraphQL 基金会发布 HTTP 规范，明确200 Not OK等状态码使用规则，新增GraphQL over HTTP媒体类型，解决代理缓存响应混淆问题。规范还规划了支持QUERY HTTP动词和持久化文档标准化，现有主流框架已适配新规。
   原文：[打开原文](https://graphql.org/blog/2026-11-12-announcing-the-graphql-over-http-spec/)

2. [Home Assistant 密码变更无效且令牌密钥明文存储漏洞披露](https://reisen-ww.github.io/hot-pages/openhot/items/p18sp3k2wv16xh13ijb6kvel1)
   来源：Hacker News 热榜 · 发布时间：2026-11-14 06:30（北京时间）
   摘要：Home Assistant 存在密码变更无效且令牌密钥明文存储的安全漏洞。测试版本 home-assistant/core 2026.11.0 发现：1. 用户令牌秘密和JWT签名密钥以明文形式存储在 config/.storage/auth 文件中；2. 长期有效令牌未设置过期时间；3. 密码变更未撤销相关令牌。建议用户立即更新配置并检查备份文件。
   原文：[打开原文](https://seclists.org/fulldisclosure/2026/Nov/34)

## 基础设施

1. [FreeBSD bhyve虚拟机活迁移支持首次完整实现](https://reisen-ww.github.io/hot-pages/openhot/items/hox5oh87bvu08t1u0frstto7z)
   来源：Hacker News 热榜 · 发布时间：2026-11-14 03:58（北京时间）
   摘要：作者在GitHub发布基于FreeBSD 15.1的bhyve虚拟机活迁移实现，实测单机迁移停机时间138-171ms，支持多vCPU协议和内存一致性检查。当前状态为WIP RFC，已规划存储网络交接和自动化测试方案，后续将扩展设备支持和性能优化。
   原文：[打开原文](https://gyptazy.com/blog/freebsd-bhyve-live-migration-support-rfc/)

## 快讯

- [基于 Rust 的 Qwen3.6 高性能推理方案开源](https://reisen-ww.github.io/hot-pages/openhot/items/tf0ub0ichb1fhjbghxb79md8q)
  来源：Hacker News 热榜 · 发布时间：2026-11-14 02:40（北京时间）
  摘要：某团队开源 Rust 写的向量数据库 Lightreason，实现 Qwen3.6 模型在单台 RTX 4090 上的 6-11 倍性能提升。仓库包含 BF16 权重优化、CUDA 图形计算、注意力缓存压缩等实现细节，并提供 Python/JS/SQL 基准测试工具。需安装 PyTorch 2.9.1 + CUDA 12.8，完整复现流程见文档。
  原文：[打开原文](https://github.com/me-farza/lightreason/tree/main)

- [Antithesis 开源 Rust 工具链，AI 5分钟通关 NetHack](https://reisen-ww.github.io/hot-pages/openhot/items/hv86jnxgvxxqrwz46m4mtg5p2)
  来源：Lobsters 热榜 · 发布时间：2026-11-13 22:34（北京时间）
  摘要：Antithesis 团队基于 Rust 开发的新工具链，通过多宇宙调试器定位 NetHack 游戏漏洞，利用概率编程语言特性实现动态策略优化。系统在 5 分钟内完成 NetHack 通关，关键突破包括：1) 多态变形机制（polymorphitis）的自动化利用；2) 基于逆向工程的动态状态管理；3) 资源约束下的价值函数迭代优化。该工具链已开源，支持自主系统在复杂状态空间中的探索与决策优化。
  原文：[打开原文](https://antithesis.com/blog/2026/nethack/)
