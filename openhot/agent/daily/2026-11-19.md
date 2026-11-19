# 开源日报 · 2026-11-19

- 期号：第 33 期
- 发布：2026-11-19 08:00（北京时间）
- 本期页：[阅读本期](https://reisen-ww.github.io/hot-pages/openhot/daily/2026-11-19)

## 头条

Claude 模型在未研究细菌蛋白质序列预测上表现突破

## 工具与项目

1. [Unref 开源 Rust 编写的 Python 死代码查找器](https://reisen-ww.github.io/hot-pages/openhot/items/osnn3oiqwa6lhsenqgyvr7p26)
   来源：Hacker News 热榜 · 发布时间：2026-11-16 21:30（北京时间）
   摘要：团队开源 Rust 编写的 Python 死代码查找器 Unref，比 vulture 快 20 倍。支持 pytest、Pydantic、SQLAlchemy 等框架，配置在 pyproject.toml，提供预提交钩子集成方案，文档地址为 unref.readthedocs.io
   原文：[打开原文](https://github.com/Apakottur/unref)

2. [Zed 编辑器发布 v1.29.1 版本，新增 Git 分支对比与 Claude 5.2 支持](https://reisen-ww.github.io/hot-pages/openhot/items/fsn8oifo8u424682gwa9rvetf)
   来源：Zed 版本发布 · 发布时间：2026-11-19 00:53（北京时间） · 一手
   摘要：Zed 编辑器发布 v1.29.1 版本，新增 Git 分支对比模式、Claude Fable 5.2 和 Mythos 5.2 模型支持，优化文件操作与界面交互。修复了自动复制响应、分支切换卡顿、绝对路径打开异常等 15 项问题。
   原文：[打开原文](https://github.com/zed-industries/zed/releases/tag/v1.29.1)

3. [Bonfire 1.1 发布：支持跨平台联邦群组协作](https://reisen-ww.github.io/hot-pages/openhot/items/lkxfc2f595j7fmw3ugjlcp8a4)
   来源：Lobsters 热榜 · 发布时间：2026-11-18 22:58（北京时间）
   摘要：Bonfire 1.1版本推出联邦群组功能，支持跨平台协作，并新增投票、话题分类等社区管理工具。兼容Mastodon API的beta版本，允许第三方应用接入。当前支持公开网络、公告频道和本地社区的联邦，私人群组跨服务器联邦功能尚在开发中。社区可自定义成员权限（如协调员、代表等角色），并计划与ATProto、Matrix等平台互通。
   原文：[打开原文](https://bonfirenetworks.org/posts/for-the-things-we-can-only-do-together/)

4. [Zed 1.30.0 预发布发布：新增 GPT-6.1 支持，优化 GPU 效率与键盘导航](https://reisen-ww.github.io/hot-pages/openhot/items/nci73vg38xnatyb8nh8z5a4ef)
   来源：Zed 版本发布 · 发布时间：2026-11-19 00:00（北京时间） · 一手
   摘要：Zed 1.30.0 预发布发布，新增对 OpenAI GPT-6.1 Terra 的支持，优化 GPU 资源使用效率，改进键盘导航和大型项目扫描性能。修复了多个崩溃和界面问题，包括解决 Windows 显示切换崩溃、Git 模块名称错误检测、终端关闭残留问题等。
   原文：[打开原文](https://github.com/zed-industries/zed/releases/tag/v1.30.0-pre)

## 应用与安全

1. [PyPI 实施更严格的软件包上传检查机制](https://reisen-ww.github.io/hot-pages/openhot/items/jofpq921ampjxjmro031mts2m)
   来源：Lobsters 热榜 · 发布时间：2026-11-19 04:00（北京时间）
   摘要：PyPI 宣布将实施更严格的软件包上传检查机制，以减少解析差异和提升安全性。当前已禁止 V7-style tar 归档和包含 ZIP 控制结构的评论，后续计划全面禁止 GNU 风格 tar 和 ZIP 评论。
   原文：[打开原文](https://blog.pypi.org/posts/2026-11-18-stricter-checks-for-uploaded-sdists/)

## 模型与数据

1. [Claude 模型在未研究细菌蛋白质序列预测上表现突破](https://reisen-ww.github.io/hot-pages/openhot/items/ttqb1gs0kkyv5y208zd5d83co)
   来源：Hacker News 热榜 · 发布时间：2026-11-18 11:47（北京时间）
   摘要：Claude Opus 5.5 和 Fable 5.2 在未研究细菌蛋白质序列预测上分别达到34.9%和54.7%的正确率，显著优于其他开源模型。实验通过668个未研究蛋白质的10步序列预测，对比发现Claude模型在顺序依赖和家族规模相关性上均优于蛋白语言模型。测试排除了已研究蛋白和依赖文献的干扰，证明其能力来自大规模蛋白质数据训练而非文献学习。
   原文：[打开原文](http://xinmingtu.cn/blog/2026/claude-opus-5-5-protein-sequences/)

## 快讯

- [CrossPoint 阅读器开源社区发布，支持EPUB排版与多设备同步](https://reisen-ww.github.io/hot-pages/openhot/items/hdnoc4zntmpe7oki92kujgwns)
  来源：Hacker News 热榜 · 发布时间：2026-11-19 01:14（北京时间）
  摘要：CrossPoint 是一款由开源社区维护的电子书阅读器，支持EPUB排版（含 justified 文本、语言感知断字和脚注）、自定义字体与页面布局、多设备阅读进度同步（与KOReader兼容），以及蓝牙翻页器控制。社区贡献者达242人，已部署于281,736台设备。
  原文：[打开原文](https://crosspointreader.com)

- [Phrack 73 期发布：23篇技术论文探讨 exploitation、AI 与硬件安全](https://reisen-ww.github.io/hot-pages/openhot/items/jtltpdmhm5w5z2wu7t3dih77h)
  来源：Hacker News 热榜 · 发布时间：2026-11-18 02:31（北京时间）
  摘要：Phrack 73 期发布，包含23篇技术论文，涵盖 exploitation、reverse engineering、AI 与硬件安全，并回顾历史漏洞如 SSH1 CRC32 的问题，探讨AI后门与信任问题。杂志通过周年纪念活动，激励社区贡献新研究，并附有4篇开源历史文章，包括2003年Linux内核后门尝试的复盘。
  原文：[打开原文](https://phrack.org/issues/73/introduction_md)

- [Context-Generic Programming v0.8.0发布：cargo-cgp工具与namespaces功能](https://reisen-ww.github.io/hot-pages/openhot/items/nki67nt24e2w7ds2pnc34zdt7)
  来源：Lobsters 热榜 · 发布时间：2026-11-19 00:08（北京时间）
  摘要：Context-Generic Programming (CGP) v0.8.0发布，包含cargo-cgp工具解决宏展开后编译错误描述不直观的问题，以及namespaces功能实现组件分组配置。
  原文：[打开原文](https://contextgeneric.dev/blog/v0.8.0-release)

- [cwida 开源 SuperEMeans 聚类算法加速方案](https://reisen-ww.github.io/hot-pages/openhot/items/pwlg764cutjpof3wq8fgpmq3v)
  来源：Hacker News 热榜 · 发布时间：2026-11-19 00:09（北京时间）
  摘要：cwida 在 GitHub 开源 SuperEMeans 聚类算法，结合 SuperKMeans 和 e-means 实现速度提升 1.8-3.2 倍，同时优化了聚类不平衡问题。对比实验显示，在 5M OpenAI 和 10M Cohere 数据集上，SuperEMeans 的召回率与 e-means 相当，但扫描的向量数量更少。
  原文：[打开原文](https://www.lkuffo.com/superemeans/)

- [RadixArk 发布 DaisyRose-27B 模型，在终端基准测试中性能提升 6.4 倍](https://reisen-ww.github.io/hot-pages/openhot/items/g6z3jhvyjqlqie1wc44a31u05)
  来源：Hacker News 热榜 · 发布时间：2026-11-19 03:39（北京时间）
  摘要：RadixArk 发布基于 Qwen3.8-27B 的 DaisyRose-27B 模型，在 Terminal-Bench 4.1 基准测试中性能从 5.6% 提升至 12%，主要得益于优化训练数据、异步强化学习框架和高效沙盒服务。训练成本降低 57%，沙盒服务可靠性达 99.95%。模型已发布至 Hugging Face，支持 BF16/FP8/NVFP4 格式下载。
  原文：[打开原文](https://www.radixark.com/blog/daisyrose-27b)
