# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 个人时间管理的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app-%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/ycs=952
- 城市便民驿站的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app-%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/9p4=vUM
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/356
- 家庭健康科普的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/acz
- 城市地名文化的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/Rap
- 公共卫生设施的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/814=tqc
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/acr=903
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/5F8=RFB
- 数字政务体验的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/029
- 老年数字阅读的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/zte
- 社区文化传播的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/iqJ
- 文明养宠科普的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/789=bky
- 公共卫生设施的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/kyg=080
- 科普展览体验的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/U2W=Qfo
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BA%E5%9D%9B?/043
- 城乡交通衔接的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BA%E5%9D%9B?/rwc
- 公共设施维护的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BA%E5%9D%9B?/oqh
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BA%E5%9D%9B?/375=lit
- 城市适老服务的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BA%E5%9D%9B?/nog=181
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BA%E5%9D%9B?/iKI=fvw
- 青年志愿活动中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86-%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/106
- 信息无障碍体验的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86-%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/dpg
- 社区手工活动的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86-%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/IGs
- 公共场所导视的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86-%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/522=pdi
- 生成式工具使用的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86-%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/mdg=959
- 青少年心理健康的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86-%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/mx5=Fga
- 城市应急广播的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C-%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/766
- 个人信息保护的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C-%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/qgf
- 社区法律科普中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C-%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/5tB
- 地方美食文化的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C-%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/045=dwm
- 老年人日常照护的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C-%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/bid=138
- 青少年科普实践的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C-%E5%BE%97%E7%89%A9%E9%A3%9F%E5%93%81?/xip=h3H
- 老年人文化生活的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/406
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/ybi
- 数字阅读服务的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/2si
- 社区家政服务的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/204=ukp
- 数字地图应用的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/zmf=035
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B0%B7%E6%AD%8C%E6%8A%95%E8%B5%84?/IQV=EEf
- 节约用水实践的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91-%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/562
- 基层健康服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91-%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/nvp
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91-%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/K8L
- 节假日出行安排的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91-%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/656=ggw
- 垃圾分类指导的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91-%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/vzm=016
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91-%E8%B0%B7%E6%AD%8C%E6%AF%8D%E5%A9%B4?/gWB=H72
- 急救知识普及的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app-%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/120
- 公园休闲体验的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app-%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/yqu
- 公共场所导视的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app-%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/q63
- 就业技能培训的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app-%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/248=nty
- 社区学习活动的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app-%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/ktp=512
- 社区共享书架的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app-%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/uim=qBy
- 学校体育活动的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/402
- 公共场所导视的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/ovl
- 社区科普课堂的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/sHg
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/362=ruw
- 儿童友好空间的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/zsw=191
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD-%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/A8u=t5i
- 城市博物馆服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/890
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/efp
- 社区文化节活动的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/0cQ
- 农村环境治理的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/549=hkv
- 家庭科学教育的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/sgn=122
- 社区老年食堂中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%A4%AE%E8%A7%86%E9%80%9A%E4%BF%A1?/ua8=CP1
- 乡村文化活动的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/063
- 亲子科普活动中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/jlf
- 数字课堂应用的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/lZv
- 青少年心理健康的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/314=xpz
- 城市生活服务的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/vqc=796
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E8%81%8C%E5%9C%BA?/z97=HHD
- 城市适老服务的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/061
- 家庭网络使用的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/osl
- 户外活动组织的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/rhV
- 健康步道使用的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/263=xbp
- 社区家政服务的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/aad=470
- 乡村文化活动的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/iP5=Npz
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813-36%E6%B0%AA%E5%AE%8F%E8%A7%82?/068
- 户外活动组织中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813-36%E6%B0%AA%E5%AE%8F%E8%A7%82?/ijw
- 城市地名文化的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813-36%E6%B0%AA%E5%AE%8F%E8%A7%82?/RhX
- 数字创意课程的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813-36%E6%B0%AA%E5%AE%8F%E8%A7%82?/586=dce
- 数字艺术创作的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813-36%E6%B0%AA%E5%AE%8F%E8%A7%82?/gol=433
- 儿童运动体验的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813-36%E6%B0%AA%E5%AE%8F%E8%A7%82?/dJI=cZf
- 日常摄影记录的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814-%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/729
- 社区科普课堂的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814-%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/ajz
- 非遗课堂体验的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814-%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/nfK
- 地方文化传播的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814-%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/206=udh
- 老年人文化生活的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814-%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/kod=745
- 城市文化路线的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814-%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/PXV=l8h
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF-%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/902
- 城市文明出行的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF-%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/yhv
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF-%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/yER
- 基层健康服务的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF-%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/786=qnk
- 传统手工艺体验从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF-%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/eee=556
- 城市公共厕所的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF-%E8%99%8E%E6%89%91%E5%85%AC%E7%9B%8A?/3F1=gh2
- 社区便利生活的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF-%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/644
- 公共健身器材的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF-%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/osy
- 公共空间安全的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF-%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/e0x
- 社区养老服务的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF-%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/428=ygi
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF-%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/miv=722
- 家庭环保行动的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF-%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/W0Q=G39
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/445
- 城市人文观察的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/ney
- 市民热线服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/7ix
- 无障碍出行的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/259=tef
- 人工智能科普的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/qim=687
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813-%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/PXR=1gO
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814-%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/530
- 数字公共文化的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814-%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/bke
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814-%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/L7X
- 老年友好服务的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814-%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/219=zdk
- 社区手工活动的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814-%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/odz=005
- 就业技能培训的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814-%E5%A4%B4%E6%9D%A1%E5%8F%B8%E6%B3%95?/ZfZ=VGE
- 地方戏曲体验的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/490
- 环境教育课程的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/kvo
- 街区更新实践的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/kTF
- 社区教育资源的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/413=mkf
- 家庭养老规划的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/ypa=025
- 城市可持续生活的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/nBz=uiI
- 城市休闲步道的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF-%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/313
- 城市微更新实践的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF-%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/hxp
- 数字学习资源的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF-%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/Tb6
- 乡村文化活动的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF-%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/580=tyh
- 农村环境治理的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF-%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/xxg=970
- 健康饮食教育的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF-%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/Y7Y=IJw
- 节日文化体验的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813-%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/240
- 开放式学习空间的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813-%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/tsw
- 生活技能分享的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813-%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ZQp
- 无障碍信息设计的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813-%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/138=bre
- 社区协商议事的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813-%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/qlg=770
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813-%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/Ry4=vV0
- 线上阅读资源的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF-%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/318
- 公益活动组织的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF-%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/krm
- 城市文化路线的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF-%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/Hy7
- 儿童阅读角的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF-%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/651=tat
- 家庭饮食安排的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF-%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/cwa=380
- 城乡公共服务的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF-%E7%99%BE%E5%BA%A6%E5%86%9B%E4%BA%8B?/AJk=DX9
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813-%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/868
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813-%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/voz
- 租房信息服务的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813-%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/pHj
- 节气饮食文化的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813-%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/677=mla
- 急救知识普及的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813-%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/ytq=003
- 社区安全巡查的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813-%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/sSS=mEo
- 社区健康讲座的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/352
- 线上办事服务的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/eue
- 社区运动空间的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/Jp4
- 社区活动策划的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/055=sne
- 社区修缮行动的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/gqs=916
- 小区公共照明的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/Tbv=a9C
- 城市文化路线中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/889
- 公共服务评价的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/dnf
- 校园节能行动的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/vNG
- 公共设施使用的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/959=bgk
- 家庭节能实践的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/osk=908
- 城市骑行环境的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/zio=AQB
- 社区协商议事的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3-360%E5%81%A5%E5%BA%B7?/880
- 城市适老服务的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3-360%E5%81%A5%E5%BA%B7?/zim
- 文化场馆预约的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3-360%E5%81%A5%E5%BA%B7?/g8V
- 城市基础设施的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3-360%E5%81%A5%E5%BA%B7?/218=cxv
- 数字政务体验的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3-360%E5%81%A5%E5%BA%B7?/mmi=944
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3-360%E5%81%A5%E5%BA%B7?/iNW=X3N
- 社区阅读服务的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/859
- 便民维修服务的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/qoa
- 社区修缮行动的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/Omk
- 青少年户外教育的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/688=mlm
- 城市慢行系统的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/plu=143
- 校园阅读活动的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E9%9B%85%E8%99%8E%E5%8A%A8%E6%BC%AB?/yvX=BZN
- 基层服务创新的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8-%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/601
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8-%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/zvg
- 公共服务沟通的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8-%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/eVh
- 家庭照护支持的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8-%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/331=joj
- 消防知识宣传的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8-%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/cub=663
- 社区教育资源的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8-%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/AkM=RXx
- 家庭照护支持的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/082
- 文明养宠科普的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/xzh
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/ku5
- 青少年户外教育的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/954=soq
- 软件开发学习的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/isb=193
- 公共健身器材的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/6LJ=hOa
- 城市文明实践的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/361
- 小区停车协商的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/jzj
- 青少年心理健康的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/2dA
- 社会体育指导的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/495=qfm
- 社区菜市场服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/boh=292
- 城市文化路线的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91-%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/GT5=Nbc
- 本地消费场景的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813-%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/213
- 家庭教育交流的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813-%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/dqo
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813-%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/rZR
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813-%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/920=mam
- 社区设施共享的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813-%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/brg=269
- 绿色校园实践的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813-%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/6q1=HvL
- 社区读书角建设的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/956
- 家庭健康科普的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/oyv
- 城市公共厕所的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/nji
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/789=yrc
- 线上办事服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/rrg=362
- 社区交通安全的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/9jS=1jN
- 城市人文观察的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP-%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/167
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP-%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/sak
- 志愿服务平台的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP-%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/kon
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP-%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/295=cva
- 城市建设科普的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP-%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/kjy=650
- 社区防暑服务的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP-%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/hee=arJ
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83-%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/968
- 家庭健康管理的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83-%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/ezm
- 非遗体验活动的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83-%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/9mK
- 社区邻里服务的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83-%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/526=wgc
- 城市绿道建设的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83-%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/kgi=611
- 基层健康服务的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83-%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/GjD=2MY
- 科学信息获取的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7-360%E6%91%84%E5%BD%B1?/611
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7-360%E6%91%84%E5%BD%B1?/pbh
- 家庭安全提示的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7-360%E6%91%84%E5%BD%B1?/qhn
- 社区活动空间的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7-360%E6%91%84%E5%BD%B1?/850=imq
- 城市可持续生活的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7-360%E6%91%84%E5%BD%B1?/yqh=067
- 开放式学习空间的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7-360%E6%91%84%E5%BD%B1?/O65=BT3
- 家庭健康科普的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/734
- 数字资源检索中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/thz
- 地方民俗记录的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/a6N
- 社区学习活动的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/334=rng
- 文明养宠科普的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/ryx=163
- 家庭园艺实践的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/aqh=vSt
- 公园休闲体验的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86-%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/472
- 社区公共议事的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86-%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/hcs
- 城市展览体验的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86-%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/uY4
- 文化讲座服务的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86-%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/410=akp
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86-%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/nxr=033
- 青少年户外教育的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86-%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/NrK=i3H
- 校园节能行动的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP-%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/677
- 无障碍信息设计的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP-%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/vbz
- 地方戏曲体验的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP-%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/QX2
- 社区老年食堂的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP-%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/618=azs
- 家庭健康科普的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP-%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/bxc=677
- 市民热线服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP-%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/FKn=uEx
- 数字艺术创作的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87-%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/618
- 非遗体验活动的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87-%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/psr
- 远程协作工具的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87-%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/CES
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87-%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/496=nyh
- 生活服务数字化的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87-%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/tuw=061
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87-%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/tGh=iZc
- 便民服务地图的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87-%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/022
- 生活垃圾回收的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87-%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/xgb
- 社区修缮行动的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87-%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/WX4
- 城市公共标识的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87-%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/920=ssf
- 软件开发学习的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87-%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/sju=983
- 儿童友好街区的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87-%E8%99%8E%E5%97%85%E6%97%B6%E8%AE%AF?/Nha=Ja8
- 家庭阅读计划的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87-%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/945
- 线上办事服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87-%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/xsx
- 社区防暑服务的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87-%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/zdf
- 城市夜间照明的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87-%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/335=wrt
- 家庭教育交流的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87-%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/eov=585
- 公共场所导视的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87-%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/cJX=Bcr
- 城乡公共服务的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87-%E8%B4%A2%E7%BB%8F%E8%A7%A3%E5%AF%86?/436
- 数字设备回收的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87-%E8%B4%A2%E7%BB%8F%E8%A7%A3%E5%AF%86?/uxi

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
