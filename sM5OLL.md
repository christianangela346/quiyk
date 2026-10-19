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

- 农村环境治理的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/1Rk
- 口袋公园建设的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/472=eje
- 儿童友好空间的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/ocs=033
- 职业技能学习中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%B4%E8%A7%A3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/SWJ=gRz
- 公共文化活动的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/831
- 社区绿色空间的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/qay
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/1K5
- 生成式工具使用的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/904=lkq
- 便民维修服务的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/wed=745
- 生活服务数字化的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/v2W=A3i
- 社区停车服务的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/637
- 社区共享书架的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/dxe
- 城乡交流活动的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/XPa
- 基层健康服务的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/866=bxq
- 城市夜间照明的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/jlp=593
- 便民服务窗口的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB320%E6%9C%9F%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/vrg=XqD
- 社区家校合作的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/731
- 全民健身活动的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/sgk
- 科学信息获取的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/h8r
- 社区庭院绿化的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/209=mhi
- 公园亲子设施的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/rhh=529
- 公共空间安全的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE%E8%A7%84%E5%BE%8B_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/cUk=TLc
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/768
- 家庭运动计划的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/npz
- 儿童户外活动的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/emF
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/466=gfl
- 学校食育活动的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/taw=211
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/j1d=qOc
- 社区快递服务的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/016
- 传统手工艺体验的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/nmm
- 公共文化活动的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/dvI
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/927=vfw
- 绿色生活实践的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/bsj=108
- 老年运动活动的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E6%89%BE%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/LvW=36g
- 城市公共座椅的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/978
- 节约用水实践的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/tdn
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/Hp2
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/213=keu
- 低碳社区实践的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/kgn=027
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%80%E6%9C%89%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/nBs=UGK
- 公共交通接驳的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/333
- 社区花园共建的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/iiu
- 城市雨天出行的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/UT3
- 无障碍信息设计的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/592=esg
- 旧物循环利用的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/vgf=969
- 城市公共厕所的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B7%A8%E5%BA%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%A7%82%E5%AF%9F?/6EY=7qx
- 非遗体验活动的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/774
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/llx
- 社区互助网络的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/uem
- 街区道路维护的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/271=euu
- 城乡交通衔接的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/iwt=797
- 智能家居应用的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E6%96%B0%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E7%83%AD%E6%A6%9C?/zAY=E5B
- 公共服务沟通的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/977
- 社会体育指导的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/pvz
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/fB7
- 社区艺术活动的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/389=mut
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/lso=070
- 城市应急科普的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/9s2=DPQ
- 就业技能培训的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/768
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/wzd
- 社区协商议事的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/5JB
- 社区停车服务的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/517=lpi
- 社区消防演练的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/yzp=641
- 城乡交流活动的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E9%9B%85%E8%99%8E%E6%88%B7%E5%A4%96?/FYp=hdu
- 学校体育活动的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/160
- 城市噪声观察的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/eub
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/0MI
- 社区科普课堂的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/927=akb
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/fdf=978
- 创业经验分享的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/XJ7=t2f
- 绿色生活实践的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/113
- 乡村产业科普的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/fyu
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/I4t
- 物业服务沟通的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/547=ipk
- 周末休闲规划的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/qoe=533
- 社区家校合作的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/cOv=Z2f
- 数字地图应用的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/346
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/gbm
- 街区更新实践的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/Uoi
- 社区协商议事的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/028=kgu
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/pfn=398
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%82%A1%E7%A5%A8?/VXQ=NWO
- 社区儿童活动的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/743
- 青少年科普实践的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/zgh
- 家庭教育交流的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/fZO
- 公共图书馆服务的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/706=nom
- 就业技能培训的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/agm=278
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%AE%97%E6%B3%95_%E8%8A%92%E6%9E%9C%E9%80%9F%E8%A7%88?/ISf=y9u
- 本地消费场景的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/492
- 城乡交流活动的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/bxk
- 社区活动策划的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/NUC
- 科学信息获取的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/669=hac
- 社区协商议事中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/gte=773
- 家庭科学教育的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/XSI=nwR
- 城市公共饮水的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/494
- 城市休闲步道的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/smq
- 本地旅行体验的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/l6I
- 数字公共文化的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/245=oth
- 公共服务数字化中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/ohq=580
- 休闲运动入门的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/IEG=mKQ
- 社区商业活力的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/299
- 食品配送体验的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/dpm
- 健康饮食教育的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/7w9
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/146=zzf
- 城市人文观察的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/ydc=225
- 租房信息服务的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E5%B1%85?/L6i=dFr
- 科技馆参观体验的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/250
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/ggx
- 街区小店体验的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/pv6
- 就业技能培训的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/569=zwl
- 租房信息服务的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/fzs=348
- 小微企业服务的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/VhJ=weh
- 信息无障碍体验的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/786
- 社区法律科普的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/jpb
- 无障碍出行的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/MBB
- 无障碍出行的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/061=snc
- 公共卫生设施的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/gyw=437
- 公共交通信息服务的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/egn=LgF
- 休闲运动入门的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%B0%E9%97%BB?/669
- 终身学习资源的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%B0%E9%97%BB?/seh
- 租房信息服务的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%B0%E9%97%BB?/2ro
- 机器学习入门的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%B0%E9%97%BB?/610=bku
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%B0%E9%97%BB?/jii=271
- 社区手工活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%96%B0%E9%97%BB?/IYT=dDD
- 软件开发学习的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/400
- 开放数据应用的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/noi
- 图书馆亲子空间的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/YrJ
- 家庭运动计划的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/184=fmo
- 健康饮食教育的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/tjv=453
- 公共空间休憩的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/Uky=uv4
- 城市水环境观察的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/953
- 家庭节能实践的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/tmw
- 就业技能培训的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/zVe
- 城市游园体验的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/962=dvw
- 公共空间照明的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/ses=725
- 数字学习资源的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/Hjn=oLF
- 家庭环保行动的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/293
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/zfq
- 城市绿道建设的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/Lo6
- 街区小店体验的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/303=ysy
- 基层服务创新的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/urm=256
- 城市微更新实践的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/Wv4=MO0
- 城市运动公园的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/501
- 数字创意课程的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/kel
- 地方文化传播的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/X0q
- 绿色校园实践中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/833=zlg
- 校园社团活动的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/dqj=458
- 绿色建筑理念的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/l9c=kKK
- 药品使用科普的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/927
- 数字公共文化的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/jyp
- 社区运动空间的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/gr4
- 街区小店体验的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/160=aef
- 节能生活方式的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/pzb=712
- 社区便民集市中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/vvJ=tKp
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/779
- 软件开发学习的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/qsj
- 城市树木认养的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/q5y
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/666=ihh
- 生成式工具使用的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/sfs=377
- 城市骑行环境的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/PLi=F2M
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/917
- 城市文明出行的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/sgs
- 社区共享书架的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/De3
- 数字生活课堂的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/369=gfw
- 城市展览体验的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/knu=556
- 本地旅行体验的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/hdB=wTV
- 基层医疗预约的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/415
- 城市博物馆活动的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/ilq
- 公共服务指南的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/HSy
- 城市公共自行车的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/578=hoi
- 休闲运动入门的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/nrb=917
- 创业经验分享中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/IOv=P4R
- 科学教育活动的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/554
- 在线教育体验的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/hfn
- 公共设施维护的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/XLB
- 城市绿色交通的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/842=els
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/gjd=066
- 节日文化体验的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/edo=HFN
- 文化场馆预约的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/111
- 社区环保活动的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/xie
- 校园社团活动的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/bXA
- 公共卫生宣传的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/566=svt
- 基层健康档案的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/rms=349
- 低碳社区实践的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E5%A4%B4%E6%9D%A1?/8g0=BKB
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/862
- 光伏知识科普的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/uwx
- 数字设备回收的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/0bZ
- 老年人出行服务的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/253=qhw
- 网络安全教育中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/acx=372
- 社区科普课堂的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/Fpi=6QK
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/781
- 数字阅读服务的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/uif
- 社区修缮行动的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/huw
- 网络信息辨识中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/849=pdm
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/opg=406
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/AUv=sKg
- 公共空间安全的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/095
- 家庭教育交流的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/vqa
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/0tY
- 无障碍出行中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/119=sny
- 家庭志愿活动的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/xhi=032
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/nJY=6fQ
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/593
- 城市绿道建设的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/ufu
- 骑行路线规划的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/zMO
- 环境教育课程的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/307=cyg
- 家庭健康科普的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/jqb=466
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/wAN=LzN
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/745
- 健康步道使用的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/rsg
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/KZU
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/102=kza
- 市民意见收集的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/was=157
- 急救知识普及的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/w0a=tpd
- 城市地名文化的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/656
- 市民热线服务的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/ufw
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/n1u
- 城市体育设施的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/330=bxb
- 社区文化节活动的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/yvq=158
- 全民健身活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E9%A1%BA%E4%B8%B0%E6%89%8B%E8%AE%B0?/tFN=QPC
- 社区菜市场服务的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/259
- 小微企业服务的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/bvq
- 校园阅读活动的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/h3J
- 家庭理财科普的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/444=rzy
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/yta=007
- 数字资源检索的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%BC%AB%E8%AF%84?/2Fb=o98
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/013
- 全民阅读推广的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/odr
- 社区儿童活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/XKQ
- 街区道路维护的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/917=lau
- 社区互助网络的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/dhs=672
- 社区志愿服务的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/VQy=nSL
- 家庭用电安全的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/070
- 网络信息辨识的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/pel
- 社区阅读服务的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/DoA
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/489=ymm
- 读书会组织的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/gno=717
- 青年职业探索的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BD%AC%E8%BD%BD?/WAV=SCX
- 青年职业探索的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/045
- 市民热线服务的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/una
- 健康步道使用的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/f6X
- 街区更新实践的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/697=svm
- 家庭健康管理的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/nho=731
- 节气饮食文化中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/jRI=AqV
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/297
- 城市文明实践的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/hsw
- 软件开发学习的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/SIE
- 公益活动组织的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/367=kmt
- 家庭照护支持中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/gux=479
- 青少年科技社团的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/RhA=bz9

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
