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

- 老年数字阅读的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/bei=612
- 城市便民驿站的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/eiY=ukN
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E9%A3%9F%E5%93%81?/358
- 城市绿色交通的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E9%A3%9F%E5%93%81?/isx
- 街区绿化养护的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E9%A3%9F%E5%93%81?/Uqd
- 城市慢行系统的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E9%A3%9F%E5%93%81?/630=fqf
- 社区家政服务的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E9%A3%9F%E5%93%81?/vkt=633
- 青年志愿活动的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E9%A3%9F%E5%93%81?/aH3=Y4x
- 本地旅行体验的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/464
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/dkc
- 生活技能分享的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/6zZ
- 社区公共议事的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/069=uwq
- 老年人文化生活的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/lab=348
- 在线学习体验的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%9F%8E%E4%BA%8B?/2xx=9Wg
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/746
- 城市运动公园的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/yco
- 城市人文观察的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/x9H
- 城市公共艺术的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/743=hwy
- 家庭运动计划的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/ejk=784
- 城市基础设施的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%AF%94%E7%89%B92.0%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/Cm2=vKf
- 青少年科普实践的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/741
- 乡村生态观察的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/tez
- 绿色办公实践的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/Zgq
- 市民意见收集的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/846=bnb
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/oyu=618
- 绿色校园实践的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/Zfz=lJ3
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/492
- 市民意见收集的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/qns
- 数字公共文化的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/YLo
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/673=xca
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/bri=865
- 公共交通接驳的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%AF%94%E7%89%B9%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/3lc=g4R
- 社区便民集市的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/288
- 乡村生活观察的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/cll
- 青年职业探索的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/idd
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/022=rjv
- 图书借阅体验的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/wmj=216
- 公共空间导览的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pc%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/np3=91B
- 健康步道使用的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/615
- 社区消防演练的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/bgg
- 休闲运动入门的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/oBD
- 地方文化传播的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/230=bjv
- 城市步行友好的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/hja=822
- 农业科普体验的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%8D%97%E5%AE%AB%E6%AF%94%E7%89%B928%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/gIi=k5r
- 职业技能学习的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/587
- 城市可持续生活的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/txe
- 公共文化活动的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/rwG
- 光伏知识科普的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/757=npe
- 节气饮食文化的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/ndo=297
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_28%E9%A2%84%E6%B5%8B%E7%BD%91%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E8%82%A1?/nX9=z3s
- 公共文化活动的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/736
- 儿童运动体验的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/kkg
- 城市文化路线的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/0Dr
- 家庭照护支持的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/251=ijc
- 数字素养提升的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/kuq=355
- 机器人科普活动的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_28%E9%A2%84%E6%B5%8B%E5%99%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/weQ=y3b
- 家庭防灾准备的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/326
- 科学运动指导的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/oas
- 科普展览体验的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/Uzb
- 乡村教育资源的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/909=crf
- 公园亲子设施的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/rjb=477
- 课后服务体验的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/875=GyF
- 街区道路维护的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E7%9F%A5%E4%B9%8E%E7%9E%AD%E6%9C%9B?/312
- 社会体育指导的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E7%9F%A5%E4%B9%8E%E7%9E%AD%E6%9C%9B?/eby
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E7%9F%A5%E4%B9%8E%E7%9E%AD%E6%9C%9B?/f4N
- 基层健康档案的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E7%9F%A5%E4%B9%8E%E7%9E%AD%E6%9C%9B?/623=yfv
- 数字艺术创作的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E7%9F%A5%E4%B9%8E%E7%9E%AD%E6%9C%9B?/nhv=694
- 家庭理财科普的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E7%9F%A5%E4%B9%8E%E7%9E%AD%E6%9C%9B?/OZP=DU9
- 城市树木认养的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/214
- 老年运动活动的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/ssf
- 节约用水实践的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/zmA
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/964=qkw
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/sto=438
- 在线学习体验的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/wqy=lC2
- 绿色消费选择中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/342
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/vuu
- 老年数字阅读的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/tjK
- 城市绿道建设从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/167=qtx
- 儿童运动体验中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/smw=655
- 休闲运动入门的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%87%A4%E5%87%B0%E9%A2%84%E6%B5%8B28%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/5bY=kxT
- 图书借阅体验的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/329
- 社区应急准备有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/mnh
- 社区健康讲座的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/IXf
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/045=szr
- 无障碍出行的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/ipr=754
- 社区养老服务的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E9%97%BA%E8%9C%9C28%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/m1K=Z2K
- 健康信息获取的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/590
- 城市绿色交通的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/vrj
- 文明养宠科普的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/5qC
- 社区防暑服务的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/179=wxz
- 读书会组织的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/wio=028
- 城市应急科普的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_pcjnd333.zyx%E9%9B%AA%E7%90%83%E9%A2%84%E6%B5%8B2.8_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/iBh=8QY
- 便民信息查询的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/521
- 农村环境治理的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/iwq
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/YQq
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/427=ynl
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/ikl=783
- 基层健康服务的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%B2%BE%E5%87%8628%E9%A2%84%E6%B5%8B%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/Bag=nnh
- 食品配送体验的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/074
- 老年数字阅读中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/bur
- 数字公共文化的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/7Zr
- 无障碍出行的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/630=hqk
- 社区快递服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/jxz=951
- 绿色消费选择中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/qr8=ygA
- 数字阅读服务的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/144
- 基层健康服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/kme
- 便民信息查询的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/xUn
- 城市文化路线的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/969=kqs
- 地方民俗记录的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/uwz=712
- 智慧停车服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E6%9C%80%E5%BC%BA%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/BPw=OX7
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/242
- 学校体育活动的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/eef
- 租房信息服务的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/Au0
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/805=aqu
- 基层医疗预约的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/nse=284
- 社区学习活动的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/euh=qY1
- 老年人出行服务的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/022
- 乡村产业科普的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/rxc
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/3JZ
- 无障碍出行中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/145=fzx
- 远程协作工具的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/eev=953
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E7%8C%9B%E9%BE%99%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/szA=mhe
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/756
- 数字生活课堂的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/plj
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/uwz
- 健康饮食教育的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/766=gjn
- 数字学习资源的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/htr=667
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%9028%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E6%91%84%E5%BD%B1?/HlG=Cou
- 公益活动组织的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/924
- 社区艺术活动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/pmv
- 社区活动策划的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/2dh
- 城市步行环境的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/908=dmc
- 旧物循环利用中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/qhv=848
- 社区心理支持的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_PC%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/1V4=cPX
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8Bpc2.8_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/007
- 基层健康档案的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8Bpc2.8_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/obz
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8Bpc2.8_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/kXD
- 数字档案服务的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8Bpc2.8_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/318=rkc
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8Bpc2.8_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/crh=508
- 公共设施维护的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8Bpc2.8_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/I8C=3Mh
- 生活服务数字化的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/038
- 城市公共自行车的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/wfk
- 家庭科学教育的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/6Fg
- 社区消防演练的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/952=xvm
- 儿童安全出行的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/qrf=990
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%A8%B1%E4%B9%90?/jLP=p6H
- 社区家政服务的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/020
- 社区互助网络的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/phm
- 个人信息保护的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/GQ1
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/453=dht
- 社区科普课堂的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/wpn=173
- 居民健康教育中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_PC%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/uzl=RYC
- 科技馆参观体验的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/792
- 家庭运动计划的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/ano
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/X0u
- 家庭节能实践的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/014=ige
- 家庭健康科普的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/wcm=149
- 城市公共自行车的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/ZCK=rcg
- 城市公共艺术的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_PC%E8%87%86%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/069
- 市民热线服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_PC%E8%87%86%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/lhf
- 邻里互助活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_PC%E8%87%86%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/vKm
- 公共服务预约的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_PC%E8%87%86%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/398=zpo
- 口袋公园建设的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_PC%E8%87%86%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/dku=555
- 数字阅读服务的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_PC%E8%87%86%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/CNR=i9f
- 公共图书馆服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/430
- 城市生活服务的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/nvr
- 数字创意课程的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/I6V
- 垃圾分类指导的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/795=goa
- 城市地名文化的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/qzs=225
- 绿色出行服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E5%A4%A7%E7%99%BD%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/5ec=66y
- 城市休闲步道的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/835
- 环境监测科普的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/zjx
- 社区养老服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/vEx
- 社区家校合作中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/751=gol
- 青年职业探索的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/udw=579
- 社区宠物管理的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_pc%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%A4%A9%E6%88%90%E8%B4%A2%E7%BB%8F?/WA7=ASg
- 社区邻里服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/986
- 街区小店体验的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/wlh
- 科学教育活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/sRo
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/631=qly
- 老旧小区改造的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/tew=526
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B210%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/vYy=Z20
- 学校体育活动的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/235
- 城市夜间照明的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/nfo
- 便民维修服务的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/j69
- 城市体育设施的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/566=zwq
- 基层健康服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/orq=537
- 家庭环保习惯的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/UyZ=qWq
- 地方文化传播的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/364
- 开放式学习空间的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/mto
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/q6a
- 社区手工活动的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/376=alw
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/vdf=488
- 邻里共享空间的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9C%88%E5%AD%90?/8bA=5yC
- 城市共享单车的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/121
- 校园社团活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/awg
- 青少年科普实践的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/vEA
- 乡村阅读空间的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/778=fng
- 数字创作工具的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/syx=267
- 儿童户外活动的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%96%AF%E7%8B%8228%E6%8C%82%E6%9C%BA%E6%B0%B8%E8%B5%9A%E6%A8%A1%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%A7%91%E6%8A%80?/AuL=lqV
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/932
- 社区安全巡查的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/cic
- 社区休闲设施的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/T4Q
- 城市运动公园的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/446=pwk
- 家庭消费规划的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/dhf=855
- 地方戏曲体验的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/Joq=6QI
- 电子商务服务的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/048
- 公共空间照明的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/vas
- 城市运动公园的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/bOU
- 农村环境治理的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/572=ajw
- 城市树木认养的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/hzy=060
- 数字课堂应用的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%B0%91%E7%94%9F?/oXG=TiG
- 文化场馆预约的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/702
- 节气饮食文化的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/ald
- 智能家居应用的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/JvV
- 安全出行教育中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/453=tiz
- 环境监测科普的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/quz=597
- 公共空间导览的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E7%99%BD%E9%A2%84%E6%B5%8B28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E7%AE%97%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/JEC=W0F
- 家庭用电安全的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/518
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/usb
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/iMP
- 儿童安全出行的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/000=ean
- 数字设备回收的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/igd=043
- 城市微更新实践的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E6%8C%82%E6%9C%BA%E6%A8%A1%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%A4%B4%E6%9D%A1?/H9I=DYB
- 垃圾分类指导的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/751
- 公共空间休憩的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/evl
- 城市住房服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/DkE
- 城市夜间照明的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/562=pnx
- 科学观察活动的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/kml=149
- 文化场馆预约的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F28%E7%A8%B3%E5%AE%9A%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E8%B4%B7?/SeH=rMI
- 老年学习活动的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/993
- 家庭健康科普的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/wrr
- 新能源出行的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/ehZ
- 社区防暑服务的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/928=xph
- 城市微更新实践的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/hdv=390
- 线上办事服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%9F%8E%E4%BA%8B?/yfg=PVe
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/123
- 数字公共文化的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/uoq
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/V0o
- 社区快递服务的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/784=pwy
- 城市骑行环境的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/zpc=888
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9Fpc28%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/LaE=nig
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/368
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/cfk
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/xeZ
- 城乡公共服务中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/055=koa
- 租房信息服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/avx=704
- 城市体育设施的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/LW3=NSM
- 公共服务数字化的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%B1%87%E5%B8%82?/921
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F28%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%B1%87%E5%B8%82?/due

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
