# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 旧物循环利用的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/847
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/apt
- 个人时间管理的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/BP1
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/295=qao
- 家庭健康管理的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/ees=939
- 社区信息发布的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90Welcome9123%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/qyl=q7z
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/789
- 社区老年食堂的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/mmg
- 租房信息服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/u9X
- 创业经验分享的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/582=qwh
- 青少年户外教育的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/vaw=217
- 社区便民服务的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB%E4%B8%89_%E9%A1%BA%E4%B8%B0%E6%B8%AF%E8%82%A1?/Yf4=GzX
- 数字创作工具的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/492
- 城市应急科普的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/hnx
- 青少年户外教育的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/scN
- 个人数据管理的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/517=ncn
- 社区公共议事中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/bhr=182
- 社区修缮行动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9EI%E5%B7%9D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/7Nq=mBA
- 城市适老服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/984
- 城市公共艺术的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/qjn
- 基层健康服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/hwg
- 节约用水实践的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/123=nph
- 公共服务评价的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/kjy=888
- 节日文化体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/b14=KJU
- 街区更新实践的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/680
- 社区便民集市的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/bvl
- 社区体育组织的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/xUd
- 城市公共空间的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/655=oee
- 城市微更新实践中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/heq=087
- 社区活动策划的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/Z5n=x8k
- 便民信息查询的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/785
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/yhb
- 城乡公共服务的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/DN2
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/778=ajd
- 社区防暑服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/svc=226
- 消防知识宣传的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/ybW=uRm
- 线上办事服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/599
- 校园社团活动的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/bva
- 城市游园体验的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/4y5
- 乡村文化活动的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/764=ejp
- 街区绿化养护的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/sut=387
- 家庭照护支持的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%BA%92%E5%8A%A8%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/aqH=nzb
- 社区手工活动的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/601
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/shl
- 农村环境治理的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/MGJ
- 健康饮食教育的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/572=jbh
- 家庭急救准备的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/vcj=594
- 生活服务数字化的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E9%87%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/xVa=fJm
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/533
- 社区手工活动的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/qqj
- 城市噪声观察的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/4g9
- 开源技术交流的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/283=nfd
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/wqo=919
- 乡村产业科普的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%9F%AD%E4%BF%A1_%E8%B4%A2%E7%BB%8F%E6%8E%A2%E5%BA%97?/x1K=Kqz
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/916
- 电动汽车充电的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/wed
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/Lk1
- 城市应急广播的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/140=chr
- 城市可持续生活的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/exq=699
- 居家防滑改造的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%97%B6%E9%97%B4%E8%B4%A2%E5%AF%8C%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/5Ja=uMT
- 科普展览体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9iv_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/212
- 健康饮水科普的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9iv_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/rrj
- 垃圾分类指导的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9iv_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/JBN
- 无障碍出行中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9iv_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/323=wxx
- 街区道路维护从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9iv_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/skf=132
- 图书馆数字服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9iv_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/XVv=bsR
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/972
- 数字设备回收的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/spe
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/QDI
- 公交无障碍服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/111=qgk
- 基层医疗预约的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/ozm=560
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%87%AD%E8%AF%81%E5%9B%BE%E7%89%87_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/mOe=UjF
- 网络安全教育的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/400
- 消防知识宣传的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/yey
- 课后服务体验的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/gTO
- 社区心理支持的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/527=shx
- 市民热线服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/dky=669
- 健康饮水科普的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E8%B4%AD%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/S6J=0EQ
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%BE%8E%E5%A6%86?/316
- 绿色快递包装的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%BE%8E%E5%A6%86?/ikb
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%BE%8E%E5%A6%86?/3Jx
- 社区快递服务的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%BE%8E%E5%A6%86?/603=agt
- 城市建设科普的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%BE%8E%E5%A6%86?/xxg=877
- 地方美食文化的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9EvIl%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E7%BE%8E%E5%A6%86?/muw=L2S
- 数字地图应用的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/917
- 市民热线服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/kxu
- 城乡公共服务的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/eJU
- 科学观察活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/092=uvn
- 乡村文化活动的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/jhc=506
- 绿色出行服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E9%B3%AF%E5%87%B0%E5%BD%A9%E7%A5%A8785cc_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%BC%80%E8%AF%BE?/zCb=NDZ
- 城市绿色交通的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/553
- 老年数字阅读的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/vos
- 旧物循环利用的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/sL0
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/855=iad
- 绿色出行服务的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/aot=922
- 乡村电商实践的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9welcome%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/lWG=OVv
- 传统节日科普的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/014
- 社区商业活力的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vqn
- 公园无障碍服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/sC8
- 城乡公共服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/885=ldt
- 文明养宠科普中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qyn=196
- 便民服务窗口的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E8%BF%90welcome%E5%A4%A7%E5%8E%85%E8%B4%AD%E5%BD%A9_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lhl=qdl
- 农产品消费体验的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/948
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/bch
- 儿童阅读角的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/kD0
- 地方旅游导览的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/400=rju
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/wzi=548
- 地方文化传播的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9EV%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/DVV=bs0
- 消防知识宣传的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A98VIII_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/246
- 本地旅行体验的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A98VIII_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/pmh
- 乡村教育资源的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A98VIII_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/OQ3
- 急救知识普及的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A98VIII_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/313=dfw
- 家庭安全提示的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A98VIII_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/rqx=829
- 数字便民地图的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A98VIII_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%B4%B7?/VW8=WfH
- 公共空间照明的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_360?/081
- 社区老年食堂的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_360?/bxu
- 文化讲座服务的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_360?/cf8
- 社区活动报名的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_360?/559=kwm
- 数字创作工具的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_360?/rso=542
- 机器学习入门的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_welcome%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%9E_360?/1KQ=faX
- 在线教育体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/125
- 家庭防灾准备的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/biw
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/Wxw
- 城市骑行环境的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/164=vkl
- 社区设施共享的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/zng=557
- 公共场所导视的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/EZo=sMs
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/156
- 老年学习活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/imi
- 数字便民地图的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/xeJ
- 社区商业活力的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/842=uou
- 图书馆数字服务的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/hye=723
- 文明养宠科普的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/EIC=7Ft
- 开放数据应用的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/195
- 绿色校园实践的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/tnz
- 社区花园共建的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/Erw
- 数字艺术创作的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/391=nts
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/yag=794
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/tCb=XZp
- 药品使用科普的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/965
- 公共服务评价的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/wnp
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/o2i
- 校园社团活动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/770=pju
- 城市绿色交通中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/gzg=942
- 社区信息发布的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91---%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/qxY=4sS
- 城市文明实践的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/425
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/xba
- 城市共享单车的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/Lsz
- 社区便利生活的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/298=xqr
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/wmc=123
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_Wolcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/EyQ=Mn1
- 社区体育组织的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/006
- 社区阅读服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/yfk
- 城市公共标识的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/2ew
- 生活垃圾回收的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/508=tsq
- 电子商务服务的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/ccb=993
- 城市微更新实践的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/PEH=pjA
- 科学信息获取的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/416
- 社区邻里服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/wsd
- 公共场所导视的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/bot
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/689=ucy
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/gwb=614
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%EF%BC%8D%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E5%BF%85%E5%BA%94%E5%8D%9A%E5%AE%A2?/LGg=4LS
- 城市公共饮水的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/724
- 儿童友好街区的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/uat
- 城市展览体验的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/ds8
- 课后服务体验中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/574=rsh
- 城市住房服务中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/kpc=942
- 传统节日科普的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/TqM=gGM
- 社区设施共享的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/678
- 社区知识分享的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/asd
- 社区托育服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/toJ
- 城市公共标识的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/612=zfk
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/rcy=826
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91168%E5%BD%A9app_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/9mk=soI
- 公共服务指南的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/026
- 青少年户外教育的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/hjq
- 城乡公共服务的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/TBy
- 创业经验分享的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/976=pdp
- 无障碍出行的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/auh=907
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/RhU=z7X
- 社区艺术活动的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/153
- 城市公共饮水的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/lpu
- 生活垃圾回收的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/gGm
- 就业技能培训的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/486=apl
- 青少年心理健康的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/fau=971
- 租房信息服务的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E5%A8%B1%E4%B9%90?/B0R=qQS
- 城市雨天出行的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/379
- 城市雨天出行的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/rel
- 公园亲子设施中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/uJh
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/241=ovx
- 社区家校合作的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/rtv=395
- 非遗体验活动的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%AF%BC%E5%B8%88_%E5%8D%B3%E5%88%BB%E6%9C%AD%E8%AE%B0?/Lxp=tqa
- 环境监测科普的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/592
- 城市公共厕所的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/rpd
- 本地旅行体验的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/tIm
- 节气饮食文化的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/666=upk
- 校园阅读活动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/sfp=782
- 本地历史资料的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%BE%9F%E8%B0%A3?/qCD=EXs
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/868
- 城市雨天出行的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/wii
- 城市公共厕所的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/rdt
- 家庭志愿活动的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/520=gni
- 城市博物馆活动的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/zhr=454
- 人工智能科普的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/oe9=1wD
- 家庭安全提示中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B4%AD_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/253
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B4%AD_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/ipz
- 老年数字阅读的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B4%AD_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/5hk
- 基层医疗预约的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B4%AD_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/801=oog
- 邻里互助活动的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B4%AD_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/hui=472
- 小区电梯维护的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%B4%AD_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/St3=EVo
- 城市运动公园的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/543
- 家庭照护支持的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/tby
- 公共设施维护的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/qyK
- 旧物循环利用的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/675=acp
- 城市展览体验的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/gcr=359
- 社区科普课堂的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E9%99%95%E8%A5%BF%E5%BF%AB3_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/67W=Kn9
- 城市生活服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/460
- 线上办事服务的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/zih
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/eJ2
- 绿色生活实践的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/139=hug
- 数字公共文化的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/ftl=573
- 家庭科学教育的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%81%A2%E5%A4%8D%E4%BA%86%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/UPY=LEQ
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/535
- 应急物资管理的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/mvv
- 青少年心理健康的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/0Kk
- 家庭阅读计划的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/498=tjz
- 开放式学习空间的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/yuh=298
- 乡村产业科普的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E6%B1%87%E8%B4%A2%E7%BB%8F?/Grq=BpM
- 社区协商议事的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/651
- 城市可持续生活的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/anv
- 城市文化路线的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/zM5
- 老年人出行服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/587=cww
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/qnv=484
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%93%AA%E4%BA%9B%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/v5M=8GO
- 城市公共自行车的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/045
- 公交站点体验的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/pwp
- 街道综合服务的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/o89
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/791=thj
- 公共卫生宣传的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/wki=200
- 社区知识分享的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E5%9C%B0%E6%96%B9?/sHn=Ewj
- 科普展览体验的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/913
- 家庭环保行动的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/xcw
- 开放式学习空间的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/bsf
- 乡村公共服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/929=vrd
- 城市公共自行车的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/mfp=803
- 机器学习入门的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/ybq=6HQ
- 光伏知识科普的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/271
- 校园安全教育的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/yob
- 社区教育资源的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/o0M
- 健康步道使用的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%9C%A8%E5%93%AA%E4%B9%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/140=ogj

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
