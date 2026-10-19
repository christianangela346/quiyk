# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 老年人文化生活的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%AE%A2%E6%9C%8D_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/8yT
- 乡村公共阅读的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%AE%A2%E6%9C%8D_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/518=czg
- 信息无障碍体验的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%AE%A2%E6%9C%8D_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/ujr=653
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%AE%A2%E6%9C%8D_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/qlR=UbS
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/879
- 城市运动公园的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/ecc
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/POw
- 城市公共厕所中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/145=els
- 老年友好服务的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/opi=202
- 乡村公共阅读的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E6%81%92%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/ee8=kfl
- 社区学习活动的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/713
- 节日文化体验的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/dpa
- 在线学习体验的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/Hs1
- 社区邻里服务的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/734=mwv
- 环境教育课程的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/azd=232
- 基层健康档案的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/xjV=jaa
- 社区协商议事的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/493
- 家庭节能实践的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/axm
- 社区邻里服务的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/ai3
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/434=hfu
- 公共场馆服务的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/jbu=166
- 智慧停车服务的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/JRL=Z6u
- 社区教育资源的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/079
- 数字生活课堂的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/fag
- 城市骑行环境的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/wqM
- 乡村生态旅游的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/023=yby
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/qts=573
- 城市休闲步道的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-app_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/dOn=Jv3
- 读书会组织的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/137
- 城市雨天出行的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/rif
- 青年志愿活动的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/lD9
- 社区法律科普的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/528=stg
- 城市可持续生活的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/bpq=533
- 科学运动指导的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E7%99%BE%E7%A7%91?/uWK=Lw4
- 软件开发学习的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/703
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/lnl
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/4pw
- 社区养老服务的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/896=ftf
- 数字创作工具的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/bui=048
- 社区公共餐饮的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/VxN=XPF
- 学校食育活动的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/847
- 公共服务预约的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/uuz
- 青少年户外教育的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/HGp
- 公共设施使用的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/532=oke
- 城市微更新实践的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/dgh=001
- 休闲运动入门的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E6%81%92%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/HkR=xvQ
- 数据分析入门的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91welcomehf%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/485
- 机器人科普活动的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91welcomehf%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/nkz
- 生成式工具使用的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91welcomehf%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/8cS
- 社区读书角建设的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91welcomehf%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/482=dph
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91welcomehf%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/kdb=403
- 便民信息查询中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E6%81%92%E5%8F%91welcomehf%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/Zaq=Jmv
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/405
- 个人信息保护的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/gkm
- 公共空间导览的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/p4e
- 城市公共标识的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/857=fjn
- 家庭节能实践的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/sys=403
- 乡村文化活动的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%A4%A9%E7%A9%BA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%9F%E8%B4%A7?/bCY=1Jc
- 城市应急科普的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/085
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/iug
- 城市空气科普的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/YdP
- 读书会组织的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/517=tgp
- 家庭安全提示的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/usk=457
- 乡村产业科普的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E6%97%A9%E6%8A%A5%E8%B4%A2%E7%BB%8F?/aj6=Xn5
- 家庭环保习惯的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/193
- 社区学习活动的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/vpb
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/QYF
- 科学教育活动的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/286=wfi
- 公共空间导览的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/eia=267
- 城市公共标识的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E5%8F%B7%E5%A4%96?/j7E=WH1
- 开放式学习空间的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E3%80%90%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E3%80%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/254
- 公共空间安全的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E3%80%90%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E3%80%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/yyp
- 公共交通接驳的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E3%80%90%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E3%80%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/BNZ
- 健康饮食教育的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E3%80%90%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E3%80%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/980=mtv
- 新能源知识普及的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E3%80%90%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E3%80%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/rmq=907
- 公共场所导视的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E3%80%90%E7%82%B9%E5%87%BB%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E3%80%91_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/jyR=nQe
- 数字学习资源的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/524
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/rcp
- 社区快递服务的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/FSQ
- 社区设施共享的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/673=cgl
- 本地消费场景的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/epa=020
- 市民热线服务的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/0R2=kA3
- 城市人文观察的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/760
- 健康饮水科普的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/dhx
- 社区商业活力的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/Wf5
- 城市步行友好的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/756=mvu
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/unj=874
- 社区便民服务的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/SOP=A20
- 社区公共议事的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/254
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/mvd
- 公园无障碍服务的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/77b
- 社区读书角建设的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/681=vfs
- 家庭健康管理的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/phy=679
- 乡村生活观察的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%AE%A0%E7%89%A9?/inu=ues
- 数字档案服务的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/656
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/lst
- 儿童友好街区的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/Y1L
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/424=yrd
- 校园社团活动的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/uxe=408
- 城市共享单车的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/zOQ=YdR
- 城市便民驿站的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_360%E4%BA%BA%E7%89%A9?/095
- 社区协商议事的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_360%E4%BA%BA%E7%89%A9?/nde
- 城市共享单车的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_360%E4%BA%BA%E7%89%A9?/lr6
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_360%E4%BA%BA%E7%89%A9?/717=lvu
- 社区运动空间的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_360%E4%BA%BA%E7%89%A9?/ddm=948
- 社区菜市场服务的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B1%AA%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%AE%89%E5%8D%93%E7%89%88_360%E4%BA%BA%E7%89%A9?/jOz=DWB
- 个人时间管理的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/772
- 儿童安全出行的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/bdf
- 家庭用电安全的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/c7t
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/476=fsu
- 城乡交流活动的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/zow=398
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/YNS=FnY
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/098
- 绿色办公实践的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/grm
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/dr2
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/767=rpr
- 居家防滑改造中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/fgw=798
- 智慧停车服务的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BF%9D%E9%99%A9?/Gnk=mSU
- 城市应急科普的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E7%99%BB%E9%99%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/392
- 城市博物馆活动的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E7%99%BB%E9%99%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/aav
- 基层健康服务的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E7%99%BB%E9%99%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/mvH
- 城市微更新实践的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E7%99%BB%E9%99%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/269=stb
- 课后服务体验的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E7%99%BB%E9%99%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/tap=392
- 城乡公共服务的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E8%BF%90%E5%9B%BD%E9%99%85-%E7%99%BB%E9%99%86_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/dtC=5pZ
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E9%B8%BF%E7%A6%8F%E5%9B%BD%E9%99%85%E4%BA%92%E8%81%94%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E8%B4%B5%E5%85%AC%E5%8F%B8%E6%97%97%E4%B8%8B%E7%9A%84%E5%90%97__%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/606
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E9%B8%BF%E7%A6%8F%E5%9B%BD%E9%99%85%E4%BA%92%E8%81%94%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E8%B4%B5%E5%85%AC%E5%8F%B8%E6%97%97%E4%B8%8B%E7%9A%84%E5%90%97__%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/xjl
- 旧物循环利用的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E9%B8%BF%E7%A6%8F%E5%9B%BD%E9%99%85%E4%BA%92%E8%81%94%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E8%B4%B5%E5%85%AC%E5%8F%B8%E6%97%97%E4%B8%8B%E7%9A%84%E5%90%97__%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/y6J
- 小区公共照明的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E9%B8%BF%E7%A6%8F%E5%9B%BD%E9%99%85%E4%BA%92%E8%81%94%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E8%B4%B5%E5%85%AC%E5%8F%B8%E6%97%97%E4%B8%8B%E7%9A%84%E5%90%97__%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/404=vvp
- 文明养宠科普的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E9%B8%BF%E7%A6%8F%E5%9B%BD%E9%99%85%E4%BA%92%E8%81%94%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E8%B4%B5%E5%85%AC%E5%8F%B8%E6%97%97%E4%B8%8B%E7%9A%84%E5%90%97__%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/buf=407
- 城市空气科普的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E9%B8%BF%E7%A6%8F%E5%9B%BD%E9%99%85%E4%BA%92%E8%81%94%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E8%B4%B5%E5%85%AC%E5%8F%B8%E6%97%97%E4%B8%8B%E7%9A%84%E5%90%97__%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/xgu=tE4
- 公共场馆服务的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/142
- 青年志愿活动的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/shf
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/PWg
- 城市展览体验的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/252=jvp
- 社区老年食堂的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/uuu=068
- 城市人文观察的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%8D%8E%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%88%86%E6%83%85?/lIW=rsc
- 家庭运动计划的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/214
- 城市基础设施的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/qaz
- 便民服务窗口的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/q89
- 街区小店体验的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/511=mio
- 社区教育资源的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/gss=681
- 老年学习活动的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E5%8A%A8%E6%BC%AB?/jBt=pSR
- 网络安全教育的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/989
- 生活垃圾回收的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/yoa
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/jrz
- 家庭运动计划的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/173=hxg
- 街道综合服务的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/rax=853
- 绿色校园实践的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0-%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/ZG3=hWm
- 户外活动组织的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/300
- 地方戏曲体验的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/wlb
- 节气饮食文化的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/2Qp
- 机器学习入门的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/908=ygl
- 科学运动指导的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/hha=960
- 城市博物馆服务的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/opR=wys
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/332
- 个人信息保护的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ail
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/2V9
- 医院导诊服务中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/949=wkm
- 智慧城市体验的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/nxd=026
- 城市生活记录的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%9B%88%E5%AF%8C%E8%B4%A2%E7%BB%8F?/QJW=BFd
- 图书馆数字服务的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/108
- 公共设施维护的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/zhz
- 公共服务沟通的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/KX9
- 校园安全教育的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/253=lnx
- 在线学习体验中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/lal=134
- 图书借阅体验的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/g7m=GSu
- 节能家电使用的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%84%89%E8%84%89%E8%88%86%E6%83%85?/976
- 公园休闲体验的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%84%89%E8%84%89%E8%88%86%E6%83%85?/yic
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%84%89%E8%84%89%E8%88%86%E6%83%85?/e2J
- 家庭消费规划的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%84%89%E8%84%89%E8%88%86%E6%83%85?/177=rpv
- 医院导诊服务的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%84%89%E8%84%89%E8%88%86%E6%83%85?/ekf=814
- 公共文化活动的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E8%84%89%E8%84%89%E8%88%86%E6%83%85?/0eG=q3j
- 社区手工活动的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/064
- 数字资源检索的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/kgo
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/5Ne
- 本地消费场景的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/221=ecy
- 校园节能行动的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/lvm=811
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%8D%8E%E5%BD%A9%E7%BD%91app_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/6eW=UOd
- 社区应急准备的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%B0%91%E7%94%9F?/873
- 环境教育课程的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%B0%91%E7%94%9F?/erx
- 街区绿化养护的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%B0%91%E7%94%9F?/7Wc
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%B0%91%E7%94%9F?/604=rha
- 社区花园共建的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%B0%91%E7%94%9F?/bqi=277
- 公交站点体验的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%B0%91%E7%94%9F?/teN=y8J
- 全民阅读推广的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/562
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/fts
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/jSG
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/111=dbr
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/zey=006
- 乡村文化空间的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%AC%AC-%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%852025_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/F4c=Xmy
- 城市博物馆服务的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/807
- 儿童户外活动中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/gkv
- 乡村文化空间的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/8h0
- 公共服务评价的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/208=cig
- 城市公共空间的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/bgs=102
- 城市基础设施的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/CBN=wWK
- 线上阅读资源的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/574
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/xrn
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/oks
- 小区停车协商的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/828=lgq
- 便民服务窗口的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/fvm=123
- 本地消费场景的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%BC%98%E4%B9%90%E5%BD%A9%E5%A4%A7%E4%BC%97%E5%A8%B1%E4%B9%90_%E5%87%A4%E5%87%B0%E6%97%B6%E8%AF%84?/vzc=I7G
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/589
- 老旧小区改造的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/nhv
- 线上阅读资源的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/UuQ
- 在线学习体验的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/525=wjb
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/sat=841
- 社区防暑服务的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/nPU=lph
- 乡村生态旅游的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/257
- 社区信息发布的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/hvk
- 科普展览体验的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/7Zt
- 数字阅读服务的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/706=ctf
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/aqp=038
- 农贸市场环境的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8D%8E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/JDc=bxx
- 老年友好服务的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/447
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/esy
- 青年职业探索中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/7Ck
- 乡村公共服务的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/980=hqx
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/aeu=355
- 街区小店体验的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%AD%E4%BF%A1%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/MtK=588
- 家庭养老规划的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/958
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/oce
- 城乡交流活动的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/VUU
- 数字设备回收的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/834=pzh
- 乡村公共文化的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/rrz=618
- 绿色办公实践的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_58%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90app_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/B89=pdi
- 老年学习活动的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/731
- 绿色快递包装的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/llv
- 亲子科普活动的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/zey
- 生活垃圾减量的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/815=rgu
- 物业服务沟通的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/fis=754
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9VIP%E5%A8%B1%E4%B9%90_%E4%B8%87%E7%9B%88%E8%B4%A2%E7%BB%8F?/XhF=Ba1
- 绿色出行服务的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/260
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/kfu
- 租房信息服务的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/61R
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/952=ubk
- 青年职业探索的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/wot=844
- 儿童安全出行的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/Z1x=ImW
- 食品安全科普的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/450
- 公共空间导览的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/kps
- 青年就业服务的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/mEq
- 环境监测科普的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/993=fys
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/vno=715
- 周末休闲规划的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_3%E5%8F%B7%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%8D%93%E7%89%88_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/CIx=RSE
- 志愿者培训交流的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E5%BE%97%E7%89%A9%E8%B5%84%E8%AE%AF?/351
- 城市运动公园的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E5%BE%97%E7%89%A9%E8%B5%84%E8%AE%AF?/nrn
- 城市骑行环境的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E5%BE%97%E7%89%A9%E8%B5%84%E8%AE%AF?/jDp
- 公共服务评价的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E5%BE%97%E7%89%A9%E8%B5%84%E8%AE%AF?/682=jzg
- 口袋公园建设的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E5%BE%97%E7%89%A9%E8%B5%84%E8%AE%AF?/pxa=804
- 健康信息获取的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%8D%8E%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-ios%E7%89%88_%E5%BE%97%E7%89%A9%E8%B5%84%E8%AE%AF?/dil=X5X

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
