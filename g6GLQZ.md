# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 社区心理支持的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B8%8D%E6%80%95%E6%8C%82%E7%9A%84%E9%98%B6%E6%A2%AF%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/nhj=859
- 城市树木认养的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B8%8D%E6%80%95%E6%8C%82%E7%9A%84%E9%98%B6%E6%A2%AF%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/RqC=oIi
- 公共文化活动的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/476
- 儿童安全出行的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/vut
- 社区文化传播的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/vaH
- 非遗课堂体验的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/403=qel
- 校园节能行动的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/qcf=962
- 图书借阅体验的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AC%E5%BC%8F_%E6%96%B0%E6%B5%AA%E6%AF%8D%E5%A9%B4?/bpg=VFS
- 青少年户外教育的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/794
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/rho
- 骑行路线规划的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/SCE
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/170=hcb
- 传统节日科普的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/dhb=949
- 城乡交通衔接的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/6an=QhA
- 急救知识普及的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E9%98%B2%E6%AD%A2%E8%BF%9E%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/670
- 校园节能行动的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E9%98%B2%E6%AD%A2%E8%BF%9E%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/sdy
- 校园节能行动的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E9%98%B2%E6%AD%A2%E8%BF%9E%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/zzV
- 基层健康档案的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E9%98%B2%E6%AD%A2%E8%BF%9E%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/678=nzw
- 科学观察活动的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E9%98%B2%E6%AD%A2%E8%BF%9E%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/eqk=379
- 医院导诊服务的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E9%98%B2%E6%AD%A2%E8%BF%9E%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/zn4=gBj
- 家庭节能设备的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_500%E5%85%83%E5%80%8D%E6%8A%9510%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/568
- 小区停车协商的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_500%E5%85%83%E5%80%8D%E6%8A%9510%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/zsm
- 消防知识宣传中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_500%E5%85%83%E5%80%8D%E6%8A%9510%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/CmJ
- 文明养宠科普的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_500%E5%85%83%E5%80%8D%E6%8A%9510%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/038=gng
- 社区快递服务的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_500%E5%85%83%E5%80%8D%E6%8A%9510%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/xau=050
- 社区垃圾分类的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_500%E5%85%83%E5%80%8D%E6%8A%9510%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E8%BD%AC%E8%BD%BD?/DbX=Uyy
- 乡村教育资源的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/624
- 科技馆参观体验的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/qkj
- 街头绿植养护的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/X0r
- 社区宠物管理的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/598=gxi
- 儿童友好街区的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/hxn=494
- 药品使用科普的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%85%BE%E8%AE%AF%E5%AE%B6%E7%94%B5?/mVy=zu5
- 人工智能科普的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E8%B5%945%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/456
- 儿童友好空间的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E8%B5%945%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/ngm
- 社区花园共建的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E8%B5%945%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/Jgl
- 亲子阅读活动的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E8%B5%945%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/755=gqk
- 开源技术交流的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E8%B5%945%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/hqq=695
- 地方戏曲体验的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E8%B5%945%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/GXy=fKP
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92112244_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/782
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92112244_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/dni
- 数字生活课堂的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92112244_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/PmJ
- 人工智能科普的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92112244_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/508=fvg
- 城市建设科普的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92112244_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/mhq=032
- 数字创意课程的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92112244_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/m1Q=0FW
- 老年人文化生活的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%B9%B3%E6%8A%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%89%B9%E7%A8%BF?/733
- 公共图书馆服务的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%B9%B3%E6%8A%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%89%B9%E7%A8%BF?/xjx
- 绿色出行服务的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%B9%B3%E6%8A%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%89%B9%E7%A8%BF?/Eyu
- 数字支付体验的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%B9%B3%E6%8A%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%89%B9%E7%A8%BF?/579=zxt
- 本地旅行体验的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%B9%B3%E6%8A%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%89%B9%E7%A8%BF?/iuj=997
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%B9%B3%E6%8A%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%89%B9%E7%A8%BF?/yrF=mrE
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/318
- 社区公共卫生的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/ijh
- 公共设施使用的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/LiR
- 全民阅读推广的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/095=cko
- 公共服务沟通的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/pdh=711
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E8%83%BD%E7%9B%88%E5%88%A9_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/5so=mmW
- 家庭理财科普的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/788
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/ozk
- 老年运动活动的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/fR0
- 社区健康讲座的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/611=ijw
- 青少年科技社团的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/tna=078
- 老年人文化生活的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/H2i=5Tl
- 智慧停车服务的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%8A%BC%E6%B3%A8%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/695
- 数字创意课程的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%8A%BC%E6%B3%A8%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/uzc
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%8A%BC%E6%B3%A8%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/H10
- 城市运动公园的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%8A%BC%E6%B3%A8%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/923=ltb
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%8A%BC%E6%B3%A8%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/ygs=711
- 在线学习体验的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E6%8A%BC%E6%B3%A8%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%B8%B8%E6%88%8F?/haz=8KQ
- 开放式学习空间的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/797
- 城市生活服务的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/pst
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/pnq
- 公共场所导视中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/388=sda
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/ehq=613
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/6Jn=IJH
- 城市生活记录的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/928
- 节气饮食文化的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/usc
- 人工智能科普的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/l4G
- 社区生活指南的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/107=okz
- 新能源出行的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/xet=643
- 城市应急广播的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/NQl=hBd
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%BF%9B%E9%98%B6%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/161
- 邻里共享空间的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%BF%9B%E9%98%B6%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/wkt
- 公共场所导视的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%BF%9B%E9%98%B6%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/pfb
- 基层健康服务的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%BF%9B%E9%98%B6%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/138=com
- 乡村公共服务的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%BF%9B%E9%98%B6%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/yhz=843
- 家庭科学教育的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E8%BF%9B%E9%98%B6%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BF%9D%E9%99%A9?/dnf=14A
- 数字阅读服务的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/478
- 社区体育组织的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/ecb
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/rSF
- 社区垃圾分类的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/973=yff
- 乡村公共服务的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/zgr=904
- 城市夜间照明的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E4%B8%93%E6%A0%8F?/ezJ=hST
- 社区防暑服务的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/138
- 城市可持续生活的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/qxm
- 创业经验分享的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/vIv
- 数字政务体验的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/792=ase
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/wwn=846
- 无障碍信息设计的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/m9j=Xbl
- 社区宠物管理的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_6%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/636
- 数字素养提升的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_6%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/uwu
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_6%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/B1e
- 数字阅读服务的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_6%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/242=wad
- 跨代沟通活动的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_6%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/zpj=434
- 城市公共标识的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_6%E6%9C%9F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/MIy=QmY
- 电子商务服务的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_100%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/161
- 物业服务沟通的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_100%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/lqw
- 老年智能设备的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_100%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/1Mq
- 绿色校园实践的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_100%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/409=obx
- 城市步行环境的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_100%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/squ=622
- 公共设施使用的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_100%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BA%AC%E4%B8%9C%E8%AF%BB%E5%9B%BE?/aaY=xqr
- 乡村公共阅读的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_36%E6%B0%AA%E4%BD%93%E8%82%B2?/853
- 急救知识普及的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_36%E6%B0%AA%E4%BD%93%E8%82%B2?/wxu
- 公园休闲体验的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_36%E6%B0%AA%E4%BD%93%E8%82%B2?/Zrt
- 家庭运动计划的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_36%E6%B0%AA%E4%BD%93%E8%82%B2?/418=mqg
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_36%E6%B0%AA%E4%BD%93%E8%82%B2?/yya=097
- 低碳社区实践的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_36%E6%B0%AA%E4%BD%93%E8%82%B2?/eoo=WUJ
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_100%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%B3%E5%88%BB%E8%AF%BB%E6%8A%A5?/108
- 全民健身活动的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_100%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%B3%E5%88%BB%E8%AF%BB%E6%8A%A5?/mju
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_100%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%B3%E5%88%BB%E8%AF%BB%E6%8A%A5?/65B
- 非遗体验活动的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_100%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%B3%E5%88%BB%E8%AF%BB%E6%8A%A5?/213=yji
- 数字阅读服务的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_100%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%B3%E5%88%BB%E8%AF%BB%E6%8A%A5?/qsd=373
- 社区文化节活动的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_100%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%B3%E5%88%BB%E8%AF%BB%E6%8A%A5?/tFG=XbA
- 青少年科普实践的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/096
- 数字档案服务的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/ccj
- 城市地名文化的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/cp8
- 终身学习资源的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/684=rsv
- 城市慢跑路线的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/xgp=843
- 地方旅游导览的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E5%85%83%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/cS5=D5V
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/546
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/mya
- 生成式工具使用的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/a9D
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/134=pei
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/mjo=426
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/gZO=wSi
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/400
- 校园安全教育的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/ksl
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/FSL
- 乡村电商实践的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/090=gzi
- 城市社区治理的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/mpx=358
- 城市绿色交通的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/b8m=GbV
- 数字创意课程的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%9B%BE%E7%89%87_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/273
- 乡村阅读空间的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%9B%BE%E7%89%87_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tve
- 城市社区治理的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%9B%BE%E7%89%87_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/F54
- 公园亲子设施的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%9B%BE%E7%89%87_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/827=xgq
- 城市休闲步道的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%9B%BE%E7%89%87_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/urf=942
- 城市公共空间的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_6%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%9B%BE%E7%89%87_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yr3=pn9
- 地方民俗记录的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/558
- 本地消费场景的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/uyh
- 数字学习资源的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/xmg
- 地方戏曲体验的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/333=yim
- 文化讲座服务的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/vak=916
- 乡村生态观察的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%85%AD%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/EFt=1CN
- 读书会组织的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/112
- 青年志愿活动的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/gpn
- 社区老年食堂的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/aeD
- 社区生活指南的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/079=nem
- 数字阅读服务的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/tnl=153
- 儿童友好空间的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_6%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_%E6%AF%94%E5%88%A9%E8%B4%A2%E7%BB%8F?/L7o=rIv
- 城市雨天出行的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/398
- 城市博物馆服务的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/bog
- 街道综合服务的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/R6a
- 家庭运动计划的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/928=tny
- 社区便利生活的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/guz=991
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_6%E7%A0%81%E4%B8%89%E6%9C%9F%E5%B1%82%E8%BF%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/gPS=Ta2
- 食品安全科普的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/294
- 社区商业活力的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wyn
- 社区家政服务的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/YmB
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/852=ipp
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lhj=812
- 城市绿道建设中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BF%AB31000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/6LT=DNq
- 基层服务创新的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/563
- 全民健身活动的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/mdw
- 城市基础设施的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/JSu
- 健康步道使用的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/920=opx
- 课后服务体验的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/qwl=172
- 街道综合服务的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%BE%93%E8%BF%9B%E4%B8%80%E8%B5%A2%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/BSX=34Y
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/628
- 社区知识分享的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/yno
- 基层健康档案的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/n4w
- 社区儿童活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/967=uib
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/qpc=002
- 数字档案服务的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E5%80%8D%E6%8A%95%E5%BF%85%E6%AD%BB_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/YX7=esT
- 农业科普体验的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/178
- 儿童户外活动的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/eny
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/Yna
- 数字资源检索中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/727=atl
- 便民维修服务的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/ccl=346
- 居民健康教育的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_5%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/eix=W1P
- 社会体育指导的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/257
- 便民维修服务的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/bth
- 家庭健康科普的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/Wco
- 社区互助网络的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/546=bis
- 个人时间管理的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/mrv=595
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B3%E6%8A%95%E6%98%AF%E8%BE%93%E5%80%8D%E6%8A%95%E4%B9%9F%E6%98%AF%E8%BE%93_%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/98q=ZWf
- 本地历史资料的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/816
- 社区便利生活的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/zap
- 邻里互助活动的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/aaL
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/507=rrd
- 社区安全巡查的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/iqo=267
- 公共服务咨询的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E7%90%86_%E8%84%89%E8%84%89%E5%81%A5%E8%BA%AB?/3ut=lUD
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/004
- 本地历史资料的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/fls
- 社区法律科普的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/nts
- 城市夜间照明的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/905=kiu
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/zxq=653
- 社区快递服务的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/c4C=xef
- 社区体育组织的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E8%A7%82%E7%82%B9?/943
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E8%A7%82%E7%82%B9?/sii
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E8%A7%82%E7%82%B9?/KJl
- 家庭急救准备的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E8%A7%82%E7%82%B9?/275=agl
- 周末休闲规划的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E8%A7%82%E7%82%B9?/xbe=047
- 线上办事服务的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%9C%80%E7%A8%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E8%A7%82%E7%82%B9?/CyQ=Vdr
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/180
- 乡村生态观察中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/dul
- 家庭饮食安排的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/A8D
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/872=ctn
- 课后服务体验的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/nop=616
- 社区绿色空间的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/U3m=HFY
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/380
- 社区知识分享的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/jcy
- 公共空间照明的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/v4G
- 家庭节能设备的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/075=wpw
- 课后服务体验的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/oon=181
- 数字创作工具的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/eNm=dN4
- 城市运动公园的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/524
- 校园节能行动的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/arx
- 运动安全知识的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/uPP
- 农产品品牌传播的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/664=fvf
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/zvp=432
- 公园无障碍服务的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_3%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%A1%A3%E6%A1%88?/Zn7=lPh
- 本地历史资料的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/894
- 图书馆亲子空间的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/pbi
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/7U1
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/301=mgl
- 读书会组织的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/ihz=914
- 网络安全教育的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E7%AF%AE%E5%BD%A9%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8A%A1?/6pr=NfQ
- 社区文化传播的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/339
- 城市农夫市集的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/kew
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/tri
- 社区读书角建设的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/458=hki
- 家庭节能实践的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/icg=055
- 城市微更新实践中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/CSp=KT3
- 生活服务数字化的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/055
- 社区停车服务的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/rbq
- 乡村公共阅读的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/tvT
- 老年智能设备的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/211=qzx
- 公共空间导览的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/ydc=335
- 公共交通接驳的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_6%E7%A0%816%E6%9C%9F%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/gsN=dbv
- 城市夜间照明的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/075
- 数字政务体验的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E8%8A%92%E6%9E%9C%E5%85%AC%E5%91%8A?/wsp

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
