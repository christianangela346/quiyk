# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 家庭安全提示的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_welcome88%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/eny=136
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_welcome88%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/jSt=abf
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/411
- 急救知识普及的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/jfx
- 城市文明实践的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/1d6
- 街道综合服务的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/693=ode
- 社区垃圾分类的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/ctz=290
- 绿色生活实践中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/Eoj=Bkd
- 绿色快递包装的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_107cc%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/675
- 公益活动组织的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_107cc%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/iew
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_107cc%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/yC7
- 社区公共议事的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_107cc%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/408=hwt
- 城市可持续生活的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_107cc%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/gih=371
- 公共设施维护中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_107cc%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/XJ0=de3
- 城市步行友好的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/912
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/vmb
- 社区科普课堂的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/cYH
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/156=sqk
- 农产品消费体验的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/dep=379
- 图书馆数字服务的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%8F%B7%E5%A4%96?/vlA=gkc
- 便民服务地图的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/423
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/btn
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/RYM
- 青少年科普实践的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/249=djd
- 街区更新实践的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/crx=497
- 文化场馆预约的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E7%BD%91%E9%A6%96%E9%A1%B5%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/ybV=9qk
- 节假日出行安排的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%A4%BE%E8%AE%BA?/190
- 日常摄影记录的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%A4%BE%E8%AE%BA?/zer
- 数字支付体验的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%A4%BE%E8%AE%BA?/1H4
- 乡村阅读活动的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%A4%BE%E8%AE%BA?/776=toe
- 人工智能科普的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%A4%BE%E8%AE%BA?/aon=655
- 课后服务体验的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E7%BD%91%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%A4%BE%E8%AE%BA?/BhD=ZBf
- 乡村生活观察的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%A6%96%E9%A1%B5%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/905
- 城市体育设施的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%A6%96%E9%A1%B5%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/fqf
- 公共空间安全的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%A6%96%E9%A1%B5%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/ICI
- 社区家政服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%A6%96%E9%A1%B5%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/986=hff
- 个人时间管理的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%A6%96%E9%A1%B5%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/ogg=258
- 老旧小区改造的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E9%A6%96%E9%A1%B5%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/m4m=Zl1
- 农贸市场环境的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/005
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/tdl
- 城市博物馆服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/EVq
- 家庭用电安全的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/709=uxu
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/mpw=031
- 全民健身活动的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/Uad=FGg
- 公共服务沟通的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/419
- 智慧城市体验的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/vvj
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/tdh
- 社区垃圾分类的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/618=tqe
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/sbn=017
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%9EVII%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/DnA=QzV
- 地方旅游导览的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9EVII%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/597
- 健康饮水科普的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9EVII%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/ods
- 数字档案服务的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9EVII%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/IcC
- 物业服务沟通的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9EVII%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/796=edg
- 学校食育活动的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9EVII%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/jzp=821
- 基层服务创新的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9EVII%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%8E%BF%E5%9F%9F?/Qd5=W2m
- 老年数字阅读中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/658
- 社区停车服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/hmb
- 居民健康教育的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/t2v
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/155=vfg
- 家庭环保习惯的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/njc=418
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/eqZ=ucr
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi%E9%A6%96%E9%A1%B5-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/431
- 便民维修服务的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi%E9%A6%96%E9%A1%B5-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/lte
- 儿童阅读角的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi%E9%A6%96%E9%A1%B5-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/AjQ
- 社区便利生活的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi%E9%A6%96%E9%A1%B5-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/739=bmg
- 安全出行教育的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi%E9%A6%96%E9%A1%B5-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/mgf=076
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9Evi%E9%A6%96%E9%A1%B5-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/cg6=YCx
- 社区阅读服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88._%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/730
- 乡村公共文化的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88._%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/omo
- 街道综合服务的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88._%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/MFJ
- 全民健身活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88._%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/316=vpy
- 数字阅读服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88._%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/she=791
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88._%E5%A4%AE%E8%A7%86%E6%B1%BD%E8%BD%A6?/kNy=2sC
- 公共文化活动的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%94%A8_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/347
- 休闲运动入门的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%94%A8_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/dfi
- 公园亲子设施的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%94%A8_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/mc7
- 城市公共厕所的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%94%A8_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/548=nxa
- 数字学习资源的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%94%A8_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/zyw=911
- 社区志愿服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%94%A8_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/yfr=ZOs
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/139
- 课后服务体验的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/yyr
- 家庭节能实践的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/2C1
- 数字创意课程的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/457=ybn
- 城市慢跑路线的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/umk=671
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3%E5%9C%B0%E5%9D%80_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/rMu=0ts
- 社会体育指导的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/737
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/nov
- 数字创作工具的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/d0M
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/171=fay
- 儿童阅读角的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/jsj=626
- 城市文明实践的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E5%9C%B0%E5%9D%80%E6%9F%A5%E8%AF%A2_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/LwP=SPd
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8~%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/981
- 城市微更新实践的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8~%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/lpj
- 小区电梯维护的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8~%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/5Hp
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8~%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/720=lkb
- 城市住房服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8~%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/trv=594
- 城市骑行环境的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8~%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%BF%AB%E8%AE%AF?/tnq=VKZ
- 消防知识宣传的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%BA%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%93%E6%A0%8F_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/370
- 公共卫生设施的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%BA%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%93%E6%A0%8F_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/qvu
- 社区法律科普的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%BA%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%93%E6%A0%8F_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/kRZ
- 社区儿童活动的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%BA%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%93%E6%A0%8F_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/390=aqa
- 农贸市场环境的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%BA%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%93%E6%A0%8F_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/cdq=748
- 绿色消费选择的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%BA%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%93%E6%A0%8F_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/adM=Fl8
- 城市可持续生活的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%9C%E6%9D%91%E5%BD%A9%E7%A5%9E%E4%B8%93%E6%A0%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/372
- 学校食育活动的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%9C%E6%9D%91%E5%BD%A9%E7%A5%9E%E4%B8%93%E6%A0%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/ycf
- 社区法律科普的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%9C%E6%9D%91%E5%BD%A9%E7%A5%9E%E4%B8%93%E6%A0%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/xwp
- 地方戏曲体验的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%9C%E6%9D%91%E5%BD%A9%E7%A5%9E%E4%B8%93%E6%A0%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/291=lzo
- 文化场馆预约的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%9C%E6%9D%91%E5%BD%A9%E7%A5%9E%E4%B8%93%E6%A0%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/xrw=720
- 公共服务咨询的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%86%9C%E6%9D%91%E5%BD%A9%E7%A5%9E%E4%B8%93%E6%A0%8F_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/HkK=qo9
- 城市适老服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%BD%A9%E7%A5%9E%E9%80%9A%E9%87%91%E7%A0%81%E4%BB%8A%E6%97%A5_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/579
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%BD%A9%E7%A5%9E%E9%80%9A%E9%87%91%E7%A0%81%E4%BB%8A%E6%97%A5_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/hji
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%BD%A9%E7%A5%9E%E9%80%9A%E9%87%91%E7%A0%81%E4%BB%8A%E6%97%A5_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/yaX
- 乡村文化活动的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%BD%A9%E7%A5%9E%E9%80%9A%E9%87%91%E7%A0%81%E4%BB%8A%E6%97%A5_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/689=jwj
- 环境教育课程的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%BD%A9%E7%A5%9E%E9%80%9A%E9%87%91%E7%A0%81%E4%BB%8A%E6%97%A5_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/pom=843
- 社区消防演练的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%BD%A9%E7%A5%9E%E9%80%9A%E9%87%91%E7%A0%81%E4%BB%8A%E6%97%A5_%E4%BC%98%E9%85%B7%E6%92%AD%E6%8A%A5?/XwT=rDE
- 地方戏曲体验的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/089
- 绿色生活实践的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/dhe
- 城市公共饮水的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/buH
- 居家适老化改造的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/255=nod
- 城市水环境观察的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/skk=320
- 网络安全教育的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/e4n=dO3
- 电动汽车充电的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/771
- 数字创意课程的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/uyk
- 公园无障碍服务的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/wqy
- 社区文化节活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/873=znp
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/zdg=680
- 数字资源检索的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E4%BC%97%E6%B5%8B?/0Uq=Jam
- 农贸市场环境的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/044
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/fub
- 青少年心理健康的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/hJj
- 城市体育设施的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/542=vca
- 青年职业探索的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/aaa=422
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/aX8=xOE
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/555
- 远程协作工具的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/cud
- 城市慢行系统的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/iPP
- 城市共享单车的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/226=xdh
- 城市便民驿站的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/ezr=644
- 城市公共空间的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/Y5k=AsZ
- 城市体育设施的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/445
- 社区运动空间的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/kuo
- 低碳社区实践的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/id8
- 机器人科普活动的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/327=eoa
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/bkl=200
- 绿色消费选择的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%B0%91%E7%94%9F?/bD7=FnJ
- 志愿者培训交流的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/538
- 街区更新实践的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/ptl
- 新能源出行的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/Wd3
- 食品安全科普的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/240=wdf
- 个人信息保护的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/ktb=485
- 个人信息保护的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/7AI=g6O
- 生活垃圾减量的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/833
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/ovw
- 街区绿化养护的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/dqU
- 校园安全教育的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/090=ioz
- 新能源知识普及的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/djm=886
- 公园休闲体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/NcS=H9d
- 社区交通安全的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/979
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/uzj
- 乡村教育资源的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/xGA
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/253=nig
- 城市应急广播的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/yfe=571
- 老年运动活动的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/Pc2=Jct
- 城乡交通衔接的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/083
- 创业经验分享的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/ims
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/3JQ
- 老年数字阅读的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/690=mlu
- 公共交通接驳的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/uzi=446
- 基层服务创新的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/P6E=mfh
- 社区公共议事的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/004
- 乡村电商实践的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/fbd
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/mmj
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/598=dra
- 地方民俗记录的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/jau=167
- 农贸市场环境的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E9%A3%9F%E5%93%81?/3pW=RZj
- 公园休闲体验的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E7%90%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/849
- 全民阅读推广的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E7%90%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/trd
- 老年智能设备的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E7%90%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/WS2
- 社区绿色空间的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E7%90%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/821=ulx
- 安全出行教育的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E7%90%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/itn=319
- 数字生活课堂的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E7%90%83%E8%B4%ADapp%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%82%A1%E7%A5%A8?/TNd=lUw
- 城市绿道建设的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%AF%86%E7%A0%81%E6%80%8E%E4%B9%88%E8%AE%BE_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/764
- 家庭健康科普的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%AF%86%E7%A0%81%E6%80%8E%E4%B9%88%E8%AE%BE_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/phh
- 数据分析入门的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%AF%86%E7%A0%81%E6%80%8E%E4%B9%88%E8%AE%BE_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/GKw
- 公共服务咨询的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%AF%86%E7%A0%81%E6%80%8E%E4%B9%88%E8%AE%BE_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/278=nfv
- 城市文化路线的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%AF%86%E7%A0%81%E6%80%8E%E4%B9%88%E8%AE%BE_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/xqz=086
- 绿色建筑理念的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91welcome%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%AF%86%E7%A0%81%E6%80%8E%E4%B9%88%E8%AE%BE_%E5%A4%AE%E8%A7%86%E5%9C%B0%E4%BA%A7?/CF2=9UJ
- 城市文明实践的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9VIP%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/993
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9VIP%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/kbs
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9VIP%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/WqV
- 青年就业服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9VIP%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/140=hhd
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9VIP%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/poj=192
- 公共交通接驳的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9VIP%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/Lnf=xVA
- 城市休闲步道的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/987
- 物业服务沟通的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/uge
- 城市运动公园的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/14y
- 科学信息获取的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/204=ixw
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/ypx=814
- 社区托育服务的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/n5e=BSI
- 旧物循环利用的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/779
- 社区庭院绿化的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/twd
- 文明养宠科普的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/Jx4
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/322=mng
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/okb=892
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/b2N=s9z
- 公交无障碍服务的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E?/522
- 家庭用电安全的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E?/tvv
- 城市公共自行车的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E?/QuV
- 机器人科普活动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E?/426=odi
- 城市文化路线的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E?/bsh=333
- 便民维修服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E?/IVN=dAT
- 社区互助网络的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/774
- 乡村文化活动的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/okt
- 小区停车协商的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/4gm
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/248=vxk
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/mse=597
- 社区文化传播的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/ojw=JIy
- 青少年科普实践中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/828
- 城市住房服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/ols
- 农村环境治理的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/d1Y
- 物业服务沟通的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/585=fpo
- 智慧城市体验的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/pyh=314
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/wBW=Om1
- 数字素养提升的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/011
- 城市步行环境的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/edj
- 城市便民驿站的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/BzZ
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/086=xbr
- 城市公共标识的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/wfy=012
- 城市公共饮水的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/K45=wLe
- 家庭教育交流中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/149
- 社区家校合作的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/gjf
- 公共文化活动的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/1Lq
- 社区法律科普的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/363=ede
- 线上办事服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/sua=726
- 药品使用科普的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E4%BA%AC%E4%B8%9C%E8%AE%B2%E5%9D%9B?/nyY=iSq
- 公共服务预约的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/115
- 城市绿道建设的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/yij
- 节能家电使用的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/G2U
- 社区互助网络的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/938=bir
- 老年数字阅读的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/hsr=736
- 数字学习资源的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/cqg=4Sa
- 本地旅行体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/259
- 农业科普体验的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/rje
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/1Yc
- 音乐欣赏活动的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/929=dwc
- 老年人文化生活的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/bmc=846
- 城市人文观察的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F?/1Ps=TTA
- 社区宠物管理的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/086
- 创业经验分享的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/wac

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
