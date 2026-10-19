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

- 社区便民集市的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/212
- 新能源出行的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/fmk
- 城市社区治理的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/jsV
- 垃圾分类指导的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/052=ysk
- 乡村电商实践的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/pqv=567
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/yDj=vga
- 城市绿色交通的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/432
- 基层服务创新的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/zld
- 科普展览体验的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/6Y4
- 城市文明出行的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/835=lnx
- 公共空间休憩的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/mxk=581
- 城市步行友好的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/FfT=6dS
- 城市夜间生活的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/703
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/cua
- 城市住房服务的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/JDF
- 小微企业服务的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/941=ewj
- 城市展览体验的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ytg=858
- 老年人日常照护的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/P7p=D1C
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/841
- 运动安全知识的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/opo
- 家庭健康科普的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Ul7
- 数字创作工具的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/958=bos
- 地方旅游导览的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rnh=901
- 社区活动策划的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/WH0=hPg
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/981
- 数字地图应用的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/bst
- 公共服务评价中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/Yk1
- 家庭科学教育的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/603=zkh
- 家庭防灾准备的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/cop=557
- 学校体育活动的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/TxV=2Eb
- 公共空间照明的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9?/852
- 生活服务数字化的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9?/kav
- 市民热线服务的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9?/YQ9
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9?/255=hgw
- 社区信息发布的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9?/osf=614
- 乡村公共文化的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9?/IXO=7bF
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/700
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/tvb
- 公共服务指南的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/ynl
- 公共服务指南的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/458=sde
- 青少年科普实践的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/pct=295
- 灵活就业交流的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/yll=vBd
- 安全出行教育的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/422
- 儿童运动体验的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/vfx
- 节能生活方式的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/Sgp
- 户外活动组织的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/967=jyl
- 公益活动组织的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/xsa=535
- 骑行路线规划的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/92E=kzz
- 家庭养老规划的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/282
- 应急物资管理的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/tar
- 城市地名文化的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/JZk
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/265=zbj
- 城市公共饮水的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/pyb=444
- 科普展览体验的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/pcw=aC6
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/008
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/asj
- 城市便民驿站的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/3dL
- 城市基础设施的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/622=uhz
- 网络信息辨识的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/fge=911
- 公共服务咨询的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E4%B9%A6?/Ulp=ccz
- 开放数据应用的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/202
- 社区公共卫生的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/cvv
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/MNp
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/125=leq
- 公共设施维护的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/lkd=555
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/WO3=WvX
- 数字地图应用的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/431
- 城市建设科普的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/ywv
- 公共服务咨询的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/SmN
- 健康饮水科普的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/009=lsl
- 城市共享单车的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/srs=203
- 社区托育服务的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/Let=YuT
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/926
- 公共文化活动的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/yys
- 公共服务评价的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/Ors
- 社区防暑服务的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/915=tva
- 社区故事采集的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/wpe=485
- 本地历史资料的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/mGh=tX4
- 软件开发学习的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/081
- 科技馆参观体验的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/yoq
- 租房信息服务的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/h4T
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/331=yyt
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/ooz=878
- 租房信息服务中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/aFx=u8V
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/975
- 家庭健康管理的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/bux
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/G7o
- 街区更新实践的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/394=xfq
- 乡村生态旅游的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/swl=107
- 机器人科普活动的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/hLR=prB
- 乡村公共服务的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/721
- 社区手工活动中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/gpw
- 开放数据应用的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/3Rs
- 节能生活方式的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/859=nfx
- 公共设施维护的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/kbt=809
- 街头绿植养护的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/QVB=yLv
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/783
- 科学信息获取的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/eqz
- 社区协商议事中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/jwr
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/944=tjc
- 个人数据管理的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/wgr=612
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%A5%BC%E5%B8%82?/z3Q=vfM
- 公共交通信息服务的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/950
- 家庭健康科普的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/xbr
- 运动安全知识的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/92g
- 节日文化体验的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/187=mtr
- 城市建设科普的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/akt=988
- 城市空气科普的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/rGh=iXc
- 邻里共享空间的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/842
- 家庭阅读计划的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/aun
- 数字阅读服务的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/FDf
- 节日文化体验的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/082=llm
- 社区快递服务的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/new=405
- 社区公共议事的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E6%8A%96%E9%9F%B3%E5%9C%B0%E6%96%B9?/oNs=kzD
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/365
- 家庭照护支持的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/wbv
- 社区邻里服务的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/WjK
- 老年人日常照护的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/569=yqf
- 城市便民驿站的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/frv=545
- 城市噪声观察的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/32d=QSK
- 社区垃圾回收中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/793
- 城市应急广播的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/ihx
- 数据分析入门的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/qKT
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/575=vry
- 公共卫生设施的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/axg=038
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/OX9=Dfo
- 开放数据应用的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/661
- 乡村产业科普的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/pye
- 街道综合服务的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/PCT
- 城市游园体验的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/835=jqg
- 本地历史资料的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/app=509
- 城市空气科普的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/SVP=XYE
- 校园社团活动的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/282
- 数字支付体验的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/axh
- 健康饮水科普中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/D9k
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/471=wsg
- 乡村公共阅读的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/uke=492
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/KP6=Z7f
- 城市人文观察的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/866
- 公共服务指南的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/mtz
- 信息无障碍体验的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/8DK
- 街区道路维护的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/757=fcy
- 公共场馆服务的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/nha=323
- 农村环境治理的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/g8R=KIp
- 城市绿道建设的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/549
- 社区运动空间的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/nqh
- 城市步行环境的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/CFt
- 个人数据管理的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/691=npo
- 旧物循环利用的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/crr=287
- 社区文化节活动的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%88%91%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%8640%E4%B8%87_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/LgB=4wU
- 乡村产业科普的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/944
- 儿童运动体验的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/etb
- 公共设施使用的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/8Rc
- 绿色消费选择的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/634=ggu
- 城市公共座椅的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/fum=347
- 骑行路线规划的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/TWV=g8G
- 网络安全教育的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/590
- 亲子阅读活动的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ewo
- 公共服务数字化的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vxL
- 数字艺术创作的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/786=odz
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jpc=814
- 数字学习资源的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BC%9A%E9%BB%91%E9%92%B1%E5%90%97_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ZcZ=rmM
- 家庭防灾准备的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/287
- 社区设施共享的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/zid
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/qMn
- 乡村公共文化的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/177=hqt
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/dhq=949
- 健康饮食教育的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E7%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8E%BF%E5%9F%9F?/7rD=fz1
- 农村环境治理的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/706
- 青少年心理健康的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/zls
- 公益活动组织的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/gDL
- 文明养宠科普的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/701=kzo
- 课后服务体验的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/nae=429
- 公共图书馆服务的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%A1%E6%A0%B8%E4%B8%AD3%E5%A4%A9%E4%BA%86_%E7%9F%A5%E4%B9%8E%E6%B1%BD%E8%BD%A6?/5Xy=C3i
- 社区公共议事中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/649
- 城市文明实践的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/fso
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/PSI
- 社区手工活动的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/877=ckm
- 健康饮水科普的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/lcv=371
- 城市展览体验的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E4%BA%86_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/Wtc=mGV
- 社区共享书架的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/797
- 开源技术交流的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/eui
- 街区道路维护的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/W6S
- 公园休闲体验的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/310=czs
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/bta=412
- 全民阅读推广的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/VS5=5AJ
- 城市公共自行车的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_360%E5%8C%BB%E8%8D%AF?/023
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_360%E5%8C%BB%E8%8D%AF?/rna
- 街区小店体验的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_360%E5%8C%BB%E8%8D%AF?/QhX
- 电动汽车充电的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_360%E5%8C%BB%E8%8D%AF?/324=pya
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_360%E5%8C%BB%E8%8D%AF?/rpc=630
- 健康信息获取的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_360%E5%8C%BB%E8%8D%AF?/yN7=V9j
- 数字阅读服务的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/591
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/eyw
- 信息无障碍体验的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/29C
- 城市文明出行的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/978=xrd
- 老年数字阅读的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/hmi=709
- 家庭用电安全的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/E93=JpC
- 文明养宠科普的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/763
- 市民热线服务的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/qzy
- 公共服务数字化的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/O1T
- 户外活动组织的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/549=sjq
- 环境监测科普的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/pns=615
- 城市绿色交通的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E5%AE%9E%E5%BD%95?/i1C=czF
- 社区环保活动的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/225
- 数字创意课程的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/byr
- 地方民俗记录的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/IxH
- 无障碍信息设计的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/777=srr
- 城市住房服务的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/kui=060
- 地方戏曲体验的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/ifA=BGF
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/513
- 家庭网络使用的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/sys
- 社区绿色空间的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/Mnw
- 绿色快递包装的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/793=ygc
- 人工智能科普的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/yye=455
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/4hF=fMZ
- 老旧小区改造的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/818
- 城市微更新实践的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/whe
- 儿童友好空间的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/LKO
- 公共文化活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/732=rst
- 家庭教育交流的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/pvx=280
- 数字创作工具的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_51%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/v8r=sSw
- 数字政务体验的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/669
- 社区科普课堂的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/rxa
- 公共空间照明的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/L2E
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/046=vdr
- 社区教育资源的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/oul=653
- 节日文化体验的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91722%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BB%8F%E6%B5%8E%E8%B4%A2%E7%BB%8F?/HeW=t6m
- 食品配送体验的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/599
- 街区绿化养护的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/mwj
- 乡村教育资源的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/TRu
- 社区体育组织的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/992=rpt
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/okv=404
- 学校食育活动的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/NRl=DRM
- 开源技术交流的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/391
- 家庭收纳实践的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/hcp
- 本地历史资料的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/0EO
- 城市空气科普的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/802=fjt
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/qdl=072
- 城市雨天出行的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E6%89%A3%E6%89%A3_%E8%B1%86%E7%93%A3%E7%9B%B4%E6%92%AD?/GY8=uTf
- 劳动教育实践的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/408
- 公共空间安全的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/cjp
- 城市文明实践的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/R7P
- 城乡公共服务的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/933=muo
- 乡村阅读活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/vqo=250
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E5%B8%AE%E4%BA%BA%E6%8A%8A%E8%BE%93%E7%9A%84%E9%92%B1%E8%B5%A2%E5%9B%9E%E5%91%A2_%E6%90%9C%E7%8B%97%E5%A8%B1%E4%B9%90?/kxm=OQN
- 城市公共艺术的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/362
- 家庭急救准备的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/aps
- 城市噪声观察的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/mRe
- 节约用水实践的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88qq%E5%8F%B7_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/737=lki

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
