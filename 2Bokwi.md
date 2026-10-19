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

- 街区小店体验的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/275
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/ude
- 社区读书角建设的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/YqN
- 居家适老化改造中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/231=zli
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/lvh=885
- 文化场馆预约的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%88%9B%E6%8A%95?/jN1=toM
- 城市生活服务的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/115
- 社区故事采集的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/ftd
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/Kkq
- 城市文化路线的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/622=dtk
- 城市可持续生活的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/iha=528
- 儿童户外活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/g0o=R6P
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/174
- 消防知识宣传的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/hrq
- 本地消费场景的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/ZNv
- 青少年科技社团的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/345=msb
- 公共场馆服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/exw=969
- 非遗体验活动的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/ynV=zVC
- 公共健身器材的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/047
- 光伏知识科普的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/axw
- 家庭运动计划的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/CDf
- 家庭理财科普的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/207=xry
- 城市文化路线的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/mar=142
- 家庭网络使用中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/p4T=Ox7
- 数字素养提升的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/699
- 城市生活服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/kjo
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/u6h
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/549=vdx
- 节能生活方式的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/dci=112
- 科学信息获取的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/UCm=eTI
- 社区绿色空间的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/868
- 劳动教育实践的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/vnm
- 社区公共卫生的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/Ks4
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/915=obd
- 公园无障碍服务的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/dsk=751
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/4An=JXD
- 学校体育活动的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/946
- 公交站点体验的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/ceq
- 城市人文观察的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/NTN
- 数字学习资源的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/481=zci
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/cyt=373
- 街区小店体验的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/byk=DCQ
- 家庭节能设备的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E5%A4%A7?/352
- 便民维修服务的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E5%A4%A7?/cum
- 公共服务数字化的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E5%A4%A7?/qM7
- 亲子科普活动的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E5%A4%A7?/573=qny
- 城市文明实践的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E5%A4%A7?/bgn=490
- 街区更新实践的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BA%BA%E5%A4%A7?/b4i=Cq3
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/234
- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/jck
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/jQl
- 电动汽车充电的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/209=wpy
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/kgz=497
- 社区运动空间的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/WEx=sKJ
- 乡村生态观察的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/542
- 全民健身活动的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/pwe
- 城市绿色交通的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/DZ4
- 文化讲座服务的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/655=pjz
- 社区绿色空间的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/gwj=531
- 乡村文化活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/WzW=xEC
- 周末休闲规划的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/596
- 节约用水实践的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/dgi
- 数字设备回收的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/jY1
- 环境教育课程的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/514=wfq
- 开放数据应用的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/fbq=972
- 绿色校园实践的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/ycA=VRE
- 旧物循环利用的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/312
- 智能家居应用的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/eus
- 城市公共厕所的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/dwX
- 数字便民地图的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/847=seq
- 社区养老服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/mqa=398
- 数字公共文化的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%BF%E4%BA%A7?/vwP=R3u
- 公益活动组织的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/985
- 课后服务体验的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/wnk
- 乡村教育资源的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/9l0
- 社区老年食堂的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/839=dlv
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/aqp=214
- 租房信息服务的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/JYJ=iR9
- 家庭运动计划的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/299
- 人工智能科普的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/nda
- 社区活动策划的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/3dx
- 急救知识普及的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/715=auo
- 公园亲子设施的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/nwr=586
- 数字便民地图的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/Eal=KvX
- 乡村生态观察的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%95%85%E6%B8%B8?/070
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%95%85%E6%B8%B8?/abp
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%95%85%E6%B8%B8?/gc4
- 城市体育设施的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%95%85%E6%B8%B8?/471=wbw
- 儿童友好空间的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%95%85%E6%B8%B8?/amw=673
- 公共卫生宣传的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%95%85%E6%B8%B8?/97N=XWY
- 城市应急广播中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/779
- 农贸市场环境的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/xgz
- 食品安全科普的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/sto
- 科学教育活动的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/566=kje
- 城市建设科普的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/anv=098
- 城市住房服务的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/Xzu=BKM
- 公共服务沟通的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/284
- 节日文化体验的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/hiz
- 城乡公共服务的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/rkL
- 社区学习活动的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/472=njk
- 城市雨天出行的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/pqc=784
- 市民热线服务的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_360%E5%8A%A8%E6%BC%AB?/Qgk=j3T
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/612
- 旧物循环利用的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/kqs
- 城市空气科普的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/FuR
- 社区家校合作的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/251=uuh
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/fbg=262
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/IZX=sAc
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/039
- 社区活动策划的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/mga
- 乡村生态观察的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/iPu
- 数字创作工具的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/386=bgz
- 急救知识普及的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/ada=882
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/Kz3=76F
- 街区更新实践的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/741
- 家庭理财科普的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/yil
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/xRR
- 数字生活课堂的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/663=fby
- 家庭阅读计划的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/wkp=733
- 数字创意课程的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/mGG=tGR
- 绿色消费选择中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/648
- 城市便民驿站的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/vok
- 青少年编程学习中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/uUg
- 乡村产业科普的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/376=nst
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/rnp=113
- 课后服务体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%99%8E%E6%89%91%E5%91%A8%E6%8A%A5?/pC6=oVD
- 社区科普课堂的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/427
- 基层健康档案的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/fkz
- 社区邻里服务的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/oFi
- 社区便民集市的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/623=oyv
- 社区快递服务的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/crc=596
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%BE%8E%E9%A3%9F?/ZUn=6MI
- 数字政务体验的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/614
- 软件开发学习的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/qnj
- 家庭食品保存的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/Urf
- 药品使用科普的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/164=bqo
- 节气饮食文化的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/jzf=767
- 乡村公共服务的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/W5V=yIZ
- 社区交通安全的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/845
- 公共设施维护的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/qfa
- 传统节日科普的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/cgr
- 社区安全巡查的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/884=kqv
- 绿色校园实践的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/xey=042
- 公共交通接驳的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/Op8=xm1
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/538
- 电动汽车充电的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/rtg
- 公共文化活动的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/PHi
- 租房信息服务的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/720=eof
- 网络安全教育的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/lpx=619
- 社区读书角建设的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/Mvw=Qn9
- 生活垃圾减量的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/613
- 学校体育活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/kjc
- 职业技能学习中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/O5M
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/664=tam
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/pcj=807
- 节日文化体验的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E7%89%88%E6%9C%AC_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/Cwd=LLU
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%96%B9%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/256
- 食品安全科普的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%96%B9%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/fmh
- 邻里共享空间的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%96%B9%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/oyP
- 家庭网络使用的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%96%B9%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/927=gav
- 社区家校合作中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%96%B9%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/ivc=548
- 数据分析入门的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%96%B9%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/qsy=KNr
- 校园社团活动的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/452
- 租房信息服务的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/ekl
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/5pJ
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/049=dym
- 生活技能分享的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/exu=452
- 科学运动指导的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/9xT=l5v
- 智能手机助老的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/718
- 市民热线服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/yhz
- 城市人文观察的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/0AL
- 在线教育体验的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/802=pwc
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/ruf=549
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/OZJ=484
- 公益活动组织的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/819
- 消防知识宣传的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/bhe
- 数字档案服务的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/gzg
- 图书借阅体验的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/647=dpz
- 街道综合服务的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/rwl=405
- 城市噪声观察的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/TVP=QAr
- 开放式学习空间的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/570
- 家庭健康科普的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/uqi
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/v3Z
- 青年志愿活动的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/715=khu
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/ddm=743
- 环境教育课程的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BA%B2%E5%AD%90?/zJd=Yle
- 学校体育活动的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/876
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/gls
- 社区家政服务的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/FFY
- 街道综合服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/083=fqk
- 老年学习活动的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/ibs=704
- 儿童安全出行中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/jpl=eCi
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/373
- 家庭运动计划的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/ixq
- 老年人出行服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/nWD
- 家庭网络使用的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/336=twz
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/wfh=025
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E6%89%98?/Tpo=Rle
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/681
- 乡村公共文化的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/hau
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/DSS
- 社区花园共建的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/949=snh
- 数字创作工具的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/hcl=109
- 乡村生活观察的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E7%89%88_%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/2c6=iw6
- 邻里互助活动的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/469
- 社区活动策划的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/wgv
- 家庭饮食安排的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/U2A
- 城市适老服务的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/196=wyi
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/jeu=008
- 城乡公共服务中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/R2k=NUK
- 智慧城市体验的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/397
- 社区信息发布中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/iuu
- 在线学习体验的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/0p6
- 药品使用科普的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/906=pgg
- 数字学习资源的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/kyj=392
- 城市树木认养的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%A6%81%E9%97%BB?/ALz=uV9
- 公共场所导视中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/720
- 垃圾分类指导的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/dpz
- 乡村公共阅读的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/HSV
- 城市公共艺术的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/323=pkg
- 儿童友好空间的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/zfs=707
- 青少年户外教育的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/TFL=giZ
- 乡村生活观察的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/676
- 气象科普传播的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/jcf
- 家庭环保行动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/nNf
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/049=xwx
- 社区体育组织的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/bzj=673
- 乡村产业科普的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/Kid=J1L
- 家庭教育交流的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/964
- 社区安全巡查的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/hgc
- 公共空间照明中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/pWP
- 家庭食品保存的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/392=ejl
- 数字公共文化的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/gbm=087
- 城市共享单车的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%98%9F%E5%BA%A7?/vWg=lEo
- 家庭食品保存的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD5%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/240
- 小微企业服务的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD5%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/gdh
- 社区防暑服务的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD5%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/hwh
- 地方文化传播的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD5%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/720=wfa
- 家庭网络使用的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD5%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/urg=964
- 老旧小区改造的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD5%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/ycp=0Pn
- 老年学习活动的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/142
- 社区运动空间的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/blz
- 环境监测科普的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/acB
- 社区文化节活动的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/022=xzh
- 科技馆参观体验的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/vok=441
- 数字学习资源的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/uYz=MDX
- 社区活动报名中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/454
- 节能家电使用的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/tiu
- 城市文明实践的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/Nzl
- 电子商务服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/375=nwo

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
