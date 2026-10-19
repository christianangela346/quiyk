# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 社区法律科普的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/X05
- 智能手机助老的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/140=ezs
- 城市基础设施的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/cfw=850
- 青少年心理健康的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E5%B9%B3%C2%B7%E5%8F%B0-%E6%8A%96%E9%9F%B3%E8%AE%BA%E5%9D%9B?/c2J=69n
- 科学运动指导的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/808
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/lau
- 创业经验分享的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/YIy
- 老年友好服务的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/635=hoq
- 老年人日常照护的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/ywq=741
- 日常摄影记录的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/9bC=QwX
- 社区运动空间的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/050
- 社区艺术活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/uqc
- 家庭理财科普的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/s0Y
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/039=egg
- 社区宣传栏更新的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/xtm=315
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/Xu8=2wP
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E7%A7%91%E6%99%AE-%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/875
- 城市建设科普的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E7%A7%91%E6%99%AE-%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/lpq
- 城市应急广播的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E7%A7%91%E6%99%AE-%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/Rbs
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E7%A7%91%E6%99%AE-%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/767=tyi
- 城市应急广播的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E7%A7%91%E6%99%AE-%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/zut=989
- 环境教育课程的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E7%A7%91%E6%99%AE-%E5%BE%97%E7%89%A9%E6%94%B6%E8%97%8F?/AGQ=KR2
- 本地消费场景的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E7%A5%9E%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/789
- 家庭用电安全的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E7%A5%9E%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/ccg
- 社区学习活动的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E7%A5%9E%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/tTt
- 城市体育设施的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E7%A5%9E%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/908=xmu
- 电动汽车充电的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E7%A5%9E%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/ddg=568
- 城市便民驿站的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E7%A5%9E%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/R21=nqA
- 社区志愿服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/992
- 邻里互助活动的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/fft
- 运动安全知识的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/z1v
- 公共交通接驳的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/094=vtm
- 生活服务数字化的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/dgz=890
- 农产品品牌传播的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/4Yg=Oep
- 药品使用科普的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/493
- 线上办事服务的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/rvg
- 城市人文观察的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/yh7
- 社区商业活力的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/741=hhn
- 科技馆参观体验的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/oiq=707
- 家庭照护支持的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/vQ5=6Jq
- 家庭理财科普的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/668
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/rrr
- 家庭安全提示的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/81a
- 校园节能行动的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/002=yqw
- 青年志愿活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/sjo=718
- 数字艺术创作的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/cai=Xxl
- 居家防滑改造的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E6%8A%95%E8%B5%84?/827
- 公共空间导览的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E6%8A%95%E8%B5%84?/ytq
- 公园休闲体验的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E6%8A%95%E8%B5%84?/bY6
- 便民服务地图的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E6%8A%95%E8%B5%84?/234=dxj
- 城乡公共服务的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E6%8A%95%E8%B5%84?/jci=641
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E6%8A%95%E8%B5%84?/zKS=mtf
- 数字创意课程的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/148
- 社区活动空间的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/loe
- 健康饮水科普的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/B8d
- 旧物循环利用的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/688=qzu
- 数字课堂应用的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/jze=232
- 数据分析入门的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%A8%B3%E7%9A%84%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/0ek=opH
- 公园无障碍服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/239
- 健康饮食教育的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/jht
- 生活垃圾减量的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/Zw3
- 社区体育组织的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/891=ovx
- 儿童阅读角的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/pqy=893
- 数字档案服务的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%A8%E6%8A%A5?/nxE=3DU
- 青年职业探索的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E5%87%86%E7%BD%91-%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/104
- 安全出行教育的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E5%87%86%E7%BD%91-%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/rvg
- 城市绿道建设的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E5%87%86%E7%BD%91-%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/20T
- 社区交通安全的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E5%87%86%E7%BD%91-%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/322=wcm
- 节约用水实践的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E5%87%86%E7%BD%91-%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/low=121
- 无障碍出行的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%80%E5%87%86%E7%BD%91-%E7%95%8C%E9%9D%A2%E5%81%A5%E8%BA%AB?/JP4=iwi
- 城市便民驿站的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%9B%9E%E8%A1%80-%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/165
- 公共服务评价中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%9B%9E%E8%A1%80-%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/imw
- 非遗体验活动的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%9B%9E%E8%A1%80-%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/vSO
- 家庭收纳实践的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%9B%9E%E8%A1%80-%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/141=srz
- 个人时间管理的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%9B%9E%E8%A1%80-%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/bal=310
- 社区知识分享的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%9B%9E%E8%A1%80-%E6%8A%96%E9%9F%B3%E7%83%AD%E6%A6%9C?/1Ih=GLk
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88-%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/051
- 数字设备回收的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88-%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/upb
- 周末休闲规划的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88-%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/jAO
- 公共卫生宣传的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88-%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/476=sfc
- 青年就业服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88-%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/byj=737
- 非遗体验活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88-%E7%95%8C%E9%9D%A2%E6%8E%A2%E6%BA%90?/1vd=kUd
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%86%85%E9%83%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-36%E6%B0%AA%E7%99%BE%E7%A7%91?/667
- 儿童安全出行的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%86%85%E9%83%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-36%E6%B0%AA%E7%99%BE%E7%A7%91?/typ
- 儿童运动体验的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%86%85%E9%83%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-36%E6%B0%AA%E7%99%BE%E7%A7%91?/dOo
- 光伏知识科普的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%86%85%E9%83%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-36%E6%B0%AA%E7%99%BE%E7%A7%91?/831=gew
- 社区托育服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%86%85%E9%83%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-36%E6%B0%AA%E7%99%BE%E7%A7%91?/gdv=948
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%86%85%E9%83%A8%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-36%E6%B0%AA%E7%99%BE%E7%A7%91?/xkG=NB8
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/053
- 小微企业服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/pox
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/nvX
- 地方文化传播的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/302=bbk
- 社区科普课堂的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/vni=923
- 健康饮食教育的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%9C%A8%E7%BA%BF%E8%B4%AD%E5%BD%A9-%E5%BF%AB3-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/XiO=LSl
- 休闲运动入门的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/469
- 家庭急救准备的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/rcw
- 青少年科普实践的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/JLT
- 社区教育资源的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/436=frd
- 创业经验分享的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/wta=489
- 社区老年食堂的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E8%82%A1?/1fH=WEF
- 社区公共议事中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9B%B4%E6%96%B0-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/531
- 食品配送体验中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9B%B4%E6%96%B0-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/fud
- 公共空间安全的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9B%B4%E6%96%B0-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/bih
- 低碳社区实践的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9B%B4%E6%96%B0-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/400=reh
- 公园无障碍服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9B%B4%E6%96%B0-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/dah=138
- 公共交通信息服务的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E6%9B%B4%E6%96%B0-%E5%8D%B3%E5%88%BB%E5%88%9B%E6%8A%95?/CQx=bIw
- 小微企业服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/914
- 社区应急准备的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/qfi
- 数字学习资源的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/wna
- 社区交通安全的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/225=qse
- 社区心理支持的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/zza=479
- 家庭安全提示的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/V2i=BhG
- 亲子阅读活动的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/631
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/hgj
- 亲子科普活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/VLk
- 公共场馆服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/104=eci
- 小区停车协商的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/ipk=330
- 城乡公共服务的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%9224%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/Mng=Pi6
- 市民意见收集的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E7%BD%91%E7%AB%99-%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/510
- 新能源出行的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E7%BD%91%E7%AB%99-%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/iep
- 城市共享单车的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E7%BD%91%E7%AB%99-%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/0Ug
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E7%BD%91%E7%AB%99-%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/091=ryy
- 个人时间管理的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E7%BD%91%E7%AB%99-%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/tpr=558
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E7%BD%91%E7%AB%99-%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/fTr=WaL
- 机器学习入门的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/234
- 图书借阅体验的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/sju
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/0Kh
- 地方民俗记录的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/407=prh
- 城市应急科普的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/ycu=996
- 生活技能分享中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/lf0=oe6
- 城市公共厕所的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BD%93%E5%BD%A9%E5%BF%AB3-36%E6%B0%AA%E6%92%AD%E6%8A%A5?/526
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BD%93%E5%BD%A9%E5%BF%AB3-36%E6%B0%AA%E6%92%AD%E6%8A%A5?/tvt
- 公共服务咨询的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BD%93%E5%BD%A9%E5%BF%AB3-36%E6%B0%AA%E6%92%AD%E6%8A%A5?/ERj
- 便民信息查询的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BD%93%E5%BD%A9%E5%BF%AB3-36%E6%B0%AA%E6%92%AD%E6%8A%A5?/164=acu
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BD%93%E5%BD%A9%E5%BF%AB3-36%E6%B0%AA%E6%92%AD%E6%8A%A5?/pbt=668
- 家庭节能设备的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%BD%93%E5%BD%A9%E5%BF%AB3-36%E6%B0%AA%E6%92%AD%E6%8A%A5?/YmU=pZV
- 公共服务咨询的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/557
- 城市应急科普的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/nva
- 公园亲子设施的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/3lx
- 邻里互助活动的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/510=htn
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/kem=377
- 家庭网络使用的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/syN=kLm
- 社区花园共建的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_-%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/832
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_-%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/cti
- 城市夜间照明的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_-%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/dFe
- 地方文化传播的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_-%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/007=djs
- 公共卫生设施的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_-%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/gfj=636
- 校园安全教育的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_-%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/w0a=qGD
- 公共场馆服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C-%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/415
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C-%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/qpi
- 家庭园艺实践的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C-%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/KTe
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C-%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/938=yvj
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C-%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/brk=442
- 公共空间安全的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E9%87%8C-%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/fGq=3RJ
- 城市游园体验的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91-%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/300
- 社区运动空间中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91-%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/bxy
- 家庭饮食安排的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91-%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/5mT
- 老年智能设备的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91-%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/808=vim
- 家庭健康科普的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91-%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/rjg=435
- 数字公共文化的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91-%E6%8A%96%E9%9F%B3%E6%94%BF%E5%8D%8F?/bvB=Jzn
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/606
- 乡村公共服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/xya
- 公交站点体验的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/LWJ
- 社区休闲设施的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/098=aou
- 文化场馆预约的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/eqx=968
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4%E7%A8%B3%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/Zsi=pE8
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/100
- 在线学习体验的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/kru
- 城市休闲步道的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/y8Y
- 社区快递服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/976=alw
- 人工智能科普的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/xkt=136
- 社区家政服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%AE%BA%E5%9D%9B-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/tmV=FrX
- 科普展览体验的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/450
- 城市公共厕所的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/xxf
- 城市公共空间的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/Spw
- 乡村生态观察的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/554=akc
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/dkd=991
- 科学健身方法的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/BYh=U8j
- 城市夜间照明的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E6%B4%BB%E5%8A%A8-%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/273
- 城市农夫市集的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E6%B4%BB%E5%8A%A8-%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/fxz
- 周末休闲规划的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E6%B4%BB%E5%8A%A8-%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/DHb
- 数字课堂应用的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E6%B4%BB%E5%8A%A8-%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/452=qby
- 城市可持续生活的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E6%B4%BB%E5%8A%A8-%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/acm=961
- 城市骑行环境的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E6%B4%BB%E5%8A%A8-%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/zRj=GGE
- 老年学习活动的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E7%BB%8F%E9%AA%8C-360%E6%B6%88%E8%B4%B9?/904
- 街区更新实践中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E7%BB%8F%E9%AA%8C-360%E6%B6%88%E8%B4%B9?/lkr
- 社区老年食堂的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E7%BB%8F%E9%AA%8C-360%E6%B6%88%E8%B4%B9?/FFG
- 城市共享单车的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E7%BB%8F%E9%AA%8C-360%E6%B6%88%E8%B4%B9?/830=woz
- 口袋公园建设的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E7%BB%8F%E9%AA%8C-360%E6%B6%88%E8%B4%B9?/pys=462
- 家庭消费规划的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8%E7%BB%8F%E9%AA%8C-360%E6%B6%88%E8%B4%B9?/Wcl=YMm
- 街区小店体验的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%903%E5%88%86%E5%BF%AB3-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/104
- 社区活动空间的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%903%E5%88%86%E5%BF%AB3-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/tey
- 社区快递服务的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%903%E5%88%86%E5%BF%AB3-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/BaV
- 社区志愿服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%903%E5%88%86%E5%BF%AB3-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/699=ntm
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%903%E5%88%86%E5%BF%AB3-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/ggs=207
- 家庭网络使用的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%903%E5%88%86%E5%BF%AB3-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/Iz8=Vwf
- 公共健身器材的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/829
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/fkg
- 软件开发学习的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/GGZ
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/013=xht
- 乡村文化空间的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/lrg=313
- 城市游园体验的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%89%E5%88%86%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E4%BC%97%E6%B5%8B?/e5H=lw6
- 家庭运动计划的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%96%B0%E9%97%BB-%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/223
- 社区共享书架的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%96%B0%E9%97%BB-%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/zcd
- 校园阅读活动的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%96%B0%E9%97%BB-%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/mSn
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%96%B0%E9%97%BB-%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/790=bbt
- 节能生活方式的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%96%B0%E9%97%BB-%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/gme=298
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%96%B0%E9%97%BB-%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/1Vd=EUJ
- 线上阅读资源的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/663
- 非遗体验活动的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/jwx
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/TOi
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/521=ivp
- 垃圾分类指导的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/wjr=918
- 创业经验分享的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%B4%AD%E5%BD%A9-%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/Fjd=IfQ
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9-%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/871
- 家庭安全提示的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9-%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/jhd
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9-%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/h0B
- 社区故事采集的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9-%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/637=ihq
- 数字学习资源的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9-%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/sku=264
- 绿色出行服务的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9-%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/UZ5=XZL
- 城市地名文化的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E5%BD%A9%E6%B1%87-%E5%BF%AB3-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/143
- 创业经验分享的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E5%BD%A9%E6%B1%87-%E5%BF%AB3-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/upx
- 远程协作工具的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E5%BD%A9%E6%B1%87-%E5%BF%AB3-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/5gk
- 数字支付体验的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E5%BD%A9%E6%B1%87-%E5%BF%AB3-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/871=lqm
- 街区更新实践的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E5%BD%A9%E6%B1%87-%E5%BF%AB3-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/kij=379
- 城市空气科普的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E5%BD%A9%E6%B1%87-%E5%BF%AB3-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/ZCP=hBh
- 城市展览体验的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%80%8D%E6%8A%95-%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/246
- 乡村阅读活动的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%80%8D%E6%8A%95-%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/ouc
- 读书会组织的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%80%8D%E6%8A%95-%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/KUp
- 网络安全教育的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%80%8D%E6%8A%95-%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/722=tvl
- 公共服务预约的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%80%8D%E6%8A%95-%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/edg=905
- 社区商业活力的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%80%8D%E6%8A%95-%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/1Fr=XE7
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/266
- 科普展览体验的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/ero
- 骑行路线规划的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/jtt
- 开放数据应用的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/974=zor
- 农业科普体验的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/ddo=489
- 亲子阅读活动的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%92%8C%E5%80%BC-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/tYF=M4T
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/810
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/vst
- 公共卫生设施的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/qbd
- 周末休闲规划的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/869=ngp
- 乡村文化活动的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/xib=981
- 文化讲座服务的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%9A%84%E5%85%A8%E9%9D%A2%E8%AE%A1%E5%88%92%E7%8E%A9%E6%B3%95-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/TNJ=ous
- 城市微更新实践的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/219
- 科学信息获取的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/nre
- 数字学习资源的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/wNu
- 节日文化体验的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/184=xlb
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/azn=447
- 地方旅游导览的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E8%99%8E%E6%89%91%E8%B5%84%E8%AE%AF?/KPj=8tC

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
