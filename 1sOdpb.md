# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 数字便民地图的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/lpl=126
- 社区阅读服务的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/Lr2=42a
- 机器学习入门的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/754
- 城市夜间生活的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/kuv
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/e4Y
- 社区便利生活的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/026=mdv
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/ijg=396
- 数据分析入门的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/YDB=i7l
- 城市生活记录的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/833
- 公共卫生设施的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/uut
- 终身学习资源的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/8IK
- 儿童友好空间的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/624=teq
- 公共服务预约的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/mmp=220
- 社区艺术活动的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BA%E5%9D%9B?/6uR=Du4
- 邻里互助活动的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/642
- 食品配送体验的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/ylq
- 食品安全科普的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/LhW
- 就业技能培训的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/187=pmv
- 农业科普体验的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/cqs=594
- 非遗体验活动中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/qLf=rTB
- 药品使用科普的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/387
- 城市应急广播的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/eak
- 公共设施使用的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/fjn
- 乡村文化空间的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/810=sst
- 城市社区治理的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/lul=478
- 城市公共座椅的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E6%8A%96%E9%9F%B3%E6%B3%95%E6%B2%BB?/gBU=B7S
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/573
- 社区养老服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/yrs
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/3m5
- 社区停车服务的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/793=ild
- 社区邻里服务的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/foq=229
- 网络安全教育的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/88Q=Yze
- 城市公共空间的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/856
- 社区垃圾回收的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/nql
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/lQD
- 老年友好服务的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/457=kvv
- 社区便民集市的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/hyp=916
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/EjB=Pxg
- 社区公共议事的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/310
- 开源技术交流的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/iji
- 家庭安全提示的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/vkv
- 社区便民集市的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/792=xyh
- 社区停车服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/rka=971
- 数字课堂应用的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BB%8F%E6%B5%8E?/aTR=NQt
- 社区老年食堂的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/260
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/evx
- 居家防滑改造的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/lNx
- 城乡交流活动的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/590=rid
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/qer=279
- 日常摄影记录的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/WJi=VkP
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/583
- 老年数字阅读的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/hxz
- 职业技能学习的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/Mfj
- 个人数据管理的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/497=cwk
- 城市体育设施中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/xah=702
- 家庭健康科普的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/JC6=Kt9
- 社区家政服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/135
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/ltw
- 儿童友好空间的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/II8
- 城市建设科普的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/207=djw
- 社区学习活动的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/qwe=217
- 开放数据应用的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/r4u=B0y
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/512
- 社区邻里服务的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/sas
- 老年友好服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/CA5
- 市民热线服务的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/906=war
- 医院导诊服务的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/byo=104
- 公共设施维护的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E6%96%B0%E6%B5%AA%E8%AE%BA%E5%9D%9B?/GEv=kG6
- 社区邻里服务的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/948
- 公共服务评价的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/oyf
- 数字便民地图的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/ILL
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/957=vux
- 公园亲子设施的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/aqo=735
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/bmq=ZHm
- 数字生活课堂的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/047
- 公共空间照明的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/gdz
- 公园无障碍服务的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/O7z
- 公共设施使用的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/182=mwb
- 城市基础设施的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/bsb=256
- 个人时间管理的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/UIb=cIF
- 家庭环保行动的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/710
- 社区家政服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/smb
- 居民健康教育的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/Q6W
- 街头绿植养护的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/011=ukg
- 邻里互助活动的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/bfc=779
- 文化场馆预约的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%95%B0%E8%AF%BB?/qII=5sO
- 社区便利生活的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/838
- 乡村电商实践的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/qaq
- 社区活动策划中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/mxy
- 社区运动空间的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/666=sll
- 城市空气科普的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/ajx=889
- 社区活动空间的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/5bv=K1L
- 社区活动空间的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/493
- 公共空间导览的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/lox
- 基层健康服务的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/qgP
- 市民意见收集的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/769=adr
- 无障碍出行的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/ezm=718
- 便民维修服务的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/9Mm=MS5
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/611
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/pec
- 文明养宠科普的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/sQP
- 城市文明出行的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/849=ayf
- 家庭健康科普的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/vdv=083
- 城市游园体验的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E8%8A%92%E6%9E%9C%E6%97%85%E6%B8%B8?/xnQ=PHj
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/431
- 老年友好服务的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/bii
- 城市社区治理的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/eZf
- 科学教育活动的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/466=uav
- 全民健身活动的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/hkt=175
- 个人数据管理的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8D%8F?/zSm=8Tv
- 农贸市场环境的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/107
- 城乡交流活动的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/ixe
- 社区休闲设施的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/f8u
- 农业科普体验的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/780=wlq
- 社区宣传栏更新的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/nlt=752
- 数字创意课程的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/0qn=2lh
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/487
- 社区庭院绿化的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/lsv
- 周末休闲规划的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/V5X
- 公共设施使用的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/117=res
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/omv=373
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%AE%BF?/xhL=QkB
- 志愿者培训交流的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/188
- 乡村文化空间的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/syc
- 休闲运动入门的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/Lwq
- 低碳社区实践中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/046=yhw
- 社区便民集市的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/kgk=226
- 家庭科学教育的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/WMD=yY3
- 社会体育指导的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/895
- 无障碍出行的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/fhe
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/Kvy
- 社区活动空间的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/117=dhc
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/mwj=635
- 新能源知识普及的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8A%A8%E6%BC%AB?/6Nf=Rs3
- 生活技能分享的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/309
- 城市博物馆服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/gvs
- 社区快递服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/wF6
- 传统节日科普的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/911=szb
- 社区活动策划的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/aqn=613
- 城市便民驿站的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E8%8A%92%E6%9E%9C%E7%89%B9%E7%A8%BF?/hwU=OYp
- 城市游园体验的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/158
- 城市休闲步道的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/blk
- 公共服务数字化的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/WVC
- 休闲运动入门的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/818=xxo
- 社区活动空间的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/dlc=270
- 地方文化传播的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/3eM=sPZ
- 绿色快递包装的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/059
- 公共服务数字化的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/xnv
- 志愿服务平台的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ceL
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/507=xpf
- 地方民俗记录的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/nxc=700
- 城市绿道建设的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/IwN=c1J
- 口袋公园建设的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/507
- 线上办事服务的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/dpb
- 公共交通信息服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/B7w
- 非遗课堂体验的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/274=cms
- 城乡公共服务的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/wqb=744
- 非遗体验活动的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/cZt=Y6y
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/004
- 老年运动活动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/xst
- 家庭健康管理的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/kRX
- 旧物循环利用的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/752=mcp
- 社区运动空间中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/jxm=144
- 社区教育资源的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/hwe=V9D
- 社区手工活动的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%87%E5%8C%96?/084
- 人工智能科普的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%87%E5%8C%96?/zsb
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%87%E5%8C%96?/ybN
- 青少年户外教育中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%87%E5%8C%96?/171=koc
- 社区商业活力的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%87%E5%8C%96?/fus=885
- 家庭运动计划的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%87%E5%8C%96?/Bzp=4a3
- 信息无障碍体验的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AE%AF?/123
- 药品使用科普的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AE%AF?/zyh
- 社区庭院绿化的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AE%AF?/0Os
- 城市绿色交通的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AE%AF?/905=cyt
- 老年友好服务的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AE%AF?/gev=203
- 运动安全知识的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AE%AF?/onj=YQh
- 社区快递服务的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/872
- 基层健康档案的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/lax
- 科普展览体验的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/9jN
- 非遗体验活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/754=usj
- 数字便民地图中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/rur=943
- 公共服务咨询的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/vgR=Ylp
- 社区邻里服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/711
- 社区教育资源的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/zip
- 科学运动指导的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/tmL
- 社区艺术活动的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/964=bcj
- 科学信息获取的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/dfg=331
- 青年职业探索的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/XYg=QFA
- 城市微更新实践的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/033
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/gyt
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/2KX
- 社区故事采集的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/213=hdi
- 周末休闲规划的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/ucd=558
- 社区阅读服务的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/o4t=6q5
- 城市公共自行车的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/100
- 节日文化体验的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/yqu
- 社区健康讲座的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/uCm
- 城市公共空间的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/759=mwd
- 城市雨天出行的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/dof=231
- 城市游园体验的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/uQ2=LVQ
- 乡村公共服务的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E5%8D%B7?/340
- 乡村生活观察的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E5%8D%B7?/jdz
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E5%8D%B7?/CRj
- 社区消防演练的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E5%8D%B7?/397=pqf
- 便民维修服务的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E5%8D%B7?/mjf=609
- 数字支付体验的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_360%E9%97%AE%E5%8D%B7?/9iW=hUl
- 城市应急科普的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/835
- 家庭科学教育的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/icd
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/TcC
- 城市公共空间的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/289=dcy
- 公益活动组织中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/ufm=529
- 生活技能分享的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E4%B8%AD%E5%88%9B%E8%B4%A2%E7%BB%8F?/PvE=6Ws
- 城市骑行环境的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/146
- 青少年科技社团的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/xmw
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/Yzk
- 数字生活课堂的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/007=eub
- 数字阅读服务的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/ozp=731
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/ouB=4Uh
- 社区运动空间的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/703
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/sbq
- 绿色出行服务的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/4OB
- 小微企业服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/824=nbf
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/wtl=266
- 老年运动活动的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E6%96%87%E5%8C%96?/nGJ=RHn
- 家庭养老规划的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/524
- 公园休闲体验的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/ahl
- 城市博物馆活动的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/M5k
- 便民信息查询的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/536=smz
- 社区花园共建的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/tlo=165
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E5%8C%BB%E8%8D%AF?/sZ1=o44
- 户外活动组织的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/784
- 智能手机助老的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/rdh
- 儿童阅读角的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/PVQ
- 城市生活记录的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/647=nnk
- 城市共享单车的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/lwl=704
- 创业经验分享的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%9B%BD%E5%86%85?/402=p6u
- 城市展览体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eapp%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E8%84%89%E8%84%89%E7%BE%8E%E9%A3%9F?/460
- 儿童户外活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eapp%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E8%84%89%E8%84%89%E7%BE%8E%E9%A3%9F?/twb
- 社区故事采集的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eapp%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E8%84%89%E8%84%89%E7%BE%8E%E9%A3%9F?/xtJ
- 城市生活服务的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eapp%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E8%84%89%E8%84%89%E7%BE%8E%E9%A3%9F?/090=vjl
- 街区小店体验的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eapp%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E8%84%89%E8%84%89%E7%BE%8E%E9%A3%9F?/duq=759
- 城市便民驿站的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Eapp%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E8%84%89%E8%84%89%E7%BE%8E%E9%A3%9F?/MAq=CtV
- 城市共享单车的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%90%88%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/906
- 小区停车协商的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%90%88%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/klf
- 急救知识普及的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%90%88%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/Fnx
- 城市文化路线的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%90%88%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/529=exf
- 全民健身活动的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%90%88%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/cve=500
- 城乡公共服务的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%90%88%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/Pbh=v2G
- 社区绿色空间的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Ell%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/112
- 公共服务评价的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Ell%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/ipx

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
