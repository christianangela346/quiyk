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

- 家庭阅读计划的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/SpS
- 租房信息服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/659=fli
- 社区活动空间的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/uwf=867
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%99%8E%E5%97%85%E6%96%87%E5%8C%96?/F3Q=S9c
- 公共服务咨询的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/199
- 儿童友好街区的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/yya
- 城市空气科普的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/m1M
- 家庭急救准备的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/920=yjs
- 公共服务数字化的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/tzm=614
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E7%99%BE%E5%BA%A6%E5%9B%9E%E6%9C%9B?/Isx=rr9
- 社区养老服务的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/199
- 城市生活记录的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/gda
- 社区儿童活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/x4i
- 城乡交流活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/887=nke
- 骑行路线规划的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/rqi=923
- 家庭健康科普的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/gZN=IMI
- 数字艺术创作的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%86%E9%A2%91?/859
- 城市休闲步道的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%86%E9%A2%91?/wdl
- 家庭教育交流中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%86%E9%A2%91?/ABJ
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%86%E9%A2%91?/304=tlk
- 老年人文化生活的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%86%E9%A2%91?/pwa=720
- 社区应急准备的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E8%A7%86%E9%A2%91?/Cob=MMI
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/502
- 无障碍信息设计的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/yun
- 社区教育资源的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/Nhr
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/348=ztj
- 家庭网络使用的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/hjs=801
- 科学观察活动的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/7TM=7aT
- 基层健康服务的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/179
- 家庭收纳实践的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/tyt
- 传统节日科普的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/Qgr
- 社区手工活动的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/196=wbv
- 社区公共卫生的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/dug=021
- 乡村生态观察的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/kLr=hUS
- 通勤路线规划的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/586
- 网络信息辨识的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/yrg
- 在线学习体验的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/fkF
- 公共卫生设施的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/114=kpg
- 校园阅读活动的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/vie=413
- 家庭用电安全的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/WhC=AjB
- 线上办事服务的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/955
- 学校食育活动的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/nnr
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/UYE
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/653=ulg
- 家庭理财科普的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/yaj=152
- 线上办事服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/Dnu=21W
- 社区菜市场服务的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%912_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/248
- 基层健康服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%912_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/zqb
- 绿色生活实践的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%912_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/wjU
- 街区更新实践的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%912_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/467=uwo
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%912_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/zfz=882
- 社区故事采集的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%912_%E7%BD%91%E6%98%93%E7%9B%98%E7%82%B9?/NGV=iQ4
- 社区互助网络的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/833
- 音乐欣赏活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/qqm
- 乡村生态旅游的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/N3Y
- 在线教育体验的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/464=eoi
- 居民健康教育的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/sha=025
- 居家防滑改造的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%BF%B0%E8%AF%84?/Vgd=KJh
- 城市运动公园的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/366
- 本地旅行体验的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/rhj
- 数字创意课程的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/3bT
- 通勤路线规划的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/012=xfr
- 儿童运动体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/qfe=578
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/0nW=8sy
- 家庭用电安全的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/583
- 小区停车协商的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/zxb
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/Hdn
- 无障碍出行的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/986=bkh
- 地方民俗记录的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/wud=164
- 公共服务预约的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%90%86%E8%B4%A2?/mKv=wwH
- 地方旅游导览的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/372
- 校园安全教育的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/pmo
- 在线学习体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/K9b
- 老年友好服务的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/728=xsu
- 社区垃圾回收的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/aoz=568
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%99%BE%E7%A7%91?/BPg=zWq
- 城市运动公园的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/579
- 青年志愿活动中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/zud
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/v3p
- 乡村生态观察的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/884=bfz
- 公共空间安全中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/tff=133
- 人工智能科普的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/LjW=NKE
- 城市社区治理的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/951
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/fqg
- 医院导诊服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/kTL
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/590=qgt
- 医院导诊服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/inj=662
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/xMP=1CI
- 便民信息查询的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/154
- 数字政务体验的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/gna
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/K6k
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/082=bfo
- 家庭志愿活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/rio=858
- 城市慢跑路线的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/0xd=WDq
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/712
- 数字支付体验的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/jyp
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/L63
- 社区科普课堂的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/944=qnh
- 城市公共空间的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xkr=386
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/IFs=5Bo
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%89%8B%E8%AE%B0?/937
- 地方文化传播的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%89%8B%E8%AE%B0?/rvg
- 社区运动空间的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%89%8B%E8%AE%B0?/WMD
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%89%8B%E8%AE%B0?/462=tts
- 社区防暑服务的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%89%8B%E8%AE%B0?/jhd=677
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%89%8B%E8%AE%B0?/T2v=3r3
- 乡村阅读活动的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/306
- 老年人出行服务的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/wfw
- 居民健康教育的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/rxs
- 公共场馆服务的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/107=fjp
- 绿色办公实践的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/hxd=931
- 社区活动空间的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%91%84%E5%BD%B1?/vhC=KlI
- 社区防暑服务的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/165
- 环境教育课程的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/iii
- 城市住房服务的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/Kfv
- 科学信息获取的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/497=jcs
- 城市文明实践的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/tqt=771
- 市民意见收集的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/x1y=eBk
- 城市步行友好的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/605
- 社区手工活动的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/tvu
- 公共设施维护的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/fIo
- 社会体育指导的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/125=cxh
- 科学信息获取的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/fcj=617
- 环境监测科普的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/JSI=5J5
- 城市体育设施的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/851
- 终身学习资源的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/cpy
- 公共设施维护的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/vqa
- 数字档案服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/672=dgt
- 个人时间管理的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/cjj=766
- 老年学习活动的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%88%B8%E5%95%86?/KXt=Avn
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/348
- 老年人出行服务的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/uwp
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/Cv1
- 街道综合服务的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/854=hqy
- 儿童户外活动的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/eeu=176
- 户外活动组织中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/IiE=ZLi
- 青少年心理健康的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/537
- 家庭环保习惯的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/lzl
- 社区体育组织的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/TEp
- 城市步行友好的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/319=srk
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/mhg=966
- 零废弃生活尝试的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/Oqb=zEI
- 社区体育组织的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_360%E4%BF%A1%E6%89%98?/156
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_360%E4%BF%A1%E6%89%98?/iqn
- 公共空间安全的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_360%E4%BF%A1%E6%89%98?/WvV
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_360%E4%BF%A1%E6%89%98?/551=own
- 文明养宠科普的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_360%E4%BF%A1%E6%89%98?/nlb=875
- 城市生活记录的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_360%E4%BF%A1%E6%89%98?/XLI=6OO
- 地方戏曲体验的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%9C%80%E6%96%B0%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/712
- 乡村产业科普的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%9C%80%E6%96%B0%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/bce
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%9C%80%E6%96%B0%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/NmU
- 社区停车服务的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%9C%80%E6%96%B0%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/927=cpj
- 社区运动空间的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%9C%80%E6%96%B0%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/hhz=436
- 科学健身方法的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD-%E6%9C%80%E6%96%B0%E5%9C%B0%E5%9D%80_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/bxV=Vh4
- 安全出行教育的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%859770_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/795
- 节能生活方式的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%859770_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/iqm
- 生活服务数字化的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%859770_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/9iQ
- 通勤路线规划的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%859770_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/400=dzk
- 社区邻里服务的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%859770_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/vlp=555
- 社区手工活动的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%859770_%E8%84%89%E8%84%89%E6%95%B0%E7%A0%81?/lF2=GnP
- 青年就业服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/818
- 读书会组织的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/nqi
- 科学教育活动的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/hGY
- 城乡公共服务的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/991=rqx
- 城市慢行系统中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/ixx=670
- 开源技术交流的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/xQ1=fUS
- 公交站点体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A8%B1app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/255
- 城市公共厕所的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A8%B1app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/nmv
- 公共服务预约的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A8%B1app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/4JS
- 数字资源检索中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A8%B1app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/382=ohd
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A8%B1app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/jyj=835
- 基层健康服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%A8%B1app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E7%9B%88%E8%B4%A2%E7%BB%8F?/oRn=3sD
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1688%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/687
- 数字设备回收的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1688%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/vex
- 街区小店体验的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1688%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/Yrx
- 网络信息辨识的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1688%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/309=hpb
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1688%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/ofz=077
- 老年人日常照护的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_1688%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/MdB=PFZ
- 城市生活服务的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/797
- 公共卫生设施的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/mmr
- 公园无障碍服务的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/AzF
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/839=fvj
- 青少年科技社团的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/web=398
- 乡村生活观察的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/2Xm=bdk
- 社区交通安全的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BC%98%E5%8F%9188%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/127
- 学校体育活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BC%98%E5%8F%9188%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/cyx
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BC%98%E5%8F%9188%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/qFp
- 数字课堂应用的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BC%98%E5%8F%9188%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/949=cyx
- 本地旅行体验的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BC%98%E5%8F%9188%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/cgm=680
- 城市绿色交通的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E4%BC%98%E5%8F%9188%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/lbG=mcY
- 城市展览体验的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vll%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/031
- 城市文化路线的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vll%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/ikb
- 地方美食文化的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vll%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/A51
- 城市空气科普的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vll%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/539=tda
- 公共卫生设施的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vll%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/awg=538
- 节能家电使用的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91vll%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/lD1=G3b
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/644
- 社区儿童活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/hrh
- 开放式学习空间的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/FFM
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/211=ltg
- 基层健康服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/izd=203
- 家庭环保习惯的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/qsr=gel
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/622
- 公交无障碍服务的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/bzo
- 青年职业探索的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/Lf3
- 图书馆数字服务的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/123=ksa
- 城市适老服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/egu=614
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/F9e=d1Q
- 数字阅读服务的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/924
- 个人信息保护的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/gwj
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/7Vm
- 节假日出行安排的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/039=mkp
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/ftc=337
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/YJa=cdS
- 环境教育课程的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/277
- 城市水环境观察的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/upt
- 个人数据管理的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/eb0
- 社区手工活动的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/746=enj
- 社区共享书架的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/xxl=047
- 公共服务咨询的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8657%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/H6Q=UPg
- 社区志愿服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/881
- 乡村教育资源中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/ddx
- 邻里共享空间的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/CdS
- 智能家居应用的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/341=nao
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/vbq=691
- 社区商业活力的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91168app%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%B6%E8%97%8F?/jEg=C5e
- 新能源出行的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/176
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/kwq
- 社区应急准备的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/rUC
- 读书会组织的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/425=uie
- 节能生活方式的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/qwv=243
- 社区公共餐饮的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/FUe=z67
- 创业经验分享的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/993
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/get
- 街头绿植养护的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/9rb
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/751=env
- 社区故事采集的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/ftg=490
- 社区生活指南中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%BF%83%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/vIt=yqE
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/901
- 非遗课堂体验的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/nbm
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/jU6
- 地方戏曲体验的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/574=rkw
- 口袋公园建设的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/pti=023
- 社区文化节活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/1Pl=yXG
- 公共空间照明的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91aqq_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/974
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91aqq_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/veu
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91aqq_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/5Ou
- 街道综合服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91aqq_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/071=mpu
- 急救知识普及的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91aqq_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/thc=168
- 老年数字阅读的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91aqq_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%80%BA%E5%B8%82?/qaf=O0A

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
