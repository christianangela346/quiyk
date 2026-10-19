# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 家庭食品保存的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E6%8E%92%E5%90%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/oca=384
- 社区文化节活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E6%8E%92%E5%90%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/r2L=lWp
- 节能生活方式的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/919
- 课后服务体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/yfw
- 社区儿童活动的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/N42
- 老年智能设备的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/486=mgz
- 社区休闲设施的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/hvs=360
- 图书馆数字服务的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E5%AE%98%E7%BD%91%E6%98%AF%E4%BB%80%E4%B9%88_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/6ko=iID
- 乡村电商实践的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%9D%83%E5%A8%81%E7%BD%91%E6%8A%95_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/041
- 旧物循环利用的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%9D%83%E5%A8%81%E7%BD%91%E6%8A%95_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/cvh
- 社区儿童活动的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%9D%83%E5%A8%81%E7%BD%91%E6%8A%95_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/Enl
- 数字创作工具的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%9D%83%E5%A8%81%E7%BD%91%E6%8A%95_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/017=wbo
- 消防知识宣传的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%9D%83%E5%A8%81%E7%BD%91%E6%8A%95_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/qza=151
- 智慧城市体验的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%9D%83%E5%A8%81%E7%BD%91%E6%8A%95_%E9%A1%BA%E4%B8%B0%E8%BD%AC%E8%BD%BD?/IAF=t0M
- 老年友好服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9C%80%E5%A4%A7%E7%BD%91%E6%8A%95%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/607
- 消防知识宣传中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9C%80%E5%A4%A7%E7%BD%91%E6%8A%95%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/bvc
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9C%80%E5%A4%A7%E7%BD%91%E6%8A%95%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/NUG
- 食品配送体验的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9C%80%E5%A4%A7%E7%BD%91%E6%8A%95%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/009=cib
- 家庭健康管理的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9C%80%E5%A4%A7%E7%BD%91%E6%8A%95%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/ghm=234
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%9C%80%E5%A4%A7%E7%BD%91%E6%8A%95%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/GQU=yj2
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/429
- 数字课堂应用的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/lym
- 学校食育活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/pPX
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/887=kxn
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/pwx=919
- 居家适老化改造的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/cUL=miI
- 绿色校园实践的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%9B%B4%E6%8E%A5%E6%89%93%E6%AC%BE%E5%88%B0%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/083
- 智能手机助老的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%9B%B4%E6%8E%A5%E6%89%93%E6%AC%BE%E5%88%B0%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/keh
- 社区设施共享的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%9B%B4%E6%8E%A5%E6%89%93%E6%AC%BE%E5%88%B0%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/Gmd
- 社区邻里服务中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%9B%B4%E6%8E%A5%E6%89%93%E6%AC%BE%E5%88%B0%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/454=zfm
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%9B%B4%E6%8E%A5%E6%89%93%E6%AC%BE%E5%88%B0%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/bwr=973
- 文化讲座服务的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%9B%B4%E6%8E%A5%E6%89%93%E6%AC%BE%E5%88%B0%E5%BE%AE%E4%BF%A1_%E5%BF%85%E5%BA%94%E6%B6%88%E8%B4%B9?/Ylu=XkP
- 青年志愿活动的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%8F%90%E5%88%B0%E6%94%AF%E4%BB%98%E5%AE%9D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/999
- 机器学习入门的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%8F%90%E5%88%B0%E6%94%AF%E4%BB%98%E5%AE%9D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/kab
- 职业技能学习的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%8F%90%E5%88%B0%E6%94%AF%E4%BB%98%E5%AE%9D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/FBX
- 城市博物馆服务的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%8F%90%E5%88%B0%E6%94%AF%E4%BB%98%E5%AE%9D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/833=gkq
- 儿童友好空间的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%8F%90%E5%88%B0%E6%94%AF%E4%BB%98%E5%AE%9D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/xmv=392
- 老年数字阅读的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%8F%90%E5%88%B0%E6%94%AF%E4%BB%98%E5%AE%9D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/dm5=QBS
- 社区公共卫生的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B65%E5%BC%A0%E7%89%8C_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/997
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B65%E5%BC%A0%E7%89%8C_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/aul
- 家庭收纳实践的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B65%E5%BC%A0%E7%89%8C_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/aBP
- 青年就业服务的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B65%E5%BC%A0%E7%89%8C_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/687=rin
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B65%E5%BC%A0%E7%89%8C_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/zyd=044
- 公园无障碍服务的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B65%E5%BC%A0%E7%89%8C_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/O8B=wxI
- 公共空间照明的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/245
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/bjm
- 气象科普传播的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/cXK
- 城市空气科普的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/459=tzb
- 软件开发学习的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/gac=567
- 青年职业探索的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%99%BE%E7%A7%91_%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/72O=Azh
- 家庭收纳实践的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%94%B5%E5%BE%AE_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/694
- 城市适老服务的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%94%B5%E5%BE%AE_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/gif
- 租房信息服务的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%94%B5%E5%BE%AE_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/lpd
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%94%B5%E5%BE%AE_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/085=blw
- 青少年编程学习的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%94%B5%E5%BE%AE_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/tcb=086
- 校园社团活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E7%94%B5%E5%BE%AE_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/DAi=IjS
- 健康信息获取的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%8F%8C%E5%8D%95%E7%82%B9%E6%98%AF%E5%95%A5%E6%84%8F%E6%80%9D_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/165
- 社区慢性病防控的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%8F%8C%E5%8D%95%E7%82%B9%E6%98%AF%E5%95%A5%E6%84%8F%E6%80%9D_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/ugm
- 家庭健康管理的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%8F%8C%E5%8D%95%E7%82%B9%E6%98%AF%E5%95%A5%E6%84%8F%E6%80%9D_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/NSH
- 数字素养提升的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%8F%8C%E5%8D%95%E7%82%B9%E6%98%AF%E5%95%A5%E6%84%8F%E6%80%9D_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/633=lmv
- 社区学习活动的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%8F%8C%E5%8D%95%E7%82%B9%E6%98%AF%E5%95%A5%E6%84%8F%E6%80%9D_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/bge=370
- 社区故事采集的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%8F%8C%E5%8D%95%E7%82%B9%E6%98%AF%E5%95%A5%E6%84%8F%E6%80%9D_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/Xt6=n7v
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%BC%80%E6%9E%AA_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/837
- 通勤路线规划的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%BC%80%E6%9E%AA_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/xkd
- 家庭食品保存的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%BC%80%E6%9E%AA_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/8Kw
- 公共空间导览中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%BC%80%E6%9E%AA_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/595=xws
- 骑行路线规划的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%BC%80%E6%9E%AA_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/rio=321
- 儿童友好街区的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E5%BC%80%E6%9E%AA_%E8%85%BE%E8%AE%AF%E8%B4%A2%E7%BB%8F?/ogz=LoE
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%80%8E%E4%B9%88%E8%B5%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/743
- 公共场馆服务的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%80%8E%E4%B9%88%E8%B5%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/jub
- 生成式工具使用的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%80%8E%E4%B9%88%E8%B5%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/vtU
- 家庭园艺实践的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%80%8E%E4%B9%88%E8%B5%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/790=vrq
- 乡村生态旅游的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%80%8E%E4%B9%88%E8%B5%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/lrt=692
- 乡村生态观察的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B%E6%80%8E%E4%B9%88%E8%B5%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/NQj=S0A
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%8A%A2%E5%BA%84%E7%89%9B%E7%89%9B%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_360%E7%89%B9%E7%A8%BF?/656
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%8A%A2%E5%BA%84%E7%89%9B%E7%89%9B%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_360%E7%89%B9%E7%A8%BF?/jvm
- 公共空间安全中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%8A%A2%E5%BA%84%E7%89%9B%E7%89%9B%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_360%E7%89%B9%E7%A8%BF?/BVT
- 物业服务沟通的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%8A%A2%E5%BA%84%E7%89%9B%E7%89%9B%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_360%E7%89%B9%E7%A8%BF?/444=tmm
- 家庭急救准备的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%8A%A2%E5%BA%84%E7%89%9B%E7%89%9B%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_360%E7%89%B9%E7%A8%BF?/fap=798
- 社区公共餐饮的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%8A%A2%E5%BA%84%E7%89%9B%E7%89%9B%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_360%E7%89%B9%E7%A8%BF?/Rht=7bJ
- 数字公共文化的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/124
- 老年运动活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/dcx
- 公园休闲体验的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/qKU
- 公交站点体验的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/894=fsp
- 老年人日常照护的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/pqg=009
- 开源技术交流的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%89%9B%E7%89%9B%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/AHG=Hk3
- 公共空间休憩的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%BA%BB%E5%B0%8F%E5%B0%86%E6%99%BA%E8%83%BD%E6%A3%8B%E7%89%8C%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/712
- 乡村阅读空间的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%BA%BB%E5%B0%8F%E5%B0%86%E6%99%BA%E8%83%BD%E6%A3%8B%E7%89%8C%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/nrx
- 绿色生活实践的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%BA%BB%E5%B0%8F%E5%B0%86%E6%99%BA%E8%83%BD%E6%A3%8B%E7%89%8C%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/Pmq
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%BA%BB%E5%B0%8F%E5%B0%86%E6%99%BA%E8%83%BD%E6%A3%8B%E7%89%8C%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/429=msp
- 青少年编程学习的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%BA%BB%E5%B0%8F%E5%B0%86%E6%99%BA%E8%83%BD%E6%A3%8B%E7%89%8C%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/fiz=413
- 城市地名文化的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%BA%BB%E5%B0%8F%E5%B0%86%E6%99%BA%E8%83%BD%E6%A3%8B%E7%89%8C%E5%8A%A0%E7%9B%9F_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/BCE=X6r
- 节能生活方式的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E6%A3%8B%E7%89%8C%E8%BD%AF%E4%BB%B6%E5%88%B6%E4%BD%9C%E5%BC%80%E5%8F%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/300
- 便民服务窗口的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E6%A3%8B%E7%89%8C%E8%BD%AF%E4%BB%B6%E5%88%B6%E4%BD%9C%E5%BC%80%E5%8F%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/foh
- 家庭节能实践的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E6%A3%8B%E7%89%8C%E8%BD%AF%E4%BB%B6%E5%88%B6%E4%BD%9C%E5%BC%80%E5%8F%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/UoH
- 职业技能学习的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E6%A3%8B%E7%89%8C%E8%BD%AF%E4%BB%B6%E5%88%B6%E4%BD%9C%E5%BC%80%E5%8F%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/463=gdo
- 社区健康讲座的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E6%A3%8B%E7%89%8C%E8%BD%AF%E4%BB%B6%E5%88%B6%E4%BD%9C%E5%BC%80%E5%8F%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/zmt=454
- 青年志愿活动的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E6%A3%8B%E7%89%8C%E8%BD%AF%E4%BB%B6%E5%88%B6%E4%BD%9C%E5%BC%80%E5%8F%91_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/MdR=oZP
- 数字档案服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%9C%9F%E4%BA%BA%E6%96%97%E7%89%9B%E7%89%9B%E8%B5%A2%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C?/519
- 社区停车服务的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%9C%9F%E4%BA%BA%E6%96%97%E7%89%9B%E7%89%9B%E8%B5%A2%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C?/zwm
- 乡村产业科普的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%9C%9F%E4%BA%BA%E6%96%97%E7%89%9B%E7%89%9B%E8%B5%A2%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C?/WXF
- 科学健身方法的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%9C%9F%E4%BA%BA%E6%96%97%E7%89%9B%E7%89%9B%E8%B5%A2%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C?/544=rmg
- 社区庭院绿化的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%9C%9F%E4%BA%BA%E6%96%97%E7%89%9B%E7%89%9B%E8%B5%A2%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C?/kvn=512
- 社区托育服务的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E7%9C%9F%E4%BA%BA%E6%96%97%E7%89%9B%E7%89%9B%E8%B5%A2%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C?/RLw=HE5
- 小区停车协商的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%A3%8B%E7%89%8C%E7%89%9B%E7%89%9B10%E5%85%83%E8%B5%B7%E5%85%85_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/054
- 公共服务数字化的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%A3%8B%E7%89%8C%E7%89%9B%E7%89%9B10%E5%85%83%E8%B5%B7%E5%85%85_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/gvb
- 公共空间安全的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%A3%8B%E7%89%8C%E7%89%9B%E7%89%9B10%E5%85%83%E8%B5%B7%E5%85%85_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/pbr
- 社区学习活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%A3%8B%E7%89%8C%E7%89%9B%E7%89%9B10%E5%85%83%E8%B5%B7%E5%85%85_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/438=gko
- 社区便利生活的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%A3%8B%E7%89%8C%E7%89%9B%E7%89%9B10%E5%85%83%E8%B5%B7%E5%85%85_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/yfo=689
- 数字课堂应用的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%A3%8B%E7%89%8C%E7%89%9B%E7%89%9B10%E5%85%83%E8%B5%B7%E5%85%85_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/OJV=3XG
- 软件开发学习的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%89%93%E9%B1%BC%E7%8E%B0%E9%87%91%E5%8F%AF%E4%B8%8A%E4%B8%8B%E5%88%86_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/596
- 城市夜间生活的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%89%93%E9%B1%BC%E7%8E%B0%E9%87%91%E5%8F%AF%E4%B8%8A%E4%B8%8B%E5%88%86_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/vqk
- 家庭园艺实践的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%89%93%E9%B1%BC%E7%8E%B0%E9%87%91%E5%8F%AF%E4%B8%8A%E4%B8%8B%E5%88%86_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/Eiv
- 城市共享单车的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%89%93%E9%B1%BC%E7%8E%B0%E9%87%91%E5%8F%AF%E4%B8%8A%E4%B8%8B%E5%88%86_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/889=nzp
- 公共设施维护的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%89%93%E9%B1%BC%E7%8E%B0%E9%87%91%E5%8F%AF%E4%B8%8A%E4%B8%8B%E5%88%86_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/aod=622
- 青少年科普实践的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%89%93%E9%B1%BC%E7%8E%B0%E9%87%91%E5%8F%AF%E4%B8%8A%E4%B8%8B%E5%88%86_%E4%BA%AC%E4%B8%9C%E8%BE%9F%E8%B0%A3?/BY7=A6V
- 在线学习体验的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%89%93%E9%B1%BC%E6%B3%A8%E5%86%8C%E9%80%81%E5%88%8658%E5%85%83_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/252
- 家庭用电安全的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%89%93%E9%B1%BC%E6%B3%A8%E5%86%8C%E9%80%81%E5%88%8658%E5%85%83_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/joi
- 开源技术交流的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%89%93%E9%B1%BC%E6%B3%A8%E5%86%8C%E9%80%81%E5%88%8658%E5%85%83_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/wWY
- 学校食育活动的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%89%93%E9%B1%BC%E6%B3%A8%E5%86%8C%E9%80%81%E5%88%8658%E5%85%83_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/720=gcc
- 个人数据管理的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%89%93%E9%B1%BC%E6%B3%A8%E5%86%8C%E9%80%81%E5%88%8658%E5%85%83_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/vhr=461
- 公共服务数字化的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%89%93%E9%B1%BC%E6%B3%A8%E5%86%8C%E9%80%81%E5%88%8658%E5%85%83_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/73D=usx
- 远程协作工具的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E8%B5%9A%E9%92%B1%E6%A3%8B%E7%89%8C%E5%AE%A4%E6%B8%B8%E6%88%8F%E7%A7%92%E6%8F%90%E5%88%B0%E8%B4%A6_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/069
- 公共空间照明的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E8%B5%9A%E9%92%B1%E6%A3%8B%E7%89%8C%E5%AE%A4%E6%B8%B8%E6%88%8F%E7%A7%92%E6%8F%90%E5%88%B0%E8%B4%A6_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/usc
- 生活垃圾减量的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E8%B5%9A%E9%92%B1%E6%A3%8B%E7%89%8C%E5%AE%A4%E6%B8%B8%E6%88%8F%E7%A7%92%E6%8F%90%E5%88%B0%E8%B4%A6_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/Om4
- 绿色办公实践的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E8%B5%9A%E9%92%B1%E6%A3%8B%E7%89%8C%E5%AE%A4%E6%B8%B8%E6%88%8F%E7%A7%92%E6%8F%90%E5%88%B0%E8%B4%A6_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/982=pus
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E8%B5%9A%E9%92%B1%E6%A3%8B%E7%89%8C%E5%AE%A4%E6%B8%B8%E6%88%8F%E7%A7%92%E6%8F%90%E5%88%B0%E8%B4%A6_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/qpd=603
- 家庭养老规划的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E8%B5%9A%E9%92%B1%E6%A3%8B%E7%89%8C%E5%AE%A4%E6%B8%B8%E6%88%8F%E7%A7%92%E6%8F%90%E5%88%B0%E8%B4%A6_%E5%BE%97%E7%89%A9%E5%9C%B0%E4%BA%A7?/1ax=Tzg
- 社区公共卫生的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_888%E6%A3%8B%E7%89%8C%E8%83%BD%E6%8C%A3%E9%92%B1%E7%9A%84%E6%B8%B8%E6%88%8F_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/910
- 开放数据应用的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_888%E6%A3%8B%E7%89%8C%E8%83%BD%E6%8C%A3%E9%92%B1%E7%9A%84%E6%B8%B8%E6%88%8F_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/exm
- 公共服务咨询的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_888%E6%A3%8B%E7%89%8C%E8%83%BD%E6%8C%A3%E9%92%B1%E7%9A%84%E6%B8%B8%E6%88%8F_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/Nh0
- 社区手工活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_888%E6%A3%8B%E7%89%8C%E8%83%BD%E6%8C%A3%E9%92%B1%E7%9A%84%E6%B8%B8%E6%88%8F_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/646=rkl
- 食品安全科普的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_888%E6%A3%8B%E7%89%8C%E8%83%BD%E6%8C%A3%E9%92%B1%E7%9A%84%E6%B8%B8%E6%88%8F_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/yhk=302
- 课后服务体验的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_888%E6%A3%8B%E7%89%8C%E8%83%BD%E6%8C%A3%E9%92%B1%E7%9A%84%E6%B8%B8%E6%88%8F_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/Tbh=jUd
- 社区儿童活动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%8A%B1%E8%90%BD%E7%89%9B%E7%89%9B_%E8%85%BE%E8%AE%AF%E4%BA%BA%E5%A4%A7?/515
- 城市步行友好的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%8A%B1%E8%90%BD%E7%89%9B%E7%89%9B_%E8%85%BE%E8%AE%AF%E4%BA%BA%E5%A4%A7?/pxw
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%8A%B1%E8%90%BD%E7%89%9B%E7%89%9B_%E8%85%BE%E8%AE%AF%E4%BA%BA%E5%A4%A7?/l6Q
- 社区艺术活动的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%8A%B1%E8%90%BD%E7%89%9B%E7%89%9B_%E8%85%BE%E8%AE%AF%E4%BA%BA%E5%A4%A7?/674=dpu
- 社区活动空间的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%8A%B1%E8%90%BD%E7%89%9B%E7%89%9B_%E8%85%BE%E8%AE%AF%E4%BA%BA%E5%A4%A7?/snr=494
- 科学教育活动的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%8A%B1%E8%90%BD%E7%89%9B%E7%89%9B_%E8%85%BE%E8%AE%AF%E4%BA%BA%E5%A4%A7?/PTT=RG1
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E7%89%9B%E7%89%9B%E4%B8%80%E7%9B%B4%E8%BE%93%E6%98%AF%E5%A5%97%E8%B7%AF%E5%90%97_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/542
- 校园阅读活动的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E7%89%9B%E7%89%9B%E4%B8%80%E7%9B%B4%E8%BE%93%E6%98%AF%E5%A5%97%E8%B7%AF%E5%90%97_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/oxb
- 老年智能设备的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E7%89%9B%E7%89%9B%E4%B8%80%E7%9B%B4%E8%BE%93%E6%98%AF%E5%A5%97%E8%B7%AF%E5%90%97_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/V5J
- 社区手工活动的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E7%89%9B%E7%89%9B%E4%B8%80%E7%9B%B4%E8%BE%93%E6%98%AF%E5%A5%97%E8%B7%AF%E5%90%97_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/425=rtf
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E7%89%9B%E7%89%9B%E4%B8%80%E7%9B%B4%E8%BE%93%E6%98%AF%E5%A5%97%E8%B7%AF%E5%90%97_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/wxn=817
- 职业技能学习的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E7%89%9B%E7%89%9B%E4%B8%80%E7%9B%B4%E8%BE%93%E6%98%AF%E5%A5%97%E8%B7%AF%E5%90%97_%E7%BD%91%E6%98%93%E7%BB%BC%E8%89%BA?/Cdd=whf
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%82%B8%E9%87%91%E8%8A%B1%E7%9C%9F%E4%BA%BA%E7%89%882017_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/039
- 城市雨天出行的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%82%B8%E9%87%91%E8%8A%B1%E7%9C%9F%E4%BA%BA%E7%89%882017_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/uvn
- 社区停车服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%82%B8%E9%87%91%E8%8A%B1%E7%9C%9F%E4%BA%BA%E7%89%882017_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/Gyi
- 家庭食品保存的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%82%B8%E9%87%91%E8%8A%B1%E7%9C%9F%E4%BA%BA%E7%89%882017_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/004=nob
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%82%B8%E9%87%91%E8%8A%B1%E7%9C%9F%E4%BA%BA%E7%89%882017_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/fmw=938
- 数字创意课程的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%82%B8%E9%87%91%E8%8A%B1%E7%9C%9F%E4%BA%BA%E7%89%882017_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/it5=iOq
- 家庭节能设备的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%BD%91%E7%AB%99%E6%B8%B8%E6%88%8F%E7%89%9B%E7%89%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/189
- 城市公共自行车的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%BD%91%E7%AB%99%E6%B8%B8%E6%88%8F%E7%89%9B%E7%89%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/emt
- 个人数据管理的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%BD%91%E7%AB%99%E6%B8%B8%E6%88%8F%E7%89%9B%E7%89%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/Wyt
- 城市展览体验的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%BD%91%E7%AB%99%E6%B8%B8%E6%88%8F%E7%89%9B%E7%89%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/045=fkb
- 社区便民集市的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%BD%91%E7%AB%99%E6%B8%B8%E6%88%8F%E7%89%9B%E7%89%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/euw=463
- 基层服务创新的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E7%9A%84%E7%BD%91%E7%AB%99%E6%B8%B8%E6%88%8F%E7%89%9B%E7%89%9B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/DCW=4oI
- 家庭收纳实践的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/833
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/cgm
- 城乡交流活动的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/slx
- 农村环境治理的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/691=rpf
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/uez=044
- 软件开发学习中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/WNu=gon
- 城市公共标识中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E5%9B%BE%E7%89%87_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/853
- 新能源出行的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E5%9B%BE%E7%89%87_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/ilf
- 城市应急科普的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E5%9B%BE%E7%89%87_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/lbL
- 志愿服务平台的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E5%9B%BE%E7%89%87_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/307=syp
- 社区学习活动的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E5%9B%BE%E7%89%87_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/vge=908
- 地方民俗记录的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E5%9B%BE%E7%89%87_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/FkH=NpO
- 图书馆数字服务有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/306
- 乡村电商实践中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/uqn
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/Ofa
- 节能生活方式的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/404=wvq
- 基层健康服务的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/nmw=512
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/zL8=DWF
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/819
- 食品配送体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/bfs
- 校园社团活动的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/3te
- 绿色消费选择的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/332=jsp
- 数字艺术创作的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/cet=031
- 社区家校合作的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E7%BD%91%E5%9D%80%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/rVN=b6D
- 城市便民驿站的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%85%A8%E5%9B%BD%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/656
- 急救知识普及的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%85%A8%E5%9B%BD%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/ghp
- 数字课堂应用的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%85%A8%E5%9B%BD%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/ylU
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%85%A8%E5%9B%BD%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/804=ldi
- 城市生活记录的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%85%A8%E5%9B%BD%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/ljs=770
- 环境教育课程的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%85%A8%E5%9B%BD%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/ARj=Brn
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92%E8%A1%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/933
- 智慧停车服务的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92%E8%A1%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/wer
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92%E8%A1%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/AfL
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92%E8%A1%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/187=syx
- 公交站点体验的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92%E8%A1%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/yfq=909
- 乡村电商实践的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_10%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92%E8%A1%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/qnD=qmf
- 家庭网络使用的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/215
- 公共卫生设施的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/xar
- 城乡公共服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/FBi
- 儿童友好空间的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/091=sos
- 公共空间安全的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/tsg=609
- 科学信息获取的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%8E%92_%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/4LZ=bNs
- 城市公共厕所的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B6%E6%9C%80%E7%81%AB%E7%9A%84app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/141
- 社区养老服务的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B6%E6%9C%80%E7%81%AB%E7%9A%84app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/zsi
- 人工智能科普的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B6%E6%9C%80%E7%81%AB%E7%9A%84app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/yMq
- 城市公共座椅的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B6%E6%9C%80%E7%81%AB%E7%9A%84app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/840=vxh
- 基层健康档案的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B6%E6%9C%80%E7%81%AB%E7%9A%84app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/lzt=154
- 社区教育资源的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B6%E6%9C%80%E7%81%AB%E7%9A%84app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/4MX=JYd
- 街区道路维护的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/958
- 周末休闲规划的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/dim
- 全民健身活动的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/gpV
- 市民热线服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/363=bvx
- 数字便民地图的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/zjq=727
- 小微企业服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E7%9A%84_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/Wt3=9CD
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/389
- 乡村生活观察的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/uzx
- 环境监测科普的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/5hN
- 数字学习资源的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/989=vsa
- 校园安全教育的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/lwp=997
- 医院导诊服务的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/PTq=T4F
- 光伏知识科普的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E5%AE%98%E6%96%B9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/576
- 青少年户外教育的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E5%AE%98%E6%96%B9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/jms
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E5%AE%98%E6%96%B9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/HfN
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E5%AE%98%E6%96%B9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/693=zhh
- 数字创意课程的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E5%AE%98%E6%96%B9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/ydm=626
- 青年职业探索的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E5%AE%98%E6%96%B9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/d64=DCw
- 数字课堂应用的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E8%B5%8C%E5%8D%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/885
- 个人信息保护的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E8%B5%8C%E5%8D%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/lll
- 绿色出行服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E8%B5%8C%E5%8D%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/bQG
- 网络安全教育的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E8%B5%8C%E5%8D%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/130=kfm
- 个人数据管理的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E8%B5%8C%E5%8D%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/lpn=286
- 机器学习入门的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E8%B5%8C%E5%8D%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%A7%81%E5%8B%9F?/3tV=cub
- 公交站点体验的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%8D%9A%E5%BD%A9%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/783
- 社区环保活动的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%8D%9A%E5%BD%A9%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/bon
- 学校体育活动的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%8D%9A%E5%BD%A9%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/tF9
- 乡村公共阅读的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%8D%9A%E5%BD%A9%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/606=jvx
- 数字资源检索的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%8D%9A%E5%BD%A9%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/vjt=732
- 社区宣传栏更新的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%8D%9A%E5%BD%A9%E5%85%AC%E5%8F%B8_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/K6v=YMI
- 健康饮食教育的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%96%E7%95%8C%E6%9C%80%E5%A4%A7%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E6%8E%92%E5%90%8D_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/391
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%96%E7%95%8C%E6%9C%80%E5%A4%A7%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E6%8E%92%E5%90%8D_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/xzv
- 社会体育指导的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%96%E7%95%8C%E6%9C%80%E5%A4%A7%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E6%8E%92%E5%90%8D_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/ZvW
- 校园社团活动的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%96%E7%95%8C%E6%9C%80%E5%A4%A7%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E6%8E%92%E5%90%8D_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/550=xpc
- 线上办事服务的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%96%E7%95%8C%E6%9C%80%E5%A4%A7%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E6%8E%92%E5%90%8D_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/igz=843
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%96%E7%95%8C%E6%9C%80%E5%A4%A7%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E6%8E%92%E5%90%8D_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/ole=XKO
- 在线教育体验的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%BC%80%E7%9B%98%E9%83%BD%E5%BE%88%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/616
- 乡村生态观察的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%BC%80%E7%9B%98%E9%83%BD%E5%BE%88%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/qbn
- 城市社区治理的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%BC%80%E7%9B%98%E9%83%BD%E5%BE%88%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/Pbt
- 城市体育设施的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%BC%80%E7%9B%98%E9%83%BD%E5%BE%88%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/960=ltm
- 城市噪声观察的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%BC%80%E7%9B%98%E9%83%BD%E5%BE%88%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/sqi=515
- 城市共享单车的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%BC%80%E7%9B%98%E9%83%BD%E5%BE%88%E5%87%86%E7%A1%AE_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/9VK=Vfy
- 生活服务数字化的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1%E7%9A%84_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/129
- 读书会组织的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E8%B6%B3%E5%BD%A9%E5%85%AC%E5%8F%B8%E6%80%8E%E4%B9%88%E6%8C%A3%E9%92%B1%E7%9A%84_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/tms

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
