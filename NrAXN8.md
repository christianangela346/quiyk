# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 家庭环保习惯的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/VJc
- 居民健康教育的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/622=kyx
- 租房信息服务的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/uzl=534
- 城市运动公园的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E5%BD%B1%E8%A7%86?/VY3=Vt7
- 家庭收纳实践的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/049
- 乡村阅读空间的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/rrq
- 城市运动公园的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/qJa
- 社区安全巡查的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/129=osq
- 家庭网络使用的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/ntw=093
- 市民热线服务的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%99%BE%E7%9B%88%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/Jr9=Bjq
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/953
- 食品安全科普的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ucv
- 公共空间导览的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/JqQ
- 科学观察活动的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/206=ciq
- 文化场馆预约的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/fwu=155
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/SWt=6AE
- 本地历史资料的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%88%8A%E7%99%BB?/199
- 城市公共艺术的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%88%8A%E7%99%BB?/nir
- 线上阅读资源的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%88%8A%E7%99%BB?/bH6
- 本地旅行体验的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%88%8A%E7%99%BB?/076=cvv
- 城市夜间生活的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%88%8A%E7%99%BB?/owz=364
- 租房信息服务的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80_36%E6%B0%AA%E5%88%8A%E7%99%BB?/wev=Hpy
- 小区停车协商的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/299
- 城市运动公园的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/dzc
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/PgF
- 数字生活课堂的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/016=que
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/lte=862
- 小微企业服务的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E8%A1%8C%E6%83%85?/FIU=q3z
- 社区消防演练的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/965
- 社区安全巡查的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/cdg
- 城市游园体验的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/Mvk
- 儿童运动体验的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/911=lkw
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/imh=052
- 社区学习活动的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8APP%E5%AE%89%E8%A3%85%E5%8C%85_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/bki=QTU
- 新能源出行的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/904
- 节日文化体验的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/npl
- 街区道路维护的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/Psk
- 科学健身方法的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/704=tqn
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/grq=552
- 社区共享书架的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%AE%A4%E8%AF%81%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/TSr=YaK
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/391
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/cle
- 公共服务指南的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/2Qv
- 儿童户外活动的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/893=mcc
- 校园社团活动的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/bbm=266
- 数字生活课堂的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%89%E9%98%B2?/1Ua=0JT
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/210
- 乡村教育资源的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/szi
- 社区停车服务的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/YuA
- 城市绿道建设的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/363=rtc
- 城市公共厕所的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/ttm=088
- 智能手机助老的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E4%B8%80%E5%88%86%E5%BF%AB3_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/x19=sgn
- 节假日出行安排的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/240
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/rxk
- 乡村生活观察的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/FwM
- 社区垃圾回收的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/190=kkv
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/xaw=344
- 老年数字阅读的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/PxR=OMz
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/849
- 乡村文化空间的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/wxm
- 绿色出行服务的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/7oT
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/595=loy
- 安全出行教育的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hln=829
- 科学运动指导的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/e1f=jo7
- 文化场馆预约的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/478
- 城市地名文化的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/edc
- 街区道路维护的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/6uG
- 数字档案服务的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/974=gun
- 数字艺术创作的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/jih=866
- 数字学习资源的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/gmb=dHW
- 社区设施共享的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/966
- 物业服务沟通的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/iue
- 租房信息服务的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/peD
- 健康信息获取的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/939=vrj
- 社区停车服务的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/exr=019
- 社区协商议事的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%9C%8D%E5%8A%A1%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/4v0=NGL
- 公共健身器材的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E5%B1%85?/528
- 软件开发学习的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E5%B1%85?/yje
- 生活服务数字化的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E5%B1%85?/LZo
- 便民信息查询的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E5%B1%85?/868=vuj
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E5%B1%85?/wyt=552
- 灵活就业交流的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E5%BD%A9%E7%A5%A8_360%E5%AE%B6%E5%B1%85?/biI=UhK
- 居家适老化改造中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/326
- 城市便民驿站的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/nif
- 健康饮食教育的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/9As
- 健康步道使用的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/911=dii
- 科学观察活动的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/lzr=730
- 社区心理支持的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%BD%B0%E5%AF%8C%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/6xf=Yfx
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/555
- 青年职业探索的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/lpt
- 家庭用电安全的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/CsK
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/780=cfk
- 社区教育资源的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/tis=937
- 公共交通接驳的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%BD%B0%E5%AF%8C%E5%BD%A9_welcome_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/Cvq=BgV
- 公共交通接驳的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/445
- 乡村教育资源的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/fxd
- 数字政务体验的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/AfA
- 生活服务数字化的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/469=irr
- 基层服务创新的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/ldc=013
- 公交站点体验的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_360%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/ITG=GhM
- 社区公共卫生的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/639
- 儿童安全出行的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/wbz
- 家庭环保行动的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/A5p
- 食品配送体验的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/328=gaz
- 药品使用科普的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/kdb=928
- 社区应急准备的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E5%AF%8C%E5%BD%A9%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85%E6%AC%A2%E8%BF%8E%E6%82%A8_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/GLi=dJM
- 科学健身方法的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/612
- 健康步道使用的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/foe
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/cHX
- 社区快递服务的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/200=wmx
- 文化讲座服务的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/ala=446
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%BD%B0%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E6%9C%ACapp_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/VIn=It1
- 节约用水实践的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/568
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/qin
- 乡村电商实践的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/b6n
- 城市公共空间的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/098=fdj
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/hdh=786
- 文化讲座服务的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91APP_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/PjQ=9he
- 健康信息获取的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/383
- 城市步行友好的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/urv
- 城市住房服务的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/FcX
- 居家防滑改造的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/202=vcr
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/gwi=854
- 休闲运动入门的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%9B%86?/Uma=d3A
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/953
- 城市地名文化的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/jtf
- 社区运动空间的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/gEP
- 农业科普体验的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/881=kzn
- 邻里共享空间的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/tmc=719
- 老年智能设备的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_U7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/aMh=QUg
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/926
- 环境监测科普的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/zuz
- 市民意见收集的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/Pqv
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/307=ddg
- 老年友好服务中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/tkb=600
- 城市公共饮水的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/4Fv=0Ot
- 乡村生活观察的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/703
- 儿童友好街区的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/poq
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/TrT
- 家庭环保行动的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/842=ydz
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/uhn=157
- 城市雨天出行的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A5%A8?/P9T=hSw
- 社区互助网络的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/622
- 医院导诊服务的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/pjn
- 光伏知识科普中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/uGB
- 社区环保活动的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/590=wqr
- 城市体育设施的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/gpj=733
- 学校体育活动的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%B1%BD%E8%BD%A6?/IyD=UAJ
- 数字创意课程的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/858
- 家庭科学教育的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/fzh
- 数字便民地图的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/CRm
- 社区互助网络的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/572=olf
- 亲子阅读活动的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/xbn=248
- 绿色办公实践的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/T8p=BSE
- 社区共享书架的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/165
- 城市体育设施的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/mfy
- 职业技能学习的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/sAX
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/939=plb
- 城市公共艺术的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/jcl=218
- 数字生活课堂的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/KMK=e79
- 志愿服务平台的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/725
- 食品安全科普的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/txh
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/iO2
- 非遗体验活动的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/643=fee
- 公共设施维护的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/jvz=354
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BD%B0%E8%B5%A2%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/KPL=rOm
- 生活服务数字化的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/664
- 社区商业活力的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/wmy
- 社区环保活动的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/TwX
- 安全出行教育的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/610=hnl
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/wvi=644
- 农村环境治理的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/Lpg=9OF
- 乡村产业科普的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/253
- 老年运动活动的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/lou
- 儿童安全出行的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/Skr
- 公园休闲体验的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/611=xrv
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/zhw=397
- 社区消防演练的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/0HZ=uCD
- 公共服务指南的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/309
- 城市住房服务的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/qpx
- 社区商业活力的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/oeM
- 本地旅行体验的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/379=vhk
- 全民健身活动的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/rvf=624
- 居家防滑改造中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app%E6%AD%A3%E8%A7%84_%E5%8D%B3%E5%88%BB%E5%8F%B8%E6%B3%95?/McB=U55
- 数字素养提升的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/790
- 农业科普体验的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/jwj
- 社区快递服务的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/cUy
- 城市适老服务的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/117=jea
- 社区共享书架的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/uik=356
- 乡村文化空间的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E5%88%B8%E5%95%86?/UXE=CCF
- 终身学习资源的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/066
- 数字阅读服务的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/lrk
- 光伏知识科普的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/fgR
- 社区体育组织的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/788=oxv
- 社区互助网络的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/qmm=442
- 智能手机助老的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BA%AA%E5%AE%9E?/2gm=RZp
- 社区公共卫生中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/723
- 文明养宠科普的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/dpu
- 城市公共厕所的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/P00
- 网络安全教育的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/177=yvd
- 休闲运动入门的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/imz=427
- 消防知识宣传的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/SOz=fzW
- 就业技能培训的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/807
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/jxe
- 绿色办公实践的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/zzP
- 智慧停车服务的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/221=fdm
- 乡村生活观察中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/ebj=337
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-welcome500%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%AE%B2%E5%9D%9B?/5NR=Kel
- 城市应急科普的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/998
- 乡村生活观察的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/iko
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/weX
- 城市可持续生活的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/829=deq
- 老年学习活动的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/npi=842
- 口袋公园建设的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%AE%9D%E9%A9%AC%E4%BC%9A-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E6%8A%A5?/aRo=9NI
- 人工智能科普的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/444
- 社区体育组织的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/hvx
- 农产品品牌传播的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/SVH
- 社区防暑服务的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/008=eba
- 社区志愿服务的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/bqr=332
- 家庭消费规划的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AE%9D%E9%A9%AC%E4%BC%9A-welcome%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/HKR=NMg
- 垃圾分类指导的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/031
- 社区停车服务中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/inj
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/6GM
- 本地消费场景的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/440=jjr
- 节约用水实践的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/gyy=661
- 社区安全巡查的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9welcome_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8D%8F?/9Uz=hDs
- 城市文明出行的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/460
- 个人时间管理的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/ctd
- 食品配送体验的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/bWt
- 社区活动空间的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/547=ibj
- 社区庭院绿化的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/jzh=424
- 社区绿色空间的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AE%9D%E9%A9%AC%E4%BC%9A%E5%BD%A9%E7%A5%A8-app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/ZRU=C1g
- 应急物资管理的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E8%A7%82%E7%82%B9?/568
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E8%A7%82%E7%82%B9?/arw
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E8%A7%82%E7%82%B9?/WPv
- 城市文明实践的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E8%A7%82%E7%82%B9?/813=ysx
- 街头绿植养护的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E8%A7%82%E7%82%B9?/srq=099
- 公共服务咨询的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E8%A7%82%E7%82%B9?/2Vs=x2t
- 科学运动指导的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/216
- 社区活动空间的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/kbp
- 物业服务沟通的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/9tg
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/858=mhr
- 儿童运动体验的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/aiw=094
- 通勤路线规划的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%85%E8%B5%A2%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/kPG=Wi4
- 社区活动策划的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/490
- 家庭环保行动的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/cem
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/LMP
- 社区停车服务的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/456=ubu
- 家庭消费规划的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/uem=113
- 城市步行友好的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/32b=jLm

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
