# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 儿童阅读角的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%B0%B1%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/2jL
- 社区学习活动的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%B0%B1%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/686=luf
- 家庭安全提示的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%B0%B1%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/bla=471
- 乡村阅读空间的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%B0%B1%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/phe=tuB
- 社区便利生活的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84-%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/251
- 家庭用电安全的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84-%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/mww
- 数字生活课堂的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84-%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/U5i
- 社区手工活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84-%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/468=rkh
- 城市雨天出行的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84-%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/uxs=396
- 无障碍信息设计的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E6%AD%A3%E8%A7%84-%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/L5O=3zI
- 全民健身活动的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B4%A2%E5%AF%8C%E4%B9%90%E8%B5%9Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/384
- 家庭用电安全的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B4%A2%E5%AF%8C%E4%B9%90%E8%B5%9Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/ate
- 城乡交流活动的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B4%A2%E5%AF%8C%E4%B9%90%E8%B5%9Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/UV3
- 公共空间休憩的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B4%A2%E5%AF%8C%E4%B9%90%E8%B5%9Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/531=yua
- 青少年编程学习的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B4%A2%E5%AF%8C%E4%B9%90%E8%B5%9Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/zza=180
- 家庭志愿活动的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E8%B4%A2%E5%AF%8C%E4%B9%90%E8%B5%9Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/45Y=2iv
- 儿童阅读角的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%8C%A3%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%80%E5%A4%A9%E8%B5%9A100%E5%BE%AE%E4%BF%A1%E6%8F%90%E7%8E%B0-%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/420
- 基层健康服务的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%8C%A3%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%80%E5%A4%A9%E8%B5%9A100%E5%BE%AE%E4%BF%A1%E6%8F%90%E7%8E%B0-%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/atu
- 数字政务体验的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%8C%A3%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%80%E5%A4%A9%E8%B5%9A100%E5%BE%AE%E4%BF%A1%E6%8F%90%E7%8E%B0-%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/Tm7
- 社区便利生活的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%8C%A3%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%80%E5%A4%A9%E8%B5%9A100%E5%BE%AE%E4%BF%A1%E6%8F%90%E7%8E%B0-%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/855=kmt
- 社区停车服务的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%8C%A3%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%80%E5%A4%A9%E8%B5%9A100%E5%BE%AE%E4%BF%A1%E6%8F%90%E7%8E%B0-%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/noe=436
- 城乡交通衔接的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%8C%A3%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%80%E5%A4%A9%E8%B5%9A100%E5%BE%AE%E4%BF%A1%E6%8F%90%E7%8E%B0-%E5%8D%B3%E5%88%BB%E8%88%86%E6%83%85?/PkM=2An
- 基层健康服务的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/584
- 城市公共自行车的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/osy
- 社区互助网络的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/d2D
- 公共空间安全的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/699=vxg
- 网络安全教育的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/ors=238
- 节约用水实践的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/02B=CCe
- 老年学习活动的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9-%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/446
- 读书会组织的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9-%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/ecz
- 公共服务沟通的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9-%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/MBY
- 小区公共照明的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9-%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/733=ldb
- 城市农夫市集的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9-%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/nuc=181
- 非遗体验活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9-%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/3xw=lSw
- 社区家校合作的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%BE%88%E5%A4%9A%E4%BA%BA%E5%8F%91%E5%B1%95%E4%B8%8B%E7%BA%BF%E5%B7%B2%E5%9B%9E%E6%9C%AC%E6%98%AF%E7%9C%9F%E5%AE%9E%E5%90%97-%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/224
- 老年数字阅读的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%BE%88%E5%A4%9A%E4%BA%BA%E5%8F%91%E5%B1%95%E4%B8%8B%E7%BA%BF%E5%B7%B2%E5%9B%9E%E6%9C%AC%E6%98%AF%E7%9C%9F%E5%AE%9E%E5%90%97-%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/oib
- 生活垃圾回收的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%BE%88%E5%A4%9A%E4%BA%BA%E5%8F%91%E5%B1%95%E4%B8%8B%E7%BA%BF%E5%B7%B2%E5%9B%9E%E6%9C%AC%E6%98%AF%E7%9C%9F%E5%AE%9E%E5%90%97-%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/RM7
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%BE%88%E5%A4%9A%E4%BA%BA%E5%8F%91%E5%B1%95%E4%B8%8B%E7%BA%BF%E5%B7%B2%E5%9B%9E%E6%9C%AC%E6%98%AF%E7%9C%9F%E5%AE%9E%E5%90%97-%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/224=bnc
- 非遗课堂体验的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%BE%88%E5%A4%9A%E4%BA%BA%E5%8F%91%E5%B1%95%E4%B8%8B%E7%BA%BF%E5%B7%B2%E5%9B%9E%E6%9C%AC%E6%98%AF%E7%9C%9F%E5%AE%9E%E5%90%97-%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/txf=490
- 药品使用科普的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%BE%88%E5%A4%9A%E4%BA%BA%E5%8F%91%E5%B1%95%E4%B8%8B%E7%BA%BF%E5%B7%B2%E5%9B%9E%E6%9C%AC%E6%98%AF%E7%9C%9F%E5%AE%9E%E5%90%97-%E7%9F%A5%E4%B9%8E%E9%80%9A%E4%BF%A1?/bbT=G0X
- 地方民俗记录的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%2C%E6%98%AF%E8%B5%8C%E5%8D%9A%E5%90%97-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/537
- 绿色出行服务的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%2C%E6%98%AF%E8%B5%8C%E5%8D%9A%E5%90%97-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/cru
- 低碳社区实践的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%2C%E6%98%AF%E8%B5%8C%E5%8D%9A%E5%90%97-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/NOw
- 社区邻里服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%2C%E6%98%AF%E8%B5%8C%E5%8D%9A%E5%90%97-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/132=fkt
- 机器人科普活动的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%2C%E6%98%AF%E8%B5%8C%E5%8D%9A%E5%90%97-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/uvx=210
- 公共卫生宣传的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%2C%E6%98%AF%E8%B5%8C%E5%8D%9A%E5%90%97-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/OO9=pUN
- 城市文明实践的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E6%98%AF%E6%B4%97%E9%92%B1%E5%90%97-%E8%85%BE%E8%AE%AF%E4%BA%BA%E7%89%A9?/160
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E6%98%AF%E6%B4%97%E9%92%B1%E5%90%97-%E8%85%BE%E8%AE%AF%E4%BA%BA%E7%89%A9?/soc
- 社区文化传播的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E6%98%AF%E6%B4%97%E9%92%B1%E5%90%97-%E8%85%BE%E8%AE%AF%E4%BA%BA%E7%89%A9?/3Af
- 街区道路维护的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E6%98%AF%E6%B4%97%E9%92%B1%E5%90%97-%E8%85%BE%E8%AE%AF%E4%BA%BA%E7%89%A9?/693=saa
- 智能家居应用的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E6%98%AF%E6%B4%97%E9%92%B1%E5%90%97-%E8%85%BE%E8%AE%AF%E4%BA%BA%E7%89%A9?/ltq=696
- 灵活就业交流的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E6%98%AF%E6%B4%97%E9%92%B1%E5%90%97-%E8%85%BE%E8%AE%AF%E4%BA%BA%E7%89%A9?/mLf=FT9
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6-%E8%A7%86%E9%A2%91-%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/245
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6-%E8%A7%86%E9%A2%91-%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/cno
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6-%E8%A7%86%E9%A2%91-%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/TDf
- 社区文化传播从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6-%E8%A7%86%E9%A2%91-%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/109=rkf
- 城市文化路线的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6-%E8%A7%86%E9%A2%91-%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/jng=074
- 数字便民地图的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6-%E8%A7%86%E9%A2%91-%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/WjM=JNB
- 城市基础设施的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%B1%9E%E4%BA%8E%E8%B5%8C%E5%8D%9A%E5%90%97-%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/552
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%B1%9E%E4%BA%8E%E8%B5%8C%E5%8D%9A%E5%90%97-%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/nqf
- 灵活就业交流的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%B1%9E%E4%BA%8E%E8%B5%8C%E5%8D%9A%E5%90%97-%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/Isd
- 社区法律科普中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%B1%9E%E4%BA%8E%E8%B5%8C%E5%8D%9A%E5%90%97-%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/009=llr
- 社区停车服务的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%B1%9E%E4%BA%8E%E8%B5%8C%E5%8D%9A%E5%90%97-%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/nsr=379
- 节约用水实践的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6%E5%B1%9E%E4%BA%8E%E8%B5%8C%E5%8D%9A%E5%90%97-%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/QQV=V5i
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A4%B4%E5%85%A51%E4%B8%87%E5%85%83%E6%AF%8F%E5%A4%A9%E6%8C%A3200-%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/719
- 城市骑行环境的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A4%B4%E5%85%A51%E4%B8%87%E5%85%83%E6%AF%8F%E5%A4%A9%E6%8C%A3200-%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/hsu
- 传统节日科普的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A4%B4%E5%85%A51%E4%B8%87%E5%85%83%E6%AF%8F%E5%A4%A9%E6%8C%A3200-%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/dNo
- 乡村公共文化的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A4%B4%E5%85%A51%E4%B8%87%E5%85%83%E6%AF%8F%E5%A4%A9%E6%8C%A3200-%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/351=cqb
- 城市绿色交通的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A4%B4%E5%85%A51%E4%B8%87%E5%85%83%E6%AF%8F%E5%A4%A9%E6%8C%A3200-%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/bll=910
- 基层健康档案的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8B%89%E4%BA%BA%E5%A4%B4%E5%85%A51%E4%B8%87%E5%85%83%E6%AF%8F%E5%A4%A9%E6%8C%A3200-%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/2Ar=Oid
- 物业服务沟通的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%88%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%B9%B4%E8%B5%A2%E4%BA%8640w%E6%94%B6%E6%89%8B%E4%BA%86-%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/664
- 家庭教育交流的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%88%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%B9%B4%E8%B5%A2%E4%BA%8640w%E6%94%B6%E6%89%8B%E4%BA%86-%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/tia
- 城市便民驿站的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%88%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%B9%B4%E8%B5%A2%E4%BA%8640w%E6%94%B6%E6%89%8B%E4%BA%86-%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/eyD
- 社区停车服务的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%88%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%B9%B4%E8%B5%A2%E4%BA%8640w%E6%94%B6%E6%89%8B%E4%BA%86-%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/554=yfu
- 数字学习资源的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%88%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%B9%B4%E8%B5%A2%E4%BA%8640w%E6%94%B6%E6%89%8B%E4%BA%86-%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/boi=722
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%88%91%E7%BD%91%E8%B5%8C%E4%B8%80%E5%B9%B4%E8%B5%A2%E4%BA%8640w%E6%94%B6%E6%89%8B%E4%BA%86-%E8%84%89%E8%84%89%E5%9B%AD%E8%89%BA?/sUy=FXQ
- 乡村产业科普的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E4%B8%80%E5%A4%A9%E8%B5%A2700%E5%9D%9A%E6%8C%81%E4%B8%80%E5%B9%B4-%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/787
- 数字课堂应用的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E4%B8%80%E5%A4%A9%E8%B5%A2700%E5%9D%9A%E6%8C%81%E4%B8%80%E5%B9%B4-%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/vwr
- 科普展览体验的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E4%B8%80%E5%A4%A9%E8%B5%A2700%E5%9D%9A%E6%8C%81%E4%B8%80%E5%B9%B4-%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/U0h
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E4%B8%80%E5%A4%A9%E8%B5%A2700%E5%9D%9A%E6%8C%81%E4%B8%80%E5%B9%B4-%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/690=yqy
- 社区生活指南的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E4%B8%80%E5%A4%A9%E8%B5%A2700%E5%9D%9A%E6%8C%81%E4%B8%80%E5%B9%B4-%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/cjf=890
- 社区休闲设施的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E4%B8%80%E5%A4%A9%E8%B5%A2700%E5%9D%9A%E6%8C%81%E4%B8%80%E5%B9%B4-%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/pvI=fnw
- 街道综合服务的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/404
- 社区体育组织的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/oqa
- 口袋公园建设的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/jKz
- 亲子科普活动中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/377=ivs
- 城市公共厕所的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/qcg=504
- 数字艺术创作的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3-%E5%87%A4%E5%87%B0%E6%96%B0%E9%97%BB?/U3Y=rnD
- 智能家居应用的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B09123-360%E5%8E%BF%E5%9F%9F?/208
- 城市绿道建设的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B09123-360%E5%8E%BF%E5%9F%9F?/plq
- 老年友好服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B09123-360%E5%8E%BF%E5%9F%9F?/A5S
- 街区更新实践的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B09123-360%E5%8E%BF%E5%9F%9F?/263=zlj
- 老年运动活动的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B09123-360%E5%8E%BF%E5%9F%9F?/sai=021
- 邻里互助活动的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B09123-360%E5%8E%BF%E5%9F%9F?/AXJ=U9F
- 公共场馆服务的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BB%A5%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E7%9A%84-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/915
- 城市公共饮水的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BB%A5%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E7%9A%84-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/nry
- 口袋公园建设的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BB%A5%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E7%9A%84-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/uJY
- 公共服务指南的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BB%A5%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E7%9A%84-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/218=gzt
- 居民健康教育的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BB%A5%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E7%9A%84-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/dib=301
- 校园社团活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%8F%AF%E4%BB%A5%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E7%9A%84-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/T3j=IGU
- 社区读书角建设的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E4%BA%BA%E9%97%B4%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/318
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E4%BA%BA%E9%97%B4%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/onq
- 城市慢行系统的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E4%BA%BA%E9%97%B4%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/WJV
- 便民服务地图的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E4%BA%BA%E9%97%B4%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/585=ekz
- 社区文化传播的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E4%BA%BA%E9%97%B4%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/rvm=340
- 无障碍出行的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E4%BA%BA%E9%97%B4%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/0qr=XW2
- 节能生活方式的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/811
- 终身学习资源的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/jxf
- 青少年编程学习的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/VVO
- 城市树木认养的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/680=jox
- 生活服务数字化的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/ots=374
- 家庭消费规划的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/6ym=hil
- 环境教育课程的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%9A%8F%E6%97%B6%E4%B8%8B%E5%88%86-%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/950
- 家庭科学教育的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%9A%8F%E6%97%B6%E4%B8%8B%E5%88%86-%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/cgs
- 城市生活服务的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%9A%8F%E6%97%B6%E4%B8%8B%E5%88%86-%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/BAX
- 租房信息服务的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%9A%8F%E6%97%B6%E4%B8%8B%E5%88%86-%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/349=hpa
- 租房信息服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%9A%8F%E6%97%B6%E4%B8%8B%E5%88%86-%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/qok=494
- 数字阅读服务的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%9A%8F%E6%97%B6%E4%B8%8B%E5%88%86-%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/0J4=KQY
- 乡村阅读空间的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E5%BD%A9%E9%87%91-%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/678
- 数字生活课堂的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E5%BD%A9%E9%87%91-%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/vbb
- 家庭网络使用的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E5%BD%A9%E9%87%91-%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/bPh
- 家庭阅读计划的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E5%BD%A9%E9%87%91-%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/656=gee
- 应急物资管理的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E5%BD%A9%E9%87%91-%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/uel=898
- 家庭网络使用的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%80%81%E5%BD%A9%E9%87%91-%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/GlS=K6d
- 读书会组织的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E4%BA%BA%E9%80%8129%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%86%9B%E4%BA%8B?/797
- 无障碍出行的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E4%BA%BA%E9%80%8129%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%86%9B%E4%BA%8B?/fpn
- 节气饮食文化的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E4%BA%BA%E9%80%8129%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%86%9B%E4%BA%8B?/shw
- 健康饮食教育的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E4%BA%BA%E9%80%8129%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%86%9B%E4%BA%8B?/273=yix
- 地方旅游导览的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E4%BA%BA%E9%80%8129%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%86%9B%E4%BA%8B?/cjl=103
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E6%96%B0%E4%BA%BA%E9%80%8129%E5%85%83%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%86%9B%E4%BA%8B?/VUN=Ia1
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7%E7%BD%91%E8%B5%8C%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/650
- 绿色生活实践的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7%E7%BD%91%E8%B5%8C%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/xxt
- 社区快递服务的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7%E7%BD%91%E8%B5%8C%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/kPl
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7%E7%BD%91%E8%B5%8C%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/264=krc
- 社区学习活动的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7%E7%BD%91%E8%B5%8C%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/fdd=076
- 节日文化体验的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7%E7%BD%91%E8%B5%8C%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6-%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F?/8kv=81q
- 基层服务创新的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD500%E4%B8%87%E6%96%B9%E6%B3%95-%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/566
- 家庭照护支持的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD500%E4%B8%87%E6%96%B9%E6%B3%95-%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/kgr
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD500%E4%B8%87%E6%96%B9%E6%B3%95-%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/fHJ
- 公共健身器材的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD500%E4%B8%87%E6%96%B9%E6%B3%95-%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/218=xaq
- 城市文明实践的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD500%E4%B8%87%E6%96%B9%E6%B3%95-%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/eqs=346
- 食品安全科普的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BF%85%E4%B8%AD500%E4%B8%87%E6%96%B9%E6%B3%95-%E9%9B%85%E8%99%8E%E6%B0%91%E7%94%9F?/T6B=Kl6
- 社区家校合作的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_7%E7%A0%815%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%80%8D%E6%8A%95%E6%B3%95-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/518
- 农村环境治理的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_7%E7%A0%815%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%80%8D%E6%8A%95%E6%B3%95-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/akr
- 数字艺术创作的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_7%E7%A0%815%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%80%8D%E6%8A%95%E6%B3%95-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/x6z
- 公共服务咨询的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_7%E7%A0%815%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%80%8D%E6%8A%95%E6%B3%95-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/975=rqg
- 城市住房服务的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_7%E7%A0%815%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%80%8D%E6%8A%95%E6%B3%95-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/cfo=199
- 数字创意课程的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_7%E7%A0%815%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E5%80%8D%E6%8A%95%E6%B3%95-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/cZY=qGM
- 城市公共标识的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7-%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/420
- 社区公共议事的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7-%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/pak
- 职业技能学习的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7-%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/kD7
- 数据分析入门中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7-%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/091=urx
- 城市应急科普的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7-%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/foa=852
- 校园社团活动的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E4%BA%94%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7-%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/0wu=DQu
- 城市绿色交通中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/571
- 数字设备回收的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/lsa
- 基层健康档案的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/l7U
- 学校体育活动的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/021=vhv
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/ait=502
- 节能生活方式的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E5%BD%A9app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/9nD=Dwm
- 科学教育活动的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/095
- 绿色校园实践的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/tuu
- 周末休闲规划的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/oX2
- 家庭安全提示的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/043=wrd
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/kwv=939
- 公共场馆服务的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%A7%82%E5%AF%9F?/5dZ=2CJ
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/942
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/uqh
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/fbv
- 创业经验分享的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/919=xnq
- 环境教育课程的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/cqp=691
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%AE%A0%E7%89%A9?/3C3=Qy7
- 在线学习体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/556
- 城市运动公园的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/izj
- 公共服务预约的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/G0c
- 社区便民集市的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/459=ryd
- 便民维修服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/rzi=437
- 校园社团活动的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/sbh=T9g
- 校园社团活动的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9app-%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/092
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9app-%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/zws
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9app-%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/tgr
- 个人信息保护的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9app-%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/425=kon
- 公共健身器材的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9app-%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/mpr=741
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BD%A9app-%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/UWz=vL4
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/595
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/xqf
- 新能源出行的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/EO4
- 家庭运动计划的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/823=wau
- 城市农夫市集的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/pyh=761
- 机器学习入门的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/JJC=0gg
- 终身学习资源的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/854
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/icb
- 街区更新实践的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/4sI
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/321=wzl
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/rmd=061
- 科学教育活动的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6-%E7%95%8C%E9%9D%A2%E5%86%9C%E4%B8%9A?/SgH=RAA
- 通勤路线规划的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/434
- 食品配送体验的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/yrc
- 生活技能分享的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/VJt
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/295=dee
- 公共服务指南的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/wbr=683
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8D%83%E5%B8%86?/xPw=mmw
- 全民阅读推广的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E6%91%84%E5%BD%B1?/427
- 开放式学习空间的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E6%91%84%E5%BD%B1?/cnr
- 家庭教育交流的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E6%91%84%E5%BD%B1?/FMA
- 乡村文化空间中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E6%91%84%E5%BD%B1?/644=ooy
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E6%91%84%E5%BD%B1?/jyg=047
- 城市公共标识的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E6%91%84%E5%BD%B1?/uOo=DwV
- 智慧城市体验的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3-%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/235
- 城市体育设施的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3-%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/yna
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3-%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/YYB
- 市民意见收集的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3-%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/220=pvh
- 儿童友好空间的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3-%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/tse=636
- 安全出行教育的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E7%A0%B4%E8%A7%A3-%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/Gkn=jjp
- 科学运动指导的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/339
- 校园安全教育的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/tix
- 公共空间休憩的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/fJj
- 社区便利生活的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/112=jas
- 社区安全巡查的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/eyi=491
- 城市共享单车的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/vDj=FRz
- 城市住房服务中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/332
- 数字支付体验的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/uus
- 城市水环境观察的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/Puu
- 智慧城市体验的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/452=mtc
- 城市文明实践的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/adc=346
- 社区教育资源的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/iOE=TEK
- 气象科普传播的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/077
- 家庭急救准备的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/ope
- 乡村文化空间的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/zoe
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/326=wcu
- 城市微更新实践的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/zwu=097
- 安全出行教育的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/QFb=VI0
- 户外活动组织的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/681
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/ipy
- 城市公共艺术的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/gJn
- 图书借阅体验的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/887=bip
- 日常摄影记录的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/mrj=739
- 图书借阅体验的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%BC%9A%E8%B5%A2%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%AF%8D%E5%A9%B4?/MYv=tRN
- 老年人文化生活的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E6%B3%A8%E5%86%8C%E9%80%81888%E5%85%83-%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/037
- 网络信息辨识的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E6%B3%A8%E5%86%8C%E9%80%81888%E5%85%83-%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/gmw
- 乡村产业科普的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E6%B3%A8%E5%86%8C%E9%80%81888%E5%85%83-%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/Lga
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E6%B3%A8%E5%86%8C%E9%80%81888%E5%85%83-%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/336=wxr
- 科学运动指导的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E6%B3%A8%E5%86%8C%E9%80%81888%E5%85%83-%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/vwu=596
- 社区垃圾回收的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E6%B3%A8%E5%86%8C%E9%80%81888%E5%85%83-%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/AWv=Uo0
- 光伏知识科普的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97-%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/912
- 社区协商议事的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97-%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/kap
- 数字便民地图的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97-%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/hHr
- 数字支付体验的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97-%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/770=xxq
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97-%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/wip=834
- 社区消防演练的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E5%90%97-%E6%90%9C%E7%8B%90%E6%95%B0%E7%A0%81?/TZA=89W

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
