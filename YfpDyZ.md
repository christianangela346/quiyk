# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 科学观察活动的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%8E%A7%E5%88%B6%E6%AF%8F%E4%B8%80%E4%B8%AA%E4%BA%BA%E8%BF%98%E6%98%AF%E6%80%8E%E6%A0%B7-%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/ypm=301
- 环境监测科普的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%8E%A7%E5%88%B6%E6%AF%8F%E4%B8%80%E4%B8%AA%E4%BA%BA%E8%BF%98%E6%98%AF%E6%80%8E%E6%A0%B7-%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/rpy=2q8
- 绿色消费选择的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_6%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/462
- 传统节日科普的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_6%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/epn
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_6%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/VVX
- 公共场馆服务的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_6%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/270=dfv
- 社区设施共享的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_6%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/gpo=575
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_6%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/pnJ=yov
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/953
- 社区家政服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/vgy
- 城乡交通衔接的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/QHe
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/978=wsd
- 街道综合服务的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/xct=384
- 公共场所导视的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_998%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/YvG=L7n
- 社区养老服务的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%84%E7%A7%8D%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/266
- 学校体育活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%84%E7%A7%8D%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/lte
- 家庭健康管理的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%84%E7%A7%8D%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/OuP
- 城市共享单车的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%84%E7%A7%8D%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/391=dmz
- 数据分析入门的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%84%E7%A7%8D%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/mxm=567
- 数字创意课程的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%90%84%E7%A7%8D%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/RTN=OT0
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_168%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E8%A7%A3%E6%9E%90-%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/222
- 开源技术交流的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_168%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E8%A7%A3%E6%9E%90-%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/xim
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_168%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E8%A7%A3%E6%9E%90-%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/y9u
- 低碳社区实践的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_168%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E8%A7%A3%E6%9E%90-%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/850=yum
- 公共交通接驳的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_168%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E8%A7%A3%E6%9E%90-%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/nxn=229
- 老年人文化生活的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_168%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E8%A7%A3%E6%9E%90-%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/Yyz=neN
- 小微企业服务中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E5%88%B0-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/932
- 电子商务服务的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E5%88%B0-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/see
- 社区交通安全的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E5%88%B0-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/5Vu
- 本地历史资料的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E5%88%B0-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/089=onu
- 数字生活课堂的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E5%88%B0-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/imr=898
- 青少年科技社团的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E5%88%B0-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/u9q=FjN
- 农贸市场环境的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F-%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/074
- 数字创意课程的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F-%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/grx
- 环境监测科普的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F-%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/KxQ
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F-%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/808=beg
- 节假日出行安排的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F-%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/xyz=141
- 家庭理财科普的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F-%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/E98=A9R
- 本地消费场景的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7-360%E9%80%9F%E8%A7%88?/856
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7-360%E9%80%9F%E8%A7%88?/wwy
- 绿色校园实践的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7-360%E9%80%9F%E8%A7%88?/kHK
- 科学教育活动的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7-360%E9%80%9F%E8%A7%88?/260=nwy
- 非遗体验活动的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7-360%E9%80%9F%E8%A7%88?/tsc=688
- 社区托育服务的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7-360%E9%80%9F%E8%A7%88?/Ojv=Via
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/737
- 城市绿道建设的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/szc
- 社区便民集市的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/myW
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/127=bpo
- 城市农夫市集的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/ppo=136
- 社区宠物管理的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%8A%92%E6%9E%9C%E5%9B%BD%E9%99%85?/O6Z=25K
- 社区家政服务的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E7%94%B5%E8%AF%9D-%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/146
- 无障碍出行的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E7%94%B5%E8%AF%9D-%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/dau
- 亲子科普活动的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E7%94%B5%E8%AF%9D-%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/vqI
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E7%94%B5%E8%AF%9D-%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/640=wqh
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E7%94%B5%E8%AF%9D-%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/ipc=975
- 城市公共标识的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E7%94%B5%E8%AF%9D-%E5%87%A4%E5%87%B0%E7%9B%98%E7%82%B9?/AxT=Kwf
- 农贸市场环境的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88-%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/879
- 农村环境治理的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88-%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/omo
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88-%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/12l
- 社区休闲设施的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88-%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/126=oht
- 社区活动报名的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88-%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/oio=979
- 学校食育活动中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88-%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/bHL=35p
- 社区公共卫生的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91APP%E6%8E%A8%E8%8D%90-%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/695
- 便民服务地图的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91APP%E6%8E%A8%E8%8D%90-%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/vwn
- 社区活动报名的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91APP%E6%8E%A8%E8%8D%90-%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/LfE
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91APP%E6%8E%A8%E8%8D%90-%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/759=xdu
- 社区设施共享的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91APP%E6%8E%A8%E8%8D%90-%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/nle=827
- 城市公共标识的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91app%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91APP%E6%8E%A8%E8%8D%90-%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/Ps7=mE9
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%8F%91%E6%9C%80%E6%96%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/392
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%8F%91%E6%9C%80%E6%96%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/gvo
- 城市体育设施的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%8F%91%E6%9C%80%E6%96%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/SZs
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%8F%91%E6%9C%80%E6%96%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/115=ziq
- 小区公共照明的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%8F%91%E6%9C%80%E6%96%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/wyx=293
- 农贸市场环境的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E4%B9%90%E5%8F%91%E6%9C%80%E6%96%B0%E9%82%80%E8%AF%B7%E7%A0%81-%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/53u=XIQ
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/132
- 社区消防演练的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/wcw
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/P11
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/854=aqe
- 数字生活课堂的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/nbn=748
- 户外活动组织的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/OAd=VZD
- 城市公共标识的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%A4%9A%E5%B0%91-36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/958
- 家庭教育交流的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%A4%9A%E5%B0%91-36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/ojv
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%A4%9A%E5%B0%91-36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/QQ0
- 城市雨天出行的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%A4%9A%E5%B0%91-36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/807=brd
- 个人数据管理的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%A4%9A%E5%B0%91-36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/qkr=916
- 本地旅行体验的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%A4%9A%E5%B0%91-36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/2Jj=Q5g
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/957
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/qhu
- 图书馆数字服务的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/RQC
- 青少年职业启蒙的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/671=ekq
- 城市慢行系统的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/sie=152
- 旧物循环利用的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/9ut=wQL
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%EF%BD%9Ewelcome%E9%82%80%E8%AF%B7%E7%A0%81-%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/028
- 社区便民集市的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%EF%BD%9Ewelcome%E9%82%80%E8%AF%B7%E7%A0%81-%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/ueq
- 城市夜间照明的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%EF%BD%9Ewelcome%E9%82%80%E8%AF%B7%E7%A0%81-%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/0ja
- 城市文明实践的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%EF%BD%9Ewelcome%E9%82%80%E8%AF%B7%E7%A0%81-%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/066=iah
- 个人信息保护的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%EF%BD%9Ewelcome%E9%82%80%E8%AF%B7%E7%A0%81-%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/hpq=761
- 个人时间管理的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%EF%BD%9Ewelcome%E9%82%80%E8%AF%B7%E7%A0%81-%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/UdS=Cus
- 家庭节能设备的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/517
- 乡村文化空间的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/fgo
- 线上办事服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/N7m
- 绿色办公实践的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/777=rkm
- 旧物循环利用的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/vnq=719
- 社区绿色空间的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E4%BB%80%E4%B9%88-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/PJd=74R
- 社区环保活动的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/315
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/aqn
- 社区知识分享的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zhN
- 青少年心理健康的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/986=jck
- 居家适老化改造的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ckz=576
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB-%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/G5c=Eqn
- 便民信息查询的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/262
- 家庭用电安全的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/dhp
- 老年人文化生活的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/MP3
- 本地消费场景的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/769=bss
- 家庭用电安全中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/xre=617
- 青少年心理健康的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%94%B3%E8%AF%B7%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E5%9C%A8%E5%93%AA%E9%87%8C-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/I8u=GEi
- 开放数据应用的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A%E5%A5%BD%E5%90%83-%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/188
- 居家防滑改造的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A%E5%A5%BD%E5%90%83-%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/jgm
- 学校食育活动的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A%E5%A5%BD%E5%90%83-%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/e0a
- 数字支付体验的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A%E5%A5%BD%E5%90%83-%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/743=eax
- 公共服务数字化的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A%E5%A5%BD%E5%90%83-%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/ktx=679
- 社区公共议事的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A%E5%A5%BD%E5%90%83-%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/Uf2=HWZ
- 读书会组织的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/734
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/qzo
- 文明养宠科普的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/zUe
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/738=jsv
- 社区信息发布的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/ahj=037
- 公共空间休憩的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%BB%80%E4%B9%88-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/qe8=lhA
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/450
- 乡村教育资源的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/ggf
- 基层健康档案的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/yLI
- 老年人出行服务的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/887=brr
- 城市文化路线的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/lxa=550
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/Pxx=LKp
- 社区信息发布的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91-%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/534
- 基层服务创新的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91-%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/kaj
- 城市步行环境中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91-%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/HxX
- 数字素养提升的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91-%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/250=hof
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91-%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/psp=384
- 通勤路线规划的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91-%E8%99%8E%E5%97%85%E7%A4%BE%E5%8C%BA?/vZg=AWW
- 青少年科普实践的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91weco%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/477
- 日常摄影记录的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91weco%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/wvv
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91weco%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/toR
- 本地消费场景的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91weco%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/473=nso
- 小区停车协商的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91weco%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/owa=106
- 读书会组织的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91weco%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/0TO=iO1
- 开放数据应用的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/050
- 城市博物馆活动的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/zkb
- 家庭养老规划的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/VM2
- 基层服务创新的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/130=jdg
- 城市人文观察的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/xdh=378
- 公共空间照明的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/hcM=I8M
- 家庭安全提示的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80-%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/328
- 无障碍信息设计的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80-%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/gmr
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80-%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/AoA
- 机器人科普活动的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80-%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/677=oot
- 城市体育设施的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80-%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/egj=304
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80-%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/UJg=hQx
- 健康信息获取的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91-%E8%85%BE%E8%AE%AF%E4%BD%93%E8%82%B2?/419
- 城市夜间生活中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91-%E8%85%BE%E8%AE%AF%E4%BD%93%E8%82%B2?/gwl
- 口袋公园建设的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91-%E8%85%BE%E8%AE%AF%E4%BD%93%E8%82%B2?/Own
- 社区儿童活动的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91-%E8%85%BE%E8%AE%AF%E4%BD%93%E8%82%B2?/923=ben
- 城市人文观察的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91-%E8%85%BE%E8%AE%AF%E4%BD%93%E8%82%B2?/yeb=660
- 食品配送体验的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91APP%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91-%E8%85%BE%E8%AE%AF%E4%BD%93%E8%82%B2?/ldE=eSP
- 家庭收纳实践的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/975
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/kwc
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/dR3
- 全民阅读推广的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/684=pse
- 社区阅读服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/yna=080
- 个人时间管理的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/Ziv=c5w
- 社区运动空间的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/134
- 新能源出行的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/aod
- 居民健康教育的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/tN5
- 日常摄影记录的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/682=smc
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/nss=662
- 街区道路维护的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/ExB=YJH
- 物业服务沟通的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/327
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/icb
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/ciY
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/084=ves
- 家庭安全提示的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/uua=366
- 文化讲座服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/HF7=xmr
- 骑行路线规划的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/741
- 老年友好服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/bnk
- 校园社团活动的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/Bu2
- 社区健康讲座的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/920=xlf
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/qeu=174
- 城乡交流活动的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81-%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/wWX=bPs
- 基层健康档案的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97-%E5%87%A4%E5%87%B0?/289
- 家庭消费规划的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97-%E5%87%A4%E5%87%B0?/nny
- 城市应急科普的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97-%E5%87%A4%E5%87%B0?/KTX
- 社区文化传播的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97-%E5%87%A4%E5%87%B0?/386=zls
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97-%E5%87%A4%E5%87%B0?/cue=285
- 农产品品牌传播的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E8%B5%9A%E9%92%B1%E5%90%97-%E5%87%A4%E5%87%B0?/wKB=efK
- 城市步行环境的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/014
- 社区教育资源的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/bod
- 社区应急准备有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/B14
- 口袋公园建设的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/563=hsd
- 公共空间休憩的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/lxx=283
- 生活垃圾减量的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E6%8B%9B%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/3rb=MX0
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/217
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/qhr
- 公共交通接驳的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/CZm
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/267=xhg
- 生活技能分享的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/jsc=275
- 城市农夫市集的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/3rA=GOv
- 骑行路线规划的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/966
- 儿童户外活动的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/hjp
- 乡村电商实践的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/XqE
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/902=qyn
- 儿童运动体验中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/ltw=738
- 老年学习活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E9%83%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%89%E9%98%B2?/RgP=7i6
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/875
- 亲子阅读活动的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/ejk
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/hUp
- 城市应急广播的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/632=ofw
- 数字创意课程的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/mfu=123
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/KN3=nNd
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/668
- 志愿服务平台的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/nts
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/Puf
- 社区公共议事的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/454=car
- 公共场所导视的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/frs=821
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%81%9A-%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/aV0=O6N
- 城市公共艺术的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F-%E6%90%9C%E7%8B%97%E5%AE%B6%E5%B1%85?/057
- 无障碍信息设计的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F-%E6%90%9C%E7%8B%97%E5%AE%B6%E5%B1%85?/vfa
- 科学教育活动的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F-%E6%90%9C%E7%8B%97%E5%AE%B6%E5%B1%85?/8yy
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F-%E6%90%9C%E7%8B%97%E5%AE%B6%E5%B1%85?/745=ofh
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F-%E6%90%9C%E7%8B%97%E5%AE%B6%E5%B1%85?/isq=737
- 社区便民服务的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%8A%A0%E7%9B%9F-%E6%90%9C%E7%8B%97%E5%AE%B6%E5%B1%85?/vHB=7Ob
- 社区庭院绿化的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/703
- 城市树木认养的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/ico
- 居家防滑改造的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/uVN
- 读书会组织的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/803=xcl
- 基层健康服务的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/lgm=177
- 文明养宠科普的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8F%90%E4%BE%9B%E6%8A%80%E6%9C%AF%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/vmt=vth
- 机器人科普活动的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97-36%E6%B0%AA%E9%A3%9F%E5%93%81?/485
- 城市公共厕所的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97-36%E6%B0%AA%E9%A3%9F%E5%93%81?/oyb
- 校园安全教育的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97-36%E6%B0%AA%E9%A3%9F%E5%93%81?/1GS
- 社区儿童活动的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97-36%E6%B0%AA%E9%A3%9F%E5%93%81?/745=ecw
- 租房信息服务的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97-36%E6%B0%AA%E9%A3%9F%E5%93%81?/jue=807
- 公园亲子设施的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E5%90%88%E6%B3%95%E5%90%97-36%E6%B0%AA%E9%A3%9F%E5%93%81?/6wK=Sgt
- 机器人科普活动的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/354
- 公共设施使用中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/xvq
- 便民维修服务的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/kDe
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/353=jyi
- 口袋公园建设中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/mcg=008
- 数字学习资源的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%90%84%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81-%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/0Dn=yHm
- 家庭阅读计划的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91-%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/421
- 公共服务数字化的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91-%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/eol

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
