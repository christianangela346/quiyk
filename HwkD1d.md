# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:16**

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

- 公共设施维护的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/ghf=497
- 线上办事服务的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E5%B1%85?/ZE5=CWh
- 公共服务评价的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/826
- 社区法律科普的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/jac
- 本地历史资料的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/WhF
- 小区公共照明的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/005=cbh
- 社区文化传播的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/vmy=876
- 亲子科普活动的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/Zik=Cqs
- 消防知识宣传的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/970
- 地方旅游导览的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/jbl
- 家庭急救准备的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/LUz
- 休闲运动入门的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/711=oqw
- 公共场所导视的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/zbw=672
- 数字公共文化中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/GWJ=sjo
- 社区活动空间的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/151
- 城市微更新实践的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/tok
- 绿色生活实践的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/Y9E
- 公共场馆服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/787=mir
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/eew=810
- 开放式学习空间的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BAapp_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/nlN=Gkf
- 灵活就业交流的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/252
- 社区菜市场服务的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/jea
- 城乡交流活动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/Iih
- 数字政务体验的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/854=abc
- 开放数据应用的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/oyz=724
- 社区便民集市的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E5%AE%89%E8%A3%85_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/FX0=aTX
- 公园亲子设施的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/978
- 家庭理财科普的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/iep
- 邻里互助活动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/IZh
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/823=xdd
- 城乡交通衔接的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/bjl=443
- 城市休闲步道的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9C%E6%9C%80%E6%96%B0_36%E6%B0%AA%E5%85%AC%E5%91%8A?/NGi=o0S
- 城市住房服务的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/702
- 志愿服务平台的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/rfx
- 城市夜间照明的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/skw
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/840=qok
- 科学运动指导的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/rmy=913
- 农产品品牌传播的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E6%88%AA_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/YKb=gUJ
- 个人时间管理的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/166
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/eeq
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/w9Y
- 社区文化传播的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/479=eyy
- 公共服务评价的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/fpu=336
- 新能源出行的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E8%AF%BB%E5%9B%BE?/lpY=UZ2
- 社区教育资源的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/752
- 城市建设科普的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/okn
- 儿童友好空间的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/w5V
- 城市共享单车的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/398=qbg
- 数字设备回收的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/ewf=247
- 邻里共享空间的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/94f=Cy9
- 个人数据管理的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/348
- 便民服务窗口的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/hdp
- 青少年科技社团的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/FSG
- 居家适老化改造的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/375=iba
- 开放数据应用的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/dhz=381
- 在线教育体验的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/9aA=NTt
- 社区快递服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/537
- 公共服务评价的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/dso
- 社区环保活动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/L8Y
- 社区托育服务的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/894=xiv
- 图书借阅体验的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/trt=853
- 便民服务地图的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/zXZ=tTP
- 周末休闲规划的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/843
- 消防知识宣传的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/lzi
- 公共场所导视的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/NTQ
- 社区活动空间的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/459=lhl
- 就业技能培训的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/fvl=921
- 全民健身活动的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1?/ULW=SCE
- 公交无障碍服务的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/937
- 公共空间安全的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/nkn
- 绿色出行服务的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/zPn
- 城市水环境观察的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/906=ier
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/iey=581
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9C%89%E6%B2%A1%E6%9C%89%E4%BA%BA%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/ban=Pmq
- 社区活动空间的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/459
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/ljk
- 家庭食品保存的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/DUf
- 社区文化节活动的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/136=sgc
- 线上阅读资源的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/bju=998
- 数字课堂应用的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BA%86%E4%B8%80%E7%99%BE%E4%B8%87_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/5GA=pNM
- 社区家校合作的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/234
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/jfj
- 社区运动空间的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/MyR
- 基层服务创新的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/037=kxl
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/ytn=827
- 城市地名文化的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89%E4%B8%80%E5%88%86%E9%92%9F_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/b0S=uGL
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/070
- 基层医疗预约的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/ibj
- 社区活动报名的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/MFW
- 安全出行教育的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/169=tkn
- 城乡交流活动的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/fdj=491
- 公共服务评价的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%BD%A9%E7%A5%A8?/9hN=Z1e
- 乡村公共服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/921
- 居民健康教育的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/iau
- 城乡交流活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/im8
- 创业经验分享的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/652=etz
- 公共健身器材的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/jqm=186
- 公共设施使用的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%BE%E6%9E%9C%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/UPX=6i6
- 家庭安全提示的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/671
- 数字学习资源的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/tet
- 公共服务预约的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/2DQ
- 新能源知识普及的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/032=rtl
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/iau=428
- 家庭急救准备的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/iG9=U83
- 家庭环保行动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/807
- 公共设施使用的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/yph
- 家庭运动计划的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/7IR
- 乡村文化活动的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/604=dxg
- 租房信息服务的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/zvm=244
- 数据分析入门的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_360%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B5%84%E8%AE%AF?/zpl=xO4
- 基层健康服务的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/655
- 街区更新实践的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/pdx
- 城乡交流活动的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/T3n
- 科普展览体验的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/958=ree
- 儿童友好空间的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/lmq=601
- 社区故事采集的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/DuM=t6f
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/625
- 数字课堂应用的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/yji
- 街区绿化养护的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/drw
- 智慧城市体验的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/039=esi
- 公共空间照明的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/hiq=627
- 城市公共厕所的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/XAf=cRq
- 市民意见收集的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/231
- 青少年科普实践的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/qgn
- 社区托育服务的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/ad9
- 公园亲子设施的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/223=nzw
- 社区环保活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/lpw=341
- 数字支付体验的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/Qb5=6wL
- 校园安全教育的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/542
- 环境教育课程的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/npj
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/OCN
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/612=heo
- 数字课堂应用的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/ift=000
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E8%8B%B9%E6%9E%9C_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/3KV=UIZ
- 数字支付体验的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/906
- 街道综合服务的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/lom
- 文化讲座服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/Dya
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/857=hje
- 乡村教育资源中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/rrk=458
- 基层医疗预约的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%BC%80%E5%85%83app%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/i3V=XhA
- 公共设施使用的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/240
- 网络信息辨识的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/ttq
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/q8i
- 科技馆参观体验的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/998=ioq
- 本地旅行体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/fii=449
- 数字便民地图的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E9%A1%B5%E7%BD%91%E5%9D%80_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/dKH=in2
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/926
- 职业技能学习的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/szg
- 社区环保活动的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/ilH
- 社区法律科普的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/740=tgw
- 科学信息获取的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/tck=688
- 街区更新实践的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E6%8A%A5?/GOd=bhz
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/863
- 城市体育设施的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/opt
- 城市雨天出行的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/7Mk
- 城市公共标识的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/322=qus
- 校园安全教育的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/gij=732
- 城市住房服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%AE%89%E5%8D%93_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/RdR=IOA
- 图书馆活动策划的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/761
- 街区绿化养护的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/vaw
- 骑行路线规划的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/xAF
- 健康步道使用的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/666=dxm
- 健康步道使用的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/pma=322
- 数字学习资源的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/qMi=su7
- 便民维修服务的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/885
- 社区知识分享的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/vvq
- 社区菜市场服务的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/myT
- 数字档案服务的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/047=uwh
- 家庭阅读计划的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/fll=743
- 气象科普传播的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/nOZ=iWM
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/224
- 乡村生活观察的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/whc
- 公共文化活动的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/OUd
- 数字创作工具的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/944=jaf
- 乡村电商实践的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/yke=433
- 老年智能设备的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%883D_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/KPA=wD5
- 数字便民地图的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/122
- 家庭照护支持的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/pbq
- 社区艺术活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/qJ0
- 青少年编程学习的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/974=lgx
- 街区绿化养护的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/uyb=121
- 公共设施使用的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/yWg=mcQ
- 气象科普传播的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/449
- 急救知识普及的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/dxp
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/W8M
- 校园社团活动的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/289=qbi
- 城市建设科普的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/flk=649
- 个人时间管理的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/FPX=sQg
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/514
- 消防知识宣传的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/lok
- 青年就业服务的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/I6M
- 开源技术交流的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/717=ufk
- 地方旅游导览的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/ttd=185
- 生活服务数字化的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/1vl=7xc
- 社区活动策划的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/532
- 乡村电商实践的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/mjb
- 老年学习活动的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/FX5
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/698=rto
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/xrv=706
- 智慧城市体验的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Eapp%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/uUM=F3L
- 科学健身方法的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/832
- 青少年心理健康的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/gml
- 社区活动空间的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/MW1
- 远程协作工具的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/421=sgm
- 科学教育活动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/ezt=848
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/Rt1=UoC
- 城市基础设施的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/324
- 生活服务数字化中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/zwn
- 农业科普体验的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/Fz8
- 城市公共饮水的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/430=eas
- 开放式学习空间的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/jui=533
- 城市绿色交通的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88APP_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/RG3=Koo
- 社区志愿服务的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/002
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/gae
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/Fgz
- 青少年户外教育的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/503=trd
- 图书馆活动策划的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/sme=408
- 家庭科学教育的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%95%85%E6%B8%B8?/GYo=bYL
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/545
- 社区修缮行动的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/fco
- 家庭园艺实践的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/LR2
- 家庭阅读计划的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/404=xjn
- 家庭网络使用中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/lsm=006
- 生成式工具使用中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Eapp%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/9Zh=kCn
- 非遗体验活动的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/671
- 城市公共自行车的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/ker
- 骑行路线规划的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/761
- 跨代沟通活动的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/658=cos
- 数字阅读服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/qds=805
- 地方美食文化的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eapp%E8%83%BD%E6%8C%A3%E5%88%B0%E9%92%B1%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%94%BE?/brL=PjZ
- 传统节日科普的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/754
- 电动汽车充电的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/kad
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/nPX
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/922=qfg
- 家庭环保行动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/mef=233
- 家庭饮食安排的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/zYa=Bu3
- 街区绿化养护的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/904
- 家庭运动计划的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/ruc
- 数字艺术创作中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/0J9
- 全民健身活动的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/953=pzp
- 儿童运动体验的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/cea=346
- 城市绿道建设的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%A4%B4%E6%9D%A1?/idi=8jr
- 乡村产业科普的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/521
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/kqe
- 数字支付体验中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/947
- 社区生活指南中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/785=rva
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/jfr=219
- 绿色消费选择的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evlll%E8%BD%AF%E4%BB%B6%E6%AD%A3%E8%A7%84%E5%90%97_%E5%93%94%E5%93%A9%E6%AF%8D%E5%A9%B4?/gcj=o7c
- 节假日出行安排的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Eapp%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/332
- 节约用水实践的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9Eapp%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84_%E8%99%8E%E6%89%91%E5%85%AC%E5%91%8A?/sak

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
