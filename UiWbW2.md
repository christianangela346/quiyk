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

- 青年职业探索的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-36%E6%B0%AA%E6%97%A5%E6%8A%A5?/202
- 全民健身活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-36%E6%B0%AA%E6%97%A5%E6%8A%A5?/bqs
- 城乡交流活动的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-36%E6%B0%AA%E6%97%A5%E6%8A%A5?/3ui
- 绿色快递包装的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-36%E6%B0%AA%E6%97%A5%E6%8A%A5?/628=pir
- 家庭健康管理的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-36%E6%B0%AA%E6%97%A5%E6%8A%A5?/kwh=520
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-36%E6%B0%AA%E6%97%A5%E6%8A%A5?/hne=BJL
- 城市文明实践的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89-%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/567
- 环境监测科普的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89-%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/ctf
- 城市绿色交通的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89-%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/IUW
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89-%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/021=atp
- 地方旅游导览的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89-%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/kcc=905
- 社区故事采集的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89-%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/acu=E1V
- 家庭消费规划的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/654
- 街区小店体验的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ahh
- 社区活动空间的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/giD
- 社区协商议事的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/470=lmr
- 老年数字阅读的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/phq=402
- 社区活动策划的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/Gbu=xJw
- 农村环境治理的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/379
- 城市文明出行的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/phu
- 环境监测科普的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/Yhk
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/112=kol
- 食品配送体验的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/dye=145
- 地方文化传播的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/AdD=Fs4
- 青少年心理健康的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85-%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/633
- 市民热线服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85-%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/nrv
- 本地消费场景的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85-%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/qmz
- 儿童友好空间的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85-%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/238=acn
- 智慧停车服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85-%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/ncg=159
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85-%E7%BD%91%E6%98%93%E6%97%B6%E6%8A%A5?/3uj=tRO
- 急救知识普及的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/966
- 城市微更新实践的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/jdr
- 便民维修服务的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/BiI
- 垃圾分类指导的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/566=nat
- 数字创作工具的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/bkg=199
- 公共交通接驳的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BC%97%E6%B5%8B?/vme=WZS
- 家庭园艺实践的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/775
- 乡村教育资源的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/bqg
- 智能家居应用的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zxM
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/027=uas
- 网络安全教育的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xub=032
- 儿童户外活动的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/49V=JJs
- 绿色出行服务的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/141
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/inw
- 城市绿色交通的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/rwY
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/855=dby
- 无障碍出行的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/rcy=399
- 机器人科普活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/9M8=2PF
- 社区信息发布的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1-%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/556
- 老年友好服务的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1-%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/yiy
- 青年就业服务的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1-%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/Hff
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1-%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/961=oih
- 农贸市场环境的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1-%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/oes=114
- 城市公共空间的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1-%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/qVH=UMd
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91-%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/519
- 个人信息保护的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91-%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/yjg
- 线上阅读资源的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91-%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/161
- 公共服务沟通的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91-%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/484=vmt
- 绿色生活实践的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91-%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/shp=687
- 社区互助网络的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91-%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/Xb7=GQp
- 绿色消费选择的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9iv-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/905
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9iv-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/iks
- 信息无障碍体验的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9iv-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/mhc
- 乡村电商实践的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9iv-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/019=crw
- 城市微更新实践的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9iv-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/kli=348
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9iv-%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/u5m=Wpi
- 开放式学习空间中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87-%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/833
- 绿色生活实践的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87-%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/uyz
- 青年职业探索的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87-%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/wyi
- 物业服务沟通的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87-%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/869=huk
- 社区老年食堂的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87-%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/wqp=064
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87-%E5%90%AF%E6%99%BA%E8%B4%A2%E7%BB%8F?/1wL=aTA
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/944
- 乡村阅读空间的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/fyj
- 数字政务体验的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/KOP
- 农村环境治理的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/422=sfh
- 社区邻里服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/rvy=074
- 数字阅读服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/MbU=rkB
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/388
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/cva
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/lph
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/804=abt
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/iuo=578
- 乡村生态观察的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/BGj=iKH
- 城市步行环境的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc-%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/502
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc-%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/znt
- 城市绿道建设的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc-%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/82Q
- 科学健身方法的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc-%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/536=ydg
- 城市公共自行车的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc-%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/crr=621
- 绿色生活实践的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc-%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/Aan=yTg
- 文化场馆预约中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83-%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/140
- 电子商务服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83-%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/wzu
- 数字创意课程的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83-%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/G9m
- 数字素养提升的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83-%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/820=tqg
- 开源技术交流的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83-%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/xio=307
- 公共服务指南的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83-%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/PGG=aUZ
- 无障碍出行的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/931
- 志愿服务平台的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/riz
- 青少年科普实践的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/aL4
- 校园阅读活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/810=txi
- 个人信息保护的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/hai=954
- 小微企业服务的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/YaE=PIy
- 数字资源检索的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8-%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/253
- 居民健康教育的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8-%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/urf
- 社区科普课堂的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8-%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/S49
- 社区便民服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8-%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/886=iwj
- 学校体育活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8-%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/mzr=619
- 数字艺术创作的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8-%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/dUv=CYc
- 城市空气科普的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BD%A98VIII-%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/425
- 租房信息服务的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BD%A98VIII-%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/nwl
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BD%A98VIII-%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/A7k
- 新能源出行的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BD%A98VIII-%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/481=fku
- 基层服务创新的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BD%A98VIII-%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/gof=571
- 青年职业探索中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BD%A98VIII-%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/H7f=eGe
- 个人时间管理的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/933
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/sdm
- 节能生活方式的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/wh5
- 农村环境治理的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/673=etx
- 社区便民服务的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/udy=900
- 课后服务体验的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E-%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/t4p=wob
- 公共服务数字化的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/962
- 家庭园艺实践的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/jdi
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/EUZ
- 城市雨天出行的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/370=ect
- 社区艺术活动的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/fjq=220
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%B6%E5%B1%85?/AyY=gbW
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/245
- 社区便利生活的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/idi
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/43V
- 市民热线服务的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/608=wjt
- 生活服务数字化的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/dox=001
- 生活垃圾回收的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3-%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/nAB=pcc
- 社区信息发布的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/478
- 科学观察活动的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/bpo
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/gTG
- 家庭收纳实践的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/623=ore
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/lwg=874
- 居民健康教育的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97?/s5c=bx6
- 公共设施使用的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/876
- 城市博物馆服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/xmh
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/W53
- 本地历史资料的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/536=omz
- 社区垃圾分类的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/jon=081
- 公共空间安全的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/RPo=9Ai
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/945
- 社区便利生活的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/bkx
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/635
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/073=pzz
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/lwa=335
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E5%9B%AD%E8%89%BA?/d3z=VOx
- 口袋公园建设的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88-%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/296
- 社区环保活动的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88-%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/qmu
- 儿童友好空间的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88-%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/0UX
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88-%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/958=dds
- 图书借阅体验的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88-%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/qyz=808
- 健康步道使用的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88-%E8%B4%A2%E7%BB%8F%E5%9F%8E%E4%BA%8B?/lpZ=yjZ
- 社区文化节活动的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/599
- 社区故事采集的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/hbq
- 电动汽车充电中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/N1t
- 农贸市场环境的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/379=lrh
- 家庭环保习惯的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/jwl=583
- 生成式工具使用的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7-%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/WjV=zJE
- 公共场所导视的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/284
- 图书馆数字服务的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/hpb
- 城市空气科普的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/50a
- 地方美食文化的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/932=mrw
- 社区信息发布的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/qrp=444
- 个人时间管理的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E8%99%8E%E5%97%85%E6%94%BF%E5%8D%8F?/C3R=vvc
- 城市博物馆活动的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91168%E5%BD%A9app-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/978
- 非遗体验活动中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91168%E5%BD%A9app-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/ize
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91168%E5%BD%A9app-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/pGG
- 公交无障碍服务的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91168%E5%BD%A9app-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/518=wco
- 街区小店体验的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91168%E5%BD%A9app-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/vcj=785
- 老年人日常照护的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91168%E5%BD%A9app-%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/mFa=jyy
- 乡村生态观察的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7-%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/425
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7-%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/hge
- 家庭志愿活动的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7-%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/1hB
- 家庭节能设备的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7-%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/800=vsz
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7-%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/ofs=018
- 节气饮食文化的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7-%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/A4Q=GuQ
- 城市步行环境的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/780
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/xyf
- 城市夜间照明的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/Sio
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/560=bcq
- 城市运动公园的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/dgl=516
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/Jtn=qTV
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/779
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/jve
- 家庭急救准备的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/7vi
- 市民热线服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/581=aws
- 社区共享书架的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/oeq=367
- 城市休闲步道的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88-%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/wrb=3Bf
- 数字便民地图的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/510
- 开源技术交流的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/cyj
- 在线学习体验的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/57C
- 人工智能科普的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/279=gdt
- 开放式学习空间的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/adz=806
- 社区便利生活的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/mX2=JAz
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/798
- 食品配送体验的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/uvh
- 社区艺术活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/TPw
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/712=yfi
- 城市骑行环境的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/zgz=394
- 电动汽车充电的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/vz1=X7J
- 地方戏曲体验的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B4%AD-%E5%BE%97%E7%89%A9?/862
- 地方旅游导览的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B4%AD-%E5%BE%97%E7%89%A9?/lep
- 节能家电使用的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B4%AD-%E5%BE%97%E7%89%A9?/qbD
- 公共场所导视的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B4%AD-%E5%BE%97%E7%89%A9?/924=aeh
- 个人信息保护的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B4%AD-%E5%BE%97%E7%89%A9?/hpe=918
- 社区托育服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B4%AD-%E5%BE%97%E7%89%A9?/krG=rRf
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/269
- 环境监测科普的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/veu
- 开放数据应用的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/UVB
- 小区停车协商的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/689=axm
- 校园节能行动的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/xhf=230
- 机器人科普活动的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/Qf0=kcL
- 社区文化节活动的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/567
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/gyq
- 儿童友好空间的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/tYu
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/428=smd
- 开放式学习空间的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/zov=571
- 社区休闲设施的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/GDN=thS
- 社区体育组织的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/553
- 社区绿色空间的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/feu
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/Vka
- 图书馆数字服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/252=hqs
- 城市可持续生活的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/dsk=100
- 节假日出行安排的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0-%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/VAM=1N1
- 环境教育课程的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/626
- 老年智能设备的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/pst
- 家庭消费规划的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/xot
- 社区邻里服务的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/922=vdt
- 社区公共卫生的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/qgl=322
- 市民意见收集的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9E%AD%E6%9C%9B?/82z=LHY
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/647
- 社区商业活力中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/rgp
- 食品配送体验的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/2ZO
- 社区读书角建设的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/119=ynx
- 城市文明实践的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/nfh=541
- 社区文化传播的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8-%E4%BC%98%E9%85%B7%E5%9B%9E%E6%94%BE?/bH8=tjm
- 城市夜间照明的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-36%E6%B0%AA%E7%99%BE%E7%A7%91?/002
- 社区安全巡查的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-36%E6%B0%AA%E7%99%BE%E7%A7%91?/qkv
- 居家适老化改造的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-36%E6%B0%AA%E7%99%BE%E7%A7%91?/nMX
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-36%E6%B0%AA%E7%99%BE%E7%A7%91?/579=dvw
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-36%E6%B0%AA%E7%99%BE%E7%A7%91?/iuc=005
- 公共交通接驳的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6-36%E6%B0%AA%E7%99%BE%E7%A7%91?/d2P=WD0
- 城市应急广播的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0-%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/155
- 本地消费场景的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0-%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/vhg
- 软件开发学习中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0-%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/Z60
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0-%E8%85%BE%E8%AE%AF%E8%BF%B0%E8%AF%84?/944=rkj

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
