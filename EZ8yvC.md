# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 儿童安全出行的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/oly=731
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/pEo=2nS
- 城市建设科普的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/162
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/rfp
- 家庭消费规划的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/p8C
- 城市环境志愿行动的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/765=ldk
- 老年人日常照护的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/czp=694
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/ZKR=cRA
- 社区慢性病防控的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/757
- 青少年心理健康的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/pqs
- 校园阅读活动的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/fZ4
- 小微企业服务的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/835=okh
- 骑行路线规划的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/ydp=005
- 老年人文化生活的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%A8%B1%E4%B9%90?/mnM=h9R
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/582
- 老年数字阅读的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/cly
- 在线学习体验的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/lUR
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/279=hsj
- 城市树木认养的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/nvl=060
- 城市绿道建设的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/9qV=Dgk
- 公共设施使用的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/672
- 社区消防演练的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/mdn
- 安全出行教育的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/A7s
- 社区家校合作的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/844=umi
- 绿色出行服务的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/ine=079
- 公交无障碍服务的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/wBh=i4B
- 家庭节能设备的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/448
- 图书借阅体验的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/cpj
- 乡村阅读空间的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/lJM
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/735=ypr
- 志愿者培训交流的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/ghx=390
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8Welcomee_%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/kIZ=YOS
- 智慧停车服务的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/100
- 公共场馆服务的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/tzr
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/ZIu
- 医院导诊服务的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/189=zsy
- 城市公共座椅的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/pal=845
- 城市噪声观察的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9--%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/dzb=uVk
- 公共卫生设施的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/468
- 社区休闲设施的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/tty
- 公共空间导览的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/5u3
- 应急物资管理的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/798=awd
- 家庭健康管理的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/lgb=691
- 数字学习资源的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/Zqh=d0F
- 食品配送体验的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/520
- 社区商业活力的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/qjd
- 社会体育指导的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/loj
- 绿色快递包装的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/475=opm
- 家庭用电安全的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/fbh=428
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/AHC=Zzg
- 读书会组织的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8C%BB%E8%8D%AF?/099
- 节假日出行安排的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8C%BB%E8%8D%AF?/kyr
- 小微企业服务的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8C%BB%E8%8D%AF?/51O
- 社区环保活动的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8C%BB%E8%8D%AF?/801=vfe
- 社区志愿服务的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8C%BB%E8%8D%AF?/hvp=192
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A85988.com_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8C%BB%E8%8D%AF?/kvP=6lw
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/377
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/okv
- 学校食育活动的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/KSY
- 亲子科普活动的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/158=vyt
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/dhs=831
- 数字设备回收的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/FsW=CPj
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/732
- 城市空气科普的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/vfr
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/zgB
- 城市共享单车的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/148=rhz
- 数字资源检索的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/lqg=301
- 智能手机助老的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/Xdo=NWE
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/848
- 数字生活课堂的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/ygu
- 在线学习体验的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/ywA
- 劳动教育实践的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/299=ljq
- 节假日出行安排的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/pim=320
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/eLX=Tqa
- 家庭食品保存的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/424
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/pab
- 街区道路维护的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/uE1
- 青少年户外教育的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/009=opr
- 社区家校合作中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/lev=997
- 青年就业服务的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90_%E7%99%BE%E5%BA%A6%E8%B5%84%E8%AE%AF?/1to=TBw
- 城市休闲步道的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/569
- 网络安全教育的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/beg
- 个人时间管理的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/zFy
- 在线学习体验的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/476=rnz
- 公共设施使用的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/ono=176
- 公共服务指南的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88%E7%9A%84_%E7%95%8C%E9%9D%A2%E7%BE%8E%E5%A6%86?/t6l=Tat
- 社区便民集市的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/531
- 科技馆参观体验的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/pbu
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/Tzu
- 数字便民地图的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/749=exq
- 数字素养提升的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/jus=729
- 地方民俗记录的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8-%E6%AD%A3%E8%A7%84_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/BYX=4kt
- 校园节能行动的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/445
- 学校体育活动的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/ssj
- 信息无障碍体验的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/eyY
- 机器学习入门的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/332=rgo
- 儿童友好空间的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/ljk=590
- 社区生活指南的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/lQ5=JJw
- 儿童友好空间的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/700
- 信息无障碍体验的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/arq
- 家庭消费规划的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/WFU
- 城市建设科普的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/220=oqx
- 家庭网络使用的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/dha=597
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/a4w=lCR
- 居家适老化改造的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/304
- 家庭节能实践的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/wua
- 城乡交流活动的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/ad4
- 家庭环保习惯的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/587=jrw
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/zlq=839
- 城市应急广播的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%89%8B%E6%9C%BA%E7%89%88%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A8%8E%E5%8A%A1?/Nyf=oPC
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/538
- 邻里互助活动的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/alf
- 文化场馆预约中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/tH0
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/621=cad
- 课后服务体验的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/ehx=917
- 乡村产业科普的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/t5c=3To
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/005
- 网络安全教育的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/bfs
- 无障碍信息设计的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/kHU
- 社区快递服务的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/421=zgv
- 社区阅读服务的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/fnj=525
- 市民热线服务的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E6%89%80%E6%9C%89%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E8%B5%B0%E5%8A%BF%E5%9B%BE2%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/ORW=frw
- 家庭安全提示的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/551
- 公共空间照明的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/uoq
- 社区健康讲座的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/Qc1
- 街头绿植养护的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/435=zgz
- 街区道路维护的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/qgj=901
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E9%A3%8E%E5%BD%A9%E7%BD%91%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83%E6%9D%80%E5%8F%B7%E5%AE%9A%E8%83%86%E6%B1%87%E6%80%BB%E5%8E%9F%E5%88%9B%E5%AD%97%E8%B0%9C_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/fDE=W8b
- 社区教育资源的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/147
- 数字地图应用的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/kvl
- 邻里互助活动的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/NUp
- 城市应急广播的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/644=osk
- 文化讲座服务的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/auo=970
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%8E%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/KNY=fJC
- 节约用水实践的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/913
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/iqu
- 社区活动策划的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/BQ6
- 居家适老化改造的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/476=ghw
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/kwc=264
- 城市生活服务的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/jLc=l9o
- 市民热线服务的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/989
- 开源技术交流的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/aff
- 社区环保活动的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/pMs
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/364=hcl
- 社区花园共建中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/rqg=005
- 公共空间安全的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%B9%BF%E8%A5%BF%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/pdR=jHt
- 数字设备回收的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/525
- 数字创意课程的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/qgo
- 社区菜市场服务的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/8PF
- 家庭节能设备的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/223=pyw
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/vlw=285
- 城市体育设施的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_3d%E6%B5%99%E6%B1%9F%E9%A3%8E%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/Sgw=Yk2
- 数字学习资源的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/471
- 城市骑行环境中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/jah
- 社区安全巡查的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/PiS
- 乡村公共文化的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/565=ggr
- 基层医疗预约的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/pzf=662
- 家庭饮食安排的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E9%A3%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%AF%E8%82%A1?/R5Y=ZhS
- 周末休闲规划的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/928
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/lwf
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/mb4
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/162=qgk
- 乡村阅读空间的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/qll=399
- 生活技能分享的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0IVWelcome%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/2RW=H10
- 城市公共饮水的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/063
- 本地旅行体验的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/mvc
- 电动汽车充电的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/f0U
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/692=xqu
- 机器学习入门的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/cgx=558
- 社区垃圾回收中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-I%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/rNp=Wku
- 居民健康教育的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/455
- 口袋公园建设的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/drh
- 社区学习活动的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/q7i
- 亲子阅读活动的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/981=hxp
- 公共服务沟通的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/rnr=907
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%87%A4%E5%87%B0IV-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E6%B0%91%E7%94%9F?/QY4=oPi
- 城市便民驿站中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/740
- 电子商务服务的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/ebv
- 公共服务指南的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/NHs
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/679=epb
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/pwa=723
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/5Ax=54W
- 公共场所导视的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/330
- 社区活动策划的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/rsm
- 居家防滑改造中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/3dK
- 城市绿道建设的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/782=dtj
- 校园安全教育的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/wgr=940
- 老年人日常照护的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/Y6n=Ts8
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/696
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/fnh
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/xv1
- 科普展览体验的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/994=jjf
- 社区法律科普的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/obf=184
- 周末休闲规划的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-welcome_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/Oj4=nVX
- 城市空气科普的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/738
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/rsf
- 无障碍出行的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/aBV
- 社区菜市场服务的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/618=zfo
- 课后服务体验的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/mqq=448
- 乡村文化空间的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%9F%B3%E4%B9%90?/wx9=Yz6
- 城市可持续生活的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/653
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/sqg
- 家庭节能实践的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/0Mh
- 公共卫生设施的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/551=rgk
- 街头绿植养护的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/srd=702
- 城市夜间照明的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/QAT=uJh
- 社区学习活动的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/360
- 居民健康教育的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/sqm
- 在线教育体验的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/rV0
- 街头绿植养护的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/816=nsr
- 校园安全教育的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/efi=261
- 社区活动策划的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/bBo=1Pi
- 老年人文化生活的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/370
- 智能家居应用的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/esn
- 骑行路线规划的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/NiU
- 社会体育指导的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/224=qmz
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/wbn=883
- 社区垃圾回收的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E7%A7%BB%E5%8A%A8%E7%AB%AF%E4%BB%8B%E7%BB%8D_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/BvR=FYA
- 城市休闲步道的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/110
- 个人信息保护的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/sin
- 社区教育资源的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/kZT
- 公共场所导视的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/235=kaf
- 农业科普体验的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/lez=557
- 休闲运动入门中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8APP_%E5%8D%B3%E5%88%BB%E8%AE%B2%E5%9D%9B?/3Lx=0Y1
- 社区慢性病防控的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/615
- 社区艺术活动的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/pzv
- 公共设施维护的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/bbF
- 市民意见收集的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/560=hjf
- 公共交通接驳的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/dsh=996
- 健康步道使用的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%AE%A2%E6%9D%A5%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E5%93%AA_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/0lS=Op0
- 社区手工活动的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/228
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/mab
- 社区健康讲座的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/3QO
- 生成式工具使用的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/745=lha
- 健康步道使用的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/wpc=611
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9VIP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AE%BF%E8%B0%88?/GSe=tLi
- 城市公共标识中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/011
- 休闲运动入门的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/bhf
- 乡村生态观察的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/Zr7
- 城市适老服务的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/018=ewc
- 社区家校合作的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/wyo=180
- 数字政务体验的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9vip%E4%B8%93%E7%89%88_%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/htq=QMX
- 小区电梯维护的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/658
- 城市慢行系统的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/igw
- 城市体育设施的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/AVZ
- 线上阅读资源的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/849=xyb
- 网络信息辨识的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/hqq=648
- 学校食育活动中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9vip%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/RAZ=hZB
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9VIP-%E7%99%BB%E5%BD%95_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/530
- 市民热线服务的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9VIP-%E7%99%BB%E5%BD%95_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/uyx

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
