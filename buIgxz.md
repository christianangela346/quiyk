# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 社区宠物管理的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%A4%A7%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/jng=989
- 绿色出行服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%A4%A7%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%AF%BB%E4%B9%A6?/Z4V=9KB
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/651
- 医院导诊服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/yjl
- 全民阅读推广的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/No2
- 青少年户外教育的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/093=vfz
- 城市绿道建设的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/aat=569
- 街头绿植养护的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E9%9F%B3%E4%B9%90?/eDY=EKp
- 数字生活课堂的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/892
- 社区快递服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/lre
- 城市公共饮水的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/2E1
- 科技馆参观体验的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/245=dky
- 亲子科普活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/tys=064
- 青少年心理健康的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%B6%88%E8%B4%B9?/Lun=94L
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/640
- 智慧停车服务的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/zra
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/7nU
- 社区文化传播的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/469=phf
- 校园节能行动的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/buy=699
- 城市公共饮水的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/ttT=ep8
- 公共场所导视的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/704
- 图书馆活动策划的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/mht
- 社区知识分享的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/MTs
- 城市文明出行的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/638=ila
- 老年人文化生活的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/jvs=353
- 机器学习入门的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/lsW=IUg
- 节能生活方式的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/000
- 青年志愿活动的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/tdp
- 社区健康讲座的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/sXd
- 社区活动策划的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/992=zqk
- 城市住房服务的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/ieb=896
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/xq4=IIg
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/514
- 数字档案服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/gzf
- 公共服务沟通的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/NjE
- 家庭急救准备的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/152=qhw
- 农贸市场环境的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/qoc=898
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/cC7=HEg
- 数字阅读服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/645
- 科普展览体验的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/yim
- 社区快递服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/Z45
- 基层健康档案的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/070=nir
- 数字设备回收的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/lox=898
- 城市噪声观察的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/KNl=bOU
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/656
- 本地旅行体验的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/lzk
- 乡村公共阅读的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/wZM
- 应急物资管理的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/773=nqm
- 公交站点体验的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/owk=930
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/qXM=ETe
- 老年友好服务的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/511
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/ubk
- 本地旅行体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/xmb
- 家庭健康科普的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/514=vto
- 灵活就业交流的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/lmw=263
- 社区托育服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/jZQ=2KE
- 节日文化体验的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/430
- 职业技能学习的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/zai
- 公共设施使用的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/Dlo
- 开放式学习空间的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/922=rqg
- 亲子阅读活动的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/usf=861
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%89%B9%E7%A8%BF?/GnH=gpM
- 邻里共享空间的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/514
- 社区故事采集的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/was
- 环境监测科普的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/EwB
- 科普展览体验的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/484=ahm
- 城市生活记录的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/crg=180
- 城市共享单车的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/4Te=Uqn
- 数字地图应用的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/978
- 校园阅读活动的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/ejr
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/nIg
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/929=xdp
- 社区手工活动的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/bxx=617
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/cff=hjt
- 数字支付体验的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/466
- 城市树木认养的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/iyv
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/mtS
- 便民信息查询的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/618=abg
- 城市绿色交通的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/nua=580
- 本地消费场景中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/gtF=bB5
- 城市骑行环境的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/417
- 城市应急广播的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/jox
- 健康信息获取的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/w67
- 终身学习资源的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/125=mfi
- 家庭食品保存的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/ouk=010
- 创业经验分享的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/50y=CEr
- 社区学习活动的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/810
- 公共交通信息服务的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/zxg
- 休闲运动入门的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/sHv
- 城市建设科普中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/846=oqn
- 公共服务预约的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/yxp=418
- 全民健身活动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/Nlf=mhi
- 老年人日常照护的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/134
- 社区公共餐饮的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/itn
- 开放式学习空间的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/VzZ
- 新能源出行的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/642=igv
- 节能生活方式的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/kpd=561
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8D%8F?/UKW=jpi
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/287
- 小区公共照明的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/sma
- 低碳社区实践的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/e8Q
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/796=dny
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/fdw=853
- 公共卫生宣传的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%91%84%E5%BD%B1?/Sqh=KFa
- 城市生活记录的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/256
- 农业科普体验的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/nkg
- 绿色快递包装的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/iJ6
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/137=ixw
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/eok=889
- 科学信息获取的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E7%95%8C%E9%9D%A2%E8%AF%BB%E5%9B%BE?/bwo=owF
- 个人信息保护的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/615
- 小微企业服务的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/geg
- 城市建设科普的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/eIl
- 农贸市场环境的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/160=cwb
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/zoh=953
- 社区读书角建设的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/zZZ=iCR
- 社区快递服务的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/114
- 读书会组织的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/hzj
- 租房信息服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/qo3
- 老年友好服务的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/335=wnt
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/nvf=082
- 社区公共议事的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/pHR=oUe
- 校园节能行动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/324
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/iol
- 城市展览体验的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/Qxs
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/628=hhk
- 科技馆参观体验的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/fks=072
- 无障碍出行的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%83%AD%E6%A6%9C?/tbD=GEM
- 急救知识普及中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/489
- 便民信息查询的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/drh
- 公交站点体验的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/NSx
- 公共场所导视中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/094=cey
- 老旧小区改造的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/ved=879
- 光伏知识科普的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%9C%AD%E8%AE%B0?/O5L=opn
- 社区法律科普的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E5%8D%9A%E5%AE%A2?/331
- 农村环境治理的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E5%8D%9A%E5%AE%A2?/dmf
- 科学信息获取的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E5%8D%9A%E5%AE%A2?/CBx
- 社区托育服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E5%8D%9A%E5%AE%A2?/050=xvf
- 便民维修服务的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E5%8D%9A%E5%AE%A2?/iil=945
- 绿色生活实践的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E5%8D%9A%E5%AE%A2?/9PX=sne
- 数字素养提升的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%A7%A3%E5%AF%86?/842
- 公共空间照明的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%A7%A3%E5%AF%86?/kvh
- 青年职业探索的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%A7%A3%E5%AF%86?/kRC
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%A7%A3%E5%AF%86?/278=wzv
- 绿色消费选择的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%A7%A3%E5%AF%86?/ybs=233
- 老年人文化生活的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%8A%92%E6%9E%9C%E8%A7%A3%E5%AF%86?/QgJ=Qgz
- 公共设施使用的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/411
- 街区小店体验的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/vhu
- 老年友好服务的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/LdH
- 科学信息获取的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/486=okw
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/cpo=313
- 家庭志愿活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/VJP=6DA
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/446
- 家庭饮食安排的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/zee
- 社区便民服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/HxN
- 家庭安全提示的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/338=zjs
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/vgi=776
- 家庭用电安全的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/UgO=VHC
- 城市生活服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/369
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/lyr
- 城市公共自行车的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/Xj4
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/010=rbp
- 全民健身活动的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/rpn=385
- 公共卫生设施的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/ddH=gRa
- 城市便民驿站的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/922
- 城市展览体验的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/rdq
- 城乡交流活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/ts9
- 学校体育活动的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/730=ikl
- 网络信息辨识的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/icb=201
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/fuy=5AJ
- 课后服务体验的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_360%E9%97%AE%E7%AD%94?/127
- 城市便民驿站中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_360%E9%97%AE%E7%AD%94?/kqs
- 城市慢跑路线的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_360%E9%97%AE%E7%AD%94?/maN
- 城市共享单车的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_360%E9%97%AE%E7%AD%94?/369=qxk
- 社区学习活动的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_360%E9%97%AE%E7%AD%94?/ybi=531
- 公益活动组织的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_360%E9%97%AE%E7%AD%94?/M4M=ysu
- 数字生活课堂的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/979
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/mwf
- 生活垃圾减量的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/14d
- 节气饮食文化的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/323=dqb
- 城乡公共服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/sir=611
- 基层服务创新的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%A6%81%E9%97%BB?/4XU=WpN
- 社区庭院绿化的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/446
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/kml
- 绿色办公实践的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/1vd
- 乡村公共文化的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/083=mqm
- 公共空间休憩的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/ynv=256
- 社区活动策划的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/nBb=9G4
- 公共空间导览的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%9B%B4%E6%92%AD?/283
- 公共服务预约的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%9B%B4%E6%92%AD?/ijp
- 课后服务体验的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%9B%B4%E6%92%AD?/wPy
- 社区心理支持的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%9B%B4%E6%92%AD?/805=qjq
- 城乡交通衔接的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%9B%B4%E6%92%AD?/aah=433
- 便民服务地图的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%9B%B4%E6%92%AD?/sMV=JoP
- 地方文化传播的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/917
- 远程协作工具的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hfk
- 物业服务沟通的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gpy
- 城市夜间生活的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/812=gmy
- 生活服务数字化的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/fmg=008
- 应急物资管理的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/QQH=hQf
- 本地消费场景的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/954
- 城市可持续生活的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/aru
- 社区故事采集的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/NN6
- 地方旅游导览的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/723=srm
- 老年人出行服务的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/agu=026
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/mgs=O3A
- 全民健身活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/160
- 社区庭院绿化的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/hwu
- 乡村文化空间的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/La2
- 低碳社区实践中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/596=clv
- 个人时间管理的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/hij=826
- 创业经验分享的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/oWG=GYr
- 城市水环境观察的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/581
- 城市水环境观察的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/cep
- 新能源知识普及中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/Rm7
- 文化场馆预约的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/114=jyu
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/ktk=745
- 社区绿色空间的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/rx6=5NT
- 乡村公共服务的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/735
- 城市运动公园的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/lmc
- 街头绿植养护的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/gwa
- 公园休闲体验的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/791=uhe
- 社区艺术活动的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/hlh=528
- 软件开发学习的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/2by=fFp
- 乡村公共文化的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/014
- 乡村文化空间的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/frs
- 社区公共议事的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/rsX
- 邻里互助活动的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/214=ebm
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/geh=040
- 城市公共空间的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/gmG=1cm
- 绿色生活实践的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/337
- 数字公共文化中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/bsv
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/n17
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/259=ica
- 电动汽车充电的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/ulw=377
- 家庭理财科普的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/AG0=zqc
- 社区公共卫生的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/225
- 公共卫生宣传的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/ekf
- 地方文化传播的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/0oZ
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/299=umm
- 社区活动策划的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/wvk=429
- 社区便民集市的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E4%BA%AC%E4%B8%9C%E6%97%B6%E8%AF%84?/ZsT=18D
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8D%9A%E5%AE%A2?/233
- 文化场馆预约中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8D%9A%E5%AE%A2?/kgc
- 城乡公共服务的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8D%9A%E5%AE%A2?/rRU
- 线上阅读资源的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8D%9A%E5%AE%A2?/615=yow
- 乡村生活观察的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8D%9A%E5%AE%A2?/sru=003
- 节日文化体验的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E8%B4%A2%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%8D%9A%E5%AE%A2?/x2n=cAF
- 地方戏曲体验的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/873
- 低碳社区实践的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%87%E6%91%98?/xxd

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
