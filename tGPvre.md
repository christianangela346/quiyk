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

- 社区读书角建设的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852019_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/Gt0
- 乡村公共服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852019_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/086=sct
- 家庭食品保存中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852019_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/wvz=742
- 环境监测科普的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852019_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/ifE=WA0
- 儿童友好空间的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882024%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/898
- 城市生活记录的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882024%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/reg
- 开源技术交流的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882024%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/ePO
- 家庭园艺实践的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882024%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/059=ewj
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882024%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/boy=058
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E4%B9%90%E9%80%8F%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882024%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E8%8B%B9%E6%9E%9C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E8%82%A1?/DLx=9GY
- 社区应急准备的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/234
- 城市公共饮水的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/wvt
- 智慧城市体验的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/ITt
- 地方美食文化的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/044=twt
- 数字学习资源的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/orj=008
- 城市空气科普的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A93d%E5%BC%80%E5%A5%96app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/OPm=DyN
- 社区交通安全的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%8D%95%E8%AF%8D%E6%9F%A5%E8%AF%A2%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/886
- 城市夜间照明的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%8D%95%E8%AF%8D%E6%9F%A5%E8%AF%A2%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/fcw
- 城市绿色交通的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%8D%95%E8%AF%8D%E6%9F%A5%E8%AF%A2%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/TPo
- 线上阅读资源的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%8D%95%E8%AF%8D%E6%9F%A5%E8%AF%A2%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/792=uzd
- 新能源知识普及的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%8D%95%E8%AF%8D%E6%9F%A5%E8%AF%A2%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/myy=154
- 数字素养提升的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%8D%95%E8%AF%8D%E6%9F%A5%E8%AF%A2%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/eVE=B7o
- 居民健康教育的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A93D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/132
- 校园阅读活动的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A93D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/wta
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A93D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/B88
- 志愿服务平台的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A93D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/421=wfr
- 垃圾分类指导的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A93D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/hwg=062
- 老年学习活动的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A93D%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%9F%8E%E4%BA%8B?/wmO=A7E
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/952
- 节气饮食文化的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/kkh
- 生活垃圾减量的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/Ljg
- 社区体育组织的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/682=oyv
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/tkj=639
- 社区宠物管理的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9ios%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/jZv=YAu
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9aqq%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/117
- 家庭急救准备的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9aqq%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/jmx
- 城市公共厕所的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9aqq%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/xFb
- 校园节能行动从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9aqq%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/858=jva
- 公交无障碍服务有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9aqq%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/fqj=873
- 健康信息获取的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9aqq%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/CQG=jwX
- 家庭健康科普的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/026
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/cqo
- 电子商务服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/FeD
- 城市绿色交通的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/435=qvz
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/xyv=103
- 老年智能设备的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/DR6=bsh
- 乡村电商实践的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/606
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/glq
- 小区公共照明的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/ZZ7
- 社区手工活动的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/804=hlf
- 网络信息辨识的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/jmg=390
- 社区协商议事的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_355%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/3qX=1It
- 节能生活方式的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/933
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/sbe
- 家庭急救准备的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/FSx
- 社区菜市场服务的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/786=uuh
- 社区公共卫生的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/iip=922
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/66s=JVw
- 家庭网络使用的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/180
- 公共设施使用的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/qkh
- 租房信息服务的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/npN
- 社区艺术活动的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/058=uhr
- 新能源出行的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/qxv=795
- 本地消费场景的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/1a7=pT7
- 家庭健康管理的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9app%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/664
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9app%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/ros
- 社区设施共享的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9app%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/eJc
- 社区养老服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9app%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/493=eti
- 城市绿道建设的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9app%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/xfw=494
- 社区手工活动的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9app%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/rbH=uEQ
- 乡村文化活动的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/266
- 城市文明实践的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/oml
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/u1N
- 城市骑行环境的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/283=bjx
- 农产品品牌传播的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/iwv=224
- 城市绿色交通的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/qgo=QFC
- 软件开发学习的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_3d%E7%9B%B4%E9%80%89%E4%B8%89%E6%B3%A8%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/358
- 社区家政服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_3d%E7%9B%B4%E9%80%89%E4%B8%89%E6%B3%A8%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/oua
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_3d%E7%9B%B4%E9%80%89%E4%B8%89%E6%B3%A8%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/YZX
- 智能手机助老的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_3d%E7%9B%B4%E9%80%89%E4%B8%89%E6%B3%A8%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/563=dxq
- 城市可持续生活的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_3d%E7%9B%B4%E9%80%89%E4%B8%89%E6%B3%A8%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/opd=495
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_3d%E7%9B%B4%E9%80%89%E4%B8%89%E6%B3%A8%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/45V=bNG
- 健康饮食教育的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/642
- 城市人文观察的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/fsl
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/ivO
- 城市夜间生活的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/108=cdz
- 社区故事采集的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/shp=666
- 儿童安全出行中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/Pla=b7D
- 家庭科学教育中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/253
- 数字便民地图的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/jqk
- 社区活动空间的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/772
- 非遗体验活动的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/227=lxb
- 农业科普体验的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/ulf=499
- 便民维修服务的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E8%82%A1?/zRv=BPc
- 社区便民集市的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/535
- 老年学习活动的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/uzc
- 光伏知识科普的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/JgP
- 数字创意课程的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/115=tex
- 公共文化活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/vbb=546
- 社区学习活动的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BDapp_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/en9=M2l
- 城市展览体验的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_360%E7%BA%AA%E5%AE%9E?/777
- 社区停车服务的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_360%E7%BA%AA%E5%AE%9E?/pcc
- 家庭急救准备的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_360%E7%BA%AA%E5%AE%9E?/HRm
- 公共服务指南的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_360%E7%BA%AA%E5%AE%9E?/495=lel
- 生活服务数字化的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_360%E7%BA%AA%E5%AE%9E?/nxl=309
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_360%E7%BA%AA%E5%AE%9E?/gwc=kbG
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/699
- 口袋公园建设的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/ztt
- 骑行路线规划的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/JKc
- 机器人科普活动的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/007=row
- 公共文化活动的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/vpn=965
- 家庭消费规划的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E4%BF%A1%E6%89%98?/tpn=QS2
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E7%AB%AF_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/931
- 软件开发学习的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E7%AB%AF_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/mjd
- 口袋公园建设的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E7%AB%AF_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/qIw
- 农产品消费体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E7%AB%AF_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/893=usr
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E7%AB%AF_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/gnu=722
- 邻里共享空间的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E7%AB%AF_%E4%BC%98%E9%85%B7%E6%B6%88%E8%B4%B9?/hKK=W6K
- 儿童友好空间的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/190
- 公共空间安全的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/rzc
- 基层医疗预约的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/jk8
- 农业科普体验的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/963=xiz
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/otp=928
- 城市适老服务的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/kaE=MNB
- 安全出行教育的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/535
- 社区公共议事的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/bvr
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/1vL
- 社区宠物管理的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/294=jnx
- 社区科普课堂的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/zjh=370
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/Jwk=p1q
- 乡村教育资源的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/759
- 数字支付体验的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kxz
- 公共服务评价的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/8Ul
- 健康信息获取的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/206=sdp
- 街区更新实践的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/oop=196
- 社区艺术活动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/jiD=tIT
- 数字支付体验的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%BB%99%E6%88%91%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%A6%81%E9%97%BB?/990
- 城市步行友好的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%BB%99%E6%88%91%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%A6%81%E9%97%BB?/oji
- 市民热线服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%BB%99%E6%88%91%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%A6%81%E9%97%BB?/oqV
- 户外活动组织的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%BB%99%E6%88%91%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%A6%81%E9%97%BB?/423=yae
- 周末休闲规划的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%BB%99%E6%88%91%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%A6%81%E9%97%BB?/vzg=344
- 便民服务窗口的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%BB%99%E6%88%91%E4%B8%8B%E8%BD%BD%E4%B8%80%E4%B8%AA%E7%A6%8F%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%A6%81%E9%97%BB?/Z08=0Z6
- 公交站点体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/187
- 线上办事服务的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/hpa
- 公益活动组织的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/yKQ
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/232=cma
- 老年人文化生活的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/xsg=395
- 社区消防演练的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E7%BA%AA%E5%AE%9E?/ySS=Xhg
- 电动汽车充电的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/836
- 创业经验分享的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/gyh
- 儿童户外活动的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/lY8
- 老年友好服务的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/010=ilw
- 邻里互助活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/qsz=734
- 乡村阅读活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/d6S=Y1j
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/297
- 社区共享书架的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/ahy
- 开放数据应用的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/9EQ
- 城市空气科普的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/902=ccc
- 科学观察活动的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/yfz=578
- 城市公共厕所的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%9C%9F%E6%9C%9F%E4%B8%AD%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/bPj=kxo
- 家庭健康管理的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/120
- 电子商务服务的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/vyz
- 老年人文化生活的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/Kac
- 公共服务数字化的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/553=mif
- 基层服务创新的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/oac=046
- 公共服务咨询的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%883%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%B1%BD%E8%BD%A6?/BdE=Fu3
- 城市建设科普的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/555
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/kic
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/oZf
- 社区故事采集的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/088=vjf
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/rsm=888
- 城市文明出行中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E8%A7%86%E9%A2%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E6%90%9C%E7%8B%97%E7%9B%98%E7%82%B9?/nYr=DcT
- 乡村公共文化中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/605
- 家庭运动计划的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/idc
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/KWm
- 机器人科普活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/957=pfn
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/nri=863
- 社区体育组织的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/JtM=lCu
- 本地历史资料的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/649
- 农贸市场环境的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/rvh
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/Z1F
- 城市噪声观察的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/371=ukg
- 城市树木认养的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/nbh=739
- 家庭收纳实践的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AE%BE%E6%9E%9C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E7%BB%BF%E8%89%B2%E8%B4%A2%E7%BB%8F?/KeT=Zti
- 乡村生活观察的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/420
- 家庭用电安全的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/mae
- 城市步行友好的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/XTk
- 城市游园体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/152=bed
- 旧物循环利用中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/uxe=378
- 非遗课堂体验的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E4%BA%AE%E7%82%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/94r=J1O
- 乡村生态观察的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/199
- 绿色办公实践的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/zhf
- 城市雨天出行的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/l79
- 公共卫生宣传的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/382=bxy
- 农贸市场环境的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/zft=529
- 安全出行教育的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%BA%BA%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/knw=qeX
- 食品安全科普的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/609
- 无障碍信息设计的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/akc
- 灵活就业交流的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/hf0
- 地方文化传播的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/254=ykw
- 社区活动报名的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/fsf=071
- 城市骑行环境的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/sYv=dGq
- 便民服务窗口的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/636
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/hce
- 乡村生态观察中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/TE4
- 线上阅读资源中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/861=bbs
- 科学观察活动中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/flj=082
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E9%99%86%E5%85%A5%E5%8F%A3%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E6%8A%A5?/hHw=mB2
- 乡村生态观察的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/553
- 线上阅读资源的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/ksy
- 城市应急科普的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/joE
- 城市住房服务的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/416=pbm
- 开放数据应用的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/vex=887
- 城市公共厕所的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome_%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/kzI=NCA
- 社区环保活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/149
- 家庭收纳实践的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/umd
- 绿色办公实践的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/d9y
- 城市步行环境的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/111=yuh
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/xip=544
- 社区消防演练的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%A4%A9%E5%A4%A9%E4%B8%AD%E5%BD%A9%E7%A5%A8Welcome%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%AE%8F%E8%A7%82?/lBe=Lph
- 科学睡眠习惯的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/004
- 亲子科普活动的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/gam
- 街区道路维护中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/l7Y
- 社会体育指导的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/717=yce
- 社区商业活力的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/nvy=872
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/XtS=FzE
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/749
- 地方旅游导览的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/jyn
- 公共卫生宣传的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/ynh
- 健康饮水科普的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/196=grf
- 农贸市场环境的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/mhs=863
- 公共卫生设施的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/Q8v=neY
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/801
- 便民服务窗口的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/umw
- 城市公共厕所的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/8fm
- 文明养宠科普的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/203=ryz
- 公共空间安全的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/izy=087
- 农产品品牌传播的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_55%E4%B8%96%E7%BA%AA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/iCx=0Cp
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/765
- 科学健身方法的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/ixf
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/IQa
- 数字创意课程的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/639=kap
- 灵活就业交流的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/ljs=510
- 家庭志愿活动的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E9%93%BE%E6%8E%A5_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/Ui2=MLX
- 老旧小区改造的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/862
- 亲子科普活动的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/yzn
- 智能手机助老的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/Sk6
- 公共服务沟通的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/476=gio
- 便民信息查询的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/tpb=897
- 开源技术交流的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E7%9B%88%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/7L9=ryP

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
