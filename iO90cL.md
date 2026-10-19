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

- 食品安全科普的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E9%92%B1%E8%83%BD%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%90%97_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/iab=975
- 创业经验分享的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E9%92%B1%E8%83%BD%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%90%97_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/5EV=zyB
- 公共服务数字化的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/419
- 社区生活指南的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/hgt
- 家庭环保行动的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/xHN
- 公共图书馆服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/748=uyc
- 灵活就业交流的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/sjc=423
- 社区艺术活动的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/sQh=08J
- 软件开发学习的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/519
- 乡村阅读空间的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/zlo
- 社区儿童活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/ZkD
- 地方民俗记录的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/732=csn
- 社区养老服务的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/smb=233
- 公共场所导视的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%B1%82%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/I1w=uII
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%9C%89%E5%9B%9E%E8%A1%80%E6%88%90%E5%8A%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/842
- 家庭运动计划的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%9C%89%E5%9B%9E%E8%A1%80%E6%88%90%E5%8A%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/gyw
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%9C%89%E5%9B%9E%E8%A1%80%E6%88%90%E5%8A%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/As3
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%9C%89%E5%9B%9E%E8%A1%80%E6%88%90%E5%8A%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/393=yyz
- 社区活动空间的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%9C%89%E5%9B%9E%E8%A1%80%E6%88%90%E5%8A%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/brh=464
- 街区绿化养护的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E6%9C%89%E5%9B%9E%E8%A1%80%E6%88%90%E5%8A%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/kee=BsH
- 科学教育活动的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/304
- 数字课堂应用的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/saa
- 城市游园体验的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/lEx
- 乡村文化活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/459=irg
- 社区教育资源的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/eeh=906
- 街区绿化养护的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/C7t=BsR
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/847
- 公共交通接驳的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/pke
- 社区文化节活动的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/oWl
- 校园阅读活动的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/886=tkg
- 数字政务体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/vyg=049
- 乡村公共文化的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1_%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/v1B=ugw
- 药品使用科普的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E9%83%BD%E6%98%AF%E5%81%87%E7%9A%84%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/650
- 周末休闲规划的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E9%83%BD%E6%98%AF%E5%81%87%E7%9A%84%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/crz
- 读书会组织的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E9%83%BD%E6%98%AF%E5%81%87%E7%9A%84%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/QCS
- 跨代沟通活动的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E9%83%BD%E6%98%AF%E5%81%87%E7%9A%84%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/254=lzw
- 城乡交通衔接的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E9%83%BD%E6%98%AF%E5%81%87%E7%9A%84%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/ajq=488
- 公共服务评价的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E9%83%BD%E6%98%AF%E5%81%87%E7%9A%84%E4%B9%88_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/tBZ=cqi
- 家庭环保行动的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/338
- 城市共享单车的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/rzb
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/kOj
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/789=umd
- 城市展览体验的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/lxe=394
- 基层健康档案的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%BD%91%E4%B8%8A%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E5%B8%88%E7%9A%84QQ_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/PTJ=WPX
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/182
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/hhw
- 公交站点体验的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/3ZP
- 城市共享单车的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/021=fue
- 社区垃圾回收的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/inl=974
- 数字学习资源的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E9%9D%A0%E8%B0%B1%E5%90%97_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/O8p=AKa
- 社区信息发布的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%87%86%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/135
- 老年数字阅读的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%87%86%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/ydx
- 社区阅读服务的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%87%86%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/z0G
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%87%86%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/945=nrz
- 无障碍出行的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%87%86%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/uzd=455
- 城市体育设施的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%87%86%E5%90%97_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/0MJ=Wuy
- 青少年科普实践的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/170
- 生成式工具使用的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/jwc
- 基层健康档案的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/TZV
- 城市公共厕所的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/101=lhu
- 街区小店体验的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/xvu=946
- 家庭健康管理的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/KwP=Ymo
- 文明养宠科普的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E7%9A%84QQ_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/483
- 公共卫生宣传的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E7%9A%84QQ_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/wmf
- 文化讲座服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E7%9A%84QQ_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/dmR
- 社区生活指南的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E7%9A%84QQ_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/864=iwf
- 城市地名文化的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E7%9A%84QQ_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/gzy=384
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88%E7%9A%84QQ_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/cGp=owS
- 家庭科学教育的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/377
- 智慧城市体验的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/zik
- 农村环境治理的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/n34
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/979=gqi
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/qqs=788
- 小区电梯维护的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%90%9C%E7%8B%90%E7%9B%98%E7%82%B9?/hRn=o1A
- 农贸市场环境的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/258
- 本地历史资料的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/jxs
- 城市慢行系统的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/ajs
- 街区更新实践的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/146=awp
- 图书借阅体验的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/rub=558
- 绿色快递包装的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/4uE=AtY
- 乡村教育资源的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/593
- 家庭收纳实践的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/bur
- 健康饮水科普的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/iwz
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/948=iey
- 公共设施维护的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/olq=021
- 农贸市场环境的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E6%98%AF%E8%B0%81_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/Jr1=eqk
- 无障碍信息设计的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/528
- 青年就业服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/axy
- 社区托育服务的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/JBE
- 青少年户外教育的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/556=xve
- 城市公共座椅的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/zkn=515
- 课后服务体验的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E8%80%81%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/q9t=sLB
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/450
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/qge
- 生成式工具使用的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/bea
- 新能源出行的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/744=elr
- 小区公共照明的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/dbz=050
- 城市空气科普的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/sd6=I3M
- 节约用水实践的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%9A%84%E6%8C%87%E5%AF%BC%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/418
- 跨代沟通活动的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%9A%84%E6%8C%87%E5%AF%BC%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/vqx
- 小微企业服务的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%9A%84%E6%8C%87%E5%AF%BC%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/LcZ
- 社区活动策划的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%9A%84%E6%8C%87%E5%AF%BC%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/545=mku
- 公共服务沟通的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%9A%84%E6%8C%87%E5%AF%BC%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/jxk=387
- 社区宠物管理的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%9A%84%E6%8C%87%E5%AF%BC%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/NzY=GEe
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%923%E5%A4%A9%E5%8C%85%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/485
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%923%E5%A4%A9%E5%8C%85%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/wgw
- 家庭节能设备的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%923%E5%A4%A9%E5%8C%85%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/wIS
- 儿童友好空间的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%923%E5%A4%A9%E5%8C%85%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/863=mna
- 地方民俗记录从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%923%E5%A4%A9%E5%8C%85%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/oct=338
- 健康饮水科普的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%923%E5%A4%A9%E5%8C%85%E5%9B%9E%E8%A1%80_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/Gz2=lro
- 数字课堂应用中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/937
- 本地历史资料的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/ebp
- 应急物资管理的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/ZZr
- 城市慢行系统的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/814=mtk
- 公共卫生宣传的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/eau=302
- 城市微更新实践的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_%E6%96%B0%E6%B5%AA%E7%BE%8E%E8%82%A1?/JQy=ibJ
- 社区协商议事的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E9%87%91%E5%88%A9_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/479
- 居家防滑改造的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E9%87%91%E5%88%A9_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/tjb
- 就业技能培训的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E9%87%91%E5%88%A9_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/twj
- 食品安全科普的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E9%87%91%E5%88%A9_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/031=klr
- 公交站点体验的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E9%87%91%E5%88%A9_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/dfy=019
- 社区托育服务的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E9%87%91%E5%88%A9_%E8%85%BE%E8%AE%AF%E5%A4%B4%E6%9D%A1?/Bqf=g3X
- 城市应急广播的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%8F%90%E4%BE%9B%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/033
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%8F%90%E4%BE%9B%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/rfw
- 开放式学习空间的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%8F%90%E4%BE%9B%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/LS9
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%8F%90%E4%BE%9B%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/414=hku
- 数字创作工具的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%8F%90%E4%BE%9B%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/hko=407
- 街区更新实践的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%8F%90%E4%BE%9B%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/Lik=5Ww
- 家庭用电安全的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/383
- 城市共享单车的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/lkp
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/YQY
- 在线学习体验的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/462=kuc
- 城乡公共服务的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/rnh=026
- 家庭照护支持的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E7%9B%B4%E5%B1%9E%E9%82%80%E8%AF%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/54E=x7D
- 青少年心理健康的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%98%AF%E9%87%91%E5%AD%97%E5%A1%94%E6%A8%A1%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/197
- 公共服务沟通的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%98%AF%E9%87%91%E5%AD%97%E5%A1%94%E6%A8%A1%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/ode
- 休闲运动入门的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%98%AF%E9%87%91%E5%AD%97%E5%A1%94%E6%A8%A1%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/KeR
- 社区体育组织的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%98%AF%E9%87%91%E5%AD%97%E5%A1%94%E6%A8%A1%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/313=gag
- 通勤路线规划中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%98%AF%E9%87%91%E5%AD%97%E5%A1%94%E6%A8%A1%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/oej=948
- 劳动教育实践的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%98%AF%E9%87%91%E5%AD%97%E5%A1%94%E6%A8%A1%E5%BC%8F_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/zhf=wnG
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%9B%9D%E5%85%89_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/894
- 公共服务数字化的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%9B%9D%E5%85%89_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/bgo
- 数据分析入门的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%9B%9D%E5%85%89_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/WNk
- 社区停车服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%9B%9D%E5%85%89_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/093=deb
- 小区公共照明的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%9B%9D%E5%85%89_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/rli=719
- 物业服务沟通的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F%E5%92%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%9B%9D%E5%85%89_%E9%A1%BA%E4%B8%B0%E5%86%9C%E4%B8%9A?/IuX=7jt
- 人工智能科普的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/730
- 信息无障碍体验的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/qji
- 城市公共饮水中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/iui
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/361=tgo
- 校园节能行动的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/trj=144
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%8D%B3%E5%88%BB%E4%BA%B2%E5%AD%90?/4ko=swB
- 职业技能学习的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/675
- 社区宠物管理的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/rtb
- 基层健康档案的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/993
- 家庭用电安全的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/833=nhh
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/ojl=658
- 市民热线服务的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/3Rf=Cff
- 网络安全教育的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E5%A1%AB%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/269
- 机器学习入门的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E5%A1%AB%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/iuk
- 社区托育服务的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E5%A1%AB%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/A2Q
- 社区便民集市的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E5%A1%AB%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/283=igy
- 文化场馆预约的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E5%A1%AB%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/ddi=257
- 公益活动组织的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81%E5%A1%AB%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/mBm=B3p
- 课后服务体验的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%8040%E4%B8%87%E6%88%90%E5%8A%9F%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%BC%E8%89%BA?/936
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%8040%E4%B8%87%E6%88%90%E5%8A%9F%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%BC%E8%89%BA?/sza
- 科学观察活动的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%8040%E4%B8%87%E6%88%90%E5%8A%9F%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%BC%E8%89%BA?/uFq
- 乡村公共服务的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%8040%E4%B8%87%E6%88%90%E5%8A%9F%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%BC%E8%89%BA?/447=pwm
- 公共空间导览的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%8040%E4%B8%87%E6%88%90%E5%8A%9F%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%BC%E8%89%BA?/pos=696
- 电动汽车充电的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%8040%E4%B8%87%E6%88%90%E5%8A%9F%E4%BA%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BB%BC%E8%89%BA?/6Na=K4m
- 青年志愿活动的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/940
- 城市生活服务的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/lua
- 城市步行环境的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/F7X
- 电动汽车充电的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/726=jcv
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/ycl=098
- 街区道路维护的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1QQ_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/WHk=fhn
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/848
- 绿色校园实践的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/zep
- 绿色出行服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/PWD
- 机器学习入门的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/847=fkn
- 乡村文化空间的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/puw=855
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/4ED=brk
- 农村环境治理的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%BE%85%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/610
- 节能家电使用的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%BE%85%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/klj
- 家庭安全提示的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%BE%85%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vjJ
- 城市文明出行的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%BE%85%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/759=hqv
- 城市步行友好的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%BE%85%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rpp=275
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%BE%85%E4%BA%BA%E5%9B%9E%E8%A1%80%E6%9C%80%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/BDd=tI0
- 物业服务沟通的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/867
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/fcy
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/1jv
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/768=avb
- 儿童户外活动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/lbn=882
- 绿色办公实践的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/Fwt=PXZ
- 读书会组织的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/751
- 个人数据管理的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/zmq
- 人工智能科普的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/YUP
- 校园节能行动的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/211=hrn
- 公共空间导览的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/quq=752
- 社区商业活力的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/Zdq=9tN
- 家庭急救准备的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/730
- 城市社区治理的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/sis
- 社区家校合作的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/hry
- 城市公共艺术的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/177=uwz
- 本地消费场景的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/mdx=637
- 科学观察活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E7%9A%84%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E7%89%B9%E7%A8%BF?/NQn=Edg
- 城市噪声观察的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/144
- 健康信息获取的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/rio
- 应急物资管理的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/AYk
- 城市公共空间的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/491=vjx
- 社区信息发布的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/aaq=961
- 城市基础设施的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/gep=DWL
- 儿童安全出行的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91PK%E6%8B%BE%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/368
- 生活服务数字化的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91PK%E6%8B%BE%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/wvo
- 线上阅读资源的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91PK%E6%8B%BE%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/zpT
- 运动安全知识的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91PK%E6%8B%BE%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/875=jat
- 乡村公共服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91PK%E6%8B%BE%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/psl=259
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91PK%E6%8B%BE%E5%85%A8%E5%A4%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E5%A4%A7?/c6I=nAe
- 基层医疗预约的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/452
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/ook
- 生活服务数字化的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/oQU
- 基层健康档案的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/933=zdy
- 城乡公共服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/sie=626
- 开放式学习空间的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%8D%83%E5%B8%86?/aEV=frU
- 食品配送体验的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/491
- 数字档案服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/llm
- 社区协商议事的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/6sC
- 社区停车服务的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/457=ecy
- 志愿服务平台的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/pzx=306
- 公共文化活动的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/2Qw=Xah
- 学校食育活动有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/047
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/lyx
- 社区心理支持的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/6Lt
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/135=bfv
- 公园休闲体验从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/fwr=051
- 地方戏曲体验的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/SIW=fzm
- 城市雨天出行的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%A0%B4%E8%A7%A3_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/862
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%A0%B4%E8%A7%A3_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/aqz
- 在线学习体验的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%A0%B4%E8%A7%A3_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/Bvp
- 社区宠物管理的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%A0%B4%E8%A7%A3_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/848=xbs
- 城市雨天出行的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%A0%B4%E8%A7%A3_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/oqc=288
- 社区知识分享的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E7%A0%B4%E8%A7%A3_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/lBR=VH5
- 数字公共文化的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E8%B6%8B%E5%8A%BF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/178
- 老旧小区改造的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E8%B6%8B%E5%8A%BF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/xnz
- 校园节能行动的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E8%B6%8B%E5%8A%BF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/BrE
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E8%B6%8B%E5%8A%BF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/564=kfl
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E8%B6%8B%E5%8A%BF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/awu=750
- 科学教育活动的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E8%B6%8B%E5%8A%BF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E8%A7%86%E9%A2%91?/fYl=NLB
- 城市绿色交通的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E6%BA%90%E7%A0%81_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/244
- 青少年职业启蒙的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BC%80%E5%A5%96%E6%BA%90%E7%A0%81_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/exg

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
