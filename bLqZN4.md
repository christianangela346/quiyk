# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 社区快递服务的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/vor=196
- 家庭健康管理的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/pG9=ytO
- 文化场馆预约的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/853
- 休闲运动入门的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/vqp
- 城市微更新实践的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/smM
- 社区便利生活的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/462=zyv
- 社区防暑服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/dao=245
- 公共卫生设施的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/E8Y=QPD
- 在线教育体验的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/432
- 老年学习活动的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/nvi
- 线上阅读资源中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/j1f
- 科学健身方法的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/005=tol
- 非遗体验活动的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/xoa=360
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/JF0=Aq3
- 城市骑行环境的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/851
- 社区设施共享的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/ixz
- 校园安全教育的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/1VI
- 数字政务体验的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/451=zfg
- 光伏知识科普的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/yaa=330
- 城市休闲步道的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/DMv=Sba
- 家庭照护支持的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/612
- 在线教育体验的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/qyl
- 新能源知识普及的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/E4W
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/130=nhu
- 数字设备回收的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/sgv=793
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/4NR=BzI
- 农村环境治理的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/442
- 城市公共饮水的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/nhe
- 公共设施使用中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/noS
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/805=trj
- 青少年科技社团的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/ote=608
- 机器学习入门的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E5%8D%9A%E5%AE%A2?/tfQ=pus
- 急救知识普及的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/900
- 老年友好服务的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/sku
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/ZgR
- 消防知识宣传的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/699=kos
- 街道综合服务的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/xly=387
- 公共设施维护的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E8%82%A1%E7%A5%A8?/XUW=KDs
- 儿童友好空间的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/431
- 社区养老服务的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/hvo
- 垃圾分类指导的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/JW9
- 绿色建筑理念的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/014=rnu
- 急救知识普及的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/bjo=612
- 家庭运动计划的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/xuu=p6s
- 数据分析入门的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/134
- 数字素养提升的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/fes
- 消防知识宣传的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/qji
- 开放式学习空间的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/127=okk
- 小区电梯维护的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/gib=448
- 电动汽车充电的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/bgX=L2B
- 社区修缮行动的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/115
- 社区读书角建设的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/gyn
- 健康饮水科普的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/BZ9
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/419=jya
- 社区儿童活动的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/ohh=677
- 街头绿植养护的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E6%89%98?/gm5=0Jk
- 开源技术交流的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/660
- 城市应急广播的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/mvc
- 数字政务体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/vAs
- 社区停车服务的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/109=fpa
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/xsi=701
- 街区道路维护的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/obC=mY1
- 终身学习资源的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/150
- 非遗课堂体验的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/tnp
- 公共场馆服务的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/5I0
- 社区快递服务的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/489=rkz
- 基层服务创新的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/lxg=516
- 城市绿道建设的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/4uM=bCl
- 灵活就业交流从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/041
- 社区公共卫生的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/hxa
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/4RX
- 全民健身活动的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/767=wax
- 在线学习体验的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/zmk=482
- 非遗体验活动的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/t6S=k8E
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/286
- 城市水环境观察的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/hbf
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/h7j
- 绿色消费选择的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/304=zbw
- 公共空间导览的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/egy=010
- 城市骑行环境的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_36%E6%B0%AA%E8%B5%84%E8%AE%AF?/zo9=CPV
- 城市空气科普的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/586
- 社区活动空间的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/klq
- 小微企业服务的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/eCd
- 社区应急准备的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/379=ggq
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/xzy=267
- 社区便民服务的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E7%83%AD%E6%A6%9C?/llB=S4Y
- 老年人出行服务的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/376
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/xny
- 乡村休闲旅游的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/iGb
- 基层服务创新的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/473=sqe
- 亲子阅读活动的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/xed=904
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E8%85%BE%E8%AE%AF%E8%A7%A3%E5%AF%86?/6Ii=vVp
- 乡村公共阅读的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/498
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/fcr
- 小微企业服务的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/tH5
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/126=zct
- 社区活动空间的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/oov=135
- 食品配送体验的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/crA=qTl
- 市民热线服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/307
- 电子商务服务的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/ckc
- 公园无障碍服务的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/Deb
- 食品安全科普的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/474=msp
- 个人数据管理的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/avf=731
- 社区心理支持的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E5%AE%89%E9%98%B2?/Oaf=fBu
- 老年人出行服务的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/572
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/qei
- 老年运动活动的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/sKj
- 旧物循环利用的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/461=civ
- 环境教育课程的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/qdr=205
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/SEV=XF7
- 老年人出行服务的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/257
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/yrh
- 城市生活服务的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/HFp
- 社区宠物管理的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/224=opx
- 信息无障碍体验的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/eoi=748
- 城市建设科普中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%B1%86%E7%93%A3%E5%88%9B%E6%8A%95?/MHI=3of
- 个人时间管理的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/442
- 环境监测科普的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/xln
- 社区菜市场服务的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/6OA
- 公交站点体验的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/173=xzd
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/avq=798
- 科学教育活动的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E7%82%B9?/LNL=Uqt
- 家庭照护支持的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/726
- 老年人日常照护的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/jzk
- 居民健康教育的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/81C
- 城市可持续生活中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/760=ijo
- 科学观察活动的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/qtp=967
- 电动汽车充电的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E4%BA%AC%E4%B8%9C%E4%B9%A6%E7%94%BB?/iqO=pTb
- 跨代沟通活动的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/492
- 城市应急广播的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/vss
- 社区消防演练的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/x8J
- 地方民俗记录的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/527=oca
- 本地旅行体验的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/xbx=560
- 基层医疗预约的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/oRT=kJE
- 城市噪声观察的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/242
- 城市应急科普的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/flo
- 城市体育设施的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/Zle
- 社会体育指导的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/006=gpn
- 社区艺术活动的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/eed=644
- 社区活动报名的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/hfh=tY2
- 公共空间休憩的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/137
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/hqq
- 公交站点体验的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/ONO
- 网络信息辨识的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/491=apl
- 家庭安全提示的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/dby=005
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/jCo=VBW
- 家庭节能实践的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/982
- 文化场馆预约的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/iyi
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/uga
- 居家防滑改造的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/963=yvm
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/lpu=770
- 社区学习活动的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/CNG=Q4W
- 光伏知识科普的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/256
- 户外活动组织的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/vhs
- 社区活动空间的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/bvX
- 数据分析入门的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/949=zlv
- 软件开发学习的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/cep=977
- 街区道路维护的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E6%8A%96%E9%9F%B3%E5%81%A5%E8%BA%AB?/bZ4=c4Y
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/387
- 城市博物馆活动的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/asi
- 老年人日常照护的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/YZm
- 生活垃圾减量的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/348=yst
- 社区心理支持的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/miu=666
- 农村环境治理的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/myl=mGJ
- 公交无障碍服务的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/203
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/amf
- 街区更新实践的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/u1B
- 食品安全科普的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/011=ebq
- 社区科普课堂的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/idi=846
- 乡村公共文化的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/2Uc=EPj
- 家庭饮食安排的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/961
- 社区交通安全的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/vjj
- 家庭收纳实践的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/qbK
- 数字资源检索中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/274=xqo
- 数字阅读服务的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/tot=496
- 农贸市场环境的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/PnE=Tq4
- 机器人科普活动的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/114
- 邻里互助活动的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/fvz
- 街区小店体验的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/SMx
- 社区养老服务的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/369=vjw
- 绿色生活实践的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/syx=007
- 生活垃圾减量的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A?/GD4=hVW
- 消防知识宣传的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/515
- 智能家居应用的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/fsc
- 亲子科普活动的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/JT5
- 学校体育活动的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/237=roc
- 个人数据管理的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/fdm=753
- 数字设备回收的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E8%84%89%E8%84%89%E6%B3%95%E6%B2%BB?/HNe=4Yh
- 社区宠物管理的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7?/927
- 社区活动报名的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7?/tkx
- 课后服务体验的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7?/sR2
- 儿童户外活动的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7?/771=nuf
- 节能生活方式的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7?/jbb=687
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7?/8IG=N1r
- 青少年编程学习的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/519
- 社区设施共享的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/wcg
- 公园亲子设施中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/ZSL
- 绿色出行服务的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/144=fzc
- 学校体育活动的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/ano=195
- 节约用水实践的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%99%A8%E6%8A%A5?/8Lc=ZyI
- 节能家电使用的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E4%B8%93%E6%A0%8F?/143
- 城市夜间生活的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E4%B8%93%E6%A0%8F?/rua
- 城市农夫市集的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E4%B8%93%E6%A0%8F?/EaQ
- 公共服务数字化的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E4%B8%93%E6%A0%8F?/757=zjf
- 个人时间管理的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E4%B8%93%E6%A0%8F?/pqb=246
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E8%B0%B7%E6%AD%8C%E4%B8%93%E6%A0%8F?/xNQ=FBk
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/803
- 社区绿色空间的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/ojv
- 社区共享书架的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/MaL
- 灵活就业交流的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/843=rtw
- 城市游园体验的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/sre=807
- 城市公共厕所的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/Ajn=4d1
- 社区交通安全的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/777
- 城市公共厕所的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/owk
- 儿童阅读角的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/IWB
- 城市建设科普的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/555=lnb
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/skh=977
- 公共空间导览中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%B4%A2%E7%BB%8F%E5%BF%AB%E6%8A%A5?/g54=Z2p
- 垃圾分类指导的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/694
- 家庭理财科普的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/ijz
- 人工智能科普的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/vVV
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/225=ebr
- 社区花园共建的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/lpc=667
- 节约用水实践的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/SwN=OYF
- 社区读书角建设的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/438
- 无障碍出行的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/qno
- 地方旅游导览的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/NM7
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/253=xcz
- 城市公共饮水的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/tuu=192
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E7%A4%BE%E5%8C%BA?/Gp2=6QZ
- 数字支付体验的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/703
- 全民健身活动的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/ant
- 校园节能行动的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/9jg
- 公共设施使用的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/266=tya
- 线上阅读资源的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/fsw=610
- 家庭运动计划的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B4%A2%E7%BB%8F%E7%BE%8E%E8%82%A1?/XCi=oNo
- 社区儿童活动的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/816
- 绿色办公实践的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/yfx
- 便民信息查询中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/tdV
- 居家适老化改造的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/423=ior
- 儿童户外活动的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/akg=232
- 公共卫生设施的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/KX2=5WR
- 家庭食品保存的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/093
- 社区家校合作中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/ojp
- 乡村生活观察的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/qhP
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/281=dfs
- 城市共享单车的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/clv=730
- 节能家电使用的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/zuo=4tx
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/238
- 数字艺术创作的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/hev

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
