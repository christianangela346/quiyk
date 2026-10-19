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

- 街区小店体验的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/614
- 社区协商议事的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/xph
- 青年职业探索的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/vmM
- 环境监测科普的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/637=ckn
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/qvq=845
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/EvX=ekY
- 地方戏曲体验的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/572
- 小区停车协商的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/bxa
- 家庭急救准备的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/3VL
- 老年数字阅读的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/392=gst
- 市民热线服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/qpc=130
- 家庭急救准备的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/i7r=N4d
- 城市空气科普的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/714
- 社区科普课堂的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/jiu
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/1oK
- 社区学习活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/734=nlw
- 社区互助网络的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/bkx=495
- 智能手机助老的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/qng=G7k
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A-%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/732
- 公交无障碍服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A-%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/dxj
- 城市水环境观察的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A-%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/1W0
- 校园节能行动的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A-%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/710=fzu
- 远程协作工具的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A-%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/grf=156
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A-%E8%B4%A2%E7%BB%8F%E7%88%86%E6%96%99?/1BM=8nF
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83-%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/194
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83-%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/ees
- 公共服务指南的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83-%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/USd
- 家庭消费规划的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83-%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/555=wmb
- 租房信息服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83-%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/vxe=423
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83-%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/UrS=h8J
- 公园亲子设施的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/127
- 环境监测科普的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/fyf
- 城市住房服务中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/9Fy
- 公共服务沟通的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/106=lqm
- 城市博物馆服务的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/dto=167
- 城乡交流活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/LqF=pnJ
- 市民意见收集的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/391
- 邻里共享空间的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/tgz
- 机器人科普活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/dUf
- 非遗课堂体验的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/435=faf
- 社区防暑服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/gbr=275
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E5%AE%B6%E5%A5%BD-%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/kxU=M9Y
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91-360%E9%9F%B3%E4%B9%90?/960
- 数字支付体验的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91-360%E9%9F%B3%E4%B9%90?/ukn
- 儿童安全出行的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91-360%E9%9F%B3%E4%B9%90?/4D5
- 科学健身方法的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91-360%E9%9F%B3%E4%B9%90?/613=arn
- 城市微更新实践的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91-360%E9%9F%B3%E4%B9%90?/gko=459
- 社区家校合作的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E500%E5%A4%A7%E5%8F%91-360%E9%9F%B3%E4%B9%90?/Bmi=EEu
- 家庭消费规划的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/319
- 社区邻里服务的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/xmc
- 绿色出行服务的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/3Da
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/793=oyf
- 公共场所导视的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/ajo=722
- 社区公共议事的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B-%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/sVL=xTe
- 绿色校园实践的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/334
- 食品安全科普的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/qht
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/X27
- 青少年心理健康的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/897=ctr
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/wqf=737
- 公共空间照明的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90Welcome%E5%BD%A9%E7%A5%A8-%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/Cd8=48N
- 校园社团活动的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88-%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/809
- 城市共享单车的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88-%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/zoz
- 居家防滑改造的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88-%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/ltF
- 社区活动空间的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88-%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/949=vty
- 邻里互助活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88-%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/uxn=040
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88-%E6%8A%96%E9%9F%B3%E5%BF%AB%E8%AE%AF?/ADF=jLQ
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/892
- 公共服务指南的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/kxx
- 小区公共照明的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/H2Y
- 居民健康教育的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/258=qeh
- 社区设施共享的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/byp=013
- 城市博物馆服务的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/u0i=a7U
- 城市慢行系统的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/504
- 环境监测科普的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/gwd
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/z1P
- 科学观察活动的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/988=cmr
- 城市文化路线的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/ynf=000
- 城市雨天出行的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/Vii=2yM
- 绿色办公实践的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97-%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/612
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97-%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/mlv
- 城市公共标识中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97-%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/ujp
- 社区活动策划的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97-%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/219=ulq
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97-%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/iiz=587
- 科学健身方法的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E7%BD%91%E7%AB%99%E8%B5%9A%E9%92%B1%E5%8F%AF%E4%BF%A1%E5%90%97-%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/8KU=RZc
- 社区学习活动的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/359
- 家庭园艺实践的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/reg
- 城市展览体验的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/2FU
- 公共空间休憩的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/877=gic
- 城市公共艺术的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/xtm=966
- 社区慢性病防控的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/hG0=Agc
- 小区停车协商的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/366
- 生活垃圾减量的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/ubf
- 城市文明实践的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/XEZ
- 老年人出行服务的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/360=ref
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/vba=963
- 公共服务沟通的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/uSx=Ebn
- 传统节日科普的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/969
- 社区修缮行动的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/pft
- 休闲运动入门的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/yUG
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/588=rqc
- 城市住房服务的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/lbg=242
- 公共文化活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%90%88%E4%BD%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/CsI=flF
- 运动安全知识的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%28kuai3%29-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/523
- 本地消费场景的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%28kuai3%29-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/cdo
- 绿色校园实践的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%28kuai3%29-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/HJn
- 青少年科普实践的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%28kuai3%29-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/986=fod
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%28kuai3%29-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/ffe=868
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%28kuai3%29-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/XVZ=5dM
- 社区手工活动的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8-%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/427
- 城市社区治理的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8-%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/zyb
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8-%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/B5T
- 社区活动策划的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8-%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/196=fpy
- 家庭消费规划的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8-%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/jio=536
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BD%91%E7%AB%99500%E5%BD%A9%E7%A5%A8-%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/SDY=YVV
- 乡村阅读活动的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89-%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/113
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89-%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/kav
- 公共服务沟通的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89-%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/aXK
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89-%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/940=srr
- 家庭健康管理的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89-%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/xkf=701
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E4%BC%97%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8com%E7%BD%91%E5%9D%80%EF%BC%88KK%EF%BC%89-%E8%B0%B7%E6%AD%8C%E8%AF%84%E8%AE%BA?/s9y=8pb
- 公共空间安全的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE-%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/283
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE-%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/oug
- 青年职业探索的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE-%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/aBz
- 城市人文观察的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE-%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/416=ocv
- 校园节能行动的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE-%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/xaf=258
- 绿色生活实践的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%BD%91%E7%AB%99%E5%BB%BA%E8%AE%BE-%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/YjB=9id
- 城市夜间照明的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84-%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/862
- 街区更新实践中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84-%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/paj
- 本地消费场景的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84-%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/y2A
- 家庭节能设备中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84-%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/951=jlz
- 城市公共座椅的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84-%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/drg=507
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%8E%A8%E8%8D%90%E6%AD%A3%E8%A7%84-%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/w1I=EwR
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89-360%E8%82%A1%E7%A5%A8?/992
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89-360%E8%82%A1%E7%A5%A8?/dxn
- 公共空间安全的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89-360%E8%82%A1%E7%A5%A8?/tNU
- 社区商业活力的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89-360%E8%82%A1%E7%A5%A8?/017=pwm
- 远程协作工具的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89-360%E8%82%A1%E7%A5%A8?/kcq=325
- 城市空气科普的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89-360%E8%82%A1%E7%A5%A8?/NdY=HW5
- 公共服务数字化的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/950
- 基层健康档案的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/mdd
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/1EF
- 开源技术交流的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/750=jqj
- 街区绿化养护的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/sxn=256
- 社区花园共建的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_Welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/cJe=7wo
- 家庭运动计划的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/709
- 周末休闲规划的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/iyj
- 社区文化节活动的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/hGh
- 地方民俗记录的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/177=ido
- 公共设施使用的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/qih=357
- 节能家电使用的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%EF%BC%88KK%EF%BC%89-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/wes=27g
- 绿色快递包装的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89-%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/844
- 城市文明出行的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89-%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/xov
- 公共空间安全的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89-%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/ev2
- 城市文化路线的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89-%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/798=ykg
- 电子商务服务的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89-%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/pep=181
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%EF%BC%88KK%EF%BC%89-%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/sM4=aYe
- 小区电梯维护的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/351
- 农贸市场环境的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/rop
- 社区家校合作的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/qGo
- 家庭阅读计划的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/152=fsk
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/ywa=729
- 物业服务沟通的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Elv%E4%BA%89%E9%9C%B8-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/IMO=J1i
- 环境教育课程的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8-%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/728
- 城乡公共服务的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8-%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/kkk
- 数字生活课堂的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8-%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/n82
- 青年职业探索的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8-%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/483=qlj
- 老年友好服务的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8-%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ekr=746
- 网络信息辨识的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8-%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/uHD=EuD
- 社区便民集市的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/846
- 小区停车协商的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/wmv
- 乡村文化活动的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/OY3
- 家庭健康科普的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/502=rgl
- 智能手机助老的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/asc=710
- 市民热线服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/AHT=aE9
- 个人时间管理的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B-%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/817
- 小区电梯维护的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B-%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/rqj
- 社区文化节活动的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B-%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/iZ2
- 绿色校园实践的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B-%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/234=nyz
- 创业经验分享的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B-%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/vda=758
- 数据分析入门的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E4%B8%80%E6%9C%9F%E5%8F%B7%E7%A0%81%E9%A2%84%E6%B5%8B-%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/i7U=IJ6
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88-%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/883
- 科学观察活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88-%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/fwh
- 城市绿道建设的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88-%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/l2B
- 乡村产业科普的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88-%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/171=eso
- 社区手工活动的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88-%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/zhq=383
- 基层服务创新的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852023%E6%9C%80%E6%96%B0%E7%89%88-%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/vM0=qqL
- 城市树木认养的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96-%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/258
- 城市树木认养的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96-%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/ept
- 社区公共议事的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96-%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/hKp
- 周末休闲规划的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96-%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/432=gis
- 全民健身活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96-%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/uwo=798
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BDapp%E5%BC%80%E5%A5%96-%E8%B0%B7%E6%AD%8C%E9%80%9A%E4%BF%A1?/749=Kz4
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/249
- 社区学习活动的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/qbv
- 青少年户外教育的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/cYx
- 家庭用电安全的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/664=ftc
- 网络信息辨识的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/zmy=350
- 城市文明实践的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/bWW=oyz
- 城市住房服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/365
- 居家适老化改造的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/gps
- 课后服务体验的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/YDy
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/085=ory
- 社区安全巡查的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/nes=166
- 城市社区治理的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E8%99%8E%E5%97%85%E6%8A%95%E7%A5%A8?/vhN=0DP
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/993
- 街区小店体验的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/ovr
- 社区邻里服务的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/X2c
- 城市文明实践的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/048=rfo
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/mlw=770
- 公共空间安全的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/2yp=5KP
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B-%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/437
- 社区交通安全的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B-%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/hzj
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B-%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/CMa
- 亲子科普活动的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B-%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/660=vup
- 公共设施维护的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B-%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/koa=903
- 志愿服务平台的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B-%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/3cu=euB
- 社区托育服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%AF%84%E8%AE%BA?/275
- 非遗课堂体验的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%AF%84%E8%AE%BA?/wdz
- 文化场馆预约的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%AF%84%E8%AE%BA?/Trb
- 城乡公共服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%AF%84%E8%AE%BA?/519=qqm
- 乡村电商实践的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%AF%84%E8%AE%BA?/hfs=277
- 城市游园体验的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%B1%9F%E8%8B%8F%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E8%AF%84%E8%AE%BA?/Jwu=C4I
- 社区教育资源的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/332
- 城市公共厕所的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/bjo
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/tC4
- 电动汽车充电的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/767=imb
- 街头绿植养护的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/tyc=745
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8D%8F?/jx6=feU
- 公共服务指南的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%EF%BC%88KK%EF%BC%89-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/498
- 公共健身器材的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%EF%BC%88KK%EF%BC%89-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/xnl
- 社区知识分享的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%EF%BC%88KK%EF%BC%89-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/6AD
- 旧物循环利用的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%EF%BC%88KK%EF%BC%89-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/387=hkw
- 城市共享单车的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%EF%BC%88KK%EF%BC%89-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/eyb=241
- 绿色校园实践的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%EF%BC%88KK%EF%BC%89-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E8%B5%84?/Imt=9dS
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3app%E8%B4%AD%E5%BD%A9-%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/361
- 急救知识普及的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3app%E8%B4%AD%E5%BD%A9-%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/dtw
- 光伏知识科普中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3app%E8%B4%AD%E5%BD%A9-%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/A3E
- 家庭运动计划的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3app%E8%B4%AD%E5%BD%A9-%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/531=lcp
- 数字便民地图的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3app%E8%B4%AD%E5%BD%A9-%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/hty=752
- 城市绿色交通的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3app%E8%B4%AD%E5%BD%A9-%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/8Zn=f0t
- 社区托育服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/979
- 低碳社区实践的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/alv
- 创业经验分享的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/UYi
- 公共服务沟通的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/343=dqq
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/dgo=881
- 社区托育服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%B7%B4%E8%A5%BF%E8%B4%A2%E7%BB%8F?/aTb=1OH
- 公共服务咨询的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D-%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/195
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D-%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/txf
- 健康步道使用的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D-%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/r6k
- 跨代沟通活动的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8app%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D-%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/821=twb

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
