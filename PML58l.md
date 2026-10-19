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

- 社区安全巡查的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/1OF
- 城市农夫市集的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/574=hjh
- 城市住房服务的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/hti=181
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/wEx=sGO
- 社区宠物管理的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E7%A5%9E%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/755
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E7%A5%9E%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/yuo
- 城乡交流活动的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E7%A5%9E%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/Qm7
- 口袋公园建设的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E7%A5%9E%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/523=lxm
- 老年数字阅读的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E7%A5%9E%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/rfc=192
- 数据分析入门的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E7%A5%9E%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/Naf=ncU
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/369
- 休闲运动入门的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/aja
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/i4u
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/205=etu
- 骑行路线规划的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/aom=366
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E5%88%AE%E5%88%AE%E4%B9%90_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/LXG=LR9
- 家庭饮食安排的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99pc%E9%A3%9E%E9%A3%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/057
- 健康饮水科普的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99pc%E9%A3%9E%E9%A3%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/gij
- 数字政务体验的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99pc%E9%A3%9E%E9%A3%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/zih
- 便民维修服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99pc%E9%A3%9E%E9%A3%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/649=nnp
- 非遗体验活动的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99pc%E9%A3%9E%E9%A3%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/vgw=710
- 小区电梯维护的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99pc%E9%A3%9E%E9%A3%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E6%96%B9?/LJi=A4r
- 儿童友好空间的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_98pc.ccxj288.cc18pc.cc_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/381
- 社区宠物管理的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_98pc.ccxj288.cc18pc.cc_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/srh
- 城乡公共服务的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_98pc.ccxj288.cc18pc.cc_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/44V
- 跨代沟通活动的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_98pc.ccxj288.cc18pc.cc_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/755=wjc
- 便民服务窗口的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_98pc.ccxj288.cc18pc.cc_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/jlw=677
- 节能家电使用的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%A2%84%E6%B5%8B%E7%BD%91%E5%9D%80_98pc.ccxj288.cc18pc.cc_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/1oz=VJ2
- 社区手工活动的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E5%90%8D%E7%88%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/276
- 城市应急科普的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E5%90%8D%E7%88%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/wjc
- 社区公共餐饮的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E5%90%8D%E7%88%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/emE
- 课后服务体验的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E5%90%8D%E7%88%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/262=ewr
- 家庭环保习惯的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E5%90%8D%E7%88%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/bie=332
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E5%90%8D%E7%88%B5_%E5%BE%97%E7%89%A9%E5%8F%B7%E5%A4%96?/bnt=Wv8
- 社区体育组织的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8D%97%E5%AE%AB28pg%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/925
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8D%97%E5%AE%AB28pg%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/ssr
- 校园节能行动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8D%97%E5%AE%AB28pg%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/qLy
- 社区庭院绿化的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8D%97%E5%AE%AB28pg%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/832=qsf
- 青少年科普实践的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8D%97%E5%AE%AB28pg%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/xog=688
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8D%97%E5%AE%AB28pg%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/4px=SRk
- 家庭健康科普的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8D%97%E5%AE%AB28pg%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/274
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8D%97%E5%AE%AB28pg%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/wyl
- 家庭收纳实践的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8D%97%E5%AE%AB28pg%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/MFn
- 社区艺术活动中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8D%97%E5%AE%AB28pg%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/110=tdx
- 老年智能设备的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8D%97%E5%AE%AB28pg%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/tpf=105
- 绿色生活实践的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8D%97%E5%AE%AB28pg%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/oCh=bXA
- 生成式工具使用的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%97%E5%AE%AB28%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/844
- 健康步道使用的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%97%E5%AE%AB28%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/onb
- 无障碍信息设计的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%97%E5%AE%AB28%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/1uh
- 社会体育指导的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%97%E5%AE%AB28%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/966=hty
- 城市博物馆活动的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%97%E5%AE%AB28%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/xcp=086
- 线上办事服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%97%E5%AE%AB28%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/BX7=TJ1
- 家庭用电安全的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/367
- 儿童友好空间的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/aju
- 生活服务数字化的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/ukX
- 青少年户外教育的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/482=ioz
- 社区养老服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/xyb=767
- 垃圾分类指导的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/KPb=ec9
- 光伏知识科普的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%99%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/072
- 公共空间照明的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%99%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/cjn
- 社区艺术活动的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%99%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/vb0
- 校园安全教育的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%99%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/891=wju
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%99%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/eln=906
- 社区家校合作的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%99%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/2Id=cHi
- 居家适老化改造的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/705
- 骑行路线规划的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/pht
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/w9M
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/887=hoy
- 软件开发学习的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/wqx=546
- 城市公共厕所的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/s1Z=iSs
- 公共服务预约的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/252
- 城市慢行系统中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/ksi
- 社区运动空间的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/LMP
- 城市共享单车的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/904=bmb
- 公园无障碍服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/dpg=760
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%8D%8E%E5%88%9B%E8%B4%A2%E7%BB%8F?/9XT=bCi
- 社区法律科普的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/883
- 骑行路线规划的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/rmw
- 老年人出行服务的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/xat
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/512=lcx
- 地方文化传播的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/fzo=660
- 城市共享单车的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/uEa=SSg
- 乡村阅读活动的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/385
- 校园节能行动的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/sbk
- 公共交通接驳的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/Xc0
- 青少年户外教育的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/023=jto
- 绿色校园实践的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/tsc=861
- 科学观察活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/OEo=wnn
- 社区互助网络的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B8%80%E4%BB%BD%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/137
- 社区文化传播的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B8%80%E4%BB%BD%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/llk
- 公交站点体验的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B8%80%E4%BB%BD%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/FPZ
- 城市建设科普的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B8%80%E4%BB%BD%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/543=eyy
- 市民意见收集的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B8%80%E4%BB%BD%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/jce=143
- 社区商业活力的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B8%80%E4%BB%BD%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/mWN=q1z
- 科普展览体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/251
- 节约用水实践的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/zmt
- 智慧城市体验中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/2L9
- 家庭节能实践的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/258=vis
- 地方美食文化的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/zvu=139
- 社区应急准备的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/gmh=J8S
- 社区互助网络的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/358
- 社区文化节活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/bft
- 城市生活服务的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/QzL
- 街区更新实践的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/626=rjy
- 城市生活记录的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/kyu=695
- 社区邻里服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Vo6=THG
- 城市适老服务的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/101
- 公共空间安全的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/cbz
- 数字素养提升的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/2GE
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/380=gqo
- 公共空间安全的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/otv=113
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E5%BF%AB%E6%8A%A5?/eun=2qf
- 儿童友好空间的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/732
- 社区商业活力的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/rmi
- 网络安全教育的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/mcP
- 志愿服务平台的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/235=awn
- 公园休闲体验的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/gbj=300
- 老年人出行服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/9VI=qrK
- 开源技术交流的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/739
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/vma
- 乡村公共阅读的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/dju
- 社区运动空间的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/023=gya
- 家庭急救准备的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/epc=136
- 社区故事采集的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/Avz=PLq
- 青少年编程学习的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/418
- 基层健康档案的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/wug
- 家庭环保行动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/Hse
- 开放式学习空间的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/767=iuf
- 数字便民地图的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/hrx=835
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/aFU=7gc
- 城市体育设施的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/165
- 旧物循环利用的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/adt
- 健康饮食教育的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/haG
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/723=hko
- 儿童运动体验的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/ygr=820
- 社区绿色空间的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/IA7=d0l
- 公共服务沟通的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/433
- 社区读书角建设的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/adf
- 老年人文化生活的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/l6P
- 健康步道使用的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/138=zdt
- 在线学习体验的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/knt=881
- 公共服务评价的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%9C%9B?/kKc=HSn
- 科学运动指导的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/853
- 周末休闲规划的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/gzd
- 城市农夫市集的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/xWO
- 小区停车协商的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/501=zch
- 儿童安全出行的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/dru=627
- 职业技能学习的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E7%A0%81?/JRF=QWH
- 环境教育课程的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/856
- 数字学习资源的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/dog
- 家庭安全提示的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/Hjp
- 灵活就业交流的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/602=zwy
- 垃圾分类指导的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/ztf=888
- 社区手工活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/ntj=7c8
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/866
- 城市公共饮水的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/jud
- 线上办事服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/pMO
- 科普展览体验的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/504=roj
- 城市公共座椅的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/xkx=700
- 开源技术交流的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/p7J=wJI
- 在线教育体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/615
- 软件开发学习的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/kyb
- 家庭理财科普的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/i3z
- 急救知识普及的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/617=gpt
- 城市博物馆活动的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/wod=432
- 社区生活指南的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E4%BC%98%E4%BF%A1_%E5%BF%AB%E6%89%8B%E7%90%86%E8%B4%A2?/91y=dkV
- 无障碍出行的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/445
- 新能源出行的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/mfp
- 垃圾分类指导的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/0UD
- 全民阅读推广的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/310=plo
- 公共空间照明的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/cxn=406
- 社区商业活力的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9C%B0%E6%96%B9?/1jw=gaa
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/207
- 家庭环保行动的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/hwg
- 生活服务数字化的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/b4O
- 城市基础设施的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/638=hcm
- 社区养老服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/mgq=567
- 小区停车协商的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%AD%E8%89%BA?/GUp=3gG
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/197
- 全民阅读推广的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/gqf
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/7de
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/126=qba
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/jrj=689
- 运动安全知识中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/7N5=spx
- 亲子阅读活动的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/255
- 线上办事服务的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/idy
- 传统节日科普的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/KyV
- 社区生活指南的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/672=asi
- 社区心理支持的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/ukw=770
- 公共设施使用的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%86%9B%E4%BA%8B?/ksN=RNv
- 家庭运动计划的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/964
- 家庭阅读计划的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/ypm
- 青年志愿活动的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/o3N
- 社区消防演练的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/792=gkx
- 乡村休闲旅游的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/ual=649
- 乡村产业科普的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/yhx=dQZ
- 城市生活记录的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/050
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/xlf
- 新能源出行的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/eXJ
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/757=psp
- 环境教育课程的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/gls=369
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/9IU=k1I
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/537
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/uty
- 城市公共空间的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/s9G
- 志愿者培训交流的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/613=lrd
- 公共服务预约的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/rnb=167
- 科学健身方法的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/yLg=OYk
- 软件开发学习的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/493
- 农产品消费体验的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/kyo
- 公交站点体验的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/xin
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/624=cpp
- 数字艺术创作的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/bgv=560
- 城乡交流活动的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%B8%A6%E8%B5%9A_%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/Yo2=9bP
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/333
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/gbv
- 社区花园共建的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/frn
- 急救知识普及的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/360=wmx
- 社区快递服务的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/nez=952
- 食品配送体验的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/GbB=Z0J
- 科技馆参观体验的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/443
- 公共服务预约的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/vbo
- 城市文化路线的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/47R
- 社区手工活动的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/708=iou
- 旧物循环利用中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/zqx=158
- 节日文化体验的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/fxi=nTf
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/124
- 基层健康档案的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/dim
- 社区知识分享的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/7r1
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/292=ccu
- 社区花园共建的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/kyt=438
- 生活垃圾回收的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/W6k=nzg
- 通勤路线规划的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/457
- 社区文化节活动的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/oxw
- 老年数字阅读中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/EJ0
- 课后服务体验的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/475=diw
- 社区休闲设施中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/gjq=503
- 本地旅行体验的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/C94=GJl
- 应急物资管理的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/955
- 城市步行环境的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/cvt
- 青年职业探索的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/80L
- 城市展览体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/758=cmn
- 健康信息获取的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/yea=069
- 青年志愿活动的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BE%A4%E8%AE%A1%E5%88%92%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%8E%A2%E6%BA%90?/QTf=b7p
- 周末休闲规划的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/677
- 城市文明实践的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/exj
- 家庭消费规划的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/GzK
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/498=dnh
- 儿童友好空间的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/nco=881
- 居家适老化改造的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/Rst=8s8

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
