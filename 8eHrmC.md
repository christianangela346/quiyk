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

- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/212
- 开放数据应用的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/ocn
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/Phv
- 社区学习活动的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/852=abr
- 气象科普传播的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/tho=513
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/FEQ=T96
- 数据分析入门的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9B%BE%E7%89%87%E5%B8%A64g%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/179
- 家庭消费规划的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9B%BE%E7%89%87%E5%B8%A64g%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/rkz
- 节能生活方式的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9B%BE%E7%89%87%E5%B8%A64g%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/1mH
- 文化场馆预约的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9B%BE%E7%89%87%E5%B8%A64g%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/708=glb
- 城市生活服务的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9B%BE%E7%89%87%E5%B8%A64g%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/spt=207
- 环境教育课程的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%9B%BE%E7%89%87%E5%B8%A64g%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/bZk=HWT
- 社区便民集市的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_4g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/388
- 口袋公园建设的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_4g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/cgs
- 邻里互助活动的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_4g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/8V4
- 城市夜间生活的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_4g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/116=iyh
- 休闲运动入门的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_4g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/noo=646
- 城市农夫市集的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_4g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%86%9C%E4%B8%9A?/soI=CFj
- 绿色出行服务的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_c5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%83%BD%E6%BA%90?/186
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_c5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%83%BD%E6%BA%90?/hoa
- 社区学习活动的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_c5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%83%BD%E6%BA%90?/PDb
- 公共服务咨询的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_c5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%83%BD%E6%BA%90?/589=dnf
- 社区协商议事的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_c5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%83%BD%E6%BA%90?/xab=537
- 数字创作工具的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_c5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%83%BD%E6%BA%90?/8n7=BtK
- 城乡交流活动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD10%E5%85%83%E8%B5%B7%E5%85%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/823
- 老年友好服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD10%E5%85%83%E8%B5%B7%E5%85%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/dli
- 社区宠物管理的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD10%E5%85%83%E8%B5%B7%E5%85%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/PkA
- 城市噪声观察的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD10%E5%85%83%E8%B5%B7%E5%85%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/084=ssv
- 居家防滑改造的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD10%E5%85%83%E8%B5%B7%E5%85%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/qdo=994
- 家庭环保习惯的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD10%E5%85%83%E8%B5%B7%E5%85%85_%E4%BA%AC%E4%B8%9C%E6%A5%BC%E5%B8%82?/qwU=LLq
- 数字素养提升的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD105%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/511
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD105%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/ecm
- 社区活动空间的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD105%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/Unl
- 城乡公共服务中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD105%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/920=fey
- 社区共享书架的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD105%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/laz=516
- 社区体育组织的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD105%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/IMH=yBv
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_757%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/585
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_757%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/ztb
- 非遗体验活动的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_757%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/Wp5
- 街道综合服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_757%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/795=lar
- 家庭环保行动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_757%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/rkg=418
- 终身学习资源的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_757%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%A3%E5%AF%86?/T5c=tB8
- 城市微更新实践的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/744
- 节约用水实践的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/tto
- 社区休闲设施的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/i2k
- 科普展览体验的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/759=ocl
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/quj=822
- 环境监测科普的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_75%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%95%B0%E8%AF%BB?/llX=UbN
- 科普展览体验的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_565%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/849
- 社区快递服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_565%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/lbl
- 城市慢跑路线的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_565%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/lDI
- 社区活动空间的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_565%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/713=syt
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_565%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/gqc=780
- 城市噪声观察的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_565%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/gQx=R7w
- 软件开发学习的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/952
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/hyc
- 城市展览体验的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/WSH
- 科技馆参观体验的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/562=dlt
- 社区快递服务的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/fqy=726
- 便民信息查询的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/maJ=A9f
- 城市博物馆服务的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A877%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/703
- 乡村生活观察的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A877%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/wqd
- 机器人科普活动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A877%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/PuZ
- 健康饮食教育的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A877%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/914=ddz
- 儿童运动体验的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A877%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/arx=449
- 小区停车协商的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A877%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/b3x=1gu
- 公共空间安全的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/083
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/fel
- 线上阅读资源的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/Lqe
- 线上阅读资源的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/974=jbn
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/enk=721
- 家庭急救准备的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%85%85%E5%80%BC10%E5%85%83%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/LG1=tG7
- 农业科普体验的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/253
- 老年人出行服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/pqu
- 社区活动策划的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/DO5
- 数字课堂应用的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/602=wij
- 公共卫生设施的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/cyw=822
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%A2%E5%A4%9A%E5%A4%9A%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/JYZ=ZjN
- 社区消防演练的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/630
- 数据分析入门的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/kna
- 健康饮食教育的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/jF7
- 节能生活方式的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/349=igf
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/xbi=498
- 社区健康讲座的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/8TJ=f7A
- 城市便民驿站的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/678
- 本地消费场景的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/rfu
- 旧物循环利用的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/ki4
- 公共服务指南的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/541=qel
- 公共健身器材的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/drb=661
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/BWA=iPW
- 社区艺术活动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/936
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/pld
- 社区活动策划的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/R4l
- 地方民俗记录的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/535=xmm
- 小区电梯维护的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/fqi=533
- 公共交通接驳的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/GCM=fKb
- 家庭防灾准备的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/000
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/gzm
- 公园无障碍服务的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/9Mo
- 生活垃圾减量的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/120=xwg
- 公共空间导览的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/vor=060
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E8%BF%B0%E8%AF%84?/5LQ=pJ2
- 小区电梯维护的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/160
- 街区更新实践的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/wpf
- 家庭节能实践的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/Ckx
- 城市可持续生活的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/797=hnt
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/tti=160
- 社区休闲设施的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/L8S=Ntn
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_139%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/552
- 健康饮水科普的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_139%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/pbo
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_139%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/NPw
- 城市绿道建设的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_139%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/639=znc
- 社区托育服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_139%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/llj=645
- 农产品消费体验的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_139%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/85F=Gd5
- 家庭科学教育的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E8%83%BD%E5%85%85%E5%80%BC%E4%BB%BB%E6%84%8F%E9%87%91%E9%A2%9D%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/187
- 数字设备回收的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E8%83%BD%E5%85%85%E5%80%BC%E4%BB%BB%E6%84%8F%E9%87%91%E9%A2%9D%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/svc
- 数字便民地图的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E8%83%BD%E5%85%85%E5%80%BC%E4%BB%BB%E6%84%8F%E9%87%91%E9%A2%9D%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/ZHt
- 便民信息查询的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E8%83%BD%E5%85%85%E5%80%BC%E4%BB%BB%E6%84%8F%E9%87%91%E9%A2%9D%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/707=bsa
- 信息无障碍体验的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E8%83%BD%E5%85%85%E5%80%BC%E4%BB%BB%E6%84%8F%E9%87%91%E9%A2%9D%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/akj=724
- 开放数据应用的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E8%83%BD%E5%85%85%E5%80%BC%E4%BB%BB%E6%84%8F%E9%87%91%E9%A2%9D%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/eXF=4q6
- 课后服务体验的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/082
- 社区法律科普的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/edl
- 农业科普体验的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/1hn
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/849=ecf
- 社区法律科普的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/bdf=583
- 城市农夫市集的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/Y0K=3ZK
- 科学运动指导的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_4G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/061
- 通勤路线规划的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_4G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/pll
- 社区便民服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_4G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/l3n
- 社区共享书架的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_4G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/258=ijo
- 社区志愿服务的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_4G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/htf=614
- 校园安全教育的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_4G%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%94%BE?/Qh3=iVg
- 青年就业服务的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/828
- 家庭饮食安排的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/qqi
- 家庭节能实践的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/3Ye
- 社区消防演练的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/357=kud
- 家庭节能设备的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/sgm=019
- 绿色办公实践的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB%E9%A2%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/ovI=vHC
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4%E4%BA%BF%E5%BD%A9%E7%A5%A8%E9%80%8141%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/931
- 家庭运动计划的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4%E4%BA%BF%E5%BD%A9%E7%A5%A8%E9%80%8141%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/ftw
- 社区家政服务的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4%E4%BA%BF%E5%BD%A9%E7%A5%A8%E9%80%8141%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/YR0
- 绿色出行服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4%E4%BA%BF%E5%BD%A9%E7%A5%A8%E9%80%8141%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/425=hjo
- 家庭安全提示的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4%E4%BA%BF%E5%BD%A9%E7%A5%A8%E9%80%8141%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/mff=146
- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_4%E4%BA%BF%E5%BD%A9%E7%A5%A8%E9%80%8141%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/qmK=GIC
- 街区道路维护的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/319
- 社区防暑服务的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/ojs
- 公益活动组织的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/12x
- 医院导诊服务的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/295=lqf
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/mjf=531
- 数字档案服务的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/Ngf=Pim
- 社区文化节活动的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/662
- 城市步行环境的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/vnc
- 城市休闲步道中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/Vo2
- 小微企业服务的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/675=tno
- 儿童友好空间的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/zrk=677
- 社区教育资源的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/XcC=Mlf
- 社区知识分享的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_106%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A81.0_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/007
- 公交站点体验的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_106%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A81.0_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/cho
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_106%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A81.0_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/Nbr
- 城市骑行环境的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_106%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A81.0_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/835=ida
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_106%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A81.0_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/zwh=266
- 智能手机助老的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_106%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A81.0_%E8%84%89%E8%84%89%E6%A6%9C%E5%8D%95?/Xmk=9tH
- 便民服务窗口的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/857
- 数字课堂应用的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/syq
- 公园亲子设施的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/zv3
- 课后服务体验的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/228=lxe
- 创业经验分享的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/omi=606
- 公共设施维护的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD106%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/n1j=vri
- 社区家政服务的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8106%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD51_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/241
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8106%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD51_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/tdl
- 城市夜间照明的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8106%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD51_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/R8G
- 社区安全巡查的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8106%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD51_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/506=eco
- 地方美食文化的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8106%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD51_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/qfs=083
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8106%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD51_%E8%8A%92%E6%9E%9C%E4%BA%B2%E5%AD%90?/PWZ=7Ad
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A975%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/489
- 城市应急广播的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A975%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/qbh
- 科学运动指导的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A975%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/YwG
- 公共服务沟通的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A975%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/355=sgh
- 社区教育资源的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A975%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/lgd=722
- 网络安全教育中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A975%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/UBs=AkX
- 社区公共卫生的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%8D%81%E5%85%83%E5%8F%AF%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/849
- 农产品消费体验的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%8D%81%E5%85%83%E5%8F%AF%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/tdo
- 社区学习活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%8D%81%E5%85%83%E5%8F%AF%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/p7a
- 社区垃圾回收中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%8D%81%E5%85%83%E5%8F%AF%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/182=gii
- 社区学习活动的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%8D%81%E5%85%83%E5%8F%AF%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/gsy=854
- 城乡公共服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%8D%81%E5%85%83%E5%8F%AF%E6%8F%90%E7%8E%B0%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%9B%AD%E8%89%BA?/Npc=i3Q
- 亲子阅读活动的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/830
- 社区儿童活动的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/rxn
- 劳动教育实践的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/Llj
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/936=stl
- 校园社团活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/lpb=451
- 农村环境治理的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/CDd=Z48
- 乡村教育资源的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/386
- 绿色出行服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/bql
- 职业技能学习的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/3lC
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/146=cnl
- 家庭急救准备的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/mul=926
- 健康饮水科普的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BDapp_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/k8Q=Q1h
- 城市博物馆服务的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/303
- 便民服务地图的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/mhs
- 社区消防演练的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/CIx
- 社区邻里服务的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/178=fnt
- 数字创意课程的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/fry=959
- 社区菜市场服务的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E5%8D%8F?/ejx=nWe
- 运动安全知识的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8500%E7%BD%91%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/676
- 人工智能科普的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8500%E7%BD%91%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/lhe
- 城市空气科普的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8500%E7%BD%91%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/8yQ
- 旧物循环利用的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8500%E7%BD%91%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/051=mhr
- 网络信息辨识中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8500%E7%BD%91%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/nld=829
- 城市应急广播的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8500%E7%BD%91%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%AF%BB%E5%9B%BE?/eEx=JkO
- 数字资源检索的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/666
- 家庭环保习惯的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/bns
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/92H
- 生活垃圾减量的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/041=yhx
- 城市体育设施的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/bjd=244
- 数字学习资源的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/8Rr=8xE
- 老年人出行服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/226
- 城市博物馆活动的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/gvb
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/2Mo
- 环境监测科普的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/206=dzj
- 志愿服务平台的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/cvf=502
- 周末休闲规划的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/IRM=ZsR
- 创业经验分享的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93app_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/518
- 公共设施维护的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93app_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/dbg
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93app_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/IQI
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93app_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/404=efb
- 数字学习资源的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93app_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/oyk=425
- 社区商业活力的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93app_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/ugx=WZg
- 老旧小区改造的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/791
- 邻里互助活动的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/osl
- 社区活动报名的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/uxN
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/213=hhc
- 开放数据应用的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/ado=018
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E7%90%86%E8%B4%A2?/vCh=Xt6
- 城市适老服务的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/362
- 城市步行友好的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/osw
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/Au1
- 电动汽车充电的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/619=sfx
- 亲子阅读活动的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/jgl=188
- 社区环保活动的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_500%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/UzB=GHt
- 校园安全教育的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%99%AE%E9%80%9A%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/613
- 数字政务体验的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%99%AE%E9%80%9A%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/msb
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%99%AE%E9%80%9A%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/sGy
- 药品使用科普的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%99%AE%E9%80%9A%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/423=oih
- 社区宠物管理的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%99%AE%E9%80%9A%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/cax=517
- 社区科普课堂的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_01%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%99%AE%E9%80%9A%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/FyM=w9j
- 全民健身活动的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_c5%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/060
- 城市休闲步道的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_c5%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/tph
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_c5%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/78q
- 邻里互助活动的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_c5%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/924=pzw

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
