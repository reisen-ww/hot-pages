# 开源热点 周报 · 2026-W45

- 期号：第 4 期
- 发布：2026-11-10 18:31（北京时间）
- 本期页：[阅读本期](https://reisen-ww.github.io/hot-pages/openhot/weekly/2026-W45)

## 导语

Meta开源Rust实现的NTS协议，提供经过认证的时间服务

Go团队发布encoding/json/v2解决15年遗留问题并优化性能，Claude Opus 5.5首次生成符合建筑许可标准的CAD图纸；Meridian浏览器和Polyend Tracker社区版开源，Puppet服务器双漏洞修复；n8n+PostgreSQL架构实现零丢失webhook处理，MaxxBench揭示大模型任务适应能力差异。

## 工具与项目

1. [Go团队发布新JSON库v2，解决长期兼容与性能问题](https://reisen-ww.github.io/hot-pages/openhot/items/d3mgvd9x8ho3ta7e14bdcmli2)
   来源：Hacker News 热榜 · 发布时间：2026-11-05 01:52（北京时间）
   摘要：Go团队在v1.27版本中发布encoding/json/v2，修复了无效UTF-8静默损坏、重复键名兼容性等15年遗留问题，并优化性能使部分场景提升10倍。新增MarshalWrite/UnmarshalRead等流式API，支持自定义序列化逻辑。附详细迁移指南与性能对比数据
   原文：[打开原文](https://go.dev/blog/jsonv2)

2. [Meridian——基于Rust和GPUI的实验性浏览器发布](https://reisen-ww.github.io/hot-pages/openhot/items/kchsblmyurhq85xape3sydd83)
   来源：Lobsters 热榜 · 发布时间：2026-11-07 17:21（北京时间）
   摘要：Meridian是一款基于Rust和GPUI的实验性浏览器，支持无JavaScript或布局复杂度低的网页浏览，并提供了Nix运行方式。其技术架构采用Servo管理网页状态，GPUI渲染界面，通过gpui-servo库实现两者交互。主要功能包括地址栏联想、垂直水平标签页、书签历史管理、分页缩放、音视频播放和阅读模式。项目在Tangled平台开发，欢迎贡献者查看开放问题列表
   原文：[打开原文](https://op.tngl.io/meridian/)

3. [某开发者开源自托管 Odoo 面板，支持一键部署与全流程管理](https://reisen-ww.github.io/hot-pages/openhot/items/uywr5wt0blfkhmkqvhc7qcggn)
   来源：Reddit r/selfhosted · 发布时间：2026-11-04 16:46（北京时间）
   摘要：某开发者开源自托管 Odoo 面板（GitHub: incubacloud），提供服务器部署、版本回滚、AI辅助运维等功能，支持免费使用并开放社区反馈。托管版（www.incubacloud.io）提供免费计划且无需信用卡。
   原文：[打开原文](https://www.reddit.com/r/selfhosted/comments/1xnj9q8/i_built_a_selfhosted_panel_to_deploy_and_manage/)

4. [Polyend 开源 Tracker 硬件固件源代码及社区版 1.0](https://backstage.polyend.com/t/tracker-the-biggest-update-yet/25120)
   来源：Lobsters 热榜 · 发布时间：2026-11-02 23:22（北京时间）
   摘要：Polyend 开源了 Tracker 硬件固件源代码及社区版 1.0，支持用户自定义插件和硬件开发。社区版新增流式长样本播放、独立音量/微移调节、插件SDK（含6种音效生成器），兼容原版、Tracker+和Tracker Mini。GitHub仓库提供完整更新日志和开发指南。
   原文：[打开原文](https://backstage.polyend.com/t/tracker-the-biggest-update-yet/25120)

5. [声明式拖拽交互库 Dragology 开源，支持数学可视化与编程界面优化](https://reisen-ww.github.io/hot-pages/openhot/items/t5a9izy0prcp39alw9ch0ykzb)
   来源：Lobsters 热榜 · 发布时间：2026-11-05 08:35（北京时间）
   摘要：GitHub 仓库 Declarative Dragging 开源，提供声明式拖拽交互框架 Dragology。该库通过指定元素拖拽后的状态模型，自动合成平滑交互，减少开发者对几何、反馈和动画的底层编写。
   原文：[打开原文](https://declarative-dragging.github.io/)

6. [LLVM Vulkan 1.1 正式发布：集成GPU加速编译插件及多平台性能测试](https://reisen-ww.github.io/hot-pages/openhot/items/x6jbye70xgu86x35toejtl1y7)
   来源：Reddit r/programming · 发布时间：2026-11-04 06:59（北京时间）
   摘要：LLVM Vulkan 1.1 正式发布，提供基于Vulkan的GPU加速编译插件，支持Clang集成。性能测试显示在特定工作负载下，RTX 5090较CPU提升3.04倍至2.28倍，但小规模任务CPU仍占优。项目已验证与LLVM 21兼容，提供Windows/Linux预编译包及在线基准测试仪表盘。
   原文：[打开原文](https://www.reddit.com/r/programming/comments/1xn802v/llvm_vulkan_11_dropin_compiler_passes_gvn_cse_cfg/)

7. [某团队开源V100 SXM2模块载体板设计参考套件，含连接器映射与NVLink连接指南](https://github.com/pigeon-labs-stack/v100-sxm2-reference)
   来源：Hacker News 热榜 · 发布时间：2026-11-03 06:30（北京时间）
   摘要：某团队在GitHub开源V100 SXM2模块载体板设计参考套件，提供800个连接器映射、NVLink双/四卡连接方案及可编辑KiCad项目模板。文档包含电源控制、时钟配置等硬件设计要点，明确标注CERN-OHL-W-2.0与CC BY-SA 4.0双许可。
   原文：[打开原文](https://github.com/pigeon-labs-stack/v100-sxm2-reference)

8. [Claude Opus 5.5 通过 Python 代码生成建筑绘图，部分成果达到施工许可标准](https://stephenjgallagher.substack.com/p/ai-can-draw-blueprints-now)
   来源：Hacker News 热榜 · 发布时间：2026-11-03 00:25（北京时间）
   摘要：建筑师通过测试 13 个 AI 模型发现，Claude Opus 5.5（2026 年 9 月发布）首次能生成符合建筑许可要求的二维平面图与三维立面图。测试显示该模型通过 Python 代码直接生成 CAD 可编辑的向量绘图，在人工反馈下修正了屋檐与山墙布局错误。
   原文：[打开原文](https://stephenjgallagher.substack.com/p/ai-can-draw-blueprints-now)

## 应用与安全

1. [Meta开源Rust实现的NTS协议，提供经过认证的时间服务](https://reisen-ww.github.io/hot-pages/openhot/items/fx67eouq9ky8jof7mpoaglguv)
   来源：Hacker News 热榜 · 发布时间：2026-11-06 02:24（北京时间）
   摘要：Meta宣布开源Rust实现的NTS协议，提供经过认证的时间服务，解决了传统NTP协议无法防止中间人篡改时间的问题。代码托管于GitHub，支持Android和iOS设备的时间服务升级，并呼吁移动操作系统厂商集成该协议。
   原文：[打开原文](https://engineering.fb.com/2026/10/06/production-engineering/nts-authenticated-time-at-meta/)

2. [利用Bash邮件验证漏洞可获取GNU Savannah系统最高权限](https://reisen-ww.github.io/hot-pages/openhot/items/gk4uplq2nx48q1nsign4uhkca)
   来源：Lobsters 热榜 · 发布时间：2026-11-02 23:06（北京时间）
   摘要：Hacktron团队通过测试发现GNU Savannah的GPG密钥验证存在漏洞，攻击者可利用该漏洞获取系统root权限并篡改Bash等项目的上游代码仓库。具体利用路径为：注册含IFS插件的邮箱地址→触发GPG密钥测试→通过Shell命令注入执行任意代码→利用未修复的内核漏洞获取root→通过备份服务器访问关键基础设施。
   原文：[打开原文](https://www.hacktron.ai/blog/hacking-gnu-savannah)

3. [Stream Vessel 修复 MCP 开放重定向漏洞：用户自主管理信任地址列表](https://reisen-ww.github.io/hot-pages/openhot/items/dmi1f2ki2iss4r576o2zdn7n9)
   来源：Hacker News 热榜 · 发布时间：2026-11-04 23:30（北京时间）
   摘要：Stream Vessel 团队通过用户自定义信任地址机制，修复了 MCP 服务器因开放重定向导致的账户接管漏洞。攻击链演示：匿名注册恶意客户端→伪造可信重定向域名→用户点击Approve→授权码泄露。
   原文：[打开原文](https://streamvessel.com/blog/mcp-trusted-redirect-uris)

4. [Puppet服务器存在远程代码执行漏洞及主机身份伪造漏洞](https://reisen-ww.github.io/hot-pages/openhot/items/s8psmpi667xx7u2313rd5s5kw)
   来源：Lobsters 热榜 · 发布时间：2026-11-04 15:39（北京时间）
   摘要：某团队发现Puppet的两个安全漏洞：1. Puppet服务器通过事件反序列化实现远程代码执行（CVSS 9.1）；2. 主机身份伪造漏洞允许未经授权的认证。漏洞影响企业环境中的配置管理，供应商已于2026年11月3日发布修复补丁，并公开安全公告（GHSA-ffr6-rwpm-p5wq和GHSA-q4hm-33rc-572g）。
   原文：[打开原文](https://neodyme.io/en/blog/puppet_rce)

5. [某团队自托管Plausible分析容器中发现未经授权的加密货币挖矿程序](https://reisen-ww.github.io/hot-pages/openhot/items/o62d4g72xdmxc1xxfrsu0wvk2)
   来源：Reddit r/selfhosted · 发布时间：2026-11-05 10:33（北京时间）
   摘要：某团队自托管Plausible分析容器中发现未经授权的加密货币挖矿程序，该程序利用CVE-2026-8467漏洞运行，最终通过/proc路径终止进程。修复措施包括升级至v3.2.1版本、删除linuxsys伪装进程、限制Docker socket访问权限，并建议设置定时更新检查和镜像追踪机制。完整分析见404privacy.com的详细技术文档。
   原文：[打开原文](https://www.reddit.com/r/selfhosted/comments/1xo7agf/cryptominer_in_my_plausible_anayltics_container/)

6. [逆向工程 macOS 脏话数据库：Apple 如何标记 Trump 为敏感但未标记其他政要](https://helgesver.re/articles/macos-vulgar-word-flags)
   来源：Hacker News 热榜 · 发布时间：2026-11-04 04:33（北京时间）
   摘要：作者通过逆向工程获取系统脏话词库（VulgarWordUsage.db），发现 Apple 将 'Trump' 标记为敏感层级，但其他当代政要如 Biden、Obama、Putin 未被标记。
   原文：[打开原文](https://helgesver.re/articles/macos-vulgar-word-flags)

7. [Firecracker 虚拟机逃逸漏洞利用方法及验证](https://reisen-ww.github.io/hot-pages/openhot/items/bgg4zo1cgfoj4jptua9z79wus)
   来源：Hacker News 热榜 · 发布时间：2026-11-07 03:33（北京时间）
   摘要：某团队在Firecracker v1.16.1中发现虚拟机逃逸漏洞，通过修改寄存器框架和触发写操作实现root权限代码执行。验证显示攻击成功后，Firecracker进程仍可正常运行，SSH服务保持响应，且临时修改的栈内容被成功恢复。
   原文：[打开原文](https://pwn.ai/blog/firecracker-escape)

8. [TideCloak 开源发布：基于Keycloak的去中心化身份管理与加密架构](https://reisen-ww.github.io/hot-pages/openhot/items/qsxad3u93sk40fr05oz1jf2d7)
   来源：Lobsters 热榜 · 发布时间：2026-11-08 05:41（北京时间）
   摘要：TideCloak 开源发布，通过去中心化架构简化开发者身份集成与加密操作。项目基于Keycloak构建，提供标准OIDC接口和SDK，开发者只需编写常规React钩子和加密函数，系统自动完成密钥管理、零知识认证、阈值签名及端到端加密，消除传统IAM的单点故障风险。
   原文：[打开原文](https://tide.org/whitepaper/tidecloak-integration)

9. [musl Linux 环境下 SSH 密码哈希漏洞的十年修复历程与持续风险](https://reisen-ww.github.io/hot-pages/openhot/items/e7id5u39sxzhczos0hxfcymte)
   来源：Lobsters 热榜 · 发布时间：2026-11-05 20:24（北京时间）
   摘要：musl Linux 环境下的 SSH 服务存在安全漏洞（CVE-2016-6210），未设置密码的账户（如 root 或默认用户）可能被 257-1024 字符长度的任意密码入侵。
   原文：[打开原文](https://sshhole.com/)

## 基础设施

1. [某团队开源自托管n8n+PostgreSQL四层架构实现零丢失webhook处理](https://reisen-ww.github.io/hot-pages/openhot/items/nlvmdcv15488psmlhr6bwpy1e)
   来源：Reddit r/selfhosted · 发布时间：2026-11-06 04:09（北京时间）
   摘要：某团队在自托管n8n中通过PostgreSQL实现四层架构，确保零数据丢失的webhook处理。方案包含：1）ingestion层使用'On Received'响应模式即时返回200 OK 2）PostgreSQL原子去重与缓冲 3）全局错误触发器写入quarantine表 4）自动指数回退重试机制。
   原文：[打开原文](https://www.reddit.com/r/selfhosted/comments/1xosvfk/why_we_moved_webhook_ingestion_to_selfhosted_n8n/)

## 模型与数据

1. [Anthropic 未发布 Mythos 系列模型检查点泄露事件](https://huggingface.co/burner22/numbat)
   来源：Hacker News 热榜 · 发布时间：2026-11-02 00:43（北京时间）
   摘要：Anthropic 未发布 Mythos 系列模型检查点泄露，包含 14 万亿参数、772 分片及完整架构验证方法。验证显示各分片文件大小一致，模型架构为混合 GDN/MLA，并附有 Python 脚本验证 tensor 内部一致性。FAQ 回答确认这是预训练中期检查点，未包含后训练或 RLHF 阶段数据。
   原文：[打开原文](https://huggingface.co/burner22/numbat)

2. [Lo与团队开源MaxxBench基准测试工具，揭示大模型任务适应能力差异](https://reisen-ww.github.io/hot-pages/openhot/items/rjbxodxyunf7aaugdwzaewy1r)
   来源：Hacker News 热榜 · 发布时间：2026-11-08 01:19（北京时间）
   摘要：Gavin Lo 团队发布开源基准测试工具MaxxBench，通过修改89个DeepSWE任务，发现模型在任务变更中的表现差异显著。例如Claude Opus 5.5在MaxxBench中得分提升至76.4%，而DeepSeek V4.1 Flash得分暴跌至55.6%。
   原文：[打开原文](https://maxxbench.unlap.ai/research/why-maxxbench/)
