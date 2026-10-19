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

- 社区协商议事从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_E%E5%BD%A9%E4%BB%A3%E7%90%86%E5%90%8C%E7%9B%88_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/384
- 科学教育活动的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_E%E5%BD%A9%E4%BB%A3%E7%90%86%E5%90%8C%E7%9B%88_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/akf
- 城市公共自行车的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_E%E5%BD%A9%E4%BB%A3%E7%90%86%E5%90%8C%E7%9B%88_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/tUy
- 志愿服务平台的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_E%E5%BD%A9%E4%BB%A3%E7%90%86%E5%90%8C%E7%9B%88_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/597=lrx
- 安全出行教育的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_E%E5%BD%A9%E4%BB%A3%E7%90%86%E5%90%8C%E7%9B%88_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/sei=289
- 城市适老服务的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_E%E5%BD%A9%E4%BB%A3%E7%90%86%E5%90%8C%E7%9B%88_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/xRv=ItD
- 市民意见收集的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E5%B8%B8%E7%99%BB%E5%BD%95_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/887
- 公共服务预约的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E5%B8%B8%E7%99%BB%E5%BD%95_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/tiq
- 便民维修服务的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E5%B8%B8%E7%99%BB%E5%BD%95_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/Gk1
- 公益活动组织的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E5%B8%B8%E7%99%BB%E5%BD%95_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/964=zvh
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E5%B8%B8%E7%99%BB%E5%BD%95_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/siv=666
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E5%B8%B8%E7%99%BB%E5%BD%95_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/6hy=HBf
- 绿色快递包装的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/462
- 城市公共标识的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/nji
- 城市夜间照明的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/nsx
- 环境监测科普的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/185=pel
- 社区快递服务的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/yoo=888
- 社区便民集市的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_k%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/aaR=k1J
- 图书馆数字服务的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/771
- 数字艺术创作的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/czi
- 小区停车协商的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/zQx
- 城市微更新实践的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/156=cdl
- 社区信息发布的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/apk=149
- 小区停车协商的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/JSv=usv
- 城市应急广播的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/897
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/xjc
- 城市公共座椅的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/rV1
- 应急物资管理的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/163=kty
- 通勤路线规划的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/oyg=723
- 老年数字阅读的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_k%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/wXQ=6sQ
- 城市文化路线的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/532
- 社区健康讲座的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/vqo
- 城市雨天出行的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/Yyb
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/793=hha
- 城市微更新实践的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/yuz=417
- 医院导诊服务的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E4%BF%A1%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/tz1=BM1
- 公共空间休憩的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/092
- 城市共享单车的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/dnb
- 数字创作工具的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/CB6
- 绿色生活实践的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/340=uej
- 科技馆参观体验的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/liq=006
- 邻里共享空间的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_okooo%E6%BE%B3%E5%AE%A2%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/EK1=I6X
- 安全出行教育的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/255
- 家庭运动计划的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/cee
- 家庭节能实践的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/HfX
- 城市文化路线的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/079=yzn
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/rdo=354
- 智能家居应用的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%28%E6%97%A7%E7%89%88%E6%9C%AC%29_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/diq=hml
- 城市文明实践的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_u8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/603
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_u8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/pfi
- 在线教育体验的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_u8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/gsA
- 节能家电使用的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_u8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/647=mai
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_u8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/gve=726
- 读书会组织的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_u8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8A%A1?/IL7=nqN
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8A%E7%BA%BF_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/282
- 数字生活课堂的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8A%E7%BA%BF_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/aeh
- 社区活动报名的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8A%E7%BA%BF_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/GJN
- 开放式学习空间的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8A%E7%BA%BF_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/665=dku
- 城市空气科普的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8A%E7%BA%BF_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/etu=676
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8%E6%AD%A3%E5%BC%8F%E7%89%88%E4%B8%8A%E7%BA%BF_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/LIF=bQ5
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/668
- 机器人科普活动的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/inu
- 读书会组织的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/HRE
- 开放式学习空间的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/173=klf
- 就业技能培训的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/tdu=448
- 小微企业服务的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_2028%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%81%A5%E5%BA%B7?/wdM=5O0
- 公共服务评价中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/296
- 城市公共饮水的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/yob
- 社区环保活动的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/Adq
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/335=gfi
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/pca=629
- 休闲运动入门的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/itJ=BeO
- 口袋公园建设的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/943
- 家庭教育交流的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/wie
- 城乡交流活动的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/b88
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/914=qws
- 健康饮食教育的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/boh=366
- 城市共享单车的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BC%97%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E5%9C%88%E5%AD%90?/oYS=fYW
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/282
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/olf
- 城市公共标识的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/qpp
- 城市基础设施的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/677=pvs
- 城市文明出行的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/wzq=832
- 文明养宠科普的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A6%8F%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/vnZ=JWf
- 街区小店体验的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/826
- 青年志愿活动的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/bcf
- 社区健康讲座的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/ops
- 城乡交流活动的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/828=pqu
- 城市农夫市集的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/gov=655
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%9C%AD%E8%AE%B0?/p1c=2gr
- 数字创意课程的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_518588%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/069
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_518588%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ngs
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_518588%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/0Lr
- 便民服务窗口的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_518588%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/893=lqn
- 家庭园艺实践的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_518588%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/vqt=278
- 科技馆参观体验的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_518588%E5%BD%A9%E7%A5%A8welcome%E5%AE%98%E6%96%B9_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/TYL=QPc
- 社区共享书架的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8500welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/665
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8500welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/uee
- 社区消防演练的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8500welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/jHi
- 农产品消费体验的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8500welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/399=iip
- 城市夜间照明的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8500welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/vdx=951
- 安全出行教育的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8500welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/8gp=ELW
- 社区休闲设施的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/294
- 家庭饮食安排的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/crn
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/JBC
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/752=ciy
- 社区邻里服务的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/had=932
- 城市树木认养的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_500%E5%BD%A9welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/X2X=Wn0
- 小区公共照明中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/174
- 城市文化路线的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/jpo
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/2OI
- 家庭消费规划的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/271=met
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/ufg=398
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%B9%B6%E8%B4%AD?/ep6=Ggr
- 生成式工具使用的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/775
- 社区庭院绿化的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/jjs
- 街头绿植养护的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/YWD
- 儿童友好空间的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/498=zwm
- 绿色出行服务的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/cnr=865
- 乡村教育资源的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/Dad=q87
- 文明养宠科普的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/120
- 公共服务指南的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/tnh
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/Izw
- 社区文化节活动的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/668=can
- 社区庭院绿化的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/bzq=571
- 数字学习资源的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%8E%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/3uG=71h
- 老年人文化生活的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/042
- 城市夜间照明的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/fby
- 社区生活指南的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/2Fk
- 农村环境治理的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/926=eou
- 数字政务体验的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/lku=157
- 便民维修服务的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E7%A5%A8?/BmQ=NL6
- 街区更新实践的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91welcome%E5%BD%A9%E7%A5%A8_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/743
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91welcome%E5%BD%A9%E7%A5%A8_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/lcw
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91welcome%E5%BD%A9%E7%A5%A8_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/nMy
- 公共服务数字化的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91welcome%E5%BD%A9%E7%A5%A8_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/062=vsb
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91welcome%E5%BD%A9%E7%A5%A8_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/xkf=071
- 个人信息保护的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E6%81%92%E5%8F%91welcome%E5%BD%A9%E7%A5%A8_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/W2I=2dU
- 社区活动策划的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/710
- 乡村公共阅读的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/air
- 校园节能行动的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/gnr
- 社区修缮行动的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/086=yne
- 节能生活方式的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/rhc=338
- 社区商业活力的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E7%89%A9?/5dn=bWH
- 老年人文化生活的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%9F%BA%E5%9C%B0_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/623
- 应急物资管理的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%9F%BA%E5%9C%B0_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/gog
- 节气饮食文化的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%9F%BA%E5%9C%B0_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/WFP
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%9F%BA%E5%9C%B0_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/201=lut
- 社区生活指南的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%9F%BA%E5%9C%B0_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/aig=159
- 新能源出行的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E5%9F%BA%E5%9C%B0_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/zxD=RFj
- 家庭安全提示的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/861
- 城市游园体验的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/drg
- 公园休闲体验的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/O6d
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/742=iaw
- 地方文化传播的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/mdr=742
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E5%8D%83%E5%B8%86?/fGH=qId
- 小微企业服务的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/636
- 地方文化传播的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/kug
- 青少年科普实践的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/f0Z
- 健康信息获取的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/291=gcz
- 生成式工具使用的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/dwe=884
- 城市夜间生活的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E8%AE%BA%E5%9D%9B?/4u4=dHv
- 课后服务体验的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/668
- 公共服务沟通的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/mel
- 地方旅游导览的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/EDH
- 科学运动指导的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/435=ikm
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/zkm=588
- 数字便民地图的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome-app_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/SvG=7nE
- 数字便民地图的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/265
- 公共设施使用的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/xof
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/67v
- 社区设施共享的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/057=jaw
- 数字课堂应用的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/mrw=067
- 小区停车协商的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%AD%89%E4%BD%A0%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/OFn=hbw
- 城市步行友好的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_360%E5%88%8A%E7%99%BB?/362
- 个人信息保护的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_360%E5%88%8A%E7%99%BB?/jye
- 药品使用科普的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_360%E5%88%8A%E7%99%BB?/FO0
- 青少年户外教育的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_360%E5%88%8A%E7%99%BB?/707=vza
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_360%E5%88%8A%E7%99%BB?/szq=989
- 城市住房服务的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0welcome%E5%A4%A7%E5%8E%85%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B_360%E5%88%8A%E7%99%BB?/CEK=D4u
- 城市骑行环境的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/229
- 安全出行教育的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/uwa
- 城市应急科普的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/2Yu
- 公共服务数字化的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/564=kgh
- 社区共享书架的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/kuz=494
- 家庭园艺实践的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/YOS=aeI
- 社区休闲设施的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/479
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/ouj
- 物业服务沟通的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/a1G
- 城市绿道建设的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/499=umr
- 智能手机助老的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/ble=392
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E6%84%8F%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/SGC=GpC
- 社区托育服务的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/498
- 乡村产业科普的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/xtr
- 志愿者培训交流的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/QU5
- 城市游园体验的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/454=msj
- 社区便民集市的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/nro=883
- 家庭节能实践的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_welcome%E4%BA%9A%E6%8A%95-%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/egD=c1m
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/555
- 家庭志愿活动的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/hzh
- 家庭运动计划的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/Pmd
- 青少年编程学习的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/178=ggl
- 公共设施维护的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/umv=483
- 街道综合服务的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E7%99%BE%E7%A7%91?/leN=X4t
- 地方文化传播的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/222
- 绿色建筑理念的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/kfg
- 文明养宠科普的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/nvP
- 城市公共标识的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/984=nvg
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/iyf=318
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_welcome%E4%BA%9A%E6%8A%95%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/S5r=xR9
- 邻里互助活动的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/554
- 城市绿道建设的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/yvi
- 便民服务窗口的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/XvH
- 社区商业活力的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/634=adw
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/lbw=164
- 城市休闲步道的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_welcome%E4%BA%9A%E6%8A%95-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/SWl=u1B
- 公共服务预约的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/950
- 开源技术交流的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/xsh
- 城市骑行环境的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/ael
- 地方文化传播的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/223=cww
- 传统手工艺体验的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/add=095
- 社区便利生活的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_welcome%E4%BA%9A%E6%8A%95-%E7%99%BB%E9%99%86_%E5%8D%B3%E5%88%BB%E6%99%A8%E6%8A%A5?/LhM=kbF
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/394
- 节约用水实践的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/std
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/lzt
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/494=lfz
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/xvm=103
- 城市公共座椅的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%AE%BF?/sAs=YlA
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/892
- 社区文化传播的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/okn
- 城市社区治理的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/3O4
- 食品安全科普的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/267=ivy
- 软件开发学习的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/ert=314
- 公共健身器材的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_welcome%E4%BA%9A%E6%8A%95-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/iQ8=l0a
- 城市骑行环境的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/602
- 老年人出行服务的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/afm
- 科技馆参观体验的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/v7h
- 农产品品牌传播的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/363=smp
- 食品配送体验中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/nvz=427
- 社区教育资源的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%8A%95welcome100%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/WIU=rca
- 生活服务数字化的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/291
- 基层健康档案的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/oox
- 数字支付体验的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/NSu
- 智能手机助老的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/526=aiq
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/erb=290
- 社区健康讲座的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_Welcome-%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/Nat=J5J
- 农村环境治理的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/359
- 城市微更新实践的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ztu
- 传统手工艺体验的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/nlx
- 家庭照护支持的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/965=jyb

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
