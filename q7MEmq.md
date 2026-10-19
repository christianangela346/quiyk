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

- 社区读书角建设的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/Azp
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/876=iqh
- 家庭节能实践的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/fjb=052
- 租房信息服务的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/woc=w8j
- 城市公共自行车的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%AE%A0%E7%89%A9?/439
- 社区活动报名的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%AE%A0%E7%89%A9?/bwf
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%AE%A0%E7%89%A9?/ejt
- 老年人文化生活的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%AE%A0%E7%89%A9?/135=opj
- 公共文化活动的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%AE%A0%E7%89%A9?/aio=005
- 街区绿化养护的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%AE%A0%E7%89%A9?/Hfm=dAz
- 地方戏曲体验的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-8-%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/382
- 非遗课堂体验的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-8-%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/uxl
- 公园休闲体验的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-8-%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/15O
- 机器学习入门的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-8-%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/491=wup
- 公共服务数字化的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-8-%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/fie=233
- 邻里互助活动的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-8-%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/Yy3=K6K
- 农产品品牌传播的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/376
- 青少年心理健康的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/qat
- 城市空气科普的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/4ll
- 老年人日常照护的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/673=juu
- 城市绿色交通的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/lyk=788
- 城市可持续生活的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/ZqS=fOY
- 数字阅读服务的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/930
- 城市微更新实践的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/alp
- 社区慢性病防控的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/gCO
- 社区停车服务的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/985=gtu
- 数据分析入门的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/ykg=894
- 城市雨天出行的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/rcI=iCu
- 本地历史资料的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9210%E6%9C%9F_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/463
- 社区体育组织中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9210%E6%9C%9F_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/oul
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9210%E6%9C%9F_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/Une
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9210%E6%9C%9F_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/738=wfg
- 社区科普课堂的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9210%E6%9C%9F_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/kdq=327
- 租房信息服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9210%E6%9C%9F_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/ZP0=bfK
- 家庭环保行动的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/492
- 乡村公共阅读的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/ggx
- 节日文化体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/igl
- 城市微更新实践的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/907=nhv
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/agh=360
- 青年职业探索的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/wdv=NDF
- 网络安全教育的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/324
- 远程协作工具的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/tpw
- 公共服务预约的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/GLx
- 居民健康教育的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/719=ssl
- 图书馆数字服务的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/paw=251
- 邻里共享空间的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/lBw=mdJ
- 社区托育服务的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/749
- 旧物循环利用的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/odr
- 城市农夫市集的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/fwR
- 社区消防演练的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/405=hyi
- 公共服务沟通的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/izc=003
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/oI4=XnP
- 社区老年食堂的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/647
- 社区托育服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/gvm
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/FN2
- 数字生活课堂的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/435=saw
- 文明养宠科普的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/ahm=575
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%85%AC%E7%9B%8A?/8kj=EDX
- 公共空间安全的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/464
- 居家适老化改造的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/htm
- 机器人科普活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/XcG
- 读书会组织的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/095=aux
- 数字资源检索的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/jwv=963
- 农村环境治理的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/Edd=LPm
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/744
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/emn
- 社区垃圾回收的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/WDR
- 公共服务评价的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/969=tza
- 城市夜间生活的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/jef=560
- 口袋公园建设的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/tBi=Peb
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/772
- 城市展览体验的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/etd
- 科技馆参观体验的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/Uxg
- 市民意见收集的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/956=dkt
- 公共卫生设施的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/rfo=106
- 物业服务沟通的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/X47=eNg
- 社区儿童活动的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A810%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/152
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A810%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/bhf
- 社区应急准备的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A810%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/Uoe
- 无障碍信息设计的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A810%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/753=hfj
- 农贸市场环境的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A810%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/dyy=768
- 城乡公共服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A810%E5%88%86%E5%BF%AB3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/TgE=CpB
- 城市地名文化中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/917
- 便民信息查询的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/tme
- 在线学习体验的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/pWb
- 基层服务创新的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/277=isr
- 城市建设科普的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/zqm=798
- 药品使用科普的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_5%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E8%85%BE%E8%AE%AF%E6%96%87%E5%8C%96?/rB3=1VD
- 公共文化活动的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/553
- 家庭环保行动的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/rtt
- 城市农夫市集的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/RAj
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/422=qok
- 亲子科普活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/tak=814
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/PwZ=EJg
- 食品安全科普的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E7%A8%B3%E8%B5%A2%E5%90%97_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/260
- 校园节能行动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E7%A8%B3%E8%B5%A2%E5%90%97_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/mej
- 文明养宠科普的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E7%A8%B3%E8%B5%A2%E5%90%97_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/j0L
- 创业经验分享的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E7%A8%B3%E8%B5%A2%E5%90%97_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/533=run
- 城市共享单车的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E7%A8%B3%E8%B5%A2%E5%90%97_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/pbo=089
- 医院导诊服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E7%A8%B3%E8%B5%A2%E5%90%97_%E8%8A%92%E6%9E%9C%E5%AE%9E%E5%BD%95?/NvY=mV2
- 农贸市场环境的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/898
- 城市绿道建设的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/ihs
- 社区绿色空间的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/X3x
- 传统节日科普的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/503=vqb
- 城市水环境观察的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/tvd=942
- 社区托育服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/se8=3Yj
- 环境教育课程的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/538
- 城市公共座椅的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/ajq
- 家庭用电安全的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/f9j
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/145=nmz
- 城市骑行环境的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/rqa=043
- 绿色办公实践的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/SBC=R5y
- 乡村文化空间的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/521
- 社区庭院绿化的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/ttk
- 公共场所导视的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/xVh
- 乡村公共阅读的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/889=cto
- 节能家电使用的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/fza=411
- 青少年科普实践中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/I9d=lkg
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/244
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/uzi
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/JIT
- 口袋公园建设的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/727=tbq
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/sye=026
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/wzl=hYo
- 绿色办公实践的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/131
- 家庭节能实践的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/thn
- 社区交通安全的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/07n
- 家庭环保习惯的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/711=swt
- 低碳社区实践的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/ewj=241
- 气象科普传播的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E6%88%BF%E4%BA%A7?/fET=6jy
- 街区更新实践的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/124
- 消防知识宣传的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/fty
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/lN3
- 数字地图应用的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/512=oxl
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/rea=677
- 城市游园体验的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/3nJ=Wpg
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/369
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/imv
- 儿童户外活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/jDx
- 社区养老服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/171=ubd
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/uhd=741
- 数字档案服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/LMp=Jva
- 节气饮食文化的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/646
- 公共交通接驳的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/chs
- 社区便民集市的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/XCQ
- 青少年科普实践的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/437=wgd
- 绿色出行服务的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/jkv=175
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/1fi=MBw
- 绿色出行服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/074
- 社区法律科普的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/lql
- 青少年心理健康的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/rVq
- 家庭消费规划的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/366=amr
- 食品配送体验的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/wjt=354
- 社区公共议事中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3app%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A8%B1%E4%B9%90?/Bt9=Cie
- 乡村文化活动的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/588
- 智能家居应用的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/lay
- 公共健身器材的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/PF5
- 家庭节能设备的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/836=tqu
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/edi=934
- 农业科普体验的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/aDD=JOY
- 城市夜间照明的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/653
- 社区读书角建设的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/ool
- 公共设施维护的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/pNf
- 图书馆活动策划的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/185=tmg
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/ahd=456
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E5%BD%A9%E7%A5%A82024%E6%89%8B%E6%9C%BA%E7%89%88_%E6%8A%96%E9%9F%B3%E6%B3%95%E5%BE%8B?/AAq=lIY
- 城市建设科普的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/074
- 基层服务创新的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/wgw
- 开放式学习空间的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/fU2
- 社区安全巡查的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/176=nea
- 公共设施维护的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/gjl=206
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%85%B4%E8%B4%A2%E7%BB%8F?/r12=cuu
- 食品安全科普的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/220
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/phm
- 城市空气科普的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/Y9T
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/320=dpz
- 社区休闲设施的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/mqb=279
- 志愿者培训交流的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/eyT=E7V
- 公共服务评价中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/991
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/ppr
- 城市公共饮水的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/JSm
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/801=yuz
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/had=083
- 公共场所导视的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%8A%E6%B5%B7%E5%BF%AB3app%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/Fqa=tpZ
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/139
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/ghz
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/czu
- 数字阅读服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/105=pad
- 城市步行环境的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/wzj=831
- 社区交通安全的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E6%B3%A8app%E7%8C%9C%E5%A4%A7%E5%B0%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/uxK=XRg
- 图书馆活动策划的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/986
- 城市公共饮水的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/swx
- 科普展览体验的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/LUj
- 社区手工活动的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/470=iqq
- 社区休闲设施的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/pqt=395
- 健康饮水科普的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E4%B8%93%E9%A2%98?/3Oi=EmW
- 健康饮水科普的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/187
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/nex
- 节日文化体验的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/zu3
- 数字便民地图的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/321=kqg
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/emn=118
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/8ye=XGQ
- 开源技术交流的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/037
- 社区文化传播中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/bfu
- 社区家校合作的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/FQ1
- 老年学习活动的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/171=rmm
- 家庭食品保存的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/rlt=462
- 城市慢行系统的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8APP_%E7%BD%91%E6%98%93%E5%9B%AD%E8%89%BA?/llS=fgC
- 社区法律科普的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/191
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/duo
- 市民意见收集的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/JOe
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/370=qik
- 文化讲座服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/viy=103
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/W9X=fyO
- 公共服务数字化的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/276
- 软件开发学习的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/rbk
- 家庭收纳实践的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/rTj
- 小区电梯维护的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/679=rcc
- 公共服务预约的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/ned=777
- 城市公共艺术的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%A4%E5%87%B0app_%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/xcK=pvO
- 城市基础设施的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/339
- 小区停车协商的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/snj
- 科学教育活动的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/SZu
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/455=njq
- 物业服务沟通的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/zpa=181
- 青少年科普实践的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-1%E8%B5%942-%E5%BD%A9%E7%A5%A8-app_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/bbl=xRf
- 无障碍信息设计的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/382
- 农产品品牌传播的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/fwa
- 社区法律科普的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/BxY
- 农产品消费体验的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/277=khe
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/whn=706
- 地方戏曲体验的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E9%9F%B3%E4%B9%90?/0vF=NFW
- 公共交通接驳的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/274
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/epq
- 便民服务地图的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/sEY
- 小区停车协商的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/153=pms
- 志愿服务平台的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/oor=576
- 老年运动活动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E7%9A%84app_%E7%95%8C%E9%9D%A2%E7%88%86%E6%96%99?/aYr=LiG
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/217
- 城乡交流活动的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/jpt
- 青少年科技社团的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/P9c
- 基层服务创新的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/909=wdn
- 社区修缮行动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/hjm=328
- 生活垃圾回收的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/Kof=91v
- 乡村产业科普的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/943
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/xxe
- 应急物资管理的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/1SH
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/850=aoc
- 科学健身方法的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/tzu=477
- 社区科普课堂的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/iNA=F7E

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
