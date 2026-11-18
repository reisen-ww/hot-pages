# 开源日报 · 2026-11-18

- 期号：第 32 期
- 发布：2026-11-18 08:00（北京时间）
- 本期页：[阅读本期](https://reisen-ww.github.io/hot-pages/openhot/daily/2026-11-18)

## 头条

Java4Shell漏洞：OpenJDK Base64解码器远程代码执行利用方法

## 工具与项目

1. [uv 0.13.9 发布：优化锁文件与支持新PEP标准](https://reisen-ww.github.io/hot-pages/openhot/items/wj5k3wnh6t3kpd3va6rwyzzsn)
   来源：uv 版本发布 · 发布时间：2026-11-17 17:57（北京时间） · 一手
   摘要：uv 0.13.9 版本发布，优化锁文件大小和读取速度（#23184），新增 PEP 832 支持（#21822）及 HTTP/2 连接管理功能（#23236），同时将 Rust 依赖版本提升至 1.98（#23263）。支持多平台预构建包（ARM64/PPC64LE/RISC-V 等），可通过 GitHub CLI 验证发布包完整性（#23185）
   原文：[打开原文](https://github.com/astral-sh/uv/releases/tag/0.13.9)

## 应用与安全

1. [Java4Shell漏洞：OpenJDK Base64解码器远程代码执行利用方法](https://reisen-ww.github.io/hot-pages/openhot/items/s06219w0ojwkjgo37ddgczjkj)
   来源：Hacker News 热榜 · 发布时间：2026-11-18 05:11（北京时间）
   摘要：Java4Shell漏洞利用方法：通过构造特定Base64编码触发OpenJDK 17.0.6+内存溢出，利用AVX-512硬件加速特性实现远程代码执行。受影响版本包括Oracle Java SE 8u511b33-perf及后续更新。PoC代码展示如何通过200万次Base64解码触发漏洞，并在内存中写入可控数据。修复建议包括禁用Base64硬件加速或AVX-512指令集。
   原文：[打开原文](https://calif.io/java4shell/)

2. [Phrack 73 期发布：23篇安全技术研究论文与历史案例分析](https://reisen-ww.github.io/hot-pages/openhot/items/gddk3fga0rdlu1wu0ud7fv75w)
   来源：Lobsters 热榜 · 发布时间：2026-11-18 01:40（北京时间）
   摘要：Phrack 73 期发布，包含23篇技术论文及8篇额外文章，涵盖容器逃逸、Windows智能卡架构、静态污点分析等安全研究主题，并附有历史案例与未来趋势分析
   原文：[打开原文](https://phrack.org/issues/73/introduction_md.html)

## 语言与底层

1. [Jiff 1.0发布：Rust生态自托管日期时间库正式上线](https://reisen-ww.github.io/hot-pages/openhot/items/o4obo8m2cfni76lakno33mg9d)
   来源：Lobsters 热榜 · 发布时间：2026-11-16 06:39（北京时间）
   摘要：Jiff团队在GitHub发布Rust日期时间库1.0版本，支持自动处理夏令时和时区转换，已被uv、Cargo、Starship、fd、Nushell等主流项目采用。该库提供友好格式的持续时间输出、 RFC 2822/ISO 8601双解析、ICU4X多语言格式支持，并包含详细的API文档和示例代码。
   原文：[打开原文](https://burntsushi.net/jiff/)

## 模型与数据

1. [MIT与Adobe联合提出新型语言模型架构Lattice of Latents](https://reisen-ww.github.io/hot-pages/openhot/items/vzk2lsme82xg9gb82xrby9mf2)
   来源：Hacker News 热榜 · 发布时间：2026-11-18 06:17（北京时间）
   摘要：MIT与Adobe团队在GitHub开源Lattice of Latents架构，通过水平隐状态流（horizontal latents）与垂直残差流（vertical residual stream）协同工作，在20B tokens预训练基础上，406M参数模型将验证困惑度从15.41降至14.40，相比传统Transformer减少45%参数量同时保持性能优势。
   原文：[打开原文](https://shivamduggal4.github.io/latent-lattice-language-models/)

## 快讯

- [哈佛大学研究人员发现AI编码工具使代码审查成为新瓶颈](https://reisen-ww.github.io/hot-pages/openhot/items/vixohsf7i9s476aec9nxqdqrv)
  来源：Hacker News 热榜 · 发布时间：2026-11-18 05:16（北京时间）
  摘要：哈佛大学研究人员通过对比718家公司的代码提交与审查数据，发现AI编码工具使工程师代码量增加30%但未提升完成效率，瓶颈转移至代码审查阶段。研究特别指出法律AI工具如Harvey和Cooley的同类问题：虽然能加速初稿生成，但审查阶段耗时增加49%，且未公开审查效率的具体指标。
  原文：[打开原文](https://complexdiscovery.com/harvard-researchers-find-ai-coding-agents-shifted-the-bottleneck-to-code-review/)

- [RunAnywhere 开源 Trainium LLM 推理引擎 TrnRT 上线](https://reisen-ww.github.io/hot-pages/openhot/items/wieiohja07pxzgnyyqef4ams9)
  来源：Hacker News 热榜 · 发布时间：2026-11-18 00:01（北京时间）
  摘要：RunAnywhere 在 GitHub 公开 TrnRT 仓库，支持 GLM-5.3-Flash 模型，提供 Docker 构建命令、编译缓存机制、双引擎部署方案及性能测试数据（单机 trn2.48xlarge 支持 32 并行请求，1M tokens 上下文，成本对比从 $0.061/百万 tokens 到 $0.040）
  原文：[打开原文](https://github.com/RunanywhereAI/trnrt)
