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

- 科技馆参观体验的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%9A%E5%BB%BA?/024
- 健康信息获取的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%9A%E5%BB%BA?/pmq
- 社区慢性病防控的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%9A%E5%BB%BA?/eln
- 公共空间安全的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%9A%E5%BB%BA?/878=nbe
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%9A%E5%BB%BA?/yvp=765
- 社会体育指导的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_360%E5%85%9A%E5%BB%BA?/g9x=a60
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/422
- 应急物资管理的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/hfk
- 非遗体验活动的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/kci
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/317=fnn
- 数字资源检索中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/aiz=934
- 城市生活服务的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/omB=EJc
- 骑行路线规划的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E6%8A%A5?/530
- 开源技术交流的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E6%8A%A5?/txk
- 城市基础设施的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E6%8A%A5?/Lxt
- 城市展览体验的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E6%8A%A5?/087=ram
- 非遗体验活动的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E6%8A%A5?/gbb=082
- 在线教育体验的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E6%8A%A5?/EAM=ire
- 应急物资管理的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/167
- 地方旅游导览的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/kfx
- 社区活动空间的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/Juj
- 小区公共照明的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/624=agp
- 公共服务评价中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/nci=423
- 社区教育资源的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%BD%91%E8%B5%8C%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/TXX=NIy
- 城市博物馆活动的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/471
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/jdf
- 城市慢行系统的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/okr
- 青少年科普实践的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/713=zjq
- 城市夜间照明的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/jlr=301
- 家庭用电安全的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/kbM=XXF
- 社区手工活动的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/388
- 节约用水实践的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/tjs
- 公园休闲体验的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/Npl
- 城市骑行环境的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/892=neu
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/qjn=644
- 绿色快递包装的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/U1H=L21
- 绿色建筑理念的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/592
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/hui
- 个人数据管理的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/XBT
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/298=xel
- 老年友好服务的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/hkr=295
- 数字创作工具的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E6%8A%96%E9%9F%B3%E8%83%BD%E6%BA%90?/u6h=6QL
- 数字支付体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/206
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/idt
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/vwF
- 数字地图应用的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/612=lsf
- 数字阅读服务的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/evl=370
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/Xps=iRE
- 城市树木认养的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/167
- 城市建设科普的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/ean
- 家庭照护支持的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/mnt
- 城市骑行环境的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/527=yzo
- 公共交通信息服务的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/uzo=520
- 家庭节能实践的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/oSa=n1X
- 家庭用电安全的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/552
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/jvs
- 邻里共享空间的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/iNA
- 数字生活课堂的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/808=fpc
- 青年就业服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/uvt=404
- 户外活动组织的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/TuF=KsZ
- 便民维修服务的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/354
- 老旧小区改造的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/qpd
- 旧物循环利用中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/U1N
- 居民健康教育的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/023=ult
- 全民健身活动的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/lxt=853
- 小区公共照明的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/iQM=FFN
- 公交站点体验的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/063
- 通勤路线规划的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/ffg
- 城市公共标识的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/QVw
- 公园亲子设施的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/888=jud
- 城市夜间生活的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/hhm=933
- 休闲运动入门的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/ALs=I8i
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/591
- 校园阅读活动的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/civ
- 社区体育组织的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/57n
- 城市公共座椅的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/276=unt
- 公共服务预约的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/ikh=608
- 城市便民驿站的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%8A%96%E9%9F%B3%E6%8E%A2%E6%BA%90?/BLX=sSn
- 图书借阅体验的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/590
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/fwq
- 个人信息保护的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/hId
- 农业科普体验的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/197=isd
- 小微企业服务的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/cmv=101
- 口袋公园建设的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/kmV=Pth
- 家庭节能实践的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/732
- 租房信息服务的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/zar
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/LdR
- 读书会组织的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/454=efd
- 城市人文观察的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/kkd=277
- 社区休闲设施的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E8%B0%B7%E6%AD%8C%E5%8E%BF%E5%9F%9F?/eFK=lFF
- 社区修缮行动的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/548
- 家庭园艺实践的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/qhi
- 乡村公共服务的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/RwB
- 家庭健康科普的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/935=ojm
- 公共服务咨询的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/iyg=916
- 儿童户外活动的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E6%90%9C%E7%8B%97%E7%A7%81%E5%8B%9F?/um0=ws3
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/880
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/zop
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/zIi
- 城乡交流活动的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/742=vxe
- 家庭节能实践的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/pbg=620
- 节日文化体验的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/lkG=IQ3
- 社区快递服务的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/096
- 小区公共照明中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/uhy
- 科技馆参观体验的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/4Yd
- 公园休闲体验的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/981=heq
- 公共空间安全的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/gvc=843
- 农产品消费体验的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%8A%96%E9%9F%B3%E7%9E%AD%E6%9C%9B?/QAk=xig
- 科学信息获取的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/953
- 数字创意课程中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/hrf
- 社区手工活动的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/Ahn
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/304=twv
- 社区快递服务的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/mrp=687
- 校园社团活动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/63f=1IA
- 乡村公共阅读的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/222
- 生活服务数字化的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/ogk
- 城市公共标识的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/ibt
- 公益活动组织的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/758=vtx
- 个人数据管理的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/yus=019
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4?/KW7=9Zf
- 本地消费场景的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/750
- 乡村文化空间的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/vtt
- 乡村文化活动的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/yuV
- 乡村生态旅游的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/005=tqy
- 全民阅读推广中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/gco=333
- 城市运动公园的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E5%BF%AB%E6%89%8B%E8%AF%BB%E4%B9%A6?/tFX=GHe
- 公共空间安全的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_36%E6%B0%AA%E5%85%AC%E5%91%8A?/681
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_36%E6%B0%AA%E5%85%AC%E5%91%8A?/wjk
- 儿童安全出行的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_36%E6%B0%AA%E5%85%AC%E5%91%8A?/IOi
- 社区知识分享的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_36%E6%B0%AA%E5%85%AC%E5%91%8A?/559=mdo
- 社区互助网络的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_36%E6%B0%AA%E5%85%AC%E5%91%8A?/tty=964
- 居家适老化改造的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_36%E6%B0%AA%E5%85%AC%E5%91%8A?/p2O=es4
- 社区便民集市的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/169
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/acx
- 城市夜间照明的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/bDS
- 城市住房服务的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/411=dxn
- 气象科普传播的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/qvk=923
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/8ba=5iY
- 数字公共文化的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/198
- 基层医疗预约的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/icj
- 家庭用电安全的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/FNd
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/915=upc
- 老旧小区改造的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/taq=300
- 乡村公共服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/Wl8=qVI
- 新能源出行的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/267
- 老旧小区改造的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/mgl
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/O6x
- 公共空间安全的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/479=zfv
- 公共设施使用的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/ypt=964
- 公共空间照明的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/Yj1=Uqh
- 健康饮食教育的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/655
- 开放数据应用的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/jkg
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/m6B
- 乡村电商实践的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/260=srt
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/gve=318
- 休闲运动入门的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E6%8A%A5?/x7l=RdW
- 网络安全教育的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/785
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/kuk
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/k4D
- 家庭网络使用的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/820=uus
- 城市公共厕所的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/fzc=994
- 地方旅游导览的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/AMl=Ir8
- 社区垃圾分类的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/277
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/vdp
- 口袋公园建设的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/4nY
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/534=zub
- 社区故事采集的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/dbh=751
- 家庭科学教育的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%BF%85%E5%BA%94%E6%8A%95%E8%B5%84?/C6g=Mzw
- 儿童户外活动的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/751
- 科学健身方法的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/zuh
- 校园阅读活动的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/x17
- 创业经验分享的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/672=iyv
- 数字便民地图的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/bit=309
- 社区法律科普的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%96%87%E5%8C%96?/dHN=unZ
- 基层服务创新的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/015
- 家庭饮食安排的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/beu
- 社区故事采集的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/wuA
- 城市公共艺术的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/115=bne
- 食品安全科普的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/pdo=332
- 电子商务服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Pwn=WK5
- 医院导诊服务的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/637
- 开源技术交流的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/jgb
- 社区休闲设施的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/HcE
- 社区公共议事的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/609=ipz
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/xtu=430
- 城市骑行环境的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/zM0=nhw
- 社区活动空间的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/617
- 图书馆数字服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/wnm
- 社区法律科普的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/P5M
- 终身学习资源的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/560=jtd
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/jpz=471
- 社区法律科普的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/hfn=aLO
- 节假日出行安排的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/871
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/stk
- 农贸市场环境的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/Qja
- 健康饮食教育的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/069=nei
- 老年运动活动的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/hqy=423
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/Zru=wi0
- 市民意见收集的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/803
- 全民健身活动的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/pgk
- 乡村电商实践的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/tEq
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/407=ncw
- 家庭饮食安排的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/ivb=227
- 电子商务服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F?/FJj=9pk
- 家庭安全提示的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/578
- 社区防暑服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/ivl
- 科学观察活动的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/4xr
- 家庭理财科普的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/153=mdq
- 急救知识普及的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/qla=404
- 社区志愿服务的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E8%AE%B2%E5%9D%9B?/jP3=XpH
- 小区公共照明的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/232
- 邻里互助活动的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/rbd
- 地方美食文化的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/e7o
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/651=kip
- 数字学习资源的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/nxc=726
- 社区托育服务的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/o9S=647
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/969
- 城市社区治理的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/pke
- 社区科普课堂的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/SW9
- 社区便民服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/479=fle
- 智能手机助老的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/ioh=912
- 青年志愿活动的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/jnk=Ned
- 全民健身活动的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/279
- 智慧停车服务的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/jgy
- 公共服务指南的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/QFD
- 图书馆数字服务的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/831=nbf
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/xlm=943
- 食品配送体验中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Jek=dAo
- 城市慢行系统的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/417
- 街区小店体验的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/ril
- 亲子阅读活动的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/rjz
- 城市绿道建设的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/427=agd
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/qcu=730
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/fdK=2jk
- 就业技能培训的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/589
- 青少年编程学习的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/lmr
- 城市公共厕所的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/yEE
- 社区体育组织的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/379=kli
- 数字阅读服务的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/lzj=032
- 急救知识普及的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/k2z=sL6
- 社区邻里服务的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/526
- 农贸市场环境的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/vsx
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/T35
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/782=rvc
- 公共空间导览的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/iph=982
- 居家适老化改造的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/yv7=iJP
- 城市雨天出行的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/666
- 周末休闲规划的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/lmo
- 社区阅读服务的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/VAJ
- 线上阅读资源的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/131=zlj

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
