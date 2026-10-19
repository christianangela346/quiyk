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

- 家庭健康管理的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/538
- 社区阅读服务的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/yiv
- 网络安全教育的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/Iwj
- 光伏知识科普的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/540=nqr
- 基层服务创新的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/plx=819
- 地方戏曲体验的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/zYA=DnS
- 志愿服务平台的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%A0%81%E4%B8%8A%E6%9D%A5%E6%96%99%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/058
- 老年人出行服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%A0%81%E4%B8%8A%E6%9D%A5%E6%96%99%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/kyg
- 本地消费场景的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%A0%81%E4%B8%8A%E6%9D%A5%E6%96%99%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/IBE
- 社区环保活动的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%A0%81%E4%B8%8A%E6%9D%A5%E6%96%99%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/434=amp
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%A0%81%E4%B8%8A%E6%9D%A5%E6%96%99%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/bwm=578
- 急救知识普及的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%A0%81%E4%B8%8A%E6%9D%A5%E6%96%99%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/D7G=pJj
- 科普展览体验的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/543
- 城市噪声观察的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/dmx
- 科学信息获取的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/40z
- 青年职业探索的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/014=iby
- 城市博物馆活动的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/tvq=782
- 节日文化体验的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_49%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/uA9=wWx
- 社区商业活力的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%90%89%E6%9E%97%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/787
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%90%89%E6%9E%97%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/npa
- 社区家政服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%90%89%E6%9E%97%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/Vf4
- 社区养老服务的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%90%89%E6%9E%97%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/696=dyl
- 智能手机助老的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%90%89%E6%9E%97%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/zrl=432
- 社区修缮行动的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%90%89%E6%9E%97%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/fYh=kjM
- 青少年编程学习的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%BB%91%E9%BE%99%E6%B1%9F%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/702
- 街道综合服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%BB%91%E9%BE%99%E6%B1%9F%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/ral
- 校园阅读活动的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%BB%91%E9%BE%99%E6%B1%9F%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/qC6
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%BB%91%E9%BE%99%E6%B1%9F%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/418=lxp
- 本地消费场景的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%BB%91%E9%BE%99%E6%B1%9F%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/nup=374
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E9%BB%91%E9%BE%99%E6%B1%9F%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/8cw=sgw
- 社区便民集市的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9App%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%AE%9A%E7%89%9B_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/482
- 数字生活课堂的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9App%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%AE%9A%E7%89%9B_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/dyv
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9App%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%AE%9A%E7%89%9B_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/pxL
- 学校体育活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9App%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%AE%9A%E7%89%9B_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/199=ehw
- 城市社区治理的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9App%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%AE%9A%E7%89%9B_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/fde=075
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9App%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%AE%9A%E7%89%9B_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/ljr=WLk
- 社区艺术活动的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9APP%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/182
- 健康饮食教育的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9APP%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/pio
- 数字设备回收的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9APP%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/iqR
- 社区老年食堂的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9APP%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/971=xfd
- 人工智能科普的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9APP%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/yah=066
- 数字设备回收的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9APP%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E6%A0%8F?/wre=aKx
- 社区活动空间的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA3d%E7%A6%8F%E5%BD%A9%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/705
- 社区教育资源的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA3d%E7%A6%8F%E5%BD%A9%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/qvs
- 科普展览体验的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA3d%E7%A6%8F%E5%BD%A9%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/uMN
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA3d%E7%A6%8F%E5%BD%A9%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/966=wuc
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA3d%E7%A6%8F%E5%BD%A9%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/mpf=708
- 儿童阅读角的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA3d%E7%A6%8F%E5%BD%A9%E7%BD%91_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/GXy=kE7
- 城乡公共服务的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/797
- 公共服务咨询的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/eax
- 本地历史资料的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/Nth
- 数字档案服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/263=cde
- 社区活动策划的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/zxy=763
- 社区快递服务中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%9B%E6%8A%95?/fMr=8FZ
- 城市公共空间的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/420
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/vqc
- 气象科普传播的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/gX4
- 数字档案服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/113=egq
- 物业服务沟通的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/xxn=216
- 城乡交通衔接的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/nET=Wqs
- 城市公共标识的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/980
- 城市便民驿站的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/oji
- 软件开发学习的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/MIV
- 社区便利生活的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/934=nrv
- 社区安全巡查的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/dws=257
- 终身学习资源的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%BA%E7%89%A9?/W0O=jEd
- 节日文化体验的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/612
- 城市慢行系统的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/uhw
- 公共文化活动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/q57
- 社区慢性病防控的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/325=wrn
- 家庭收纳实践的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/zfl=260
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/y02=TNo
- 社区设施共享的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/753
- 老年数字阅读的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/tzv
- 城市公共厕所的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/EeQ
- 急救知识普及的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/645=fvv
- 数字资源检索的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/arv=802
- 乡村公共阅读的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/N1l=2Wy
- 儿童友好空间的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/813
- 志愿服务平台的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/bjg
- 乡村生态观察的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/EEc
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/922=uvw
- 小区公共照明的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ptc=158
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%A6%8F%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/QNw=Nux
- 家庭消费规划的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/024
- 青年职业探索的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/csi
- 本地消费场景的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/ThE
- 数字素养提升的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/328=lbe
- 社区读书角建设的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/bna=630
- 家庭科学教育的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/Nua=U9x
- 社区庭院绿化的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/190
- 物业服务沟通的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/keg
- 公共服务指南的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/98q
- 城市噪声观察的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/923=oqc
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/evm=612
- 绿色建筑理念的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/4vZ=cwu
- 智能家居应用的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/729
- 创业经验分享的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/kfr
- 读书会组织的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/n9P
- 个人时间管理的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/965=uze
- 社区停车服务的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/pra=319
- 健康饮食教育中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%89%B4?/sya=L31
- 社区商业活力的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E5%B9%B6%E8%B4%AD?/462
- 市民热线服务的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E5%B9%B6%E8%B4%AD?/cls
- 智慧城市体验的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E5%B9%B6%E8%B4%AD?/rpM
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E5%B9%B6%E8%B4%AD?/642=amo
- 公共图书馆服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E5%B9%B6%E8%B4%AD?/pbn=421
- 社区公共议事的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E5%B9%B6%E8%B4%AD?/7vj=fOE
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/217
- 社区心理支持的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/yjm
- 社区故事采集的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/gdf
- 城市建设科普的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/959=cyr
- 数据分析入门的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/tie=818
- 家庭园艺实践的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/eqY=cCk
- 公共服务预约的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/608
- 家庭饮食安排的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/rez
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/6F2
- 城市共享单车的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/248=sls
- 社区活动空间的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/wxo=306
- 社区停车服务的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/EtK=4fB
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%B5%B0%E5%BC%8F%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/462
- 租房信息服务的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%B5%B0%E5%BC%8F%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/xiu
- 数字创作工具的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%B5%B0%E5%BC%8F%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/2BH
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%B5%B0%E5%BC%8F%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/933=jif
- 科学运动指导的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%B5%B0%E5%BC%8F%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/jiu=611
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%B5%B0%E5%BC%8F%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E7%BE%8E%E5%A6%86?/GEG=nNh
- 居家防滑改造的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/015
- 智能家居应用的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/uhw
- 城市夜间生活的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/DQu
- 城市共享单车的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/602=csr
- 家庭科学教育的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/qjg=840
- 农业科普体验的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/SHc=UWR
- 数字政务体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%8B%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/156
- 家庭健康科普的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%8B%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/qfu
- 文化场馆预约的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%8B%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/jF6
- 小区电梯维护的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%8B%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/689=pjo
- 灵活就业交流的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%8B%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/lkh=879
- 网络信息辨识的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%8B%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%94%B6%E8%97%8F?/2l4=uWo
- 小区停车协商的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/009
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/ety
- 儿童阅读角的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/8cz
- 数字政务体验的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/428=dzv
- 垃圾分类指导的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/zhz=388
- 数字公共文化的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/nRJ=mEq
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/653
- 社区家政服务的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/tgd
- 公共卫生设施的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/2DP
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/238=mdf
- 社区文化节活动的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/exs=748
- 公交站点体验的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/xE6=uqU
- 读书会组织的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9app_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/902
- 乡村公共服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9app_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/gbi
- 城市公共厕所的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9app_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/f2R
- 社区信息发布的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9app_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/743=tps
- 绿色校园实践的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9app_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/bns=752
- 数字素养提升的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9app_%E8%B1%86%E7%93%A3%E8%BD%AC%E8%BD%BD?/v8O=czp
- 公共场馆服务的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%88%91%E6%83%B3%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/585
- 校园阅读活动的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%88%91%E6%83%B3%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/olp
- 小区停车协商的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%88%91%E6%83%B3%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/yeu
- 城市社区治理的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%88%91%E6%83%B3%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/164=ceh
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%88%91%E6%83%B3%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/xzr=809
- 节约用水实践的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%88%91%E6%83%B3%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E5%B0%9A?/VFO=oVz
- 街区小店体验的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E5%BD%A9%E5%AE%9Dapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/491
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E5%BD%A9%E5%AE%9Dapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/ldf
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E5%BD%A9%E5%AE%9Dapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/1nK
- 青少年科技社团的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E5%BD%A9%E5%AE%9Dapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/997=xwy
- 家庭环保习惯的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E5%BD%A9%E5%AE%9Dapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/rrm=428
- 课后服务体验的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%9A%E5%BD%A9%E5%AE%9Dapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E9%97%AE%E7%AD%94?/2cs=HNy
- 城市体育设施中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/908
- 老年人日常照护的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/zdf
- 传统手工艺体验的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/JOC
- 生活服务数字化的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/250=cgz
- 城市博物馆活动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/mnd=535
- 青年职业探索中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/cS8=bNk
- 城市体育设施的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/526
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/hma
- 街区小店体验的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/67Y
- 健康饮食教育的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/264=lgo
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/adw=716
- 家庭用电安全的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E4%BA%94%E7%A6%8F%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/Xvz=MkG
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/646
- 地方旅游导览的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/zcz
- 地方旅游导览的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/qcq
- 智能家居应用的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/357=otj
- 社区环保活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/uef=714
- 校园社团活动的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/Kjp=6kx
- 公共交通信息服务的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/888
- 城市可持续生活的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/xyw
- 城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/hx6
- 街区更新实践中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/374=xhf
- 节假日出行安排的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/dcj=696
- 城市公共艺术的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/fsX=4d5
- 科学教育活动的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/477
- 数字素养提升的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/bth
- 电子商务服务的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/d85
- 社区花园共建的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/785=kiv
- 城市公共饮水中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/fqx=282
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/Ypq=oVJ
- 健康步道使用的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/523
- 数字生活课堂的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/ffu
- 社区信息发布的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/dmb
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/447=api
- 乡村产业科普的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/rdw=813
- 全民健身活动的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/cEk=tQC
- 城市空气科普的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%A8%E4%BB%80%E4%B9%88%E5%A5%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/498
- 科学观察活动的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%A8%E4%BB%80%E4%B9%88%E5%A5%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/ghj
- 骑行路线规划的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%A8%E4%BB%80%E4%B9%88%E5%A5%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/A1t
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%A8%E4%BB%80%E4%B9%88%E5%A5%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/011=don
- 乡村生活观察的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%A8%E4%BB%80%E4%B9%88%E5%A5%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/yfs=427
- 乡村生态观察的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%A8%E4%BB%80%E4%B9%88%E5%A5%BD_%E6%96%B0%E6%B5%AA%E6%94%B6%E8%97%8F?/upi=U5A
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E5%9C%A8%E7%94%B5%E8%84%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/683
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E5%9C%A8%E7%94%B5%E8%84%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/stq
- 社区活动空间的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E5%9C%A8%E7%94%B5%E8%84%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/Tg4
- 家庭教育交流的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E5%9C%A8%E7%94%B5%E8%84%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/806=hnt
- 小区停车协商中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E5%9C%A8%E7%94%B5%E8%84%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/qfm=034
- 校园社团活动的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E5%9C%A8%E7%94%B5%E8%84%91%E4%B8%8A%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%B3%95%E6%B2%BB?/SsL=Sdp
- 文化场馆预约的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/376
- 全民阅读推广的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/yga
- 骑行路线规划的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/YFU
- 公共卫生宣传的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/534=axy
- 学校体育活动的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/qiu=721
- 远程协作工具的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/LWY=ZZs
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/825
- 家庭教育交流的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/svp
- 公共服务预约的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/Qd5
- 老年友好服务的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/590=ueo
- 电动汽车充电的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/dsv=200
- 城市基础设施的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/Zhu=dhT
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/422
- 小区停车协商的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/vvj
- 软件开发学习的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/H9u
- 绿色校园实践的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/728=gyl
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/fgc=196
- 街区道路维护中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/K4n=x1b
- 社区艺术活动的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%92%E8%8D%89%E5%9D%AA%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/656
- 城市共享单车的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%92%E8%8D%89%E5%9D%AA%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/lhf
- 基层服务创新的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%92%E8%8D%89%E5%9D%AA%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/Kbg
- 城市文明出行中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%92%E8%8D%89%E5%9D%AA%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/501=joq
- 家庭理财科普的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%92%E8%8D%89%E5%9D%AA%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/bae=184
- 乡村文化空间的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%92%E8%8D%89%E5%9D%AA%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/IYe=mI9
- 老年智能设备的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%B0%E9%97%BB?/871
- 城市社区治理的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%B0%E9%97%BB?/vnn
- 社区应急准备的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%B0%E9%97%BB?/UZf
- 数字支付体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%B0%E9%97%BB?/458=hox
- 公共设施维护的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%B0%E9%97%BB?/hop=795
- 校园节能行动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3d%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%96%B0%E9%97%BB?/l1i=XEE
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/749
- 口袋公园建设的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/mfo
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/b3A
- 城市便民驿站的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/334=con

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
