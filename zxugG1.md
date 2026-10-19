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

- 环境教育课程的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BF%85%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/621
- 垃圾分类指导的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BF%85%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/nhy
- 公共服务沟通的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BF%85%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/dOq
- 小区电梯维护的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BF%85%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/657=ivt
- 新能源知识普及的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BF%85%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/fun=626
- 家庭健康科普的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BF%85%E5%87%BA%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%88%86%E6%9E%90?/qU6=qnY
- 数字档案服务的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%84%E5%90%88%E5%9B%BE%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/181
- 青年职业探索的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%84%E5%90%88%E5%9B%BE%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/kur
- 农村环境治理的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%84%E5%90%88%E5%9B%BE%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/lrc
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%84%E5%90%88%E5%9B%BE%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/426=llq
- 城市步行环境的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%84%E5%90%88%E5%9B%BE%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/upt=419
- 节气饮食文化的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%84%E5%90%88%E5%9B%BE%E8%A1%A8_%E6%BE%8E%E6%B9%83%E5%9B%BE%E9%89%B4?/HAN=qs2
- 智慧城市体验的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/572
- 社区科普课堂的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/ovz
- 乡村公共服务的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/LmP
- 数字素养提升的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/126=xej
- 市民热线服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/lzv=564
- 城市博物馆服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%AE%8F%E8%A7%82%E8%B4%A2%E7%BB%8F?/lNQ=c44
- 社区垃圾回收的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/332
- 小区停车协商的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/fqx
- 光伏知识科普的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/3Kf
- 亲子科普活动的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/303=qfg
- 社会体育指导的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/cpk=064
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E5%9B%BE?/KbR=sC7
- 科学观察活动的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/046
- 公共空间安全的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/rct
- 儿童阅读角的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/DSM
- 基层健康服务中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/782=vgz
- 家庭运动计划的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/btj=157
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E9%A1%BA%E4%B8%B0%E4%BF%9D%E9%99%A9?/7IX=R6z
- 城市便民驿站的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%AD%E7%9A%84%E5%AF%B9%E5%AD%90%E6%98%AF%E4%BB%80%E4%B9%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/004
- 职业技能学习的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%AD%E7%9A%84%E5%AF%B9%E5%AD%90%E6%98%AF%E4%BB%80%E4%B9%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/eat
- 地方文化传播的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%AD%E7%9A%84%E5%AF%B9%E5%AD%90%E6%98%AF%E4%BB%80%E4%B9%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/CVC
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%AD%E7%9A%84%E5%AF%B9%E5%AD%90%E6%98%AF%E4%BB%80%E4%B9%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/199=sbl
- 家庭节能实践的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%AD%E7%9A%84%E5%AF%B9%E5%AD%90%E6%98%AF%E4%BB%80%E4%B9%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/rhg=458
- 社区运动空间的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%AD%E7%9A%84%E5%AF%B9%E5%AD%90%E6%98%AF%E4%BB%80%E4%B9%88_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/HMy=ma0
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E6%9C%89%E5%A4%9A%E5%B0%91%E6%B3%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/562
- 学校食育活动的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E6%9C%89%E5%A4%9A%E5%B0%91%E6%B3%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/gsk
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E6%9C%89%E5%A4%9A%E5%B0%91%E6%B3%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/FgE
- 智能家居应用的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E6%9C%89%E5%A4%9A%E5%B0%91%E6%B3%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/714=mle
- 农产品品牌传播的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E6%9C%89%E5%A4%9A%E5%B0%91%E6%B3%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/mgu=624
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E6%9C%89%E5%A4%9A%E5%B0%91%E6%B3%A8_%E6%90%9C%E7%8B%97%E5%88%B8%E5%95%86?/Y0A=XwD
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E5%90%8E%E4%B8%8B%E6%9C%9F%E6%80%8E%E4%B9%88%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/710
- 数字创意课程的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E5%90%8E%E4%B8%8B%E6%9C%9F%E6%80%8E%E4%B9%88%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/vol
- 城乡交通衔接的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E5%90%8E%E4%B8%8B%E6%9C%9F%E6%80%8E%E4%B9%88%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/iRM
- 运动安全知识的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E5%90%8E%E4%B8%8B%E6%9C%9F%E6%80%8E%E4%B9%88%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/741=jdh
- 校园安全教育的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E5%90%8E%E4%B8%8B%E6%9C%9F%E6%80%8E%E4%B9%88%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/yiu=130
- 社区志愿服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E5%90%8E%E4%B8%8B%E6%9C%9F%E6%80%8E%E4%B9%88%E4%B9%B0_%E4%BA%AC%E4%B8%9C%E5%A4%B4%E6%9D%A1?/hkM=eKY
- 健康信息获取的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/049
- 农贸市场环境中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/rfr
- 安全出行教育的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/gfR
- 本地消费场景的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/610=izd
- 城市农夫市集的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/vcw=138
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A1%8C%E6%83%85?/5pM=ypI
- 新能源知识普及的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/467
- 城市文明出行的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/odh
- 青年职业探索的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/FMB
- 小微企业服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/709=yuf
- 公共空间导览的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/hzb=281
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/FIY=WmU
- 公共设施维护的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E6%A6%82%E7%8E%87%E6%9C%89%E5%A4%9A%E5%A4%A7_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/632
- 消防知识宣传的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E6%A6%82%E7%8E%87%E6%9C%89%E5%A4%9A%E5%A4%A7_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/xnh
- 城市游园体验的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E6%A6%82%E7%8E%87%E6%9C%89%E5%A4%9A%E5%A4%A7_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/Hdd
- 城市慢跑路线的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E6%A6%82%E7%8E%87%E6%9C%89%E5%A4%9A%E5%A4%A7_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/420=tlr
- 数字资源检索的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E6%A6%82%E7%8E%87%E6%9C%89%E5%A4%9A%E5%A4%A7_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/tvj=220
- 图书借阅体验的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%87%BA%E5%AF%B9%E5%AD%90%E6%A6%82%E7%8E%87%E6%9C%89%E5%A4%9A%E5%A4%A7_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/ajJ=zs3
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E5%A4%9A%E5%B0%91%E7%BB%84%E5%90%88_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/605
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E5%A4%9A%E5%B0%91%E7%BB%84%E5%90%88_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/fjr
- 社区活动报名的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E5%A4%9A%E5%B0%91%E7%BB%84%E5%90%88_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/HdL
- 绿色出行服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E5%A4%9A%E5%B0%91%E7%BB%84%E5%90%88_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/315=ser
- 公共服务预约的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E5%A4%9A%E5%B0%91%E7%BB%84%E5%90%88_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/gxr=584
- 公共空间安全中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E5%8F%B7%E5%A4%9A%E5%B0%91%E7%BB%84%E5%90%88_%E8%85%BE%E8%AE%AF%E6%B3%95%E5%BE%8B?/Qot=DFU
- 社区信息发布的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E4%B8%80%E5%85%B1%E5%A4%9A%E5%B0%91_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/985
- 急救知识普及的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E4%B8%80%E5%85%B1%E5%A4%9A%E5%B0%91_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/fqx
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E4%B8%80%E5%85%B1%E5%A4%9A%E5%B0%91_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/HLT
- 社区休闲设施的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E4%B8%80%E5%85%B1%E5%A4%9A%E5%B0%91_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/361=xuw
- 数字便民地图中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E4%B8%80%E5%85%B1%E5%A4%9A%E5%B0%91_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/mri=764
- 家庭急救准备的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%AF%B9%E5%AD%90%E4%B8%80%E5%85%B1%E5%A4%9A%E5%B0%91_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/2Bn=CFq
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/856
- 亲子阅读活动的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/ezg
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/oyR
- 数字设备回收的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/916=rle
- 智慧停车服务的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/rqh=050
- 家庭健康管理的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/Tpi=lSf
- 医院导诊服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/219
- 公共服务数字化的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/ica
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/9nk
- 乡村产业科普的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/874=ebn
- 光伏知识科普的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/uni=827
- 智能家居应用的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E6%A6%82%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/PvF=DUz
- 儿童阅读角中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/685
- 无障碍出行的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/leq
- 老年运动活动的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/MEo
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/427=aqz
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/vku=252
- 社区消防演练的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/hAr=Sje
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%86%E7%A1%AE%E7%8E%87%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/779
- 社区消防演练的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%86%E7%A1%AE%E7%8E%87%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/cfo
- 社区菜市场服务的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%86%E7%A1%AE%E7%8E%87%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/LXM
- 老年智能设备的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%86%E7%A1%AE%E7%8E%87%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/237=rkp
- 周末休闲规划的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%86%E7%A1%AE%E7%8E%87%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/mjb=875
- 街区绿化养护的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%86%E7%A1%AE%E7%8E%87%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/joZ=fnd
- 科学教育活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%80%E6%B3%A8%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/164
- 青少年职业启蒙的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%80%E6%B3%A8%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/pdn
- 社区运动空间的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%80%E6%B3%A8%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/XAb
- 智能手机助老的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%80%E6%B3%A8%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/295=cio
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%80%E6%B3%A8%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/wfi=723
- 智慧停车服务的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%80%E6%B3%A8%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/3az=hfJ
- 数字设备回收的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%87%BA%E7%8E%B0%E8%B1%B9%E5%AD%90%E7%9A%84%E8%A7%84%E5%BE%8B_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/796
- 学校食育活动的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%87%BA%E7%8E%B0%E8%B1%B9%E5%AD%90%E7%9A%84%E8%A7%84%E5%BE%8B_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/xka
- 本地历史资料的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%87%BA%E7%8E%B0%E8%B1%B9%E5%AD%90%E7%9A%84%E8%A7%84%E5%BE%8B_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/j8w
- 社区便民服务的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%87%BA%E7%8E%B0%E8%B1%B9%E5%AD%90%E7%9A%84%E8%A7%84%E5%BE%8B_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/428=ggl
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%87%BA%E7%8E%B0%E8%B1%B9%E5%AD%90%E7%9A%84%E8%A7%84%E5%BE%8B_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/mel=813
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%87%BA%E7%8E%B0%E8%B1%B9%E5%AD%90%E7%9A%84%E8%A7%84%E5%BE%8B_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/0xf=uJW
- 社区生活指南的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/084
- 城市雨天出行的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/yum
- 社区体育组织的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/3AS
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/395=mod
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/jla=859
- 家庭健康科普的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/Fxr=jsD
- 城市慢行系统的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/204
- 城市夜间照明的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/ygc
- 社区艺术活动的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/Kha
- 社区科普课堂中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/160=pig
- 家庭节能设备的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/bht=415
- 老年人文化生活的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/nGl=fWv
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/366
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/cvh
- 数字公共文化的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/iO1
- 数字设备回收的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/009=rqp
- 基层健康服务的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/bhb=594
- 社区活动策划的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B1%B9%E5%AD%90%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%8C%BB%E8%8D%AF?/JJj=JUw
- 校园节能行动从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/082
- 数字设备回收的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/crx
- 社区休闲设施的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/CG4
- 社区艺术活动的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/134=anp
- 社区公共卫生的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/sbk=972
- 网络安全教育的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%B1%B9%E5%AD%90%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E5%9F%BA%E9%87%91?/nW4=Gez
- 城市公共饮水的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E4%B8%80%E8%88%AC%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%87%BA%E8%B1%B9%E5%AD%90_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/423
- 家庭节能实践的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E4%B8%80%E8%88%AC%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%87%BA%E8%B1%B9%E5%AD%90_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/nrb
- 社区手工活动的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E4%B8%80%E8%88%AC%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%87%BA%E8%B1%B9%E5%AD%90_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/Dzm
- 城市水环境观察的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E4%B8%80%E8%88%AC%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%87%BA%E8%B1%B9%E5%AD%90_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/408=wpf
- 乡村电商实践的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E4%B8%80%E8%88%AC%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%87%BA%E8%B1%B9%E5%AD%90_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/hyy=176
- 读书会组织的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E4%B8%80%E8%88%AC%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%87%BA%E8%B1%B9%E5%AD%90_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/ksH=YPo
- 社区公共议事中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/550
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/buk
- 城市步行环境的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Osa
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/460=ooi
- 社区文化传播的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/niy=860
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%89%8D%E5%85%86_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/HOo=URI
- 开放数据应用的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/783
- 家庭理财科普的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/gar
- 乡村电商实践的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/YzH
- 社区便利生活的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/032=fub
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/uhz=769
- 生活服务数字化的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E7%9A%84%E5%BE%81%E5%85%86%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/AUC=pf0
- 食品配送体验的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E5%89%8D%E5%BC%80%E4%BB%80%E4%B9%88%E5%8F%B7_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/333
- 全民健身活动的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E5%89%8D%E5%BC%80%E4%BB%80%E4%B9%88%E5%8F%B7_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/est
- 社区运动空间的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E5%89%8D%E5%BC%80%E4%BB%80%E4%B9%88%E5%8F%B7_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/Qn3
- 社区互助网络的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E5%89%8D%E5%BC%80%E4%BB%80%E4%B9%88%E5%8F%B7_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/384=jmy
- 亲子阅读活动的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E5%89%8D%E5%BC%80%E4%BB%80%E4%B9%88%E5%8F%B7_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/qid=030
- 科学信息获取的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%87%BA%E8%B1%B9%E5%AD%90%E5%89%8D%E5%BC%80%E4%BB%80%E4%B9%88%E5%8F%B7_%E5%93%94%E5%93%A9%E7%9B%98%E7%82%B9?/iET=N1t
- 社区慢性病防控的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%89%E4%B8%AA%E6%9C%BA%E4%BC%9A_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/023
- 家庭网络使用的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%89%E4%B8%AA%E6%9C%BA%E4%BC%9A_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/sip
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%89%E4%B8%AA%E6%9C%BA%E4%BC%9A_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/Hra
- 绿色生活实践的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%89%E4%B8%AA%E6%9C%BA%E4%BC%9A_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/275=mnt
- 全民健身活动的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%89%E4%B8%AA%E6%9C%BA%E4%BC%9A_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/kkj=272
- 儿童友好空间的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E4%B8%89%E4%B8%AA%E6%9C%BA%E4%BC%9A_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/hAB=u8s
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B1%B9%E5%AD%90%E5%90%8E%E9%9D%A2%E5%BF%85%E5%87%BA%E5%A4%A72023%E7%AC%AC%E5%8D%81%E4%B8%80%E6%9C%9F_360%E7%88%86%E6%96%99?/004
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B1%B9%E5%AD%90%E5%90%8E%E9%9D%A2%E5%BF%85%E5%87%BA%E5%A4%A72023%E7%AC%AC%E5%8D%81%E4%B8%80%E6%9C%9F_360%E7%88%86%E6%96%99?/dxh
- 社区信息发布的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B1%B9%E5%AD%90%E5%90%8E%E9%9D%A2%E5%BF%85%E5%87%BA%E5%A4%A72023%E7%AC%AC%E5%8D%81%E4%B8%80%E6%9C%9F_360%E7%88%86%E6%96%99?/Xpf
- 健康信息获取的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B1%B9%E5%AD%90%E5%90%8E%E9%9D%A2%E5%BF%85%E5%87%BA%E5%A4%A72023%E7%AC%AC%E5%8D%81%E4%B8%80%E6%9C%9F_360%E7%88%86%E6%96%99?/566=xmh
- 街区绿化养护的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B1%B9%E5%AD%90%E5%90%8E%E9%9D%A2%E5%BF%85%E5%87%BA%E5%A4%A72023%E7%AC%AC%E5%8D%81%E4%B8%80%E6%9C%9F_360%E7%88%86%E6%96%99?/ldz=784
- 小区公共照明的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%B1%B9%E5%AD%90%E5%90%8E%E9%9D%A2%E5%BF%85%E5%87%BA%E5%A4%A72023%E7%AC%AC%E5%8D%81%E4%B8%80%E6%9C%9F_360%E7%88%86%E6%96%99?/sSn=RLb
- 基层健康档案的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_3d%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%B7%E5%89%8D%E5%85%86_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/623
- 绿色校园实践的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_3d%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%B7%E5%89%8D%E5%85%86_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/ojh
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_3d%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%B7%E5%89%8D%E5%85%86_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/Dsb
- 无障碍出行的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_3d%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%B7%E5%89%8D%E5%85%86_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/823=daj
- 健康信息获取的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_3d%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%B7%E5%89%8D%E5%85%86_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/nrb=645
- 乡村公共文化的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_3d%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%B7%E5%89%8D%E5%85%86_%E8%8A%92%E6%9E%9C%E5%9C%88%E5%AD%90?/klB=e8U
- 农产品消费体验从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_3D%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%A3%E8%AF%80_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/472
- 城市夜间照明的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_3D%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%A3%E8%AF%80_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/sgy
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_3D%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%A3%E8%AF%80_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/tFt
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_3D%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%A3%E8%AF%80_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/722=ter
- 老年人日常照护的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_3D%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%A3%E8%AF%80_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/wup=111
- 消防知识宣传的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_3D%E6%9C%80%E5%87%86%E7%9A%84%E5%87%BA%E8%B1%B9%E5%AD%90%E5%8F%A3%E8%AF%80_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/bWI=3dM
- 公共空间导览的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E8%A7%84%E5%88%99_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/950
- 小区公共照明的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E8%A7%84%E5%88%99_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/cgg
- 公共服务评价的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E8%A7%84%E5%88%99_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/Q4h
- 地方戏曲体验的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E8%A7%84%E5%88%99_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/668=gkh
- 通勤路线规划的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E8%A7%84%E5%88%99_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/rzf=462
- 城市住房服务的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E8%A7%84%E5%88%99_%E8%85%BE%E8%AE%AF%E7%89%B9%E7%A8%BF?/ivg=vZD
- 远程协作工具的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/683
- 社区垃圾分类的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/eqv
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/3ND
- 社区家政服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/229=oyf
- 城市共享单车的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/kpk=479
- 家庭用电安全的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/uHq=Gjy
- 社区托育服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%BD%91%E7%BB%9C%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/411
- 电子商务服务的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%BD%91%E7%BB%9C%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/ibb
- 家庭运动计划的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%BD%91%E7%BB%9C%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/t4X
- 老年友好服务的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%BD%91%E7%BB%9C%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/991=lux
- 基层医疗预约的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%BD%91%E7%BB%9C%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/vnm=282
- 开放式学习空间的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%BD%91%E7%BB%9C%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E6%89%91%E6%8A%95%E8%B5%84?/gt6=YDv
- 绿色快递包装的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/271
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/kuy
- 社区养老服务的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ctW
- 街道综合服务的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/087=cpg
- 社区家校合作的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/kba=044
- 城市基础设施的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Qo3=Lmx
- 公共服务咨询的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%A0%B4%E8%A7%A3_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/920
- 在线教育体验的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%A0%B4%E8%A7%A3_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/tai
- 物业服务沟通的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%A0%B4%E8%A7%A3_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/4Jq
- 环境监测科普的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%A0%B4%E8%A7%A3_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/512=den
- 便民信息查询的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%A0%B4%E8%A7%A3_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/jpc=811
- 街道综合服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E7%A0%B4%E8%A7%A3_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/FQU=93l
- 街头绿植养护的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/679
- 通勤路线规划的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/lgu
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/UA6
- 社区托育服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/610=kgl
- 街区小店体验的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/eub=084
- 学校体育活动的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%A7%84%E5%88%99%E8%AF%B4%E6%98%8E%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE-%E5%8F%A3%E8%AF%80_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/KwS=L9G
- 城市共享单车的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/590
- 街区小店体验的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/wts
- 生活技能分享的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/GlW
- 在线学习体验的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/273=zni
- 社区应急准备的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/qjw=127
- 公共服务指南的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3%E5%9B%BE%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%88%86%E6%96%99?/HNx=tlW
- 社区信息发布的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3-%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/387
- 农村环境治理的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3-%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/xcd
- 社区故事采集的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3-%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/NDG
- 全民健身活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3-%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/961=cia
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3-%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/phi=406
- 家庭科学教育中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3-%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/M9v=tLW
- 儿童友好空间的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E7%A0%B4%E8%A7%A3_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/970
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E7%A0%B4%E8%A7%A3_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/nlg
- 城市基础设施的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E7%A0%B4%E8%A7%A3_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/xRn
- 社区运动空间中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E7%A0%B4%E8%A7%A3_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/383=kvx
- 街道综合服务的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E7%A0%B4%E8%A7%A3_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/qil=576
- 家庭志愿活动的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%A6%82%E4%BD%95%E7%A0%B4%E8%A7%A3_%E6%90%9C%E7%8B%97%E4%BA%BA%E5%A4%A7?/dJl=g6s
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/521
- 儿童阅读角的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/qzm
- 公共空间休憩的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/BP9
- 健康饮食教育的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/915=gfc
- 老年友好服务的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/bmr=955
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%8A%80%E5%B7%A7_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/Pmp=gMK
- 开放式学习空间的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F%E6%9D%80%E8%82%96_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/924
- 社区读书角建设的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F%E6%9D%80%E8%82%96_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/ysp
- 城市生活记录的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F%E6%9D%80%E8%82%96_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/OYs
- 地方美食文化的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%B0%B8%E4%B9%85%E5%87%BA%E7%89%B9%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F%E6%9D%80%E8%82%96_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/357=ltc

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
