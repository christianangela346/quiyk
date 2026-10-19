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

- 个人数据管理的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/urn
- 公园休闲体验中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/034=ttg
- 社区绿色空间的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/efy=714
- 社区公共餐饮的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BD%A9%E7%94%A8%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/0I2=NuH
- 数字支付体验的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/174
- 青少年科技社团的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/lcl
- 物业服务沟通的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/cQk
- 农产品消费体验的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/353=dnt
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/ntt=723
- 社区体育组织的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%88%86%E5%88%86%E5%BD%A9APP_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/QIk=800
- 老年数字阅读的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/714
- 社区科普课堂的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/tbz
- 旧物循环利用的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/SLs
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/969=fbt
- 科学运动指导的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/qqx=922
- 城市可持续生活的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%88%86%E5%88%86%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/Jwz=zTi
- 居家适老化改造的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/599
- 生成式工具使用的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/jso
- 青年职业探索的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/7qy
- 儿童友好空间的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/522=gpt
- 安全出行教育的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/kpk=576
- 传统节日科普的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/gxH=IDa
- 本地消费场景的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/740
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/rhd
- 健康步道使用的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/wJx
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/413=omk
- 绿色出行服务的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/bcn=558
- 城市可持续生活的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%96%B9%E6%B3%95_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/2cA=CBw
- 社区设施共享的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/357
- 乡村公共服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/exs
- 绿色生活实践的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/7iT
- 街区道路维护的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/566=ngx
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/eyl=410
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/b3U=yHY
- 儿童安全出行的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%9B%B4%E8%90%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/303
- 乡村公共服务的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%9B%B4%E8%90%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/tjw
- 社区故事采集的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%9B%B4%E8%90%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/2hP
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%9B%B4%E8%90%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/414=iad
- 绿色校园实践的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%9B%B4%E8%90%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/pyd=966
- 社区科普课堂的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%9B%B4%E8%90%A5%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/tga=oXx
- 家庭食品保存的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/253
- 社区公共议事的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/gzn
- 家庭网络使用的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/NJT
- 数字支付体验的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/897=sji
- 低碳社区实践的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/ndl=202
- 学校食育活动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%93%94%E5%93%A9%E6%97%85%E6%B8%B8?/dIM=hwV
- 绿色快递包装的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/428
- 城市公共空间的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/zos
- 社区知识分享的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/Hfv
- 公共交通接驳的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/281=hqk
- 老旧小区改造的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/zni=411
- 社区艺术活动的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E8%B5%84%E8%AE%AF?/Q88=nhg
- 基层健康服务的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/684
- 数字公共文化的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/vuc
- 全民阅读推广的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/1P3
- 社区家政服务的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/159=lwl
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/thb=412
- 非遗体验活动的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E5%81%A5%E8%BA%AB?/a85=nLx
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/892
- 公共设施维护的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/wun
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/LzH
- 职业技能学习的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/682=wcf
- 社区教育资源的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/pmf=716
- 邻里互助活动的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/yYq=qQU
- 公共服务沟通的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF?/986
- 节能生活方式的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF?/jvf
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF?/Cv6
- 读书会组织的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF?/648=gpi
- 小微企业服务的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF?/fal=418
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF?/7eZ=Xvl
- 公共设施维护的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/602
- 社区安全巡查的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/wua
- 儿童友好空间的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/Nue
- 本地消费场景的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/818=wjn
- 地方戏曲体验的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/kwy=950
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A5%A8?/Mur=Y2J
- 节气饮食文化中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E8%83%BD%E4%B8%8B%E8%BD%BD%E5%90%97_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/403
- 儿童安全出行的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E8%83%BD%E4%B8%8B%E8%BD%BD%E5%90%97_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/gwt
- 社区便利生活的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E8%83%BD%E4%B8%8B%E8%BD%BD%E5%90%97_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/odF
- 便民服务窗口的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E8%83%BD%E4%B8%8B%E8%BD%BD%E5%90%97_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/910=gnc
- 在线学习体验的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E8%83%BD%E4%B8%8B%E8%BD%BD%E5%90%97_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/yzf=448
- 数字创意课程的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E8%83%BD%E4%B8%8B%E8%BD%BD%E5%90%97_%E9%9B%85%E8%99%8E%E7%BB%BC%E8%89%BA?/tb0=Bz3
- 家庭安全提示的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/915
- 环境监测科普的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/onv
- 软件开发学习的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/FGt
- 图书馆活动策划的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/407=elm
- 公益活动组织的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/lna=206
- 基层健康档案的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/1r6=OHZ
- 城市噪声观察的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/861
- 乡村文化空间中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/nib
- 公共服务评价的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/5UH
- 数字设备回收的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/794=gon
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/dbj=021
- 城市文明出行的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E4%BD%93%E5%BD%A9%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%89%8B%E8%AE%B0?/Tta=bRr
- 无障碍信息设计的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/004
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/mxd
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/ZFS
- 数字创作工具的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/988=xis
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/twr=228
- 个人时间管理的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/XL4=JRH
- 公共设施维护的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/411
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/bdo
- 家庭安全提示的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/LgE
- 市民意见收集的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/248=rus
- 小区停车协商的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/iax=190
- 药品使用科普的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/TSg=CCs
- 社会体育指导的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/193
- 学校食育活动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dov
- 家庭阅读计划的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/s4e
- 在线教育体验的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/412=xqd
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/mql=445
- 社区设施共享的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E7%BD%91%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC%E5%8F%B7_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jNG=B2e
- 新能源出行的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/793
- 户外活动组织的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/cod
- 社区协商议事的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/wnz
- 无障碍出行的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/791=zpy
- 社区交通安全的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/ipa=326
- 户外活动组织的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/HLX=qUy
- 乡村公共文化的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/548
- 数字艺术创作的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/fey
- 乡村生活观察的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/EHY
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/934=jvs
- 志愿者培训交流的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/dnq=107
- 开源技术交流的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/uyt=glU
- 社区家校合作的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/644
- 家庭教育交流的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/bff
- 应急物资管理的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/ykw
- 在线教育体验的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/178=rcu
- 城市雨天出行的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/qac=401
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E8%99%8E%E6%89%91%E5%AE%9E%E5%BD%95?/BgP=lxX
- 公园休闲体验的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%88%B8%E5%95%86?/725
- 休闲运动入门的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%88%B8%E5%95%86?/wsu
- 骑行路线规划的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%88%B8%E5%95%86?/nSz
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%88%B8%E5%95%86?/305=qtf
- 数字档案服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%88%B8%E5%95%86?/ofx=228
- 农贸市场环境的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E6%B0%91%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E5%88%B8%E5%95%86?/61M=2G2
- 社区便民服务的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/581
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/pyk
- 城市共享单车的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/fsl
- 全民健身活动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/538=aeg
- 城市雨天出行的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/pra=601
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/426=c7R
- 社区安全巡查的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/603
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/jvc
- 信息无障碍体验的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/juY
- 城市文明实践的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/735=agd
- 骑行路线规划的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/wmx=315
- 公共服务指南的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/keM=Lie
- 社区垃圾分类的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/207
- 节日文化体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/mzn
- 儿童运动体验的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/urP
- 软件开发学习的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/939=gop
- 公共交通接驳的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/wtn=281
- 城市步行环境的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/V5Z=u2A
- 便民服务地图的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/209
- 青少年科技社团的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/mhr
- 家庭志愿活动的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/nrf
- 环境教育课程的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/033=bvt
- 城市住房服务中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/ixf=012
- 科技馆参观体验的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E7%BA%AA%E5%AE%9E?/Bn6=XGJ
- 公共交通接驳的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/888
- 校园安全教育的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/mbv
- 社区协商议事的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/dIz
- 社区运动空间的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/503=hjn
- 小区公共照明的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/qmj=755
- 公共设施维护的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%BA%AA%E5%AE%9E?/Fhb=aDT
- 老年友好服务的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/180
- 社区商业活力的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/xmr
- 校园安全教育的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/MP1
- 公共空间安全的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/522=nxs
- 城市公共标识的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/eqr=182
- 居家防滑改造的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/YM2=M1q
- 气象科普传播的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/464
- 无障碍出行的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/rwc
- 职业技能学习的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/Xzr
- 社区商业活力的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/913=zah
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/row=012
- 城市微更新实践的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852024_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/y8y=SIA
- 校园阅读活动的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/128
- 亲子阅读活动的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/mfw
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/L1l
- 城乡公共服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/824=don
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/euh=085
- 城市水环境观察的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/8r7=9gd
- 健康步道使用的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/765
- 社区知识分享的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/quc
- 科技馆参观体验的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/0k3
- 社区共享书架的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/629=ycm
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/mkt=214
- 应急物资管理的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/u8b=3sh
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/619
- 社区快递服务的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/nyn
- 家庭健康管理中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/n8k
- 公共空间休憩的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/874=kgy
- 城市文化路线的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/psx=686
- 科学运动指导的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%93%94%E5%93%A9%E6%95%B0%E7%A0%81?/KkG=lCO
- 社区科普课堂的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/641
- 社区设施共享中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/bxs
- 市民热线服务的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/sVX
- 光伏知识科普的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/797=btv
- 城乡公共服务中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/jep=728
- 本地消费场景的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%87%A4%E5%87%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%B6%88%E8%B4%B9?/pgO=ATA
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/964
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/khd
- 图书借阅体验的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/y8B
- 城市生活服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/088=oxm
- 基层服务创新的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/pkz=000
- 家庭理财科普的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/gLW=cCh
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/514
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/pbi
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/0NO
- 租房信息服务的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/127=ewg
- 社区知识分享的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/hwq=463
- 家庭园艺实践的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_2020%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/GZD=KZs
- 街区更新实践的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/662
- 社区老年食堂的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/hwc
- 地方文化传播的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/FrE
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/431=cpl
- 城市绿道建设的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/bko=689
- 社区手工活动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E6%B5%99%E6%B1%9F%E7%A6%8F%E5%BD%A9%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/O6d=ZYX
- 家庭照护支持的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/253
- 社区便民服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/xzr
- 市民热线服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/SUf
- 城市树木认养的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/583=cpd
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/idq=024
- 公共图书馆服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/53b=Yc8
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/365
- 街区更新实践中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/tdy
- 数字档案服务的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/K4H
- 邻里互助活动的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/878=gui
- 城市建设科普的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/zyq=799
- 老年人日常照护的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E7%BD%91%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/84A=iIv
- 日常摄影记录的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/981
- 乡村文化空间的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/qkf
- 智能家居应用的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/zzh
- 街区道路维护的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/054=slj
- 科技馆参观体验的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/ung=339
- 城市噪声观察的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/6Kr=hjL
- 城市建设科普中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/543
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/zev
- 学校体育活动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/ltd
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/233=gvz
- 社区教育资源的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/vyo=303
- 安全出行教育的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/ru0=yW1
- 城乡交流活动的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/303
- 休闲运动入门的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/hnh
- 城市文明出行的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/wns
- 社区便利生活的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/405=hje
- 家庭健康科普的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/bbm=200
- 老年数字阅读的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E5%8A%A8%E6%BC%AB?/5l3=T8n

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
