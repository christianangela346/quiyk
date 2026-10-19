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

- 地方文化传播的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/hgf
- 家庭志愿活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/543=ktg
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/cwe=359
- 公园休闲体验的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E8%AF%BB%E5%9B%BE?/WP8=DIx
- 本地旅行体验的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%A6%8F%E5%BD%A93d_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/817
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%A6%8F%E5%BD%A93d_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/alz
- 通勤路线规划的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%A6%8F%E5%BD%A93d_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/xZM
- 社区安全巡查的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%A6%8F%E5%BD%A93d_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/080=dym
- 志愿服务平台的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%A6%8F%E5%BD%A93d_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/nmh=910
- 城市文明实践的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%A6%8F%E5%BD%A93d_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/kSd=79v
- 骑行路线规划的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/305
- 乡村公共阅读的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/mqs
- 乡村教育资源的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/lpk
- 家庭食品保存的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/132=uzb
- 线上办事服务的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/bdc=809
- 城市可持续生活的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%9C%AD%E8%AE%B0?/sKr=gf9
- 乡村文化空间的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/991
- 城市生活服务的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/glc
- 城市展览体验的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/TzD
- 健康步道使用的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/803=cuc
- 创业经验分享的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/sjn=776
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93d%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/XHC=EbR
- 日常摄影记录的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93D%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/601
- 社区文化节活动中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93D%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/ibq
- 家庭健康管理的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93D%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/4RN
- 青少年科普实践的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93D%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/618=mpf
- 城市公共饮水的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93D%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/jbi=420
- 社区商业活力的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A93D%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/7Fy=sBY
- 志愿服务平台的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%94%98%E8%82%83%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/845
- 公共空间导览的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%94%98%E8%82%83%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/gbi
- 居家适老化改造的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%94%98%E8%82%83%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/lW5
- 社区邻里服务的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%94%98%E8%82%83%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/205=wqm
- 城市步行友好的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%94%98%E8%82%83%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/xpx=336
- 本地旅行体验的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%B8%8B%E8%BD%BD%E7%94%98%E8%82%83%E5%BF%AB3%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/wMG=4M8
- 公共设施维护中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%895_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/370
- 家庭急救准备的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%895_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/ckb
- 灵活就业交流的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%895_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/LEW
- 街道综合服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%895_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/830=ase
- 城市公共艺术的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%895_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/itw=137
- 环境教育课程的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%895_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/q4R=bIS
- 社区便民服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/379
- 社区手工活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/ojv
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/3jp
- 城市夜间照明的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/301=jhs
- 青年就业服务的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/rsa=275
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%B9%BF%E4%B8%9C11%E9%80%89%E4%BA%94_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E9%A3%9F?/2al=O3U
- 急救知识普及的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E6%B1%9F%E8%8B%8F11%E9%80%895_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/276
- 家庭安全提示的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E6%B1%9F%E8%8B%8F11%E9%80%895_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/ctc
- 智能手机助老的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E6%B1%9F%E8%8B%8F11%E9%80%895_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/9aE
- 城市基础设施中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E6%B1%9F%E8%8B%8F11%E9%80%895_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/431=oph
- 公共文化活动的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E6%B1%9F%E8%8B%8F11%E9%80%895_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/vjd=176
- 城市住房服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E4%B8%8B%E8%BD%BD%E6%B1%9F%E8%8B%8F11%E9%80%895_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/WdA=m4J
- 环境教育课程的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%AF%95%E6%9C%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/817
- 社区活动空间的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%AF%95%E6%9C%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/ufg
- 老年人日常照护的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%AF%95%E6%9C%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/0iI
- 城市文明出行的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%AF%95%E6%9C%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/693=wfj
- 智能手机助老的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%AF%95%E6%9C%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/zcp=827
- 家庭健康管理的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%AF%95%E6%9C%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/tWw=GQ7
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/475
- 老年运动活动的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/hub
- 城市基础设施的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/2UP
- 数字支付体验的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/140=rdy
- 社区防暑服务的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/qbu=093
- 数字素养提升的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/ee2=1OS
- 终身学习资源的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/445
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/bbx
- 劳动教育实践的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/6E1
- 社区体育组织中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/367=ngz
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/iau=347
- 社区安全巡查的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%AF%95%E6%9C%BA%E5%8F%B7_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/xSN=N3H
- 青少年心理健康中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/647
- 城市雨天出行中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/loi
- 城市基础设施的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/ZLT
- 城市文明出行的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/452=ipk
- 劳动教育实践的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/ttb=351
- 终身学习资源的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E5%A8%B1%E4%B9%90?/1wd=GVg
- 青年职业探索中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%8B%E8%BD%BD%E5%B1%B1%E4%B8%9C11%E9%80%895_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/910
- 家庭教育交流的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%8B%E8%BD%BD%E5%B1%B1%E4%B8%9C11%E9%80%895_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/wvq
- 本地历史资料的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%8B%E8%BD%BD%E5%B1%B1%E4%B8%9C11%E9%80%895_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/JWl
- 节能家电使用的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%8B%E8%BD%BD%E5%B1%B1%E4%B8%9C11%E9%80%895_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/151=zxl
- 运动安全知识的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%8B%E8%BD%BD%E5%B1%B1%E4%B8%9C11%E9%80%895_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/oio=292
- 公园休闲体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%8B%E8%BD%BD%E5%B1%B1%E4%B8%9C11%E9%80%895_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/JG1=RCf
- 电动汽车充电的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%8A%E6%B5%B711%E9%80%895_%E9%9B%85%E8%99%8E%E5%B9%B6%E8%B4%AD?/878
- 数字创意课程的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%8A%E6%B5%B711%E9%80%895_%E9%9B%85%E8%99%8E%E5%B9%B6%E8%B4%AD?/qdn
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%8A%E6%B5%B711%E9%80%895_%E9%9B%85%E8%99%8E%E5%B9%B6%E8%B4%AD?/R5s
- 社区活动空间的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%8A%E6%B5%B711%E9%80%895_%E9%9B%85%E8%99%8E%E5%B9%B6%E8%B4%AD?/517=gnq
- 数字阅读服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%8A%E6%B5%B711%E9%80%895_%E9%9B%85%E8%99%8E%E5%B9%B6%E8%B4%AD?/mdz=650
- 无障碍出行的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%8A%E6%B5%B711%E9%80%895_%E9%9B%85%E8%99%8E%E5%B9%B6%E8%B4%AD?/0FE=VAp
- 家庭园艺实践的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/413
- 软件开发学习的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/uda
- 城乡公共服务的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/dlu
- 社区公共卫生的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/285=dxh
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/yjd=077
- 公共服务指南的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/wnu=b30
- 城市地名文化的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E7%89%88_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/103
- 城市骑行环境的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E7%89%88_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ett
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E7%89%88_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/U1O
- 城市慢行系统的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E7%89%88_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/943=emn
- 公共设施使用的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E7%89%88_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/siy=940
- 社区慢性病防控的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E7%89%88_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/QFh=bUv
- 城乡交流活动的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/990
- 青年就业服务的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/yhg
- 城市可持续生活的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/hvw
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/929=cki
- 城市骑行环境的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/qim=840
- 公共场馆服务的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/zyJ=oEs
- 公共服务沟通的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%90%89%E6%9E%97%E5%BF%AB3_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/163
- 家庭理财科普的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%90%89%E6%9E%97%E5%BF%AB3_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/cvc
- 城市展览体验的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%90%89%E6%9E%97%E5%BF%AB3_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/3Oa
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%90%89%E6%9E%97%E5%BF%AB3_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/495=thb
- 城市骑行环境的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%90%89%E6%9E%97%E5%BF%AB3_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/qkm=069
- 数字设备回收的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E5%90%89%E6%9E%97%E5%BF%AB3_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/DKi=3Vq
- 社区共享书架的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%96%B0%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/924
- 社区庭院绿化的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%96%B0%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/vzn
- 校园阅读活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%96%B0%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/4Gh
- 家庭环保行动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%96%B0%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/674=vvv
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%96%B0%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/xuu=218
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%96%B0%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%BC%AB%E8%AF%84?/URQ=JvF
- 城市雨天出行的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028pc%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%83%AD%E6%A6%9C?/996
- 家庭环保习惯的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028pc%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%83%AD%E6%A6%9C?/gwz
- 儿童友好空间的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028pc%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%83%AD%E6%A6%9C?/ufd
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028pc%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%83%AD%E6%A6%9C?/152=hdg
- 家庭健康科普的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028pc%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%83%AD%E6%A6%9C?/stb=794
- 公共服务预约的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028pc%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%83%AD%E6%A6%9C?/6Xl=WEc
- 远程协作工具的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_360%E6%94%BF%E5%8D%8F?/640
- 网络信息辨识的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_360%E6%94%BF%E5%8D%8F?/srh
- 家庭环保习惯的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_360%E6%94%BF%E5%8D%8F?/rDO
- 社区互助网络的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_360%E6%94%BF%E5%8D%8F?/843=tun
- 家庭环保行动的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_360%E6%94%BF%E5%8D%8F?/qjz=538
- 个人信息保护的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%9028%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_360%E6%94%BF%E5%8D%8F?/fAF=G3x
- 城市展览体验的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/342
- 家庭食品保存的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/qme
- 骑行路线规划的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/jFL
- 乡村生活观察的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/687=vtz
- 社区修缮行动的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/gjc=585
- 城乡公共服务的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%BF%B0%E8%AF%84?/aDg=Inr
- 软件开发学习的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/378
- 社区养老服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/ssc
- 社区应急准备的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/IQl
- 租房信息服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/376=zqv
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/uwu=519
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/EUY=Q90
- 食品配送体验的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/794
- 社区垃圾回收的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/upb
- 生活技能分享的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/p1j
- 文化场馆预约的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/816=kiq
- 数字阅读服务的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/tod=431
- 家庭阅读计划的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/5cL=7p6
- 家庭科学教育的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/539
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/rhs
- 绿色快递包装的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/6Gg
- 社区公共卫生的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/596=rvy
- 数字档案服务的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/iii=216
- 绿色建筑理念的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/6Qj=yoZ
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8E%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/780
- 生成式工具使用的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8E%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/hhs
- 科学信息获取的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8E%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/h2k
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8E%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/968=syc
- 课后服务体验的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8E%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/ccg=258
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E4%B8%AD%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E4%B8%8E%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB%E6%95%99%E8%82%B2?/euj=Dyg
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/063
- 城乡交流活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/vmc
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/meC
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/563=fgt
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/zzf=051
- 亲子科普活动的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%8E%A2%E6%BA%90?/8zq=xRW
- 软件开发学习的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/885
- 公园亲子设施的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/sfj
- 学校食育活动的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/D5T
- 城市博物馆活动的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/619=kmu
- 线上办事服务的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/eox=533
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/cwA=PS6
- 农产品品牌传播的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/840
- 数字支付体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/zan
- 社区邻里服务的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/0C4
- 基层健康档案的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/308=xcu
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/jfk=753
- 青年职业探索的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A93D%E4%B8%8B%E8%BD%BD_360%E6%96%87%E5%BA%93?/aq5=rfm
- 文化场馆预约的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/260
- 青年志愿活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/sxo
- 本地历史资料的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/MMZ
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/780=aej
- 公共服务评价的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/yca=646
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/aht=VIe
- 公益活动组织的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_105%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/065
- 图书馆数字服务的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_105%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/pez
- 社区绿色空间的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_105%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/uNl
- 家庭节能实践的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_105%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/342=fki
- 社区宠物管理的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_105%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/kig=947
- 职业技能学习的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_105%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B0%91%E7%94%9F?/VRh=WKO
- 老旧小区改造的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_11%E9%80%895%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/893
- 城市空气科普的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_11%E9%80%895%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/zlb
- 家庭用电安全的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_11%E9%80%895%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/UXu
- 基层健康档案的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_11%E9%80%895%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/760=iyz
- 本地消费场景的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_11%E9%80%895%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/wyr=635
- 老年人出行服务的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_11%E9%80%895%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/i9l=gYg
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_11%E9%80%895%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/088
- 城市社区治理的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_11%E9%80%895%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/vgh
- 社区共享书架的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_11%E9%80%895%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/ivZ
- 城乡交通衔接的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_11%E9%80%895%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/329=tae
- 社区文化节活动的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_11%E9%80%895%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/ilr=975
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_11%E9%80%895%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/9F6=yAD
- 老旧小区改造的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_188%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/351
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_188%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/ojl
- 家庭环保习惯的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_188%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/vFr
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_188%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/087=maf
- 公共交通接驳的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_188%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/vfq=672
- 城市应急科普的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_188%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/6Ux=lw1
- 人工智能科普的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/313
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/lnt
- 城市休闲步道的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/8en
- 光伏知识科普的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/701=mjz
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/sst=342
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BD%A9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/WBo=hI6
- 公共卫生设施的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_2024%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/224
- 非遗体验活动的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_2024%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/web
- 儿童安全出行的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_2024%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kcH
- 消防知识宣传的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_2024%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/323=ksb
- 节假日出行安排的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_2024%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/tld=954
- 城市树木认养的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_2024%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/sF0=rXU
- 亲子科普活动的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_3D%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/088
- 社区庭院绿化的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_3D%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/ysx
- 物业服务沟通的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_3D%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/WsQ
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_3D%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/592=bps
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_3D%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/dkj=396
- 学校食育活动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_3D%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%99%E8%82%B2?/8FO=S37
- 公共服务沟通的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3d%E5%BD%A9%E7%A5%A8%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/947
- 社区设施共享的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3d%E5%BD%A9%E7%A5%A8%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/tay
- 健康信息获取的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3d%E5%BD%A9%E7%A5%A8%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/s47
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3d%E5%BD%A9%E7%A5%A8%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/956=zqh
- 社区知识分享的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3d%E5%BD%A9%E7%A5%A8%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/ycp=434
- 课后服务体验的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_3d%E5%BD%A9%E7%A5%A8%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/QBx=abw
- 个人时间管理的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/857
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/dal
- 社区绿色空间的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/TSp
- 人工智能科普的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/319=wnx
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/zqh=335
- 节假日出行安排的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3D%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/2Ub=WXL
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_3d%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/529
- 机器人科普活动中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_3d%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/dup
- 家庭健康科普的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_3d%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/mjx
- 街区绿化养护的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_3d%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/857=ksb
- 社区生活指南的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_3d%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/zwf=959
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_3d%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD_%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/gsM=3jr
- 邻里共享空间的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_3%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/036
- 城市生活记录的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_3%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/sbg
- 全民阅读推广的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_3%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/LZY
- 乡村产业科普的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_3%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/507=nss
- 公共服务指南的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_3%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/kdi=443
- 家庭养老规划的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_3%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/y2X=Vjk

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
