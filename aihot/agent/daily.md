# AI 日报 · 2026-11-12

- 期号：第 32 期
- 发布：2026-11-12 08:00（北京时间）
- 本期页：[阅读本期](https://reisen-ww.github.io/hot-pages/aihot/daily/2026-11-12)

## 头条

AWS发布UAEF框架：支持多框架AI代理闭环评估的开源系统

## 模型发布/更新

1. [DeepMind发布AlphaGenome 2模型：解析细胞读取DNA机制以增进疾病理解](https://reisen-ww.github.io/hot-pages/aihot/items/lgk58pak7v504xjvk5iprvffm)
   来源：Google DeepMind · 发布时间：2026-11-11 23:00（北京时间） · 一手 · 另有 1 家信源报道
   摘要：DeepMind发布AlphaGenome 2模型，通过单细胞生物学与人类遗传学结合，显著提升特定细胞类型基因表达预测精度（较前代因果变体识别率提高30%至16%，方向性基因效应识别率提升23%至43%）。该模型支持未见过的新细胞状态推断（如COVID-19 mRNA疫苗激活的T细胞），并首次整合DNA甲基化预测功能。现提供非商业API访问和商业预览，已包含107百万个体细胞数据训练。
   相关：
   - [DeepMind发布AlphaGenome 2：精准解析细胞级疾病根源](https://reisen-ww.github.io/hot-pages/aihot/items/orlugphkp6ti32tu7o4jj7lrm) · The Verge · AI · 2026-11-11 23:00（北京时间）
   原文：[打开原文](https://deepmind.google/blog/alphagenome-2-deciphering-how-cells-read-dna-to-better-understand-disease/)

## 产品发布/更新

1. [Google 发布 Gemini Decision 1 决策 API](https://reisen-ww.github.io/hot-pages/aihot/items/gcx8d0d4bglnlr8u0hazs3oa9)
   来源：The Decoder · 发布时间：2026-11-12 04:12（北京时间）
   摘要：Google Deepmind 推出 Gemini Decision 1 决策 API，单次处理 1000 个跨模态问题（文本/图像/音频/视频/PDF）。
   原文：[打开原文](https://the-decoder.com/google-joins-the-decision-model-wave-with-gemini-decision-1-scoring-1000-questions-in-a-single-pass/)

2. [AWS Bedrock发布Kimi K3.1 Pro Highspeed智能体](https://reisen-ww.github.io/hot-pages/aihot/items/teb9htf41ab5b3bgrk3znurb4)
   来源：AWS Machine Learning Blog · 发布时间：2026-11-11 09:07（北京时间） · 一手
   摘要：AWS发布Kimi K3.1 Pro Highspeed智能体，性能提升2-3倍并支持工具调用和流式输出。该产品通过Amazon Bedrock平台提供API调用示例，包含使用OpenCode集成开发环境、成本优化策略（Flex层级）、显式提示缓存技术（需256+稳定前缀），同时保持数据隔离（不共享给Moonshot AI且零数据留存）。
   原文：[打开原文](https://aws.amazon.com/blogs/machine-learning/introducing-kimi-k3-1-pro-on-amazon-bedrock/)

3. [Gemini 4 Carbon宣布价格调整并开放给更广泛用户](https://reisen-ww.github.io/hot-pages/aihot/items/a66rrswlvnedf3xr8w45ihhk7)
   来源：Simon Willison · 发布时间：2026-11-11 04:09（北京时间）
   摘要：Gemini 4 Carbon宣布对价格进行调整（$2/million输入→$4/million输入，$10/million输出→$20/million输出）并开放给更广泛用户。
   原文：[打开原文](https://simonwillison.net/2026/Nov/10/llm-gemini/)

4. [AWS发布官方本地测试工具aws-emulator](https://reisen-ww.github.io/hot-pages/aihot/items/ytr16cta7tqam6vxjl5ko0890)
   来源：Simon Willison · 发布时间：2026-11-12 05:18（北京时间）
   摘要：AWS发布官方本地测试工具aws-emulator，无需付费API密钥即可模拟其多款服务。该工具由Rust编写，首月获29,684次代码贡献，但当前仅支持Docker运行于macOS或Windows平台。
   原文：[打开原文](https://simonwillison.net/2026/Nov/11/aws-emulator/)

## 行业动态

1. [xAI旗下Grok构建应用泄露患者数据及内部销售信息](https://reisen-ww.github.io/hot-pages/aihot/items/bthsmafmicxeqe7evxfk94kzd)
   来源：The Decoder · 发布时间：2026-11-11 20:53（北京时间）
   摘要：Grok构建的应用存在大规模数据泄露风险，包括患者记录和内部销售信息。Claroc报告显示94.7%的未授权访问应用来自SpaceXSI员工，涉及企业销售团队名单、广告提案等敏感数据。SpaceXSI虽已下线24个涉事内部应用，但未修复其他用户公开应用的安全漏洞。此前已发生Grok泄露370万对话记录和用户文件上传事件，爱尔兰数据保护机构正在调查。
   原文：[打开原文](https://the-decoder.com/grok-built-apps-exposed-patient-data-plaintext-passwords-and-spacexsis-own-sales-pipeline/)

2. [AI模型评测与行业动态：Gemini Carbon、Claude Fable 5.2与Qwen 3.8对比](https://reisen-ww.github.io/hot-pages/aihot/items/gb2p8bzjvm9280vpinoffk2gg)
   来源：Latent Space · 发布时间：2026-11-11 17:34（北京时间）
   摘要：Mercor完成20亿美元估值D轮融资后，Google发布Gemini 4 Carbon并公布多模态应用场景。评测显示Carbon在CursorBench上领先Astra 6.2%，但存在幻觉问题；Claude Fable 5.2在生成游戏、Excel式应用等场景表现突出，但评测方法存在争议。
   原文：[打开原文](https://latent.space/p/ainews-mercor-750m-series-d-at-20b-valuation-3b-run-rate/)

3. [Nvidia因CEO丑闻面临证券欺诈集体诉讼](https://reisen-ww.github.io/hot-pages/aihot/items/gs4mnf5hczvnui1w6tzcs5gbh)
   来源：TechCrunch · AI · 发布时间：2026-11-10 06:23（北京时间）
   摘要：Nvidia因CEO Jensen Huang与情报部门关联的丑闻，遭到Rosen Law Firm等律所发起证券欺诈集体诉讼。指控内容包含公司隐瞒与Megaspeed的数据中心合作，导致股价单日下跌4.27%至$7.97。诉讼依据包括CEO与间谍关联的虚假陈述，以及证券法中首诉触发机制。法律专家预测可能形成市场欺诈经典案例，涉及数亿美元赔偿。
   原文：[打开原文](https://techcrunch.com/2026/11/09/the-race-is-on-to-sue-nvidia/)

4. [OpenAI单季度收入首次突破10亿美元](https://reisen-ww.github.io/hot-pages/aihot/items/fn9ifc2ks3c049342h52cq013)
   来源：TechCrunch · AI · 发布时间：2026-11-12 00:14（北京时间）
   摘要：OpenAI单季度收入首次突破10亿美元，同比增长近50%。但与Anthropic Q3收入17亿美元的规模相比，OpenAI在收入增速和云服务市场份额仍处追赶阶段。双方收入计算方式存在差异：OpenAI仅统计自身分成，而Anthropic包含合作伙伴收入。
   原文：[打开原文](https://techcrunch.com/2026/11/11/openais-quarterly-revenue-reportedly-crosses-10b-for-the-first-time/)

5. [NVIDIA生态初创公司应用AI技术提升混合废物回收效率](https://reisen-ww.github.io/hot-pages/aihot/items/lp6jzin22hrhuqo0gptnfvsxl)
   来源：NVIDIA Blog · 发布时间：2026-11-11 11:00（北京时间） · 一手
   摘要：NVIDIA支持的初创公司通过AI技术提升混合废物回收效率，具体案例包括AIRECO（95%识别准确率，目标年处理量4.8万吨）、EverestLabs AI（识别40亿物体，回收2.5万吨材料）和reverse.fashion（300多系统应用，效率提升10%-30%），展示了AI在资源循环利用中的实际应用效果。
   原文：[打开原文](https://blogs.nvidia.com/blog/ai-recycling-startups/)

## 论文研究

1. [AWS发布UAEF框架：支持多框架AI代理闭环评估的开源系统](https://reisen-ww.github.io/hot-pages/aihot/items/h8p3jjqnri7gxeo113jxngsz0)
   来源：AWS Machine Learning Blog · 发布时间：2026-11-11 23:50（北京时间） · 一手
   摘要：AWS推出开源评估框架UAEF，支持LangGraph、LangChain等框架的AI代理进行多维度指标（工具调用、响应质量、推理能力等）评估。系统通过适配器统一处理不同框架的执行轨迹，存储结果至DynamoDB/S3，生成对比报告和LLM辅助分析。案例显示企业客户通过该框架检测退化、优化提示词和模型，实现闭环迭代。
   原文：[打开原文](https://aws.amazon.com/blogs/machine-learning/uaef-a-framework-agnostic-system-for-closed-loop-evaluation-of-ai-agents/)

2. [Hugging Face发布多向量嵌入模型压缩训练方法](https://reisen-ww.github.io/hot-pages/aihot/items/pcyak5qzcd3ms9tocpk7c842b)
   来源：Hugging Face Blog · 发布时间：2026-11-11 08:00（北京时间） · 一手
   摘要：Hugging Face发布token pooling-aware训练方法，通过Ward层次聚类将平均文档向量数压缩至原值的25%（pool\_factor=4），在NanoBEIR@13测试集上nDCG@10从49.03提升至51.23（+2.20），同时保持检索质量。
   原文：[打开原文](https://huggingface.co/blog/token-pooling)

## 快讯

- [AWS Bedrock AgentCore 推出Web Search API](https://reisen-ww.github.io/hot-pages/aihot/items/ypeb1f0v8rmp877nn7q1fe4f3)
  来源：AWS Machine Learning Blog · 发布时间：2026-11-12 07:13（北京时间） · 一手
  摘要：AWS推出Web Search API，开发者可通过API直接调用实时网页搜索功能，无需创建资源，支持多种集成场景。该API提供域名过滤、时间范围筛选（1-25结果/次），结果包含文本摘要、URL、发布时间等。
  原文：[打开原文](https://aws.amazon.com/blogs/machine-learning/introducing-the-web-search-api-on-amazon-bedrock-agentcore/)

- [DXC Technology 在 AWS Bedrock 上构建多模型 AI 基础设施](https://reisen-ww.github.io/hot-pages/aihot/items/k9vvfagkxqc13uh0mxoxlvck2)
  来源：AWS Machine Learning Blog · 发布时间：2026-11-12 04:45（北京时间） · 一手
  摘要：DXC Technology 在 AWS Bedrock 上构建了面向企业IT运营的治理型多模型AI基础设施（DXC OASIS），通过分离模型选择与编排层实现灵活扩展。
  原文：[打开原文](https://aws.amazon.com/blogs/machine-learning/how-dxc-technology-built-a-multi-model-ai-substrate-on-amazon-bedrock/)

- [AWS发布Bedrock AgentCore及多款AI模型更新](https://reisen-ww.github.io/hot-pages/aihot/items/b18pmb6vgyeyiyiy1cmujshnn)
  来源：AWS Machine Learning Blog · 发布时间：2026-11-12 06:26（北京时间） · 一手
  摘要：AWS在2026年10月推出Bedrock AgentCore及多款AI模型，包括Claude Haiku 5.5（成本降低75%）、GPT-6.1 Terra（速度提升三倍，价格降低50%）和GLM 5.3等。新工具支持多模型调用、成本优化及本地安全运行，并新增结构化输出和语音交互功能。
  原文：[打开原文](https://aws.amazon.com/blogs/machine-learning/icymi-what-landed-for-ai-builders-in-october-2026/)

- [AWS发布23个可重用资产加速生成式AI交付](https://reisen-ww.github.io/hot-pages/aihot/items/xyvokmcqey8oysculfp2gc9af)
  来源：AWS Machine Learning Blog · 发布时间：2026-11-12 03:19（北京时间） · 一手
  摘要：AWS发布23个可重用资产，帮助客户将生成式AI开发时间从数月缩短至数周。案例显示DoorDash通过Contact Center GenAI Agent实现日处理10万+语音请求，Ricoh利用GenAIDP资产将文档处理吞吐量提升7倍。
  原文：[打开原文](https://aws.amazon.com/blogs/machine-learning/accelerating-generative-ai-delivery-with-reusable-assets/)

- [NVIDIA Nemotron 3.5 Super VL 已上线 Amazon SageMaker JumpStart](https://reisen-ww.github.io/hot-pages/aihot/items/sbs3k0trw2tcon19u3ujm2ar6)
  来源：AWS Machine Learning Blog · 发布时间：2026-11-10 04:01（北京时间） · 一手
  摘要：AWS JumpStart 上线 NVIDIA Nemotron 3.5 Super VL 多模态模型，提供 NVFP4（优化推理）和 BF16（全精度）两种变体，支持图像、视频及文本输入，并附详细部署步骤与性能对比数据。
  原文：[打开原文](https://aws.amazon.com/blogs/machine-learning/nvidia-nemotron-3-5-super-vl-is-now-available-in-amazon-sagemaker-jumpstart/)

- [英国监管机构威胁对未采用AI防护考试形式的高校实施制裁](https://reisen-ww.github.io/hot-pages/aihot/items/is28cob65a2xhrltq5hgsjnn6)
  来源：The Decoder · 发布时间：2026-11-11 19:54（北京时间）
  摘要：英国高等教育监管机构OfS威胁对未采用AI防护考试形式的高校实施制裁。OfS与第三方机构联合调查显示127所高校中超过300个教学单位存在学生使用AI完成论文且成绩与人工撰写无显著差异的问题，部分学生甚至通过ChatGPT完成整篇论文后无法回忆基础内容。
  原文：[打开原文](https://the-decoder.com/uk-regulator-threatens-universities-with-sanctions-unless-they-adopt-ai-proof-exam-formats/)

- [AWS SageMaker AI 推出基于使用量的计费模式](https://reisen-ww.github.io/hot-pages/aihot/items/kks1tp5vorkir67sgz7lwd1o8)
  来源：AWS Machine Learning Blog · 发布时间：2026-11-11 23:10（北京时间） · 一手
  摘要：AWS SageMaker AI 推出基于使用量的计费模式，支持实时双向流推理的按秒计费。客户通过AWS Marketplace订阅Deepgram等模型时，软件费用按实际音频处理量（如720秒对应12分钟）计收，基础设施费用仍单独计算。
  原文：[打开原文](https://aws.amazon.com/blogs/machine-learning/introducing-usage-based-pricing-for-amazon-sagemaker-ai-bidirectional-streaming/)

- [Google DeepMind发布AlphaProof Code工具，四周完成Signal加密协议验证](https://reisen-ww.github.io/hot-pages/aihot/items/dt3urf5lbe93e756rbg2xvyv2)
  来源：The Decoder · 发布时间：2026-11-12 02:18（北京时间）
  摘要：Google DeepMind发布AlphaProof Code工具，四周完成Signal加密协议验证，并实现自动化漏洞检测。该工具通过AI agents编写验证代码，覆盖六百万行代码，标记约1%需人工审查，并成功识别预植测试漏洞。
  原文：[打开原文](https://the-decoder.com/google-deepminds-alphaproof-code-verified-signals-cryptographic-core-in-four-weeks-instead-of-years/)

- [OpenAI企业销售推动季度营收达10亿美元但仍落后Anthropic](https://reisen-ww.github.io/hot-pages/aihot/items/guk114ayhjdqmy2r31tocgq6k)
  来源：The Decoder · 发布时间：2026-11-11 20:12（北京时间）
  摘要：OpenAI 2026年第三季度营收达10亿美元（同比增长约50%），调整后运营亏损扩大至-109%，仍落后于计划IPO的Anthropic（Q3营收17亿美元，亏损567百万美元）。
  原文：[打开原文](https://the-decoder.com/enterprise-sales-push-openais-quarterly-revenue-to-10-billion-though-it-still-trails-anthropic/)

- [DeepL 推出实时翻译新模型 Aure，支持捕捉说话者的语气、情感和语速](https://reisen-ww.github.io/hot-pages/aihot/items/wp4jw5tozghwvwuenxvh2ov8b)
  来源：The Decoder · 发布时间：2026-11-11 21:50（北京时间）
  摘要：DeepL 推出实时翻译新模型 Aure，支持捕捉说话者的语气、情感和语速。该模型通过分离语音身份、语调旋律和内容进行独立翻译，并利用强化学习避免输出口音。目前支持英语、德语、西班牙语等8种语言，已应用于 DeepL Voice for Online Meetings 等场景。DeepL 此前收购音频流媒体团队 Mixhalo 以强化实时语音翻译能力。
  原文：[打开原文](https://the-decoder.com/with-its-new-voice-model-deepl-voice-now-translates-intonation-and-speaking-speed-into-other-languages-as-well/)
