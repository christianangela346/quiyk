# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 社区志愿服务的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_PC%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/Bwv
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_PC%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/965=uxr
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_PC%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/jit=526
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_PC%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%97%B6%E6%8A%A5?/lms=wit
- 城市社区治理的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/458
- 乡村公共服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/ebx
- 城市住房服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/Oo7
- 城市空气科普的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/425=lqh
- 智慧城市体验的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/vfu=507
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/TOd=gpV
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/899
- 社区阅读服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/oof
- 城市应急科普的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/1m3
- 智慧城市体验的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/621=cer
- 环境监测科普的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/gsh=163
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%B0%91%E7%94%9F?/Qb2=J94
- 环境教育课程的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/476
- 社区生活指南的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/mwx
- 社区休闲设施的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/q1X
- 社区心理支持的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/939=npq
- 绿色出行服务的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/zzo=678
- 城市雨天出行的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/sMJ=PMi
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/310
- 老年友好服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/aie
- 读书会组织的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/NDz
- 网络安全教育的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/357=tig
- 青少年心理健康的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/jkj=990
- 城市适老服务的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E9%A3%9F%E5%93%81?/UvE=7qD
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/554
- 城市基础设施的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/ntv
- 小微企业服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/AGS
- 社区托育服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/138=ebb
- 公共交通信息服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/sxk=579
- 城市步行环境的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/t30=6TM
- 无障碍信息设计的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/805
- 社区快递服务的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/kji
- 数字课堂应用中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/gHc
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/369=wre
- 基层医疗预约的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/ldm=547
- 公共交通接驳的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E5%9B%BE%E9%89%B4?/8pX=a4d
- 城市博物馆服务的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/063
- 数字课堂应用的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/zbc
- 公共服务沟通的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/uU8
- 城市休闲步道的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/132=hog
- 校园社团活动的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/vvg=004
- 城乡交流活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/Hon=dd3
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/580
- 社区儿童活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/idw
- 亲子科普活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/h7N
- 基层医疗预约的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/752=vao
- 社区手工活动的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/kva=821
- 城乡交通衔接的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/jfF=pfq
- 数据分析入门中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/472
- 城市文明出行的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/lpc
- 基层服务创新的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/1X2
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/738=wtv
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/uvw=481
- 校园阅读活动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/w0B=PF4
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/318
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/yqy
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/ciu
- 城市应急科普的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/010=vwj
- 社区应急准备的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/utb=970
- 社区协商议事的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/H4m=YCZ
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/009
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/ctk
- 就业技能培训的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/Gb6
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/738=knu
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/hkv=315
- 文化讲座服务的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/AP0=isc
- 城市可持续生活的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/860
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/euo
- 公共服务咨询的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/ZFn
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/791=nuc
- 数字素养提升中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/eak=490
- 口袋公园建设的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/qZn=ZXn
- 城市体育设施的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/358
- 节假日出行安排的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/xbv
- 家庭养老规划的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/Wpg
- 本地旅行体验的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/951=kci
- 农业科普体验的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/ufb=337
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/Wto=Zb1
- 家庭安全提示的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/810
- 消防知识宣传的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/wlw
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/S7U
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/514=ayk
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/kpb=608
- 街区更新实践的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/L67=Fvz
- 公共设施使用的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/538
- 青年就业服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/fax
- 本地旅行体验的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/6QQ
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/233=hbc
- 科学健身方法的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/vzj=156
- 市民意见收集的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%8A%A8%E6%BC%AB?/iYR=Ho9
- 公共空间安全的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/300
- 绿色校园实践的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/olp
- 数字生活课堂的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/Vix
- 城市骑行环境的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/051=mbb
- 老年友好服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/adu=568
- 智慧停车服务的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/uIc=M41
- 公共空间休憩的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/588
- 公共空间照明的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/tfo
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/CSY
- 家庭食品保存的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/215=yyh
- 儿童安全出行的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/gkt=831
- 农贸市场环境的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/CVQ=wxi
- 城市雨天出行的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/432
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/rag
- 社区环保活动的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/lfF
- 课后服务体验的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/044=dwl
- 社区慢性病防控的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/rwc=659
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/zxM=PF8
- 社区便民集市的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/368
- 社区公共卫生的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/dcd
- 生活技能分享的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/7xt
- 老年运动活动的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/136=fcx
- 城市文明出行的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/tpt=343
- 城市夜间照明的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/Qs7=96Z
- 社区老年食堂的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/460
- 社区手工活动中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/rhb
- 社区科普课堂的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/z1G
- 数字资源检索的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/377=oad
- 社区科普课堂的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/lid=762
- 地方民俗记录的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/AH1=jPl
- 邻里共享空间的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/666
- 社区防暑服务的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/hdy
- 社区老年食堂的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/ly9
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/926=yjz
- 本地旅行体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/mbb=964
- 社区消防演练的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E7%82%B9?/esL=188
- 社区生活指南的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/588
- 生活技能分享的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/lge
- 乡村产业科普的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/aUh
- 社区活动空间的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/899=waw
- 社区协商议事的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/idm=566
- 公共设施使用的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/W0S=gJq
- 社区快递服务的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/917
- 家庭志愿活动的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/nsm
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/Gk7
- 社区儿童活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/804=lvr
- 老年运动活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/nzg=401
- 邻里互助活动的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/yHn=t1O
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92__%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/573
- 亲子科普活动的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92__%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/ocu
- 青年职业探索的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92__%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/HXP
- 社区快递服务的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92__%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/659=yvd
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92__%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/abm=648
- 居民健康教育的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E8%AE%A1%E5%88%92__%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/5aB=bfK
- 智慧停车服务的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B%E7%8E%A9%E6%B3%95_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/844
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B%E7%8E%A9%E6%B3%95_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/xxs
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B%E7%8E%A9%E6%B3%95_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/2N0
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B%E7%8E%A9%E6%B3%95_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/906=tzb
- 居家适老化改造的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B%E7%8E%A9%E6%B3%95_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/bjz=781
- 旧物循环利用的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_pc%E8%9B%8B%E8%9B%8B%E7%8E%A9%E6%B3%95_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/LWA=haO
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_pc%E8%9B%8B%E8%9B%8B%E7%BB%84%E5%90%88%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/397
- 数字设备回收的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_pc%E8%9B%8B%E8%9B%8B%E7%BB%84%E5%90%88%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/vrm
- 应急物资管理的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_pc%E8%9B%8B%E8%9B%8B%E7%BB%84%E5%90%88%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/n7L
- 急救知识普及的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_pc%E8%9B%8B%E8%9B%8B%E7%BB%84%E5%90%88%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/151=mjv
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_pc%E8%9B%8B%E8%9B%8B%E7%BB%84%E5%90%88%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/zia=424
- 城市公共饮水的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_pc%E8%9B%8B%E8%9B%8B%E7%BB%84%E5%90%88%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/twZ=63X
- 线上办事服务的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/284
- 城市公共厕所的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/crh
- 线上办事服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/Gqc
- 邻里共享空间的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/896=qnd
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/dqk=747
- 节约用水实践的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_pc%E8%9B%8B%E8%9B%8B%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/S6D=qR4
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/944
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/xac
- 青年就业服务的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/Ixi
- 社区便利生活的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/618=ecb
- 亲子科普活动的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/yjv=983
- 基层医疗预约的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E6%97%85%E6%B8%B8?/t1G=N7a
- 社区活动报名中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8A_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/695
- 绿色生活实践的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8A_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/cqw
- 社区庭院绿化的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8A_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/T4R
- 科普展览体验的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8A_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/924=tuy
- 节能生活方式的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8A_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/ztz=390
- 街区绿化养护的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8A_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/nBg=NBp
- 社区公共议事的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/696
- 地方美食文化的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/cxs
- 节约用水实践的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/YLM
- 城乡交流活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/804=sku
- 无障碍信息设计的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/dha=095
- 基层健康服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/N14=2uO
- 便民服务窗口的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B28%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/229
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B28%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/nik
- 本地消费场景的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B28%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/bUB
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B28%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/664=tdc
- 家庭收纳实践的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B28%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/jgh=175
- 社区学习活动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B28%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A7%91%E6%8A%80?/C67=4cY
- 城乡公共服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28pc%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/999
- 数字资源检索的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28pc%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/lqh
- 农业科普体验的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28pc%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/saf
- 绿色消费选择的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28pc%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/282=qfx
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28pc%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/iiv=327
- 乡村公共服务的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28pc%E9%A2%84%E6%B5%8B_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/16t=2F0
- 公共交通接驳的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/245
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/vdi
- 城市公共饮水的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/tGu
- 城乡交流活动的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/404=bko
- 地方美食文化的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/doq=456
- 家庭安全提示的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/Pfo=tp3
- 城市步行友好的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/847
- 便民维修服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/htn
- 公共服务评价的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/JrI
- 社区停车服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/915=fxz
- 城市休闲步道的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/uun=758
- 街区小店体验的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/6tj=fSh
- 环境监测科普的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_PC%E8%9B%8B%E8%9B%8B28%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/753
- 老年学习活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_PC%E8%9B%8B%E8%9B%8B28%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ede
- 数字支付体验的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_PC%E8%9B%8B%E8%9B%8B28%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/IZJ
- 公共场所导视的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_PC%E8%9B%8B%E8%9B%8B28%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/614=lau
- 乡村阅读活动的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_PC%E8%9B%8B%E8%9B%8B28%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yqm=225
- 乡村教育资源的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_PC%E8%9B%8B%E8%9B%8B28%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rgu=xuF
- 家庭养老规划的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/526
- 在线教育体验的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/utz
- 数字生活课堂的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/UxT
- 城市应急广播的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/308=kbc
- 城市夜间生活的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/wbb=495
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%B7%A5%E5%85%B7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/VMp=Hjn
- 户外活动组织的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/855
- 绿色消费选择的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/dux
- 地方文化传播的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/Jj8
- 生活技能分享的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/823=fdd
- 校园安全教育的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/njp=412
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_PC%E8%9B%8B%E8%9B%8B%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/5Se=2E6
- 社区停车服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/883
- 农业科普体验的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/kor
- 社区便民服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/4Fb
- 家庭安全提示的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/188=sjx
- 社区学习活动的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/giy=330
- 旧物循环利用的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B28%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/BNG=Ahw
- 城市基础设施的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A93d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B__%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/679
- 终身学习资源的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A93d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B__%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/ygi
- 城市共享单车的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A93d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B__%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/Nsy
- 学校食育活动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A93d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B__%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/628=mct
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A93d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B__%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/sfq=544
- 数字创意课程的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A93d%E8%83%86%E7%A0%81%E9%A2%84%E6%B5%8B__%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/FaS=1CV
- 绿色生活实践的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB%E7%89%9B%E5%BD%A9%E7%BD%91_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/082
- 街道综合服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB%E7%89%9B%E5%BD%A9%E7%BD%91_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/oit
- 医院导诊服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB%E7%89%9B%E5%BD%A9%E7%BD%91_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/ilH
- 图书馆数字服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB%E7%89%9B%E5%BD%A9%E7%BD%91_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/868=ncq
- 街区道路维护的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB%E7%89%9B%E5%BD%A9%E7%BD%91_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/adv=840
- 地方戏曲体验的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB%E7%89%9B%E5%BD%A9%E7%BD%91_%E8%99%8E%E5%97%85%E5%86%9B%E4%BA%8B?/1s2=BYs
- 城市雨天出行的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E4%B8%93%E5%AE%B6_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/441
- 社区防暑服务的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E4%B8%93%E5%AE%B6_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/bzo
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E4%B8%93%E5%AE%B6_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/Mco
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E4%B8%93%E5%AE%B6_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/280=yrn
- 社区手工活动的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E4%B8%93%E5%AE%B6_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/zzh=429
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E7%A6%8F%E5%BD%A93d%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E4%B8%93%E5%AE%B6_%E8%99%8E%E5%97%85%E6%B1%BD%E8%BD%A6?/VeL=xR1

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
