# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 节约用水实践的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vsp=571
- 公共场馆服务的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dxL=ZHf
- 社区便利生活的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/731
- 社区防暑服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/jpk
- 社区老年食堂的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/LhK
- 个人时间管理的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/102=jfn
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/orz=521
- 公共卫生宣传的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/qQT=RU9
- 地方美食文化的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/903
- 信息无障碍体验的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/kor
- 社区手工活动的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/1Tn
- 社区设施共享的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/789=bjb
- 文明养宠科普的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/pwe=420
- 电动汽车充电中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/CMy=V51
- 垃圾分类指导的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/288
- 城市公共标识的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/qxi
- 家庭节能设备的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/X7H
- 社区便民集市的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/588=bdh
- 家庭消费规划的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/gaf=613
- 社区便利生活的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%8E%BF%E5%9F%9F?/3Jk=sfA
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/485
- 开放式学习空间的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/yqr
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/4gr
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/221=ntd
- 小区电梯维护的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/pyk=623
- 家庭网络使用的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%A5%BF%E4%BA%9A%E8%B4%A2%E7%BB%8F?/1DI=gDo
- 城市适老服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/051
- 街区小店体验的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/sll
- 乡村生活观察的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/QU4
- 城市步行友好的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/358=nge
- 社区便民集市的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/yro=492
- 公共空间照明的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E6%94%BF%E5%8D%8F?/l8J=4mc
- 开放数据应用的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/017
- 社区养老服务的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/pza
- 社区学习活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/sZx
- 创业经验分享的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/745=oyd
- 生活垃圾减量的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/vir=629
- 社区知识分享的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/F4U=JMA
- 图书借阅体验的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/628
- 社区共享书架的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/thw
- 居家防滑改造的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/KG5
- 环境监测科普的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/365=kil
- 社区故事采集的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/bhv=167
- 健康步道使用的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/YIu=B0c
- 家庭运动计划的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/432
- 运动安全知识的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/ouq
- 社区环保活动的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/cfp
- 社区学习活动的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/826=bnv
- 地方戏曲体验的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/yls=179
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E4%BA%AC%E4%B8%9C%E8%BF%B0%E8%AF%84?/OkG=pLP
- 儿童友好街区的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/806
- 数字档案服务的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/lak
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/f4I
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/473=svj
- 远程协作工具的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/pzx=177
- 公共图书馆服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/eBm=KC6
- 本地消费场景的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_360%E6%92%AD%E6%8A%A5?/576
- 数字公共文化的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_360%E6%92%AD%E6%8A%A5?/wbw
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_360%E6%92%AD%E6%8A%A5?/8ja
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_360%E6%92%AD%E6%8A%A5?/698=gpq
- 骑行路线规划的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_360%E6%92%AD%E6%8A%A5?/zwc=242
- 家庭健康科普的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_360%E6%92%AD%E6%8A%A5?/U5h=b0T
- 数字设备回收的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/796
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/znc
- 青年志愿活动的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/ufg
- 社区修缮行动的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/319=asg
- 垃圾分类指导的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/lru=693
- 跨代沟通活动的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/rXs=Kir
- 青少年户外教育的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/698
- 城市骑行环境的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/snf
- 青少年科普实践的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/Fv7
- 社区快递服务的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/948=rql
- 物业服务沟通的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/pey=335
- 城市水环境观察的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%AE%9E%E5%BD%95?/Rr5=9uq
- 居民健康教育的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/211
- 城市基础设施的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/xvx
- 开放数据应用的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/uRq
- 城市夜间照明的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/387=peu
- 公共卫生设施的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/itf=493
- 农贸市场环境中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%99%9A%E6%8A%A5?/B8Y=Yav
- 城市公共自行车的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/395
- 在线学习体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/zcd
- 传统手工艺体验的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/ImQ
- 家庭网络使用的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/420=srh
- 公共交通接驳的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/rht=097
- 社区体育组织的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E4%B8%93%E9%A2%98?/2Ya=msb
- 家庭科学教育的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/072
- 科学观察活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/ouh
- 城市社区治理的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/Btp
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/681=xaw
- 老年友好服务的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/zpw=859
- 社区设施共享的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E5%8E%BF%E5%9F%9F?/H4G=77Z
- 乡村产业科普的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/307
- 电动汽车充电的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/tli
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/vk0
- 生活服务数字化的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/784=qal
- 城市文明出行的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/iek=582
- 公交站点体验的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/YJw=IsV
- 亲子阅读活动的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/902
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/usi
- 城市骑行环境的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/EpY
- 网络安全教育的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/545=yla
- 公共空间照明的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/ccx=320
- 低碳社区实践的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/Oey=gqz
- 校园社团活动的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/099
- 地方美食文化的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/vkf
- 青少年科技社团的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/P7A
- 药品使用科普的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/199=pqh
- 数字支付体验的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/jyq=224
- 社区绿色空间的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/Bzp=imv
- 城市运动公园的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_360%E7%9E%AD%E6%9C%9B?/832
- 社区菜市场服务的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_360%E7%9E%AD%E6%9C%9B?/zgc
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_360%E7%9E%AD%E6%9C%9B?/D7X
- 儿童友好空间的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_360%E7%9E%AD%E6%9C%9B?/181=jzm
- 环境教育课程的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_360%E7%9E%AD%E6%9C%9B?/nnl=142
- 光伏知识科普的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_360%E7%9E%AD%E6%9C%9B?/sqy=9Yo
- 乡村教育资源的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/435
- 邻里互助活动的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/pyi
- 科普展览体验的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/CEm
- 家庭安全提示的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/972=lkl
- 社区手工活动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/jak=043
- 城市便民驿站的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/u3E=xLi
- 社区宠物管理的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E8%88%86%E6%83%85?/218
- 社区应急准备的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E8%88%86%E6%83%85?/zvi
- 科学健身方法的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E8%88%86%E6%83%85?/UGT
- 数字资源检索的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E8%88%86%E6%83%85?/677=kvg
- 家庭用电安全的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E8%88%86%E6%83%85?/mvp=162
- 儿童友好空间的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E8%88%86%E6%83%85?/3Qt=PhN
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/922
- 健康信息获取的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/hkx
- 人工智能科普的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/XWl
- 社区故事采集的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/703=zwf
- 公共场所导视的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/fld=976
- 家庭环保行动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/P8Z=Jyo
- 城市夜间照明的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/338
- 社区健康讲座的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/rph
- 旧物循环利用的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/8ur
- 数字素养提升的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/802=miv
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/eij=907
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/k77=5Zx
- 老年数字阅读的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/713
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/bna
- 社区体育组织的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/zi3
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/586=epz
- 城市应急科普的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/dbd=565
- 公共服务指南的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/Nqi=tYx
- 社区学习活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/262
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/hxc
- 家庭收纳实践的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/2RF
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/326=ojv
- 城市夜间生活的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/nld=752
- 社区协商议事的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/iNv=XK0
- 开放数据应用的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/190
- 公共交通接驳的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/yxo
- 旧物循环利用的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/DdJ
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/941=ady
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/wpj=211
- 老年智能设备的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%9B%B4%E6%92%AD?/VkQ=nGy
- 数字生活课堂的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/477
- 社区公共卫生的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/urh
- 数字便民地图的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/yHe
- 居家防滑改造的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/003=dey
- 公共服务指南的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/jar=851
- 社会体育指导的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/E4T=DbS
- 城市夜间生活的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/997
- 社区快递服务的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/pgu
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/HSC
- 健康饮水科普的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/958=qrm
- 数字艺术创作的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/iaf=602
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E6%94%B6%E8%97%8F?/amj=fl5
- 社区公共议事的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/002
- 街道综合服务的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/xgz
- 居家适老化改造的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/TfH
- 健康饮食教育的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/407=lba
- 文化场馆预约的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/srg=844
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/t4M=7D9
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/169
- 绿色生活实践的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/fdl
- 智慧城市体验的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/clT
- 公共卫生设施的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/406=jop
- 数字公共文化的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/sdo=079
- 家庭照护支持中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/sbp=IHS
- 城市噪声观察的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/556
- 信息无障碍体验的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/fxi
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/LVI
- 家庭理财科普的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/340=irt
- 科学运动指导的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/kxx=827
- 城市应急科普的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/53i=Hcm
- 家庭志愿活动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/339
- 城市公共艺术的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/wam
- 基层健康档案的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/CKO
- 本地旅行体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/824=icf
- 公共文化活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/wbm=647
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/xiT=eME
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/466
- 乡村生态观察的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/yii
- 社区便民服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/DlN
- 数字创意课程的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/640=slo
- 志愿服务平台的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/kli=287
- 生成式工具使用的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%94%BF%E5%8A%A1?/U2E=aVW
- 城市体育设施的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/212
- 家庭阅读计划的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/ghd
- 新能源出行的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/R9g
- 社区读书角建设的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/774=cjk
- 气象科普传播的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/mtv=998
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/j3y=9IR
- 社区应急准备的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/121
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/jgi
- 健康步道使用的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/8wB
- 城市公共标识中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/418=egr
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/gyl=420
- 乡村公共阅读的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/auR=ln5
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/809
- 物业服务沟通的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/vch
- 农村环境治理的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/net
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/667=zpo
- 街区更新实践的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/zby=773
- 公共服务数字化的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/2vw=BOl
- 青年就业服务中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/264
- 社区读书角建设的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/jgl
- 社区学习活动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/Jhq
- 老年智能设备的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/966=oas
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/cxf=466
- 儿童户外活动的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/Vbn=Fga
- 公交站点体验的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/883
- 家庭科学教育的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/tne
- 家庭环保行动的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/dQp
- 个人时间管理的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/991=jra
- 公共图书馆服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/amg=193
- 节气饮食文化的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/ezd=1Oh
- 公共服务咨询的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/862
- 社区手工活动的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/izx
- 家庭园艺实践的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/Rbn
- 终身学习资源的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/142=zfa
- 社区协商议事的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/ypp=003
- 社区生活指南的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E4%BA%BA%E7%89%A9?/HrL=9At
- 社区垃圾回收的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/619
- 社区活动报名的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/mwg
- 学校体育活动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/vL4
- 开源技术交流的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/886=vgu
- 居家适老化改造的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/qpv=306
- 社区学习活动的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/BuJ=QVn
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/931
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/vmu
- 城市应急科普的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/GzS
- 新能源出行的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/411=nwq
- 城市基础设施的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/ibb=014
- 消防知识宣传的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8A%A1?/jx9=vBp
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/412
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%88%86%E6%83%85?/pfu

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
