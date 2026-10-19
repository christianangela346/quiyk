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

- 亲子科普活动的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/zUs
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/660=mhi
- 社区修缮行动的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/rxq=113
- 绿色生活实践的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/h45=Ebm
- 绿色消费选择的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/366
- 社区设施共享的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/jke
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/pfH
- 急救知识普及的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/042=mml
- 城市慢行系统的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/hob=353
- 社区消防演练的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/Gb0=JuP
- 公共场所导视的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/626
- 街区道路维护的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/con
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/Ne1
- 农村环境治理的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/927=ker
- 社区老年食堂的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/aly=371
- 科普展览体验的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%A4%B4%E6%9D%A1%E7%BB%BC%E8%89%BA?/2Cp=Vbc
- 城乡公共服务的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/579
- 城市适老服务的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/swq
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/dN4
- 健康步道使用的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/188=olb
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/yhk=908
- 社区便民集市的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/OtK=5d3
- 在线学习体验的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/350
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/ehs
- 城市可持续生活的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/4RL
- 传统节日科普的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/585=dme
- 社区快递服务的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/mgd=343
- 公交无障碍服务的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/8Uf=wGK
- 城市雨天出行的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/281
- 城市公共艺术的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/nho
- 数字艺术创作的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/rrk
- 青少年科普实践的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/686=yhr
- 城市公共标识的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/jzi=008
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E5%AE%8F%E8%A7%82?/6DL=jvZ
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/661
- 公园休闲体验的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/fca
- 药品使用科普的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/Uix
- 城市公共厕所的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/795=mgt
- 社区活动空间的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/vyh=135
- 乡村阅读空间的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E6%8A%A5?/m1A=Pod
- 志愿者培训交流的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/064
- 社区文化节活动的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/jpb
- 城市生活记录的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/bzv
- 老年友好服务的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/472=sck
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/wqu=492
- 健康信息获取的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_36%E6%B0%AA%E6%B6%88%E8%B4%B9?/cRE=NSE
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/313
- 乡村文化活动的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/iom
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/an6
- 儿童户外活动的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/291=ebh
- 城市绿色交通的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/bwz=563
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/Wek=6hZ
- 家庭饮食安排的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/002
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/cqa
- 社区老年食堂的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/odE
- 健康信息获取的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/847=jyi
- 城市博物馆服务的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/nfz=369
- 线上办事服务的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E8%AE%BA%E5%9D%9B?/oKm=C0j
- 城市农夫市集的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/165
- 城市基础设施的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/dut
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/UW5
- 社区环保活动的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/441=erq
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/wug=161
- 乡村生态旅游的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BF%A1%E8%AE%BF?/lRa=khs
- 小区公共照明的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/539
- 学校食育活动的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/ieq
- 公共设施维护的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/pqn
- 公共文化活动的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/884=sij
- 城市文明实践的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/wof=277
- 课后服务体验中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/5s2=Pie
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/529
- 青年就业服务的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/ytk
- 城市人文观察的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/u2o
- 开放数据应用中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/170=kzl
- 日常摄影记录的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/yof=449
- 儿童友好空间的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/zcb=WPu
- 数字阅读服务的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/234
- 公交站点体验的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/jag
- 家庭健康科普的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/q6v
- 小微企业服务的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/044=ydy
- 药品使用科普的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/pyd=055
- 读书会组织的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/w6C=yld
- 社区文化传播的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/692
- 学校食育活动的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/yvr
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/GWA
- 电动汽车充电的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/800=elv
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/fps=341
- 城乡公共服务的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E5%9B%BD%E9%99%85?/GEb=8bx
- 居家防滑改造的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/066
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/oln
- 公园亲子设施的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/taM
- 环境教育课程的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/754=dag
- 文化场馆预约的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/aet=903
- 社区托育服务的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BF%AB%E8%AE%AF?/Nsc=SzG
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/903
- 城市共享单车的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/znj
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/NKE
- 家庭运动计划的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/865=bfm
- 社区活动报名的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/xne=598
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/fER=xzp
- 社区消防演练的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/008
- 城乡交流活动的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/rqm
- 创业经验分享的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/UCr
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/221=ehd
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/hlq=431
- 社区养老服务的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/WOi=dW9
- 城市展览体验的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/224
- 便民服务窗口的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/upo
- 社区法律科普的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/Kwr
- 公园无障碍服务的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/305=msq
- 社区文化节活动的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/saa=178
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/kQF=Iau
- 青年就业服务的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/816
- 城市公共空间的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/adc
- 城市文化路线的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/GYg
- 数字公共文化的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/184=beq
- 街区道路维护的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/xir=221
- 城市夜间生活的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%A8%8E%E5%8A%A1?/St0=d4l
- 社区教育资源的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/264
- 城市树木认养的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/epb
- 城市文明实践的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/BIv
- 邻里互助活动的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/894=dhz
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/cls=582
- 社区儿童活动的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/Gun=ZZU
- 食品配送体验的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/789
- 数字创意课程的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/vyy
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/tB8
- 社区文化传播的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/757=xkp
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/gxk=271
- 光伏知识科普的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%93%94%E5%93%A9%E5%85%AC%E5%91%8A?/ats=MVB
- 健康饮水科普从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/673
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/duh
- 食品安全科普的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/nAK
- 绿色校园实践的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/186=ope
- 城乡公共服务的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/obd=941
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/iNE=JUQ
- 社区防暑服务的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/864
- 电动汽车充电的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/dhh
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/gvd
- 老年智能设备的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/472=wec
- 地方文化传播的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/sut=858
- 青年志愿活动的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%88%86%E6%96%99?/yxO=fhS
- 城市生活服务的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/895
- 家庭急救准备的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/dfd
- 科学健身方法的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/S4c
- 公共服务数字化的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/663=vpm
- 街区绿化养护的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/xxx=776
- 公共场所导视的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E5%B1%85?/2Be=gs4
- 公共空间休憩的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/301
- 家庭养老规划的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/yde
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/c4I
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/857=kvi
- 青少年编程学习的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/lfr=787
- 科学教育活动的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E6%85%A7%E7%9C%BC?/JAp=4rQ
- 城市空气科普的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/786
- 公共空间休憩的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/eou
- 居家适老化改造的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/0f0
- 数字艺术创作的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/398=iod
- 数据分析入门的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/ujg=743
- 社区垃圾回收的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/YId=xha
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93?/193
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93?/xgg
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93?/DSk
- 儿童阅读角中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93?/075=bmj
- 社区便民集市的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93?/ycq=261
- 社区便利生活的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93?/r3A=wnd
- 乡村产业科普的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/961
- 社会体育指导的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/akh
- 学校食育活动的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/wlB
- 线上阅读资源的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/457=dui
- 城市绿色交通的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/caq=315
- 文化场馆预约的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E5%B9%B6%E8%B4%AD?/xPu=oTL
- 全民健身活动的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/695
- 街区更新实践的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/hjn
- 青少年心理健康的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/n4D
- 乡村生态旅游的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/814=hle
- 乡村文化空间的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/spm=647
- 老年友好服务的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/uID=5DI
- 城市绿道建设的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E5%AE%B6%E5%B1%85?/115
- 社区体育组织的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E5%AE%B6%E5%B1%85?/mvi
- 城市应急科普的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E5%AE%B6%E5%B1%85?/Vat
- 地方文化传播的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E5%AE%B6%E5%B1%85?/778=khb
- 社区阅读服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E5%AE%B6%E5%B1%85?/luh=375
- 社区公共卫生的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_360%E5%AE%B6%E5%B1%85?/MWV=CYm
- 租房信息服务的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/016
- 城市适老服务的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/wmc
- 城市住房服务的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/c4f
- 食品安全科普的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/737=bhq
- 社区活动策划的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/rtz=555
- 传统节日科普的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/IuD=Pmp
- 城市应急广播的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%BE%97%E7%89%A9?/932
- 家庭用电安全的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%BE%97%E7%89%A9?/kfj
- 城市共享单车的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%BE%97%E7%89%A9?/sj5
- 周末休闲规划的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%BE%97%E7%89%A9?/315=uuj
- 社区公共议事中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%BE%97%E7%89%A9?/dfu=988
- 数字艺术创作的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%BE%97%E7%89%A9?/gul=BUj
- 青少年户外教育的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/610
- 在线学习体验的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/xbz
- 公共图书馆服务的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/TND
- 城市人文观察的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/297=euj
- 节能家电使用的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/npq=301
- 志愿者培训交流的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/gU6=CjS
- 居民健康教育的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/498
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/kdo
- 社区协商议事的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/UwQ
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/403=fla
- 城市绿色交通的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/ood=854
- 数字生活课堂的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/QTJ=wQR
- 农村环境治理的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/807
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/mtl
- 小微企业服务的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/E2o
- 城市共享单车的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/613=eno
- 周末休闲规划的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/lmi=617
- 城市公共饮水的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E8%81%8C%E5%9C%BA?/EJY=kqP
- 家庭节能实践的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/495
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/qxp
- 公共卫生设施的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/VNP
- 老年学习活动的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/431=hkr
- 城市体育设施的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/yzq=282
- 亲子科普活动的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/GSr=pGM
- 城市夜间生活的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/522
- 青年就业服务中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/lai
- 社区公共卫生的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/Toy
- 在线教育体验的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/897=lvp
- 街头绿植养护的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/ksh=879
- 数字公共文化的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/BNK=XoW
- 数字档案服务的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/296
- 医院导诊服务的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/phh
- 图书馆数字服务的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/zUw
- 社区家校合作的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/737=nuz
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/xtz=794
- 校园安全教育的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/GPM=Tcx
- 乡村文化空间的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/939
- 基层健康档案的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/keb
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/VxE
- 儿童阅读角的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/885=hbd
- 基层服务创新的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/jbh=549
- 社区志愿服务的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/oOo=iEu
- 课后服务体验的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/231
- 科普展览体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/vsc
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/CTb
- 乡村文化空间的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/442=vxz
- 地方美食文化的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/jey=354
- 本地旅行体验的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/53S=mpO
- 城市住房服务的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/676
- 市民热线服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/gxo
- 社区文化节活动的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/TpY
- 智能手机助老的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/128=dfe
- 数字阅读服务的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/evl=911
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E8%99%8E%E6%89%91%E5%88%B8%E5%95%86?/3IZ=kEU

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
