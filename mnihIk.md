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

- 城市博物馆活动的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/eda=277
- 城市休闲步道的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/HmK=S8L
- 社区健康讲座的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/100
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/ysh
- 药品使用科普的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/9ie
- 传统节日科普的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/912=rfw
- 乡村公共服务的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/uig=558
- 社区交通安全的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%8E%A2%E6%BA%90?/zy6=Jr0
- 社区快递服务的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/491
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/ayv
- 社区运动空间的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/nKm
- 社区教育资源的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/589=yso
- 基层健康服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/itm=479
- 公共空间休憩的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E5%A4%9A%E5%B0%91_%E5%BE%97%E7%89%A9%E4%BD%93%E8%82%B2?/QH1=fX4
- 邻里共享空间的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/712
- 节约用水实践的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/ddp
- 城市博物馆活动的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/3rk
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/248=baq
- 本地消费场景的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/ywc=696
- 绿色建筑理念的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%A6%9C%E5%8D%95?/poz=6AE
- 志愿者培训交流的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/156
- 数据分析入门的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/dwa
- 家庭照护支持的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/BWx
- 社区绿色空间的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/756=vfp
- 科学健身方法的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/qwm=568
- 社区绿色空间的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/j6m=3q9
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/007
- 软件开发学习的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/kyb
- 乡村生态观察的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/IZz
- 邻里共享空间的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/179=qdd
- 家庭节能设备的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/iyb=647
- 科学运动指导的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%A0%E5%86%9B_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/8Ti=cLr
- 社区安全巡查的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/275
- 家庭用电安全的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/ekz
- 药品使用科普的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/fH1
- 社区商业活力的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/443=lfs
- 数字政务体验的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/kzd=588
- 乡村生态观察的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%A4%B4%E5%A4%A7%E4%B8%8D%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/pIT=T2e
- 绿色生活实践的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/400
- 休闲运动入门的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/oni
- 跨代沟通活动的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/hHy
- 志愿服务平台的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/667=sug
- 日常摄影记录的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/lpt=874
- 社区共享书架中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%90%86%E8%B4%A2?/4pd=tUj
- 城市公共标识的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/179
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/sfy
- 城市噪声观察的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/oNg
- 城市空气科普的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/251=hdr
- 校园安全教育的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/tmt=942
- 公共设施维护中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/R6u=qhl
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/976
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/wnm
- 公共服务评价的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/kjA
- 社区志愿服务的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/973=mwi
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/yxa=898
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E8%B4%B4%E5%90%A7_%E5%8D%B3%E5%88%BB%E7%9B%B4%E6%92%AD?/qAf=iS4
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/688
- 生成式工具使用的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/tje
- 农贸市场环境的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/FIE
- 节假日出行安排的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/492=hps
- 通勤路线规划的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/sik=480
- 环境教育课程中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E7%A8%B3%E5%AE%9A%E8%83%9C%E7%8E%87_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%B4%B7?/Lwp=DOL
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/818
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/uli
- 周末休闲规划的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/Xcj
- 社区体育组织的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/951=dkt
- 邻里共享空间的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/isv=342
- 社区文化节活动的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%9A%84%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E5%9B%BD%E9%99%85?/wzZ=lmU
- 人工智能科普的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/291
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/lfk
- 社区知识分享的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/NDE
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/614=xif
- 生成式工具使用的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/rhj=617
- 本地消费场景的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/XGT=wTf
- 地方美食文化的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/594
- 城市生活记录的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/cok
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/pIY
- 租房信息服务的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/011=aua
- 城市应急广播的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/tfy=232
- 城市展览体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E4%B8%8E%E5%A4%A7%E5%B0%8F%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E4%BF%A1%E6%89%98?/oHe=ipc
- 公共交通信息服务的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/814
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/hhg
- 电子商务服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/IFm
- 家庭网络使用的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/856=uue
- 创业经验分享的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/lfk=810
- 城市适老服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%AF%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/nb7=z4N
- 科学信息获取的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/215
- 农业科普体验的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/okf
- 公共空间照明的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/EHH
- 绿色办公实践的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/867=ghr
- 科学运动指导的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/odg=299
- 数字政务体验的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/GDL=8Se
- 社区公共议事的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/838
- 家庭饮食安排的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/tir
- 社区故事采集的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/hbf
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/516=ufm
- 家庭教育交流的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/ydk=060
- 消防知识宣传的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%94%B5%E8%84%91%E7%89%88_%E6%8A%96%E9%9F%B3%E5%A8%B1%E4%B9%90?/IM0=pAK
- 绿色出行服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/849
- 日常摄影记录的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/mfz
- 乡村文化空间的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/zvd
- 健康步道使用的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/981=zcz
- 农村环境治理的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/jnd=974
- 数字素养提升的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E7%8E%A9%E6%B3%95_%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/SZf=z5a
- 智慧停车服务的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/284
- 社区学习活动的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/zlj
- 社区公共卫生的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/FrX
- 数字公共文化的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/777=gui
- 社区家校合作的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/zqs=930
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E6%80%A7_%E6%8A%96%E9%9F%B3%E5%A4%B4%E6%9D%A1?/nT3=5pF
- 社区活动策划的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/181
- 文化讲座服务中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/ooe
- 社区家政服务的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/nxH
- 户外活动组织的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/778=sak
- 城市微更新实践的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/qtg=913
- 公共设施维护的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/Hch=UsD
- 青年志愿活动的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/393
- 城市博物馆活动的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/vot
- 公共设施使用的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/v3V
- 骑行路线规划的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/216=flw
- 青少年心理健康的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/ric=991
- 邻里互助活动的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E9%A2%9C%E8%89%B2%E7%9A%84_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/14P=sMP
- 社区设施共享的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/484
- 城市适老服务的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/xvi
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/n9t
- 绿色快递包装的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/348=wei
- 城市雨天出行的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/gim=995
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/KMj=pPB
- 远程协作工具的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/991
- 无障碍出行的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/oka
- 城市雨天出行的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/1hu
- 传统节日科普的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/565=erg
- 绿色出行服务的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/kec=746
- 城市慢跑路线的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%96%87%E5%8C%96?/DFX=fGL
- 社区老年食堂的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/119
- 城乡公共服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/gjs
- 绿色快递包装的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/Fj2
- 城市公共空间的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/983=yau
- 乡村生态旅游的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/eul=815
- 软件开发学习的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/Ds1=Sqj
- 街区更新实践的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/724
- 公共空间安全的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/yfd
- 公益活动组织的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/rl9
- 乡村阅读空间的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/226=rpk
- 城市共享单车的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/tfh=663
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8app%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/ytv=1Wt
- 社区共享书架的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/454
- 日常摄影记录的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/jzt
- 运动安全知识的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/tEl
- 数据分析入门的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/702=lij
- 城市公共艺术的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/rfo=089
- 社区手工活动中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%85%8D%E8%B4%B9%E7%89%88_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/tHl=zbY
- 社区宣传栏更新的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/061
- 社区艺术活动的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/tfq
- 社区菜市场服务的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/IpZ
- 城市农夫市集的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/133=ivi
- 城市可持续生活的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/lxl=216
- 家庭节能实践的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8A%A9%E6%89%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E7%89%B9%E7%A8%BF?/2VU=L60
- 开放数据应用的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%97%B6%E6%8A%A5?/717
- 社区家校合作的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%97%B6%E6%8A%A5?/dcw
- 校园阅读活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%97%B6%E6%8A%A5?/hWV
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%97%B6%E6%8A%A5?/272=rmq
- 本地旅行体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%97%B6%E6%8A%A5?/kpv=529
- 公共卫生设施的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E6%97%B6%E6%8A%A5?/9ka=v25
- 文明养宠科普的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/155
- 医院导诊服务的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/ydm
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/pSm
- 公共健身器材的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/846=jtk
- 口袋公园建设的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/vfd=238
- 绿色办公实践中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BF%A1%E8%AA%89_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/Y8c=XmU
- 文明养宠科普的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/791
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/edu
- 数字资源检索的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/J7V
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/101=uyx
- 乡村公共服务的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/mjo=370
- 公园无障碍服务的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E4%B9%B0%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/aWv=XTW
- 城市慢跑路线的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/841
- 老年友好服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/xck
- 在线学习体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/DEf
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/124=kvp
- 社区托育服务的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/acj=248
- 城市公共艺术的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%80%81%E5%B8%88_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/bNk=um1
- 环境教育课程的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/390
- 周末休闲规划的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/bjb
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/loW
- 科普展览体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/993=rgo
- 健康信息获取的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/uph=690
- 城市展览体验的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/WXd=F1y
- 老年智能设备的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/193
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/uzm
- 社区花园共建的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/7EX
- 家庭网络使用的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/854=fwv
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/gub=774
- 社区教育资源的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/OJ4=5zt
- 公园休闲体验的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/451
- 公共空间安全的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/eyu
- 街区更新实践的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/jGP
- 城市社区治理的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/581=ray
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/jcc=703
- 社区宠物管理的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%A7%81%E5%8B%9F?/X3z=d3S
- 市民热线服务的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/569
- 儿童友好街区的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/gnc
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/XNX
- 乡村生态观察的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/804=pfq
- 城市夜间生活的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/bvx=372
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%8B%B1%E4%BC%A6%E8%B4%A2%E7%BB%8F?/OWs=UBi
- 公共文化活动的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/489
- 社区养老服务的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/too
- 城市文明出行的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/LZ6
- 社区科普课堂中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/598=igi
- 健康步道使用中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/jnh=132
- 校园安全教育的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/ii2=r0d
- 城市步行友好的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/241
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/vzg
- 节假日出行安排的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/t0n
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/493=ffr
- 农村环境治理的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/srp=070
- 公交站点体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%80%81%E5%B8%88%E5%AE%9E%E5%8A%9B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E9%94%90%E8%AF%84?/MHJ=euE
- 运动安全知识的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/973
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/dcn
- 机器学习入门的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/ZFi
- 本地消费场景的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/678=fsv
- 城市公共空间的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/dpe=294
- 健康步道使用的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3-%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/hrZ=nzN
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/050
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/rbw
- 图书馆数字服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/rOO
- 学校食育活动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/620=ysh
- 城市公共饮水的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/wzj=639
- 居民健康教育的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/Cbq=A90
- 公共空间安全的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/349
- 街区小店体验的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/srk
- 校园安全教育的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/YeV
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/428=siv
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/gwt=922
- 公共场所导视的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%A8%B3%E5%AE%9A%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/pUk=FA9
- 公园休闲体验的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/502
- 城市公共艺术的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/wad
- 节气饮食文化的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/hP5
- 家庭消费规划的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/976=ckn
- 公交站点体验的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/ncb=214
- 基层健康档案中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E5%BF%AB3_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/WlO=Q0r
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/953
- 城市骑行环境的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/jjw
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/WhD
- 个人时间管理的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/420=bfz
- 公园亲子设施中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/yhh=580
- 居家适老化改造的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9A%84%E6%8A%80%E5%B7%A7%E5%92%8C%E8%A7%84%E5%BE%8B%E8%AF%A6%E8%A7%A3_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/PY6=2xB
- 社区老年食堂的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E6%AD%A3%E7%A1%AE%E6%96%B9%E6%B3%95_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/749
- 家庭环保习惯的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E6%AD%A3%E7%A1%AE%E6%96%B9%E6%B3%95_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/ync

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
