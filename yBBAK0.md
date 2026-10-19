# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:16**

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

- 社区绿色空间的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Ev11%E4%B8%8B%E8%BD%BDapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/570
- 数字设备回收的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Ev11%E4%B8%8B%E8%BD%BDapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/vhf
- 儿童安全出行的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Ev11%E4%B8%8B%E8%BD%BDapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/izB
- 公共健身器材的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Ev11%E4%B8%8B%E8%BD%BDapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/802=jeo
- 公交无障碍服务的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Ev11%E4%B8%8B%E8%BD%BDapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/hsg=766
- 亲子阅读活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9Ev11%E4%B8%8B%E8%BD%BDapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/Biv=7GQ
- 家庭健康科普中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/646
- 居民健康教育的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/ekm
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/QBQ
- 家庭用电安全的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/097=bjj
- 老年友好服务的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/wes=135
- 机器人科普活动的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/jW4=QtR
- 节假日出行安排的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Eapk%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/212
- 社区邻里服务的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Eapk%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/tel
- 居家防滑改造中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Eapk%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/gdb
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Eapk%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/832=ayl
- 气象科普传播的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Eapk%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/nzi=064
- 老年人文化生活的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Eapk%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%97%A5%E6%8A%A5?/qLQ=GNG
- 城市应急广播的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Capp_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/895
- 社区安全巡查的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Capp_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/mjh
- 社区花园共建的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Capp_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/fg4
- 社区老年食堂的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Capp_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/868=uxm
- 家庭环保习惯的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Capp_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/bzo=455
- 城市噪声观察的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9Capp_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/jVb=CEJ
- 非遗体验活动的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/192
- 城市绿色交通的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/wre
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/x99
- 社区庭院绿化的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/969=tfe
- 图书馆数字服务的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/kgr=197
- 老旧小区改造的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/6v6=JLt
- 老年运动活动的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/629
- 地方美食文化的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/wmm
- 数字艺术创作的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/bm2
- 青少年编程学习中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/659=xzy
- 环境教育课程中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/cjr=188
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/Y0y=cZM
- 社区信息发布的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6ios_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/799
- 基层健康服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6ios_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/yor
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6ios_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/GLh
- 智能手机助老的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6ios_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/287=hfv
- 线上办事服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6ios_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/syz=056
- 终身学习资源的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E8%BD%AF%E4%BB%B6ios_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/ESM=uuM
- 城乡交通衔接的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Elll%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/022
- 在线教育体验的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Elll%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/xyz
- 数字资源检索的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Elll%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/BNS
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Elll%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/364=puo
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Elll%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/nsn=303
- 儿童友好空间的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9Elll%E8%8B%B9%E6%9E%9C_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/wHL=I3I
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eiv%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/622
- 社区协商议事的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eiv%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/wff
- 城市共享单车的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eiv%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/oHl
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eiv%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/195=ejs
- 生活技能分享的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eiv%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/ztr=187
- 青年就业服务的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eiv%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/P7Y=o4q
- 机器人科普活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E1%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/545
- 居民健康教育的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E1%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/wwn
- 社区文化节活动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E1%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/i4u
- 老年人文化生活的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E1%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/694=mqd
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E1%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/xyx=730
- 个人时间管理的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E1%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%95%8C%E9%9D%A2%E6%A5%BC%E5%B8%82?/IhA=0YN
- 社区家政服务的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Elll%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/922
- 城市文化路线的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Elll%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/rif
- 数字公共文化的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Elll%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/jMt
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Elll%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/335=vpz
- 社区家政服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Elll%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/kxe=173
- 城市人文观察的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Elll%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%85%9A%E5%BB%BA?/hw5=u1f
- 乡村教育资源的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E8%80%81%E7%89%88%E6%9C%AC%E9%93%BE%E6%8E%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/467
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E8%80%81%E7%89%88%E6%9C%AC%E9%93%BE%E6%8E%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/cbg
- 儿童友好街区的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E8%80%81%E7%89%88%E6%9C%AC%E9%93%BE%E6%8E%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/PGk
- 在线教育体验的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E8%80%81%E7%89%88%E6%9C%AC%E9%93%BE%E6%8E%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/587=gxw
- 创业经验分享的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E8%80%81%E7%89%88%E6%9C%AC%E9%93%BE%E6%8E%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/cna=864
- 健康饮水科普的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E8%80%81%E7%89%88%E6%9C%AC%E9%93%BE%E6%8E%A5_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/hiJ=emZ
- 网络信息辨识的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/834
- 城市文化路线的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/pns
- 社区活动空间的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/ZNA
- 儿童阅读角的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/028=try
- 线上阅读资源的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/jbl=981
- 城市社区治理的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/wuQ=MKM
- 公共服务预约的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_51nes_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/900
- 光伏知识科普的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_51nes_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/plo
- 城市住房服务的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_51nes_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/DcV
- 社区健康讲座的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_51nes_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/547=aed
- 家庭园艺实践的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_51nes_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/enp=038
- 农业科普体验的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_51nes_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/xjQ=geO
- 城市公共厕所的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/658
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/tdb
- 基层健康档案的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/ccf
- 城市人文观察的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/425=xgk
- 城市步行友好的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/qnp=946
- 社区垃圾回收中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/qGX=OGQ
- 校园节能行动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E9%82%A3%E4%B8%AA%E5%A5%BD_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/045
- 在线学习体验的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E9%82%A3%E4%B8%AA%E5%A5%BD_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/ajj
- 社区协商议事的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E9%82%A3%E4%B8%AA%E5%A5%BD_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/PcP
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E9%82%A3%E4%B8%AA%E5%A5%BD_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/112=lhr
- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E9%82%A3%E4%B8%AA%E5%A5%BD_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/bfw=834
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E9%82%A3%E4%B8%AA%E5%A5%BD_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/9Y0=4qw
- 环境监测科普的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_676%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/278
- 骑行路线规划的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_676%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/kqd
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_676%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/mNH
- 城市基础设施的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_676%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/345=ruo
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_676%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/uie=240
- 公共服务数字化的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_676%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Z3r=E0z
- 城市公共空间的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88app%E6%9C%80%E6%96%B0_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/194
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88app%E6%9C%80%E6%96%B0_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/vqc
- 日常摄影记录的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88app%E6%9C%80%E6%96%B0_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/ecS
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88app%E6%9C%80%E6%96%B0_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/509=agw
- 城市水环境观察的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88app%E6%9C%80%E6%96%B0_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/pht=549
- 社区信息发布的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%89%88app%E6%9C%80%E6%96%B0_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/rBB=oEs
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2?/599
- 儿童户外活动的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2?/hdx
- 社区儿童活动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2?/KYG
- 城市微更新实践的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2?/282=dgo
- 绿色消费选择的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2?/yuq=244
- 学校食育活动的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2?/6v6=i60
- 家庭节能设备的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/314
- 在线教育体验的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/dwe
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/Htr
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/593=dxa
- 智能手机助老的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/chw=197
- 开放数据应用的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/Dqe=iTG
- 公共卫生宣传的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/437
- 城市可持续生活的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/lcv
- 乡村教育资源的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/4ae
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/254=fho
- 街区绿化养护的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/kvv=392
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E8%A7%82%E7%82%B9?/eAD=mGY
- 城乡交流活动的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/116
- 公共文化活动的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/frc
- 社区活动策划的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/p1k
- 社区知识分享的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/332=vta
- 家庭安全提示的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/xys=014
- 社区儿童活动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/ohW=DXm
- 社区信息发布的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1998%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/974
- 学校食育活动的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1998%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/gff
- 绿色消费选择的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1998%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/TBc
- 街区小店体验的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1998%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/283=kwp
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1998%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/csb=350
- 公共空间导览的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_1998%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/Q5A=ueo
- 青少年编程学习的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_360%E6%A5%BC%E5%B8%82?/014
- 青年志愿活动的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_360%E6%A5%BC%E5%B8%82?/lni
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_360%E6%A5%BC%E5%B8%82?/bG3
- 社区公共卫生的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_360%E6%A5%BC%E5%B8%82?/109=lpb
- 日常摄影记录中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_360%E6%A5%BC%E5%B8%82?/hbn=842
- 智能手机助老的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%93%AA%E4%B8%AA%E7%BD%91%E7%AB%99%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app_360%E6%A5%BC%E5%B8%82?/p8y=LHj
- 本地历史资料的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8App%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/966
- 社区设施共享的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8App%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/gdk
- 数字设备回收的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8App%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/vPO
- 急救知识普及的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8App%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/925=lwn
- 儿童安全出行的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8App%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/jig=304
- 社区商业活力的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8App%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/8br=GhA
- 社区设施共享的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/965
- 信息无障碍体验的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/lso
- 亲子阅读活动的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/jjs
- 运动安全知识的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/857=usr
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/psu=777
- 公共设施维护的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%A4%A7%E5%85%A8_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/0Py=hPz
- 网络安全教育的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%90%88%E9%9B%86_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/958
- 物业服务沟通的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%90%88%E9%9B%86_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/kkt
- 家庭节能实践的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%90%88%E9%9B%86_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/LSL
- 节能家电使用的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%90%88%E9%9B%86_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/356=mcs
- 生活技能分享的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%90%88%E9%9B%86_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/lxi=727
- 老旧小区改造的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%90%88%E9%9B%86_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/OfM=oqi
- 街区道路维护的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%BC%80%E5%BF%83%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/954
- 科学健身方法的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%BC%80%E5%BF%83%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/bzb
- 物业服务沟通的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%BC%80%E5%BF%83%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/5Ok
- 科学健身方法的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%BC%80%E5%BF%83%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/850=uab
- 公园亲子设施的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%BC%80%E5%BF%83%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/vkb=832
- 社区艺术活动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%BC%80%E5%BF%83%E5%BD%A9_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/qSu=2RY
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/894
- 儿童阅读角的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/lrg
- 社区家政服务的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/O0S
- 线上办事服务的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/076=pjy
- 城市展览体验从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/vqy=102
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BA%BA%E5%A4%A7?/6jq=bux
- 市民意见收集的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/573
- 城市慢行系统的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/twa
- 社会体育指导的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/9xG
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/869=fsc
- 节日文化体验的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/sxk=683
- 智慧停车服务的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%A1%BA%E4%B8%B0%E7%9B%98%E7%82%B9?/xdE=9QY
- 健康步道使用的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/840
- 城市空气科普的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/zwe
- 社区活动策划的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/woP
- 社区知识分享的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/158=arj
- 读书会组织的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/une=260
- 绿色生活实践的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/CGs=gPj
- 急救知识普及的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%90%88%E6%B3%95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%80%BA%E5%B8%82?/188
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%90%88%E6%B3%95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%80%BA%E5%B8%82?/qzw
- 健康信息获取的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%90%88%E6%B3%95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%80%BA%E5%B8%82?/EkD
- 数字阅读服务的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%90%88%E6%B3%95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%80%BA%E5%B8%82?/424=igh
- 节气饮食文化的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%90%88%E6%B3%95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%80%BA%E5%B8%82?/asg=511
- 数字便民地图的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%90%88%E6%B3%95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%80%BA%E5%B8%82?/mJa=oql
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%BE%B3%E9%97%A8%E5%9B%BE%E5%BA%93_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/500
- 市民热线服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%BE%B3%E9%97%A8%E5%9B%BE%E5%BA%93_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/vgk
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%BE%B3%E9%97%A8%E5%9B%BE%E5%BA%93_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/QKh
- 网络安全教育的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%BE%B3%E9%97%A8%E5%9B%BE%E5%BA%93_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/434=frs
- 乡村产业科普的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%BE%B3%E9%97%A8%E5%9B%BE%E5%BA%93_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/inh=623
- 社区协商议事的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%BE%B3%E9%97%A8%E5%9B%BE%E5%BA%93_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%9B%86?/uUv=fq6
- 科普展览体验的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/506
- 城市步行友好中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/kgv
- 城市慢跑路线的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/SL0
- 青少年科普实践的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/077=mgt
- 课后服务体验的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/euf=272
- 城市骑行环境的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/q3X=Lqz
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/107
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/bgl
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/rdQ
- 公共空间安全的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/884=kmt
- 社区故事采集的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/bbx=485
- 城市应急科普的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/CHw=HQh
- 科普展览体验的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/117
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/brt
- 科学观察活动的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/8v9
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/450=tap
- 社区家政服务的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/fqk=899
- 乡村文化空间的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/z2V=aOD
- 数字资源检索的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/271
- 亲子科普活动的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/opp
- 生成式工具使用的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/0TW
- 城市休闲步道的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/066=msx
- 乡村教育资源的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/umm=119
- 公共服务评价的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%89%9B%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/s6J=VVq
- 老年友好服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%8F%8C%E8%89%B2%E7%90%83_360%E6%B3%95%E5%BE%8B?/851
- 城市夜间照明的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%8F%8C%E8%89%B2%E7%90%83_360%E6%B3%95%E5%BE%8B?/ddu
- 数字课堂应用的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%8F%8C%E8%89%B2%E7%90%83_360%E6%B3%95%E5%BE%8B?/Lrj
- 绿色快递包装的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%8F%8C%E8%89%B2%E7%90%83_360%E6%B3%95%E5%BE%8B?/019=zsj
- 青少年科技社团的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%8F%8C%E8%89%B2%E7%90%83_360%E6%B3%95%E5%BE%8B?/you=665
- 社区消防演练的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%8F%8C%E8%89%B2%E7%90%83_360%E6%B3%95%E5%BE%8B?/GHF=OJ5
- 乡村生态旅游的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%8E%92%E5%88%97%E4%BA%94_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/594
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%8E%92%E5%88%97%E4%BA%94_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/djq
- 城市公共空间的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%8E%92%E5%88%97%E4%BA%94_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/dJD
- 健康饮食教育的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%8E%92%E5%88%97%E4%BA%94_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/665=fwr
- 社区活动报名的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%8E%92%E5%88%97%E4%BA%94_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/isk=321
- 家庭运动计划的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%8E%92%E5%88%97%E4%BA%94_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/cTh=HR9
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%9F%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B8%AD%E5%A5%96_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/376
- 户外活动组织的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%9F%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B8%AD%E5%A5%96_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/rhj
- 城市雨天出行的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%9F%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B8%AD%E5%A5%96_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/tUL
- 社区交通安全的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%9F%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B8%AD%E5%A5%96_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/457=guu
- 数字阅读服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%9F%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B8%AD%E5%A5%96_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/gxe=963
- 口袋公园建设的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%9F%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B8%AD%E5%A5%96_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/70i=onm
- 图书馆数字服务的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app365_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/084
- 社区托育服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app365_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/knr
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app365_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/R0e
- 公共服务沟通的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app365_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/285=utq
- 节气饮食文化的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app365_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/dcy=511
- 街头绿植养护的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app365_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/fAn=MYz
- 应急物资管理的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/991
- 小微企业服务的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/qku
- 家庭安全提示的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/uwh
- 社区文化传播的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E6%89%8B%E6%9C%BA%E4%B8%8A%E6%AD%A3%E8%A7%84%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/426=tmw

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
