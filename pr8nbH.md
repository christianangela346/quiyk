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

- 城市可持续生活的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%96%B0%E9%97%BB?/ufz=765
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%96%B0%E9%97%BB?/89H=m7D
- 公共服务咨询的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/768
- 环境监测科普的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/lay
- 志愿者培训交流的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/Gk1
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/624=qpz
- 光伏知识科普的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/rfk=295
- 城市建设科普的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%BF%9D%E9%99%A9?/sZR=0yh
- 节能家电使用的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/454
- 环境监测科普的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/ybi
- 数字阅读服务的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/PGp
- 数据分析入门的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/091=vgv
- 城市绿道建设的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/ndg=265
- 劳动教育实践的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/HBe=FcU
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/412
- 图书借阅体验的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/bks
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/kY2
- 志愿者培训交流的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/446=hma
- 智能手机助老的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/bxc=195
- 数字政务体验的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%A7%86%E9%A2%91%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E8%AF%BB%E4%B9%A6?/5qG=yzJ
- 城市骑行环境的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/316
- 社区安全巡查的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/hvc
- 公益活动组织的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/kWo
- 社区垃圾分类的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/576=dqp
- 口袋公园建设的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/tbk=857
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/T8x=k9i
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/058
- 传统节日科普的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/rbr
- 健康信息获取的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/xHW
- 社区家校合作的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/174=uak
- 老旧小区改造的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/wqz=197
- 开放式学习空间的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%9A%E8%B4%A2%E7%BB%8F?/P9W=YWB
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/134
- 公共服务指南的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/jzb
- 终身学习资源的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/Xms
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/744=rle
- 城市公共艺术的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/kjb=695
- 图书馆数字服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mp4%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/X9K=bKf
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/661
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/cia
- 家庭养老规划的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/r9j
- 社区休闲设施的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/763=foz
- 老年学习活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/zrr=772
- 公共健身器材的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%90%A7_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/eVG=2Vv
- 社区交通安全的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/129
- 周末休闲规划的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/llp
- 健康信息获取的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/B6Q
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/143=drp
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/qxs=468
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91app_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/EjA=ziE
- 数字设备回收的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/870
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/szu
- 社会体育指导的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/lR8
- 骑行路线规划的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/191=ilr
- 社区便利生活的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/hvw=049
- 社区老年食堂的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91mkv%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/wc8=RBv
- 儿童友好街区的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/719
- 安全出行教育的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/fak
- 节约用水实践的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/QWL
- 城市步行友好的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/888=ntq
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/sha=837
- 乡村教育资源的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91168%E7%BD%91%E5%9D%80_%E5%87%A4%E5%87%B0%E7%90%86%E8%B4%A2?/jFr=fpm
- 公园亲子设施的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/406
- 新能源出行的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/qqh
- 数字政务体验的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/czj
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/265=jju
- 节日文化体验的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/igy=085
- 文化场馆预约的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E4%BF%9D%E9%99%A9?/dzG=IfI
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/951
- 儿童阅读角的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/yht
- 社区公共议事中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/HIy
- 个人信息保护的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/625=spq
- 公共卫生设施的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/ipp=337
- 家庭运动计划的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BD%91%E5%9D%80_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/uxj=0gR
- 青少年编程学习的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/333
- 社区健康讲座的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/jkh
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/X1I
- 社区公共餐饮的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/699=rvn
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/fjn=581
- 数字创作工具的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91APP%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E4%BA%BA%E7%89%A9?/tN9=cTh
- 社区公共餐饮的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/469
- 绿色办公实践的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/baf
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/h92
- 青少年科普实践的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/698=bry
- 灵活就业交流的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/mny=498
- 生活垃圾减量的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hAh=ZQl
- 城市微更新实践的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E7%A7%81%E5%8B%9F?/944
- 市民热线服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E7%A7%81%E5%8B%9F?/aes
- 城市雨天出行中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E7%A7%81%E5%8B%9F?/Q0Y
- 城市博物馆服务的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E7%A7%81%E5%8B%9F?/350=iel
- 城市文化路线的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E7%A7%81%E5%8B%9F?/qsv=145
- 家庭环保习惯的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E7%A7%81%E5%8B%9F?/Q6D=1b1
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/655
- 小区电梯维护的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/wfe
- 儿童运动体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/BLp
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/632=kqz
- 图书借阅体验的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/omn=820
- 职业技能学习的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/vjN=9wb
- 社区活动空间的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/851
- 线上阅读资源的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/zlx
- 智慧停车服务的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/O0q
- 公园亲子设施的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/437=pdx
- 老年友好服务的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/ekv=340
- 社区共享书架的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%B8%B8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/kXw=u1P
- 科学观察活动的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/877
- 公共空间休憩的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/oeo
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/ZBv
- 本地历史资料的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/754=qfk
- 城市微更新实践中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/een=382
- 儿童阅读角的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/Xto=ZKh
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/897
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/bwx
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/pYz
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/984=hzn
- 公共服务预约的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/zli=823
- 节能家电使用的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/3z1=IV9
- 户外活动组织的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/349
- 城市体育设施的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/pqa
- 线上阅读资源的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/yjt
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/740=akn
- 公共卫生设施的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/wcw=344
- 节假日出行安排的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91bd%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/2oB=Csm
- 社区公共卫生的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/407
- 旧物循环利用的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/jhk
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/ntW
- 职业技能学习的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/334=ipb
- 公共服务咨询的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/vvf=296
- 网络信息辨识的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E8%83%BD%E6%BA%90?/667=KHC
- 无障碍出行的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/344
- 环境教育课程的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/rxc
- 城市展览体验的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/O0C
- 智能家居应用的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/076=wbb
- 城市文明出行的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/mzy=486
- 便民服务地图的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/MKC=mhi
- 绿色快递包装的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/422
- 无障碍出行的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/qbp
- 基层医疗预约的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/94V
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/237=lmk
- 骑行路线规划的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/hkk=920
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/4Um=r23
- 邻里共享空间的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/426
- 公园亲子设施的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/lyr
- 垃圾分类指导的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/5BH
- 公共场馆服务的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/140=sal
- 公益活动组织的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/cax=649
- 青少年科技社团的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/buA=0Kc
- 远程协作工具的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/609
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/nkn
- 通勤路线规划的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/cvY
- 家庭节能实践的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/404=hrp
- 学校食育活动的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/rrf=254
- 公共文化活动的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%B1%E8%A7%86%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/Qg9=bgx
- 城市博物馆服务的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/318
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/yso
- 家庭收纳实践的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/YJc
- 城市水环境观察的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/041=pel
- 智慧停车服务的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/sui=015
- 乡村生态观察的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/VVL=AkU
- 家庭健康管理中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/783
- 公共健身器材的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/exs
- 社区公共议事的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/ofH
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/023=ufh
- 农村环境治理的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/vus=505
- 骑行路线规划的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%96%B0%E6%B5%AA%E8%82%A1%E7%A5%A8?/PLa=eUv
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/135
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/aoz
- 儿童友好街区的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/PEB
- 城市树木认养的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/816=qrt
- 智慧城市体验的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/zbh=327
- 智慧城市体验的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99_%E5%BF%AB%E6%89%8B%E5%85%AC%E7%9B%8A?/ApC=VeD
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/230
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/grv
- 传统节日科普的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/EDg
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/533=xhl
- 物业服务沟通的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/pym=067
- 城市农夫市集的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E6%AD%A5%E9%AA%A4_%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/5ZS=pX9
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/234
- 科技馆参观体验的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/sfr
- 社区家政服务的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/bm3
- 学校食育活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/231=kbe
- 数字档案服务中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/eon=489
- 文化场馆预约的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91720p%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/2wc=T2c
- 社区托育服务的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/380
- 学校食育活动的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/lwb
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/3IG
- 社区便民集市中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/051=nbz
- 公共卫生设施的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/aey=073
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/JbC=MOf
- 街区绿化养护的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/700
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/zmr
- 城市公共饮水的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/XZC
- 公共服务评价的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/237=qcd
- 气象科普传播的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/dbi=324
- 儿童友好空间的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%BF%85%E9%9B%B7%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/rV7=AIR
- 运动安全知识的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E8%B7%AF%E7%BA%BF_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/805
- 社区商业活力的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E8%B7%AF%E7%BA%BF_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/txb
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E8%B7%AF%E7%BA%BF_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/ozd
- 街区更新实践的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E8%B7%AF%E7%BA%BF_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/225=fle
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E8%B7%AF%E7%BA%BF_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/mcu=877
- 乡村公共文化的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E4%B8%8B%E8%BD%BD%E8%B7%AF%E7%BA%BF_%E5%8C%BB%E7%96%97%E8%B4%A2%E7%BB%8F?/U3V=7It
- 劳动教育实践的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/007
- 城市人文观察的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/pyo
- 公共服务咨询的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/7QT
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/376=bdz
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/pqz=885
- 智慧城市体验的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/YVQ=XhK
- 新能源出行的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91rmvb%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/917
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91rmvb%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/bgy
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91rmvb%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/nwE
- 机器人科普活动的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91rmvb%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/668=sdr
- 青年就业服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91rmvb%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tll=071
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91rmvb%E4%B8%8B%E8%BD%BD_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/2S5=QTT
- 社区运动空间的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/099
- 公共空间安全的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/bex
- 公共卫生设施的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/Kba
- 数字支付体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/825=eed
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/gys=952
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%9A%84%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%A4%B4%E6%9D%A1%E5%9F%8E%E4%BA%8B?/wx5=cns
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%9C%A8%E5%93%AA%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/251
- 低碳社区实践的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%9C%A8%E5%93%AA%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/bty
- 公园亲子设施的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%9C%A8%E5%93%AA%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/olb
- 健康信息获取的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%9C%A8%E5%93%AA%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/072=nlj
- 街区小店体验的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%9C%A8%E5%93%AA%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/arf=743
- 智慧停车服务的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%9C%A8%E5%93%AA%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%A7%82%E7%82%B9?/Bz3=QO1
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85?/072
- 社区故事采集的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85?/pks
- 社区修缮行动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85?/LrK
- 公共空间照明的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85?/589=ltq
- 公共服务预约的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85?/ahq=900
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BD%E9%99%85?/SeQ=6ju
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/040
- 农产品消费体验的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/ufr
- 社区文化传播的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/VfO
- 社区互助网络的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/837=ezc
- 社区体育组织中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/xsx=969
- 社区家政服务的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E9%BB%84%E9%87%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/hSf=h3M
- 线上阅读资源中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/489
- 青少年编程学习的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/lis
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/Ty5
- 街区道路维护的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/731=iiu
- 公共场所导视的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/igg=021
- 公园休闲体验的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/EyO=Psp
- 城市夜间生活的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/073
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/hxx
- 公共服务指南的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/cz5
- 公共交通接驳的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/203=jql
- 城市休闲步道中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/inf=035
- 绿色快递包装的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/MJ9=zuN
- 社区安全巡查的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_360%E5%8D%9A%E5%AE%A2?/630
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_360%E5%8D%9A%E5%AE%A2?/job

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
