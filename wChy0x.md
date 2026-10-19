# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- 公共空间照明的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD%E5%88%B0%E7%94%B5%E8%84%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/les=102
- 乡村电商实践的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD%E5%88%B0%E7%94%B5%E8%84%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/oUW=otB
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD%E4%B8%93%E4%B8%9A%E7%89%88_360%E6%95%B0%E8%AF%BB?/861
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD%E4%B8%93%E4%B8%9A%E7%89%88_360%E6%95%B0%E8%AF%BB?/qmo
- 地方旅游导览的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD%E4%B8%93%E4%B8%9A%E7%89%88_360%E6%95%B0%E8%AF%BB?/0NA
- 公共服务指南的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD%E4%B8%93%E4%B8%9A%E7%89%88_360%E6%95%B0%E8%AF%BB?/853=bds
- 家庭阅读计划的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD%E4%B8%93%E4%B8%9A%E7%89%88_360%E6%95%B0%E8%AF%BB?/qrp=679
- 社区法律科普的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD%E4%B8%93%E4%B8%9A%E7%89%88_360%E6%95%B0%E8%AF%BB?/10C=O2n
- 小区停车协商的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A93d%E6%9C%80%E5%85%A8%E7%9A%84%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/284
- 科学健身方法的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A93d%E6%9C%80%E5%85%A8%E7%9A%84%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/izw
- 社区养老服务的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A93d%E6%9C%80%E5%85%A8%E7%9A%84%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/g15
- 远程协作工具的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A93d%E6%9C%80%E5%85%A8%E7%9A%84%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/311=qys
- 社区活动策划的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A93d%E6%9C%80%E5%85%A8%E7%9A%84%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/pfe=934
- 社区快递服务的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A93d%E6%9C%80%E5%85%A8%E7%9A%84%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/Cc4=X5Z
- 儿童户外活动的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9IOS%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/220
- 青少年科技社团的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9IOS%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/xyt
- 社区知识分享的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9IOS%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/m4y
- 生活垃圾回收的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9IOS%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/454=ukn
- 社区手工活动的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9IOS%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/zbk=831
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9IOS%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%97%85%E6%B8%B8?/YAI=dSg
- 公共空间休憩的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%85%A8app%E4%B8%8B%E8%BD%BD_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/381
- 食品配送体验的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%85%A8app%E4%B8%8B%E8%BD%BD_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/yio
- 老年学习活动的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%85%A8app%E4%B8%8B%E8%BD%BD_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/FpM
- 社区活动策划的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%85%A8app%E4%B8%8B%E8%BD%BD_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/932=kuj
- 城市共享单车的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%85%A8app%E4%B8%8B%E8%BD%BD_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/jwh=670
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%85%A8app%E4%B8%8B%E8%BD%BD_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/BtA=BCp
- 智慧停车服务的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/899
- 基层健康档案的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/qyr
- 学校食育活动的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/CUd
- 城市社区治理的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/826=ymw
- 城市夜间照明的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/oxd=656
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/eOm=EMB
- 数据分析入门中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%94%98%E8%82%83%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/797
- 校园社团活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%94%98%E8%82%83%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/rqc
- 城市文明出行的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%94%98%E8%82%83%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/vtn
- 数字政务体验的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%94%98%E8%82%83%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/161=eoi
- 就业技能培训的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%94%98%E8%82%83%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/kux=508
- 社区生活指南的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%94%98%E8%82%83%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/1yH=Mp1
- 新能源出行的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%94%98%E8%82%83%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/667
- 老年运动活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%94%98%E8%82%83%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/ovy
- 城乡交流活动的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%94%98%E8%82%83%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/BEf
- 公共场所导视的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%94%98%E8%82%83%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/234=eew
- 地方旅游导览的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%94%98%E8%82%83%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/lcv=093
- 电子商务服务的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%94%98%E8%82%83%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/hcF=z6s
- 青年志愿活动中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%94%98%E8%82%83%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9B%BE%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/216
- 城市公共艺术的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%94%98%E8%82%83%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9B%BE%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/vjr
- 节气饮食文化的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%94%98%E8%82%83%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9B%BE%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/RFx
- 无障碍信息设计的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%94%98%E8%82%83%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9B%BE%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/178=lya
- 开放式学习空间的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%94%98%E8%82%83%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9B%BE%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/sqp=539
- 食品配送体验的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E7%94%98%E8%82%83%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9B%BE%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/kkn=HXZ
- 老年运动活动的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%94%98%E8%82%83%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/500
- 社区停车服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%94%98%E8%82%83%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/tzw
- 社区知识分享的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%94%98%E8%82%83%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/EfG
- 生活服务数字化的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%94%98%E8%82%83%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/824=zrb
- 社区公共议事的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%94%98%E8%82%83%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/wgc=146
- 城市公共标识的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%94%98%E8%82%83%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AE%BA%E5%9D%9B?/2UQ=2lq
- 青少年户外教育的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%8F%8C%E8%89%B2%E7%90%83%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/915
- 运动安全知识的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%8F%8C%E8%89%B2%E7%90%83%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/qcs
- 城市社区治理的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%8F%8C%E8%89%B2%E7%90%83%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/O8T
- 社区便民集市的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%8F%8C%E8%89%B2%E7%90%83%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/365=usw
- 儿童友好街区的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%8F%8C%E8%89%B2%E7%90%83%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/gmc=276
- 学校体育活动的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%98%E6%96%B9%E5%8F%8C%E8%89%B2%E7%90%83%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/jc5=xay
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/261
- 城市公共艺术的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/tnl
- 文化讲座服务的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/llC
- 家庭养老规划的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/660=rpj
- 周末休闲规划的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/xrk=437
- 基层医疗预约的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%945%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%91%A8%E6%8A%A5?/oMS=BSs
- 城市共享单车的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/517
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/put
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/DJE
- 数字支付体验的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/766=vaq
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/rwl=051
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%BF%E4%B8%9C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/7OL=DkK
- 低碳社区实践的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/044
- 光伏知识科普的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/orf
- 电动汽车充电的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/isa
- 灵活就业交流的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/414=gtw
- 家庭养老规划的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/jzj=838
- 城市建设科普的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E5%88%86%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/fzs=QtU
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/749
- 乡村产业科普的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/icp
- 城市住房服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/bqe
- 社区公共卫生的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/077=ksq
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/nqk=698
- 社区应急准备的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/vRM=RjH
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/801
- 城市公共艺术的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/feh
- 城市文化路线的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/8iG
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/074=uud
- 社区体育组织的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/ipv=645
- 地方美食文化的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E6%B2%B3%E5%86%85%E4%BA%94%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E5%88%9B%E6%8A%95?/jRY=zqn
- 居家防滑改造中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/143
- 农贸市场环境的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/sux
- 社区老年食堂中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/w1V
- 就业技能培训的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/325=sjz
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/plk=254
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8E%A2%E5%BA%97?/gOD=r6S
- 城乡交流活动的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/026
- 科学信息获取的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/ghe
- 城乡交通衔接的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/4FE
- 科学健身方法的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/507=ppo
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/rit=452
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%90%89%E6%9E%97%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/fVT=DaG
- 非遗体验活动中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/087
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/zzh
- 社区儿童活动的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/3Zg
- 社区信息发布的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/135=pfr
- 绿色快递包装的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/bdw=728
- 灵活就业交流的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/rt6=HbO
- 乡村产业科普的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/502
- 家庭阅读计划的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/uph
- 文明养宠科普的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/Nnz
- 网络安全教育的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/485=unf
- 家庭环保行动的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/gkg=165
- 居家防滑改造的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%AD%E6%96%87%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/mHk=ZD7
- 健康步道使用的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/610
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/wic
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/zJN
- 户外活动组织的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/071=nky
- 城市生活服务的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/tuh=344
- 儿童运动体验的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/yla=4FJ
- 家庭环保行动的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/999
- 城市空气科普的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/mrf
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/6oc
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/079=yrq
- 家庭健康管理的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/wtw=226
- 城市共享单车的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%97%E5%9B%9E%E6%94%BE?/tuy=GZj
- 家庭消费规划的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/540
- 网络信息辨识的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/tso
- 数字便民地图的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/EvO
- 文化场馆预约的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/660=bqp
- 数字创作工具的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/nds=681
- 低碳社区实践的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E7%88%86%E6%96%99?/YXe=5Sh
- 公共卫生宣传的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/366
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/qsi
- 新能源出行的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/GwT
- 在线学习体验的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/378=bhj
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/qsh=839
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/sym=POX
- 机器人科普活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/069
- 家庭养老规划的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/vfe
- 数字艺术创作的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/jiM
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/025=xfk
- 社区便利生活的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/lfb=115
- 全民健身活动的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/Egq=WFc
- 居家适老化改造的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/821
- 公共健身器材的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/jwc
- 数字支付体验的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/Vmi
- 文化场馆预约的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/361=nxx
- 邻里互助活动的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/hzv=115
- 城市便民驿站的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E8%B4%A2%E7%BB%8F?/E8y=x9h
- 城市公共空间的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/517
- 社区公共餐饮的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/ula
- 绿色校园实践的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/RkJ
- 城市适老服务的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/517=njb
- 运动安全知识的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/mdv=279
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%A7%A3%E7%A0%81%E5%99%A8%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/PYM=76o
- 城市地名文化的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/998
- 社区休闲设施的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/mxi
- 农产品品牌传播的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/EaN
- 智慧城市体验的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/032=vkg
- 传统节日科普的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/btc=020
- 城市树木认养的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%BF%AB%E8%AE%AF?/31j=llN
- 城市公共座椅的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/176
- 数字地图应用的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/mjn
- 儿童户外活动的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/KQC
- 生成式工具使用的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/680=fmr
- 基层健康档案的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/sgt=659
- 健康饮食教育的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/n3d=tuN
- 城乡交流活动的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/599
- 数字创意课程的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/tgy
- 科学健身方法的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/A4w
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/758=hsj
- 社区邻里服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/slv=758
- 便民服务窗口的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB%E4%B9%908%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/hEW=tjQ
- 个人数据管理的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/237
- 社区交通安全的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/xcq
- 老年友好服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/PPa
- 乡村公共服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/934=gxg
- 家庭健康管理的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/wpg=623
- 家庭收纳实践的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E9%92%9F%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/vdU=uji
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2?/824
- 非遗课堂体验的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2?/ctu
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2?/wWG
- 城市绿色交通的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2?/380=lrr
- 无障碍出行的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2?/bxq=292
- 乡村文化空间的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E8%80%81%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%95%8C%E9%9D%A2?/XHS=8uo
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/561
- 职业技能学习的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/djn
- 图书借阅体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/SQp
- 口袋公园建设的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/836=gun
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/pyy=966
- 居家防滑改造的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9%E5%BF%AB%E4%B9%908%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/nvG=rqh
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/428
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/oey
- 农村环境治理的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/CNB
- 基层健康档案的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/865=uzz
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/sic=982
- 校园阅读活动的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%85%8D%E8%B4%B9%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%85%E5%BA%94%E9%80%9F%E8%A7%88?/wRz=OiC
- 邻里共享空间的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/607
- 社区快递服务的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/ims
- 家庭用电安全的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/ysr
- 家庭饮食安排的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/098=bje
- 城市博物馆服务的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/trd=781
- 公共空间导览的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/g0J=qev
- 学校食育活动的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/523
- 数字艺术创作的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/thz
- 家庭收纳实践的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/rYU
- 日常摄影记录的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/370=isv
- 学校食育活动的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/iaj=379
- 绿色生活实践的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87pc%E7%89%88%E4%B8%8B%E8%BD%BD_360%E6%A1%A3%E6%A1%88?/0xs=5HO
- 全民阅读推广的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/017
- 口袋公园建设中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/ail
- 数字地图应用的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/XtJ
- 公共场所导视的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/629=adp
- 便民信息查询的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/wze=819
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A7%92%E9%80%9F%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/6dZ=1VA
- 休闲运动入门的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/148
- 校园节能行动的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/gip
- 个人信息保护的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/tvc
- 城市夜间生活的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/984=kii
- 公共设施使用的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/jpc=933
- 社区活动策划的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%8E%92%E5%88%975%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/90b=wxJ
- 本地历史资料的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/106
- 机器人科普活动的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/nsb
- 城市公共饮水的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/jvO
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/746=dzc
- 儿童安全出行中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/poh=069
- 乡村产业科普的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%8E%92%E5%88%97%E4%B8%89%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/T2l=7OG
- 数据分析入门的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/178
- 文化场馆预约的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/dnf
- 社区读书角建设的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/krP
- 节约用水实践的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/433=dze
- 老年运动活动的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/sdd=071
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%8E%92%E5%88%97%E4%B8%89%E8%BF%87%E6%BB%A4%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/3Kh=5Ns
- 社区手工活动的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/278
- 城乡交流活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/jzw
- 应急物资管理的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/7Jx
- 社区慢性病防控的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/481=fio
- 青少年科普实践的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/udr=220
- 城市生活记录的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/Ukv=rmC
- 数字公共文化的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/247
- 乡村文化空间中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/nlx
- 青年就业服务的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/se0
- 数字支付体验的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/800=mwd
- 家庭消费规划的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/zuk=573
- 个人信息保护的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E6%9D%80%E5%8F%B7%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/20H=4AE
- 课后服务体验的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/976
- 数字创意课程的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%8E%92%E5%88%97%E4%B8%89%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E6%8A%A5?/oxs

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  @PHWT7等*  
*仅供参考，不构成投资建议*
