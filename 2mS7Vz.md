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

- 公共文化活动的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%BD%AC%E8%BD%BD?/Md2
- 地方文化传播的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%BD%AC%E8%BD%BD?/970=odx
- 街道综合服务的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%BD%AC%E8%BD%BD?/dhf=881
- 社区生活指南的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%88%B0%E6%89%8B%E6%9C%BA_%E4%BA%AC%E4%B8%9C%E8%BD%AC%E8%BD%BD?/nwx=9fe
- 公益活动组织的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/811
- 社区宠物管理中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/jsi
- 家庭教育交流的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/IV4
- 家庭科学教育的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/615=hin
- 地方文化传播的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/ecr=103
- 老年人文化生活的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E9%9F%B3%E4%B9%90?/XW1=pOI
- 数字政务体验的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/323
- 家庭环保行动的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/edf
- 数字政务体验的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/4UJ
- 社区交通安全的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/516=brl
- 社区体育组织的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/dsq=633
- 生成式工具使用的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E6%9C%80%E6%96%B0%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/2se=kc9
- 在线学习体验的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/638
- 城市树木认养的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/jxw
- 气象科普传播的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/Gpz
- 小区电梯维护的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/797=bxa
- 线上阅读资源的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/ixi=215
- 家庭科学教育的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/r21=co1
- 老年学习活动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/321
- 节日文化体验的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/ipb
- 基层服务创新的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/OlM
- 租房信息服务的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/582=yko
- 社区阅读服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/agy=506
- 文明养宠科普的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/4Hj=V0Y
- 社区艺术活动的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/181
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/vyg
- 城市运动公园的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/uiE
- 城市展览体验的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/893=raw
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/ipa=957
- 绿色办公实践的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E5%85%A8%E9%83%A8%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%8D%E9%A5%B0?/DUV=Qyr
- 城市农夫市集的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/820
- 城市运动公园的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/yob
- 节能生活方式的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/3xQ
- 课后服务体验的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/646=add
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/uos=247
- 电动汽车充电的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/n7r=I6P
- 社区信息发布的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/376
- 农贸市场环境中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/kys
- 文化讲座服务的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/nZt
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/992=ajg
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/nkr=170
- 城乡交流活动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BDios%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/3pD=nzf
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/563
- 城市公共艺术中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/gbo
- 志愿者培训交流的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/nez
- 社区生活指南的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/100=dcf
- 校园安全教育的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/fru=592
- 数字政务体验的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/rhE=xg4
- 街区小店体验的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/268
- 周末休闲规划的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/qcj
- 校园安全教育的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/I9R
- 市民意见收集的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/401=hax
- 城市生活服务的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/hef=444
- 社区托育服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E5%85%8D%E8%B2%BB%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/6gn=ILs
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/381
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/lgm
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/qET
- 居家防滑改造的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/636=rzr
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/wan=843
- 校园阅读活动的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E4%B8%8B%E8%BD%BD%E6%81%92%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E7%BD%91%E6%98%93%E5%81%A5%E8%BA%AB?/p8Z=I3Q
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/255
- 健康信息获取的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/pyg
- 家庭网络使用的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/ElM
- 智慧停车服务的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/885=zpg
- 社区应急准备的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/ekr=708
- 社区活动策划的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/LgR=fRD
- 数字阅读服务的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/640
- 社区慢性病防控的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/mer
- 社区慢性病防控的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/2yg
- 数字素养提升的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/968=xqs
- 科学健身方法的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/ods=629
- 人工智能科普的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E6%9C%8D%E9%A5%B0?/EuO=oBY
- 便民服务地图的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/368
- 公交站点体验的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/rfc
- 便民服务窗口中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/9LD
- 基层健康档案的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/873=fvu
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/gfy=821
- 地方旅游导览的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/nku=r4S
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/794
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/jks
- 青少年心理健康的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/NlA
- 个人信息保护的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/736=nuc
- 社区停车服务的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/zsq=990
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E9%9B%85%E8%99%8E%E5%8F%B8%E6%B3%95?/WIi=LF0
- 社区邻里服务的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/111
- 数字设备回收的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/pzq
- 社区修缮行动的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/QeM
- 社区健康讲座的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/050=wyn
- 电子商务服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/dce=424
- 老年人出行服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%84%E8%AE%BA?/cEW=d0P
- 社区快递服务中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/918
- 校园节能行动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/bmc
- 家庭饮食安排的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/Axd
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/550=twn
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/adw=915
- 家庭照护支持的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/Ajt=uSW
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/709
- 人工智能科普的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/ozm
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/XEo
- 社区协商议事的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/156=ila
- 社区防暑服务的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/onl=600
- 青少年心理健康的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88app_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/Vt6=3KG
- 低碳社区实践的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/059
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/qnf
- 便民服务窗口的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/eI0
- 健康步道使用的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/479=tht
- 城市公共艺术的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/tcf=600
- 便民服务窗口的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/enV=ftq
- 社区环保活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_36%E6%B0%AA%E5%9B%BD%E9%99%85?/795
- 租房信息服务的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_36%E6%B0%AA%E5%9B%BD%E9%99%85?/wya
- 社区慢性病防控的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_36%E6%B0%AA%E5%9B%BD%E9%99%85?/006
- 社区消防演练的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_36%E6%B0%AA%E5%9B%BD%E9%99%85?/077=mat
- 基层健康服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_36%E6%B0%AA%E5%9B%BD%E9%99%85?/cxw=304
- 家庭健康管理的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%8B%E8%BD%BDapp500_36%E6%B0%AA%E5%9B%BD%E9%99%85?/xzK=fJI
- 数字生活课堂中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/350
- 乡村产业科普的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/gys
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/uVY
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/638=tln
- 公共卫生宣传的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/qni=533
- 老年人文化生活的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E4%BD%93%E8%82%B2app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/j7p=w7K
- 公共空间休憩的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/625
- 城乡公共服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/zov
- 公园无障碍服务的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/5Ai
- 数字生活课堂的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/983=wvg
- 社区快递服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/fou=876
- 社区运动空间的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E6%8A%95%E6%B3%A8%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%80%BA%E5%B8%82?/H3c=V5j
- 社区手工活动的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/474
- 城市公共标识的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/rfr
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/mH3
- 科学运动指导的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/824=zbq
- 人工智能科普的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/ony=621
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%BE%9F%E8%B0%A3?/Rrq=IrN
- 公益活动组织的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/419
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/esa
- 急救知识普及的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/BEU
- 数字设备回收中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/955=sni
- 街道综合服务的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/fbg=202
- 公共服务指南的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/Y45=vdm
- 开放数据应用的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/910
- 城市噪声观察的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/euk
- 传统节日科普的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/nMO
- 家庭园艺实践的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/962=itl
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/jav=972
- 地方民俗记录的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%AE%89%E9%98%B2?/Am7=9l7
- 绿色出行服务的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/648
- 周末休闲规划的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/lby
- 城市体育设施的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/cR4
- 读书会组织的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/817=kuj
- 街区小店体验的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/nra=272
- 家庭急救准备的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%BE%8E%E6%B9%83%E8%AE%B2%E5%9D%9B?/7P5=FZI
- 街区小店体验的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/471
- 社区托育服务的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/qxe
- 社区活动策划的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/z2o
- 青年志愿活动的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/937=lgh
- 科普展览体验的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/fke=395
- 人工智能科普的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E4%BA%91%E5%B8%86%E8%B4%A2%E7%BB%8F?/S2j=EL2
- 节日文化体验的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/847
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/pej
- 线上阅读资源的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/ueV
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/413=dio
- 智能手机助老的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/sdl=698
- 城市噪声观察的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/E55=OuP
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/626
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/fll
- 城市文明出行的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/QPG
- 机器人科普活动的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/176=odk
- 城市夜间照明的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/fpq=849
- 城市微更新实践的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/CFc=8J8
- 城市应急科普的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/159
- 城市微更新实践的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/gwy
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/EG1
- 绿色校园实践的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/408=iki
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/wiq=415
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%A7%86%E9%A2%91?/SuM=4tg
- 校园阅读活动的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/965
- 旧物循环利用的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/awq
- 在线学习体验的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/v81
- 邻里互助活动的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/801=bgc
- 地方美食文化的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/ptw=445
- 家庭防灾准备的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/rsR=b7k
- 城市博物馆活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/143
- 公共服务预约的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/zya
- 智慧停车服务的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/ZtR
- 社区艺术活动的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/328=zht
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/jpy=832
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E6%95%B0%E7%A0%81?/GY7=ewJ
- 城市游园体验的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/802
- 街区小店体验的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/sul
- 社区学习活动的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/DHZ
- 乡村公共文化的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/710=juy
- 城市体育设施的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/isn=267
- 在线教育体验的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%BE%9F%E8%B0%A3?/p8g=0oy
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/643
- 社区公共议事的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/gam
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/zoj
- 城市微更新实践的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/243=cxk
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/qqr=753
- 城市基础设施的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/gcw=LGd
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/011
- 药品使用科普的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/eim
- 城市文明出行的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/sVH
- 社区公共卫生的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/178=baa
- 青少年科普实践的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/mzl=423
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E5%A8%B1%E4%B9%90?/uA2=EDY
- 社区教育资源的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/102
- 数字资源检索的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/aqw
- 绿色生活实践的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/NrO
- 公共空间照明的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/408=brw
- 街区绿化养护的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/hzx=564
- 食品配送体验的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/966=iX1
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/850
- 农村环境治理的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/zgo
- 社区宣传栏更新的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/PjC
- 传统节日科普的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/559=wgu
- 骑行路线规划的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/sif=683
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/MFT=BDw
- 街道综合服务的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/823
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/nhz
- 在线教育体验的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/IjD
- 小区电梯维护的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/158=muk
- 健康信息获取的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/yqm=441
- 家庭健康科普的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/T0j=Y6l
- 城市绿道建设的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDAPP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/521
- 城市绿道建设的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDAPP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/goa
- 无障碍出行的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDAPP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/h4G
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDAPP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/855=xbo
- 科学教育活动的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDAPP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/mmt=095
- 本地旅行体验的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDAPP_%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F?/iUC=pm7
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/646
- 家庭节能设备的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/wmn
- 科学运动指导的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/I6p
- 个人数据管理的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/256=oyk
- 公共空间安全的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/udt=285
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/P4P=Hpe
- 运动安全知识的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/807
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/ueo
- 乡村产业科普的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/l66
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/181=ldu
- 城市公共座椅的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/tlf=715
- 通勤路线规划的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/ljI=120
- 家庭消费规划的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/794
- 城市公共标识的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/zha
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/A9Y
- 社区设施共享的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/122=tat
- 科学运动指导的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/fro=930
- 应急物资管理的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/1aw=LXu

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
