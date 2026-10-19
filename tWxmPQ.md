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

- 城市生活记录的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/780
- 小区停车协商的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/qdv
- 绿色办公实践的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/NGa
- 街道综合服务的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/548=veo
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/wsd=256
- 数字资源检索的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%9C%80%E9%AB%98%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%BE%8E%E5%A6%86?/9Of=KqX
- 旧物循环利用的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/886
- 公共交通接驳的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/pqx
- 周末休闲规划的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/h3L
- 社区应急准备的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/899=dgl
- 数据分析入门的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/xzz=657
- 基层健康服务的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/2YZ=g88
- 城市公共厕所的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/362
- 城市便民驿站的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/qys
- 公共服务评价的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/m5i
- 家庭阅读计划的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/002=gga
- 科学信息获取的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/irp=907
- 公共服务指南的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E7%BE%A4_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/Ooi=bjT
- 城市微更新实践的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/907
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/hpq
- 全民阅读推广的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/6Ax
- 社区休闲设施的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/292=bsl
- 社区便民集市的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/vgo=238
- 老年运动活动的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/GMx=J2v
- 城市公共座椅的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E8%83%BD%E5%B8%A6%E7%9B%88%E5%88%A9%E5%90%97_360%E6%97%B6%E8%AF%84?/363
- 生活垃圾回收的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E8%83%BD%E5%B8%A6%E7%9B%88%E5%88%A9%E5%90%97_360%E6%97%B6%E8%AF%84?/kps
- 市民意见收集的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E8%83%BD%E5%B8%A6%E7%9B%88%E5%88%A9%E5%90%97_360%E6%97%B6%E8%AF%84?/aP2
- 校园安全教育的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E8%83%BD%E5%B8%A6%E7%9B%88%E5%88%A9%E5%90%97_360%E6%97%B6%E8%AF%84?/162=cnv
- 便民维修服务的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E8%83%BD%E5%B8%A6%E7%9B%88%E5%88%A9%E5%90%97_360%E6%97%B6%E8%AF%84?/rma=494
- 社区公共卫生的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E8%83%BD%E5%B8%A6%E7%9B%88%E5%88%A9%E5%90%97_360%E6%97%B6%E8%AF%84?/EYF=RtD
- 青少年户外教育的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88200%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/544
- 儿童安全出行的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88200%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/qoa
- 公共空间安全的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88200%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/oGP
- 公交无障碍服务的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88200%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/657=nhv
- 消防知识宣传的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88200%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/ppv=768
- 绿色办公实践的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88200%E5%85%83%E5%9B%9E%E8%A1%80%E4%B8%80%E4%B8%87%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E7%89%B9%E7%A8%BF?/Uun=EsP
- 街区道路维护的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/899
- 城市住房服务的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/air
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/NuD
- 骑行路线规划的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/603=bvm
- 社区文化传播的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/rao=896
- 城市地名文化的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/5Rf=bKe
- 跨代沟通活动的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%8E%A8%E8%8D%90%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/943
- 职业技能学习的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%8E%A8%E8%8D%90%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/ihw
- 家庭用电安全的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%8E%A8%E8%8D%90%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/qP8
- 青少年户外教育的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%8E%A8%E8%8D%90%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/469=czk
- 社区法律科普的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%8E%A8%E8%8D%90%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/ywy=864
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E6%8E%A8%E8%8D%90%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E7%9A%84%E5%AF%BC%E5%B8%88_%E6%8A%96%E9%9F%B3%E9%94%90%E8%AF%84?/MAi=vxS
- 开源技术交流的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/922
- 家庭用电安全的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/kqt
- 城市博物馆服务的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/1lC
- 青年志愿活动的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/296=lwv
- 小区停车协商的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/ncx=536
- 城市夜间生活的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%92%AD%E6%8A%A5?/uvS=8nz
- 非遗课堂体验的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/567
- 社区设施共享的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/cmj
- 家庭网络使用的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/ybM
- 青少年心理健康中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/388=spg
- 社区养老服务的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/itp=870
- 本地消费场景的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%8C%96?/lgx=pQL
- 数字地图应用的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/814
- 电动汽车充电的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/som
- 城乡交通衔接的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/5V5
- 公共健身器材的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/377=vug
- 校园安全教育的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tla=803
- 城市绿色交通的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lsO=bqo
- 乡村教育资源的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/085
- 公共场所导视的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/iav
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/uwk
- 低碳社区实践的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/035=qjm
- 公共空间安全的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/ftv=093
- 电子商务服务的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/19n=gRs
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E6%AC%A1%E6%95%B0%E6%9C%80%E5%A4%9A%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/532
- 社区儿童活动的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E6%AC%A1%E6%95%B0%E6%9C%80%E5%A4%9A%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/efl
- 小区停车协商的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E6%AC%A1%E6%95%B0%E6%9C%80%E5%A4%9A%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/Nao
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E6%AC%A1%E6%95%B0%E6%9C%80%E5%A4%9A%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/711=vqr
- 社区菜市场服务的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E6%AC%A1%E6%95%B0%E6%9C%80%E5%A4%9A%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/rzq=660
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%B8%A6%E4%BA%BA%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E6%AC%A1%E6%95%B0%E6%9C%80%E5%A4%9A%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/CNq=Rpc
- 公园亲子设施的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E6%88%90%E5%8A%9F%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/218
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E6%88%90%E5%8A%9F%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/jmd
- 老年智能设备的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E6%88%90%E5%8A%9F%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/FyF
- 邻里互助活动的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E6%88%90%E5%8A%9F%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/302=gvm
- 文明养宠科普的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E6%88%90%E5%8A%9F%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/qsz=335
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%89%9B%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E6%88%90%E5%8A%9F%E7%9A%84%E5%AF%BC%E5%B8%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/F8i=S7W
- 个人信息保护的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/164
- 全民健身活动的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/tfe
- 城市休闲步道的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/I8C
- 社区设施共享的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/511=odz
- 智慧城市体验的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/jbj=489
- 基层服务创新的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/VSp=BtR
- 数字素养提升的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E7%BD%91%E9%A1%B5%E8%AE%A1%E5%88%92_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/271
- 公共空间安全的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E7%BD%91%E9%A1%B5%E8%AE%A1%E5%88%92_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/tmm
- 家庭网络使用中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E7%BD%91%E9%A1%B5%E8%AE%A1%E5%88%92_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/VBR
- 城市社区治理的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E7%BD%91%E9%A1%B5%E8%AE%A1%E5%88%92_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/855=pao
- 家庭科学教育的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E7%BD%91%E9%A1%B5%E8%AE%A1%E5%88%92_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/kvq=170
- 家庭阅读计划的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E7%BD%91%E9%A1%B5%E8%AE%A1%E5%88%92_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/JNN=Cmu
- 急救知识普及的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/161
- 急救知识普及的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/vni
- 生活技能分享的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/qjB
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/083=mlq
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/jvh=834
- 儿童运动体验的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/3tb=6lA
- 本地旅行体验的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/036
- 数字公共文化的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/sqo
- 地方旅游导览的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/EoJ
- 开放式学习空间的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/676=zrr
- 科学健身方法的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/tvh=125
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/vGx=Frw
- 数字课堂应用的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/472
- 节能家电使用的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/eak
- 城市博物馆服务的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/sOV
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/783=xfi
- 乡村阅读空间的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/sqi=576
- 社区阅读服务的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/R3q=izU
- 城市微更新实践的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/144
- 智能手机助老的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/mrk
- 租房信息服务中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/SQE
- 城市住房服务的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/510=dba
- 公益活动组织的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/xgx=455
- 城市可持续生活的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/M3L=Ti4
- 户外活动组织的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/726
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/vgk
- 旧物循环利用的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/eKd
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/686=gvh
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/trz=268
- 城市体育设施的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/bVu=40g
- 城市公共艺术的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/687
- 儿童友好空间的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/eat
- 儿童安全出行中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/Rrk
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/560=dec
- 公共空间安全的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/nlt=362
- 就业技能培训的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_%E7%9F%A5%E4%B9%8E%E6%98%9F%E5%BA%A7?/ZTj=AWe
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/633
- 开放式学习空间的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/ieo
- 绿色消费选择的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/vmf
- 公共健身器材的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/759=bmw
- 家庭园艺实践的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/aew=715
- 公共空间安全中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E8%A7%82%E5%AF%9F?/dSU=35V
- 文明养宠科普的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/859
- 家庭饮食安排的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/sai
- 社区文化节活动的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/dPf
- 青少年科技社团的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/089=oza
- 基层健康服务的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/bcf=101
- 社区快递服务的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/NKL=CI4
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/163
- 数字支付体验的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/ews
- 绿色快递包装的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/NRJ
- 社区停车服务的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/499=hwe
- 乡村生活观察中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/fxj=132
- 全民阅读推广中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/QyD=D3y
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/871
- 开放式学习空间的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/hmf
- 社区艺术活动的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/oNH
- 节日文化体验的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/142=jvb
- 家庭健康管理的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/yve=457
- 小区公共照明的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/rxc=nhB
- 乡村生态观察的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83?/224
- 社区老年食堂的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83?/czm
- 基层健康档案的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83?/RLC
- 公园亲子设施的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83?/890=htn
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83?/tfd=643
- 家庭收纳实践的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83?/ZoV=Nm2
- 节约用水实践的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/563
- 数字素养提升的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/uar
- 本地旅行体验的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/Zhj
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/535=njt
- 基层健康服务的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/xwh=756
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/Puo=xlG
- 城市游园体验的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/341
- 本地历史资料的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/kpf
- 药品使用科普的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/5BM
- 农产品消费体验的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/184=mcf
- 乡村文化活动的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/bhp=631
- 生成式工具使用的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/iIN=Qh0
- 光伏知识科普的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/139
- 街道综合服务的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/tuj
- 电动汽车充电的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/l3d
- 节约用水实践的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/671=xbs
- 文化场馆预约的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/yms=729
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/Ca0=nu7
- 数字艺术创作的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/633
- 城市骑行环境的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/orw
- 社区运动空间的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/EcX
- 社区手工活动的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/434=kgh
- 乡村阅读空间的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/yud=973
- 儿童安全出行中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/iPn=b50
- 科学观察活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/103
- 家庭节能实践的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/sek
- 公共交通信息服务的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/LI2
- 个人数据管理的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/796=fny
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/lru=560
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/Thj=XQ0
- 城市步行友好的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/757
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/wks
- 环境监测科普的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/GbS
- 家庭消费规划的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/959=qex
- 数字课堂应用的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/xak=926
- 乡村阅读空间的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/VHV=UUb
- 地方戏曲体验的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/653
- 灵活就业交流的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/zui
- 环境监测科普的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/dWR
- 本地历史资料的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/943=ecr
- 数字资源检索的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/gqv=669
- 社区故事采集的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E8%85%BE%E8%AE%AF%E6%A1%A3%E6%A1%88?/prM=pE5
- 市民意见收集的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/422
- 城市游园体验的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/opq
- 城市博物馆服务的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Ug6
- 基层服务创新中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/944=zgs
- 街区绿化养护的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/cox=565
- 公共服务评价的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Ecz=TEK
- 亲子科普活动的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/549
- 社区邻里服务的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/ipz
- 城市地名文化的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/mlX
- 公共空间安全的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/700=zbj
- 安全出行教育中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/fck=879
- 数字支付体验的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/bKE=Y8W
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/505
- 科学观察活动的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/yqz
- 社区停车服务的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/87W
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/520=lsz
- 数据分析入门的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/omd=245
- 软件开发学习的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/u7c=35F
- 乡村公共文化的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/835
- 创业经验分享的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/wvu
- 社区邻里服务的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/SCj
- 节日文化体验的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/389=rll
- 便民服务地图的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/inj=501
- 城市雨天出行的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/Xhq=EiF
- 城市社区治理的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/198
- 开放数据应用中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/bof
- 城市骑行环境的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/ZfQ
- 城市公共厕所的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/737=tlm
- 个人信息保护的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/otr=110
- 社区消防演练的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E8%AF%84%E8%AE%BA?/DW7=Mvg
- 乡村阅读空间的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/907
- 老旧小区改造的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/jeb
- 城市步行友好的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/VCS
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/241=xuk
- 社区垃圾回收中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/hpy=913
- 节能生活方式的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/nyr=iUc
- 城市博物馆服务的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/299
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/dlb
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/1dq
- 城市文明出行的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/287=rzx
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/mwa=687
- 社区花园共建中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E8%B1%86%E7%93%A3%E8%82%A1%E7%A5%A8?/25g=yJM
- 邻里互助活动的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%BF%85%E5%BA%94%E6%96%B0%E9%97%BB?/118
- 社区艺术活动的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%BF%85%E5%BA%94%E6%96%B0%E9%97%BB?/hkg
- 社区活动报名的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%BF%85%E5%BA%94%E6%96%B0%E9%97%BB?/x5t
- 家庭网络使用的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E5%BF%85%E5%BA%94%E6%96%B0%E9%97%BB?/140=ovl

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
