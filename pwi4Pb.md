# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 社区修缮行动中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%8D%81%E5%A4%A7%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/2bo
- 日常摄影记录中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%8D%81%E5%A4%A7%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/279=qnv
- 公共场所导视的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%8D%81%E5%A4%A7%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/hxh=448
- 在线学习体验的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E5%8D%81%E5%A4%A7%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%98%AF%E4%BB%80%E4%B9%88_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/vt0=Sb3
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E8%BE%93%E4%BA%86%E4%BB%A5%E5%90%8E%E6%88%91%E8%AF%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85?/793
- 个人信息保护的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E8%BE%93%E4%BA%86%E4%BB%A5%E5%90%8E%E6%88%91%E8%AF%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85?/onh
- 社区防暑服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E8%BE%93%E4%BA%86%E4%BB%A5%E5%90%8E%E6%88%91%E8%AF%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85?/M3P
- 农贸市场环境的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E8%BE%93%E4%BA%86%E4%BB%A5%E5%90%8E%E6%88%91%E8%AF%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85?/480=hku
- 节日文化体验的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E8%BE%93%E4%BA%86%E4%BB%A5%E5%90%8E%E6%88%91%E8%AF%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85?/hjs=306
- 老年人日常照护的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E8%BE%93%E4%BA%86%E4%BB%A5%E5%90%8E%E6%88%91%E8%AF%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85?/E61=mEF
- 在线学习体验的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%BD%9C%E5%BC%8A_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/395
- 青少年职业启蒙的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%BD%9C%E5%BC%8A_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/iyq
- 非遗体验活动的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%BD%9C%E5%BC%8A_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/tBb
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%BD%9C%E5%BC%8A_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/788=ngw
- 城市住房服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%BD%9C%E5%BC%8A_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/rag=594
- 地方民俗记录的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E4%BD%9C%E5%BC%8A_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/o04=1jC
- 公共服务评价有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BF%BD%E6%9D%80%E6%A8%A1%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/945
- 公共服务评价的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BF%BD%E6%9D%80%E6%A8%A1%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/sqp
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BF%BD%E6%9D%80%E6%A8%A1%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/U2H
- 街区道路维护的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BF%BD%E6%9D%80%E6%A8%A1%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/005=rzs
- 户外活动组织的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BF%BD%E6%9D%80%E6%A8%A1%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/hrv=784
- 乡村公共文化中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BF%BD%E6%9D%80%E6%A8%A1%E5%BC%8F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/mjF=3Rm
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E4%B8%89%E5%8D%81%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/548
- 城市游园体验的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E4%B8%89%E5%8D%81%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/pgb
- 城市噪声观察的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E4%B8%89%E5%8D%81%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/GKE
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E4%B8%89%E5%8D%81%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/771=fyo
- 城市农夫市集的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E4%B8%89%E5%8D%81%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/syh=369
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E4%B8%89%E5%8D%81%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E7%A4%BE%E8%AE%BA?/BUc=ZIJ
- 社区心理支持的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/374
- 城市水环境观察的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/xfk
- 无障碍信息设计的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/F0E
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/535=bdw
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/xyd=485
- 基层医疗预约的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E5%BF%85%E5%BA%94%E5%8E%86%E5%8F%B2?/lKk=Pdv
- 光伏知识科普中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%8510000%E6%AF%8F%E5%A4%A9%E4%B9%B0%E4%B8%A4%E6%B3%A8%E5%8C%85%E8%B5%A2_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/512
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%8510000%E6%AF%8F%E5%A4%A9%E4%B9%B0%E4%B8%A4%E6%B3%A8%E5%8C%85%E8%B5%A2_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/apa
- 农村环境治理的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%8510000%E6%AF%8F%E5%A4%A9%E4%B9%B0%E4%B8%A4%E6%B3%A8%E5%8C%85%E8%B5%A2_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/oin
- 城市便民驿站中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%8510000%E6%AF%8F%E5%A4%A9%E4%B9%B0%E4%B8%A4%E6%B3%A8%E5%8C%85%E8%B5%A2_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/430=zqa
- 周末休闲规划的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%8510000%E6%AF%8F%E5%A4%A9%E4%B9%B0%E4%B8%A4%E6%B3%A8%E5%8C%85%E8%B5%A2_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zst=600
- 租房信息服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%8510000%E6%AF%8F%E5%A4%A9%E4%B9%B0%E4%B8%A4%E6%B3%A8%E5%8C%85%E8%B5%A2_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/3YO=3pQ
- 数字设备回收的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%8B%8F%E5%B7%9E%E5%BF%AB%E7%BA%BF3%E5%8F%B7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/848
- 传统节日科普的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%8B%8F%E5%B7%9E%E5%BF%AB%E7%BA%BF3%E5%8F%B7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/ifk
- 街道综合服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%8B%8F%E5%B7%9E%E5%BF%AB%E7%BA%BF3%E5%8F%B7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/iGr
- 学校体育活动的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%8B%8F%E5%B7%9E%E5%BF%AB%E7%BA%BF3%E5%8F%B7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/948=pbh
- 数字便民地图的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%8B%8F%E5%B7%9E%E5%BF%AB%E7%BA%BF3%E5%8F%B7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/fny=386
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%8B%8F%E5%B7%9E%E5%BF%AB%E7%BA%BF3%E5%8F%B7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/C19=cqw
- 非遗体验活动的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/535
- 数字艺术创作的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/qgk
- 老年学习活动的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/3OJ
- 安全出行教育的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/577=uqo
- 社区运动空间的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/wfa=959
- 老年友好服务的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/1Ub=syz
- 农贸市场环境的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%BB%8A%E6%97%A5%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/250
- 乡村生态观察中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%BB%8A%E6%97%A5%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/clt
- 社区活动空间的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%BB%8A%E6%97%A5%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/fso
- 公园休闲体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%BB%8A%E6%97%A5%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/487=jls
- 数字设备回收的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%BB%8A%E6%97%A5%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/mls=564
- 公共服务指南的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E4%BB%8A%E6%97%A5%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/9Mz=nGa
- 街区小店体验的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/950
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/geb
- 气象科普传播的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/hGr
- 家庭教育交流的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/548=whq
- 社区防暑服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/ejw=285
- 儿童安全出行的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%AE%89%E5%8D%93%E7%89%88%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/78h=KWB
- 社区手工活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0app%E5%BD%A9%E7%A5%A8785%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/890
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0app%E5%BD%A9%E7%A5%A8785%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/cbs
- 青年志愿活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0app%E5%BD%A9%E7%A5%A8785%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/yvh
- 公共图书馆服务的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0app%E5%BD%A9%E7%A5%A8785%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/282=bar
- 图书馆数字服务的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0app%E5%BD%A9%E7%A5%A8785%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/cjw=923
- 职业技能学习的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0app%E5%BD%A9%E7%A5%A8785%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/eVY=FzX
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E9%BA%BB%E5%B0%86%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/060
- 创业经验分享的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E9%BA%BB%E5%B0%86%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/tcd
- 科学健身方法的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E9%BA%BB%E5%B0%86%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/tIG
- 社区庭院绿化的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E9%BA%BB%E5%B0%86%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/158=qrl
- 绿色消费选择的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E9%BA%BB%E5%B0%86%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/qek=963
- 城市社区治理的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E9%BA%BB%E5%B0%86%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/Qd3=XTT
- 通勤路线规划的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/103
- 社区休闲设施的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/toa
- 传统手工艺体验的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/0HA
- 家庭用电安全的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/921=ugw
- 数字公共文化的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/swd=833
- 个人信息保护的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B9%A6%E7%94%BB?/niS=fX1
- 安全出行教育的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%A4%9C%E5%A7%91%E5%A8%98_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/694
- 网络安全教育中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%A4%9C%E5%A7%91%E5%A8%98_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/bdi
- 青年志愿活动的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%A4%9C%E5%A7%91%E5%A8%98_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/xHK
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%A4%9C%E5%A7%91%E5%A8%98_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/792=ack
- 家庭节能设备的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%A4%9C%E5%A7%91%E5%A8%98_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/arl=914
- 口袋公园建设的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%A4%9C%E5%A7%91%E5%A8%98_%E8%99%8E%E6%89%91%E7%BE%8E%E8%82%A1?/MM0=hne
- 社区活动空间的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B6%88%E6%B6%88%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/120
- 青年志愿活动的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B6%88%E6%B6%88%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/pen
- 数字支付体验的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B6%88%E6%B6%88%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/UPu
- 城市适老服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B6%88%E6%B6%88%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/548=qht
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B6%88%E6%B6%88%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/dol=690
- 就业技能培训的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B6%88%E6%B6%88%E4%B9%90_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B6%88%E8%B4%B9?/ATL=Pag
- 社区托育服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%90%8D%E5%AA%9B_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/971
- 在线学习体验的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%90%8D%E5%AA%9B_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/vdv
- 社区宠物管理的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%90%8D%E5%AA%9B_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/4Sd
- 周末休闲规划的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%90%8D%E5%AA%9B_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/034=wdt
- 社区应急准备的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%90%8D%E5%AA%9B_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/lqo=859
- 青年就业服务的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%90%8D%E5%AA%9B_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/lhT=yuJ
- 社区慢性病防控的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B5%B7%E7%9B%97_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/942
- 公共设施使用的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B5%B7%E7%9B%97_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/xkm
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B5%B7%E7%9B%97_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/zx0
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B5%B7%E7%9B%97_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/122=uhf
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B5%B7%E7%9B%97_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/ocw=389
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%B5%B7%E7%9B%97_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/GYM=fbF
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/425
- 节日文化体验的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/ccg
- 劳动教育实践的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/IEX
- 家庭教育交流的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/408=zzm
- 公共交通信息服务的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/sgi=539
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8Capp%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/02Q=5je
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%89%91%E9%B1%BC%E8%B5%A2%E9%92%B1%E6%8F%90%E7%8E%B0%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/961
- 城市绿道建设的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%89%91%E9%B1%BC%E8%B5%A2%E9%92%B1%E6%8F%90%E7%8E%B0%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/znu
- 城市体育设施的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%89%91%E9%B1%BC%E8%B5%A2%E9%92%B1%E6%8F%90%E7%8E%B0%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/YVz
- 物业服务沟通中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%89%91%E9%B1%BC%E8%B5%A2%E9%92%B1%E6%8F%90%E7%8E%B0%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/911=nwa
- 地方旅游导览的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%89%91%E9%B1%BC%E8%B5%A2%E9%92%B1%E6%8F%90%E7%8E%B0%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/iav=581
- 家庭收纳实践的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E6%89%91%E9%B1%BC%E8%B5%A2%E9%92%B1%E6%8F%90%E7%8E%B0%E6%AD%A3%E7%89%88_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/OSA=t3O
- 乡村生态观察的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/434
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/atz
- 健康饮食教育的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/otH
- 药品使用科普的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/691=lgc
- 环境教育课程的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/uda=931
- 社区艺术活动的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E8%B5%8C%E9%92%B1%E7%89%9B%E7%89%9B_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/eG8=HO2
- 城市噪声观察的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/840
- 家庭健康管理的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/usj
- 家庭网络使用的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/Vo6
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/602=omk
- 环境教育课程的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/hqf=796
- 基层健康档案的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/Y2R=W2f
- 城市便民驿站的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A610%E4%B8%AA%E4%B9%B09%E4%B8%AA_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/872
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A610%E4%B8%AA%E4%B9%B09%E4%B8%AA_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/oup
- 城市公共自行车的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A610%E4%B8%AA%E4%B9%B09%E4%B8%AA_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/aF8
- 老年学习活动的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A610%E4%B8%AA%E4%B9%B09%E4%B8%AA_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/731=ksh
- 急救知识普及的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A610%E4%B8%AA%E4%B9%B09%E4%B8%AA_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/qak=039
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A610%E4%B8%AA%E4%B9%B09%E4%B8%AA_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/AkY=crE
- 市民热线服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%BA%E5%95%A5%E4%B8%80%E7%9B%B4%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/262
- 社区邻里服务的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%BA%E5%95%A5%E4%B8%80%E7%9B%B4%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/lje
- 城市休闲步道的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%BA%E5%95%A5%E4%B8%80%E7%9B%B4%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/GtG
- 公共场所导视的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%BA%E5%95%A5%E4%B8%80%E7%9B%B4%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/152=dws
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%BA%E5%95%A5%E4%B8%80%E7%9B%B4%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/wgm=324
- 青少年科普实践的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%BA%E5%95%A5%E4%B8%80%E7%9B%B4%E8%83%BD%E8%B5%A2_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/jYb=mMt
- 数字阅读服务的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A67%E7%A0%81%E4%B8%BA%E5%95%A5%E4%BC%9A%E8%BE%93_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/669
- 健康信息获取的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A67%E7%A0%81%E4%B8%BA%E5%95%A5%E4%BC%9A%E8%BE%93_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/kva
- 绿色办公实践的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A67%E7%A0%81%E4%B8%BA%E5%95%A5%E4%BC%9A%E8%BE%93_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/I9b
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A67%E7%A0%81%E4%B8%BA%E5%95%A5%E4%BC%9A%E8%BE%93_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/514=hba
- 终身学习资源的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A67%E7%A0%81%E4%B8%BA%E5%95%A5%E4%BC%9A%E8%BE%93_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/imm=929
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A67%E7%A0%81%E4%B8%BA%E5%95%A5%E4%BC%9A%E8%BE%93_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/EyO=LTM
- 社区应急准备的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E5%B0%B1%E6%98%AF%E8%AF%88%E9%AA%97_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/542
- 家庭安全提示的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E5%B0%B1%E6%98%AF%E8%AF%88%E9%AA%97_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/qsf
- 家庭志愿活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E5%B0%B1%E6%98%AF%E8%AF%88%E9%AA%97_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/PTm
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E5%B0%B1%E6%98%AF%E8%AF%88%E9%AA%97_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/340=nuj
- 家庭养老规划的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E5%B0%B1%E6%98%AF%E8%AF%88%E9%AA%97_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/fho=864
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E5%B0%B1%E6%98%AF%E8%AF%88%E9%AA%97_%E9%9B%85%E8%99%8E%E8%B5%84%E8%AE%AF?/iJK=eSI
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%8A%8A%E4%B8%8D%E4%B8%AD_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/686
- 公共卫生宣传的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%8A%8A%E4%B8%8D%E4%B8%AD_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/sxp
- 社区花园共建的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%8A%8A%E4%B8%8D%E4%B8%AD_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/5Eb
- 公共卫生设施中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%8A%8A%E4%B8%8D%E4%B8%AD_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/049=uhp
- 气象科普传播的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%8A%8A%E4%B8%8D%E4%B8%AD_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/cxs=439
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E4%B8%80%E6%8A%8A%E4%B8%8D%E4%B8%AD_%E8%B1%86%E7%93%A3%E6%98%9F%E5%BA%A7?/yDO=jlS
- 城市空气科普的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E5%A5%97%E8%B7%AF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/930
- 公共空间照明的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E5%A5%97%E8%B7%AF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/wrj
- 急救知识普及的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E5%A5%97%E8%B7%AF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/nQn
- 家庭照护支持的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E5%A5%97%E8%B7%AF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/341=fyz
- 绿色出行服务的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E5%A5%97%E8%B7%AF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/kky=238
- 老年友好服务的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E5%A5%97%E8%B7%AF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E6%B2%BB?/TAs=u8s
- 家庭健康管理的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%8E%A7%E5%88%B6%E6%93%8D%E4%BD%9C_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/651
- 口袋公园建设的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%8E%A7%E5%88%B6%E6%93%8D%E4%BD%9C_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/lqc
- 公交无障碍服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%8E%A7%E5%88%B6%E6%93%8D%E4%BD%9C_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/Ce1
- 家庭网络使用的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%8E%A7%E5%88%B6%E6%93%8D%E4%BD%9C_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/208=cbh
- 社区健康讲座的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%8E%A7%E5%88%B6%E6%93%8D%E4%BD%9C_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/yah=496
- 就业技能培训的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%8E%A7%E5%88%B6%E6%93%8D%E4%BD%9C_%E9%87%91%E5%8D%9A%E8%B4%A2%E7%BB%8F?/PLL=bbp
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E7%A9%BA%E5%88%B6%E5%9B%BE%E7%89%87_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/513
- 学校食育活动的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E7%A9%BA%E5%88%B6%E5%9B%BE%E7%89%87_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/zih
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E7%A9%BA%E5%88%B6%E5%9B%BE%E7%89%87_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/0Rj
- 城市宠物友好空间的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E7%A9%BA%E5%88%B6%E5%9B%BE%E7%89%87_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/330=hmn
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E7%A9%BA%E5%88%B6%E5%9B%BE%E7%89%87_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/acg=586
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E7%A9%BA%E5%88%B6%E5%9B%BE%E7%89%87_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/MT6=8KM
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/457
- 节假日出行安排的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/esf
- 绿色校园实践的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/ngZ
- 公共空间安全的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/820=cdu
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/jzc=093
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%93%94%E5%93%A9%E6%94%B6%E8%97%8F?/vrD=ilf
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%8620%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/698
- 家庭急救准备的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%8620%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/ayx
- 老年人出行服务的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%8620%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/r6h
- 基层健康服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%8620%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/314=jms
- 课后服务体验的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%8620%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/wwm=783
- 家庭急救准备的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E8%B5%8C%E8%B5%9B%E8%BD%A6%E8%BE%93%E4%BA%8620%E4%B8%87%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/kLz=2oh
- 城市适老服务的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%98%9B_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/672
- 社区快递服务的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%98%9B_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/iwd
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%98%9B_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/p66
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%98%9B_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/293=bzm
- 城市公共厕所的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%98%9B_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/qqk=627
- 城市博物馆活动的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%98%9B_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/1dT=Pha
- 学校食育活动的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/348
- 地方美食文化的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/pnx
- 数字艺术创作的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/3Dd
- 非遗课堂体验的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/067=hdp
- 城市生活服务的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/wkv=281
- 城市展览体验的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/LdF=U6q
- 青少年科技社团的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E5%88%B0%E7%8E%A9%E5%AE%B6%E7%9A%84_36%E6%B0%AA%E9%A3%9F%E5%93%81?/326
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E5%88%B0%E7%8E%A9%E5%AE%B6%E7%9A%84_36%E6%B0%AA%E9%A3%9F%E5%93%81?/nrv
- 社区故事采集的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E5%88%B0%E7%8E%A9%E5%AE%B6%E7%9A%84_36%E6%B0%AA%E9%A3%9F%E5%93%81?/U3q
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E5%88%B0%E7%8E%A9%E5%AE%B6%E7%9A%84_36%E6%B0%AA%E9%A3%9F%E5%93%81?/647=sai
- 青少年心理健康的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E5%88%B0%E7%8E%A9%E5%AE%B6%E7%9A%84_36%E6%B0%AA%E9%A3%9F%E5%93%81?/gjp=274
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E5%88%B0%E7%8E%A9%E5%AE%B6%E7%9A%84_36%E6%B0%AA%E9%A3%9F%E5%93%81?/IiV=kWh
- 线上办事服务的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E9%92%B1%E5%88%B9%E4%B8%8D%E4%BD%8F%E8%BD%A6__%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/814
- 家庭健康管理的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E9%92%B1%E5%88%B9%E4%B8%8D%E4%BD%8F%E8%BD%A6__%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/meo
- 街区绿化养护的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E9%92%B1%E5%88%B9%E4%B8%8D%E4%BD%8F%E8%BD%A6__%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/Mp5
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E9%92%B1%E5%88%B9%E4%B8%8D%E4%BD%8F%E8%BD%A6__%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/352=skk
- 社区活动报名的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E9%92%B1%E5%88%B9%E4%B8%8D%E4%BD%8F%E8%BD%A6__%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/drd=712
- 家庭食品保存的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E9%92%B1%E5%88%B9%E4%B8%8D%E4%BD%8F%E8%BD%A6__%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/1eM=43Q
- 数字政务体验的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E6%9C%89%E6%B2%A1%E6%9C%89%E5%B0%B1%E4%BC%9A%E8%B5%A2_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/178
- 学校体育活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E6%9C%89%E6%B2%A1%E6%9C%89%E5%B0%B1%E4%BC%9A%E8%B5%A2_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/ffz
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E6%9C%89%E6%B2%A1%E6%9C%89%E5%B0%B1%E4%BC%9A%E8%B5%A2_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/Fft
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E6%9C%89%E6%B2%A1%E6%9C%89%E5%B0%B1%E4%BC%9A%E8%B5%A2_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/826=hhq
- 家庭节能实践的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E6%9C%89%E6%B2%A1%E6%9C%89%E5%B0%B1%E4%BC%9A%E8%B5%A2_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/jmb=430
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E7%BB%9C%E8%B5%9B%E8%BD%A6%E6%9C%89%E6%B2%A1%E6%9C%89%E5%B0%B1%E4%BC%9A%E8%B5%A2_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/e8W=NZC
- 青少年心理健康的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8F%82%E4%B8%8E%E7%BD%91%E7%BB%9C%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%A4%84%E7%BD%9A_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/566
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8F%82%E4%B8%8E%E7%BD%91%E7%BB%9C%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%A4%84%E7%BD%9A_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/exe
- 城市生活记录的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8F%82%E4%B8%8E%E7%BD%91%E7%BB%9C%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%A4%84%E7%BD%9A_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/h1q
- 课后服务体验的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8F%82%E4%B8%8E%E7%BD%91%E7%BB%9C%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%A4%84%E7%BD%9A_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/366=kuo
- 数字素养提升的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8F%82%E4%B8%8E%E7%BD%91%E7%BB%9C%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%A4%84%E7%BD%9A_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/ven=356
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8F%82%E4%B8%8E%E7%BD%91%E7%BB%9C%E4%B8%8A%E8%B5%9B%E8%BD%A6%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E5%A4%84%E7%BD%9A_%E6%90%9C%E7%8B%97%E5%81%A5%E5%BA%B7?/WFh=XJX
- 公益活动组织的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/354
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/rsw
- 社区托育服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/4bu
- 社区养老服务的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/662=zao
- 节能家电使用的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/bwd=409
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9C%B0%E4%BA%A7?/HWZ=bs9
- 城市便民驿站的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%BB%84%E9%87%91%E7%BD%91%E7%AB%99app%E5%85%8D%E8%B4%B9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/553
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%BB%84%E9%87%91%E7%BD%91%E7%AB%99app%E5%85%8D%E8%B4%B9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/jpy
- 志愿者培训交流的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%BB%84%E9%87%91%E7%BD%91%E7%AB%99app%E5%85%8D%E8%B4%B9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/jFe
- 环境教育课程的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%BB%84%E9%87%91%E7%BD%91%E7%AB%99app%E5%85%8D%E8%B4%B9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/449=uaw
- 公共设施维护的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%BB%84%E9%87%91%E7%BD%91%E7%AB%99app%E5%85%8D%E8%B4%B9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/ahn=493
- 健康信息获取的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E9%BB%84%E9%87%91%E7%BD%91%E7%AB%99app%E5%85%8D%E8%B4%B9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/hzz=pze
- 绿色建筑理念的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/172
- 家庭网络使用的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/hji
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/uPq
- 智慧停车服务的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/928=ftm
- 老年人日常照护的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/uuo=321
- 地方民俗记录的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%99%E8%82%B2?/Da3=oKb
- 城市运动公园的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/604
- 电子商务服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/jht
- 家庭用电安全的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/WBC
- 线上办事服务的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/882=bdv
- 环境监测科普的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/hxo=656
- 城市骑行环境的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/gVt=VRp

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
