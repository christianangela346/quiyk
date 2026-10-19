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

- 城市共享单车的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/621
- 城市文明出行的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/hnb
- 数字艺术创作的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/OBj
- 公共设施维护的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/708=uwl
- 老旧小区改造的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/syc=977
- 城市公共空间的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E8%82%A1%E7%A5%A8?/1ER=2sQ
- 社区法律科普的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/126
- 公共空间导览的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/pwu
- 社区休闲设施的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/L7R
- 社区艺术活动的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/098=giz
- 城市公共艺术的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/hve=505
- 食品配送体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/A0n=wvj
- 科学运动指导的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97._%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/258
- 绿色出行服务的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97._%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/sch
- 城市适老服务的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97._%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/SHn
- 家庭节能实践的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97._%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/111=zxb
- 社区停车服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97._%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/jch=041
- 文明养宠科普的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97._%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/6ep=EGr
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/255
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/wbk
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/Jco
- 生成式工具使用的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/137=icz
- 家庭防灾准备的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/zai=788
- 社区活动策划的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E6%96%B9%E6%A1%88_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/zTq=oXJ
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/922
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/ret
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/oCa
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/660=qom
- 社区活动报名的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/ytd=282
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E7%9A%84%E6%8A%80%E5%B7%A7_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/vJG=zXz
- 绿色办公实践的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/203
- 个人数据管理的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/tzy
- 城市博物馆活动的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/3yP
- 在线教育体验的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/958=hqk
- 节假日出行安排的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/nbd=377
- 城市公共厕所的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-_%E5%BE%97%E7%89%A9%E5%9F%BA%E9%87%91?/SCl=2nD
- 公共文化活动的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/407
- 公共服务数字化的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/byp
- 社区健康讲座的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/rVc
- 家庭网络使用的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/751=xlu
- 农业科普体验的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/ope=773
- 城市公共自行车的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_1%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/oqp=dq2
- 城市公共自行车的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E7%9A%84%E7%A7%98%E5%AF%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/282
- 文化讲座服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E7%9A%84%E7%A7%98%E5%AF%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/faw
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E7%9A%84%E7%A7%98%E5%AF%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/WPf
- 市民热线服务的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E7%9A%84%E7%A7%98%E5%AF%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/374=uko
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E7%9A%84%E7%A7%98%E5%AF%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/giv=964
- 信息无障碍体验的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E7%9A%84%E7%A7%98%E5%AF%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/Prb=NQY
- 社区儿童活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E8%80%81%E5%B8%88_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/148
- 远程协作工具的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E8%80%81%E5%B8%88_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/tvj
- 公共空间休憩的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E8%80%81%E5%B8%88_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/hSQ
- 传统节日科普的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E8%80%81%E5%B8%88_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/805=hvc
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E8%80%81%E5%B8%88_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/dcn=985
- 应急物资管理的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0app%E6%8E%A8%E8%8D%90%E8%80%81%E5%B8%88_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/Spm=AmN
- 公共交通信息服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/416
- 小微企业服务的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/meh
- 线上办事服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/ZOQ
- 生活技能分享的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/128=nhe
- 就业技能培训的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/osb=748
- 科学观察活动的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%AD%E8%AE%B0?/yl2=S6n
- 城市步行友好的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/299
- 社区公共卫生的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/qde
- 老年人出行服务的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/9Ov
- 家庭科学教育的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/084=wly
- 人工智能科普的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/pwm=202
- 街道综合服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/MrR=onw
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/365
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/sci
- 城市公共厕所的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/DcE
- 健康饮水科普的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/621=dyz
- 城市人文观察的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/iis=766
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95_%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/fue=lwR
- 药品使用科普的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/150
- 城市步行友好的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/nys
- 城市微更新实践的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/AM1
- 社区邻里服务的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/783=geu
- 社区应急准备的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/opx=107
- 无障碍信息设计的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/Ma1=M0R
- 数字阅读服务的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E9%95%BF%E9%BE%99%E7%9A%84%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/783
- 地方旅游导览的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E9%95%BF%E9%BE%99%E7%9A%84%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/vbz
- 节约用水实践的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E9%95%BF%E9%BE%99%E7%9A%84%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/F9d
- 个人时间管理的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E9%95%BF%E9%BE%99%E7%9A%84%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/903=npj
- 社区活动空间的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E9%95%BF%E9%BE%99%E7%9A%84%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/pkz=183
- 智慧城市体验的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E9%95%BF%E9%BE%99%E7%9A%84%E8%A7%84%E5%BE%8B%E7%A0%B4%E8%A7%A3_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/BaP=7yn
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_360%E9%A3%9F%E5%93%81?/031
- 社区交通安全的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_360%E9%A3%9F%E5%93%81?/nwm
- 城市建设科普的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_360%E9%A3%9F%E5%93%81?/ZGk
- 社区商业活力的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_360%E9%A3%9F%E5%93%81?/831=uig
- 公共空间休憩的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_360%E9%A3%9F%E5%93%81?/luh=046
- 邻里互助活动的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3%E7%9A%84%E5%BD%A9%E7%A5%A8%E6%8A%80%E5%B7%A7_360%E9%A3%9F%E5%93%81?/dMf=yvT
- 日常摄影记录的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/798
- 社区手工活动的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/inc
- 城市文明出行的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/SGB
- 青少年心理健康的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/703=bms
- 城市文明出行的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/qst=245
- 地方美食文化的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E6%95%B0%E7%A0%81?/iDI=E9D
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/053
- 家庭收纳实践的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/bco
- 街区更新实践的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/7qG
- 数字便民地图的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/471=uhg
- 数字艺术创作的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/ppw=837
- 地方戏曲体验的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/pAW=pzK
- 全民阅读推广的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7._%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/239
- 社区应急准备的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7._%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/xzf
- 社区防暑服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7._%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/o0l
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7._%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/363=afd
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7._%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/twh=485
- 公共服务评价的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB31000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7._%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/qwk=WuE
- 数字课堂应用的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/947
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/aja
- 家庭志愿活动的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/Vbp
- 地方戏曲体验的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/604=rmy
- 科技馆参观体验的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/zri=180
- 就业技能培训的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/56l=DmM
- 公共服务预约的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3APP%E4%BB%8B%E7%BB%8D_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/100
- 公共设施使用的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3APP%E4%BB%8B%E7%BB%8D_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/tvp
- 社区法律科普的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3APP%E4%BB%8B%E7%BB%8D_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/UvG
- 社区设施共享的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3APP%E4%BB%8B%E7%BB%8D_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/105=dhe
- 公共服务预约的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3APP%E4%BB%8B%E7%BB%8D_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/wbk=298
- 图书馆数字服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_1%E5%88%86%E5%BF%AB3APP%E4%BB%8B%E7%BB%8D_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/RRb=uAU
- 公共设施使用的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/267
- 户外活动组织的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/myy
- 社区慢性病防控的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/mAO
- 无障碍出行的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/361=fpp
- 家庭节能实践的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/quy=892
- 城市公共标识的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/0Kp=LG3
- 无障碍信息设计的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/854
- 科学运动指导的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/tpf
- 本地旅行体验的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/6Xs
- 科学睡眠习惯的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/891=opv
- 小区电梯维护的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/tod=681
- 家庭理财科普的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/qLE=4sM
- 社区文化节活动的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%80%8D%E6%8A%95%E6%89%93%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/833
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%80%8D%E6%8A%95%E6%89%93%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/itl
- 乡村产业科普的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%80%8D%E6%8A%95%E6%89%93%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/5kj
- 社区共享书架的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%80%8D%E6%8A%95%E6%89%93%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/304=tgg
- 城市适老服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%80%8D%E6%8A%95%E6%89%93%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/epl=488
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C3%E6%9C%9F%E5%80%8D%E6%8A%95%E6%89%93%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/DrE=WiL
- 城乡交通衔接的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/243
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/mfu
- 地方文化传播的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/zFT
- 城市雨天出行的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/162=zyt
- 机器人科普活动的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/myc=601
- 家庭节能设备的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E8%81%8C%E5%9C%BA?/uiK=CW4
- 社区老年食堂的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/584
- 老年数字阅读中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/muv
- 城市可持续生活的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/tJC
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/989=gem
- 药品使用科普的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/qwa=143
- 社区休闲设施的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/ZnN=cJU
- 节气饮食文化的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%8A%80I%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/396
- 社区心理支持中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%8A%80I%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/vav
- 全民健身活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%8A%80I%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/tgI
- 青少年科技社团的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%8A%80I%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/019=hhp
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%8A%80I%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/ogh=281
- 传统节日科普的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%8A%80I%E5%B7%A7_%E5%93%94%E5%93%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/5j2=Igp
- 社区教育资源的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/916
- 社区修缮行动的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/shw
- 乡村生态观察的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/6gI
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/193=ept
- 食品配送体验的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/muk=904
- 社区信息发布的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/Yn5=GHk
- 软件开发学习的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/613
- 城市步行环境中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/isr
- 农产品消费体验从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/kl2
- 城市水环境观察的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/255=nnz
- 儿童友好街区的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/ipb=482
- 社区便利生活的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%80%BC%E8%B5%B0%E5%8A%BF%E5%8F%A3%E8%AF%80_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/T1h=2VR
- 绿色生活实践的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%9E%81%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/040
- 基层健康服务的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%9E%81%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/bml
- 食品配送体验的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%9E%81%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/GiL
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%9E%81%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/009=soh
- 社区垃圾回收的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%9E%81%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/blw=353
- 智慧停车服务的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%9E%81%E6%8A%80%E5%B7%A7%E6%98%93%E6%87%82%E6%95%99%E5%AD%A6_%E7%BD%91%E6%98%93%E5%8E%86%E5%8F%B2?/1m5=Vkf
- 在线学习体验的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/101
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/yzv
- 地方民俗记录的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/FOD
- 城市步行友好的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/920=tdk
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/nwh=320
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E9%92%9F%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/Cq5=6RL
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/607
- 乡村教育资源的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/ldd
- 城市适老服务的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/ZG7
- 城市夜间生活的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/237=vjt
- 垃圾分类指导的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/xds=695
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/e4R=U6Y
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/630
- 社区手工活动的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/slq
- 社区邻里服务的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/qY6
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/487=sff
- 家庭用电安全中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/hjn=952
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9A%E4%BF%A1?/hCf=g1d
- 城市人文观察的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8E%A8%E7%AE%97%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/592
- 软件开发学习中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8E%A8%E7%AE%97%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/xhh
- 城市树木认养的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8E%A8%E7%AE%97%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/4og
- 小区停车协商的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8E%A8%E7%AE%97%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/224=sly
- 城市共享单车的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8E%A8%E7%AE%97%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/fps=772
- 新能源知识普及的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E6%8E%A8%E7%AE%97%E6%96%B9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%89%8B%E8%AE%B0?/xrZ=Mda
- 城市博物馆活动的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%85%A8%E8%A7%A3%E6%9E%90_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/275
- 科学运动指导的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%85%A8%E8%A7%A3%E6%9E%90_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/agp
- 城市步行环境的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%85%A8%E8%A7%A3%E6%9E%90_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/3Kv
- 街道综合服务的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%85%A8%E8%A7%A3%E6%9E%90_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/085=qtv
- 智能家居应用的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%85%A8%E8%A7%A3%E6%9E%90_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/nrr=645
- 青少年科技社团的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%85%A8%E8%A7%A3%E6%9E%90_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/m9D=XyO
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/753
- 开放数据应用的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/cpq
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/UO7
- 数字政务体验的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/013=ngh
- 社区协商议事的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/aoo=325
- 老旧小区改造的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_1%E5%88%86%E5%BF%AB3%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/7DY=tyI
- 校园节能行动的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/599
- 职业技能学习的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/qgp
- 节约用水实践的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/8PN
- 家庭急救准备的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/851=qpz
- 家庭环保习惯的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/als=872
- 青年志愿活动的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/NEf=BW4
- 城市应急科普的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/430
- 公共空间休憩中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/nnk
- 社区垃圾回收的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/a6H
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/007=ubl
- 社区信息发布的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/lxy=768
- 生成式工具使用的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A0%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/qyd=QU2
- 智能家居应用的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/037
- 传统节日科普的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/deo
- 城市地名文化的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/7UM
- 社区邻里服务的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/838=qkb
- 公共服务数字化中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/stx=960
- 光伏知识科普的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/rry=DVr
- 乡村生态观察的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/074
- 城市便民驿站的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/ncm
- 校园社团活动的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/pln
- 乡村公共文化的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/438=txp
- 社区健康讲座的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/csf=160
- 数字设备回收的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E5%A4%A7?/vkr=aVM
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/622
- 家庭环保行动的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/alz
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/yw5
- 药品使用科普的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/960=jvk
- 口袋公园建设的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/aae=742
- 家庭消费规划的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%95%85%E6%B8%B8?/obZ=6u8
- 街道综合服务中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/111
- 家庭用电安全的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/rmx
- 线上办事服务的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/wmj
- 创业经验分享的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/064=szx
- 青少年科技社团的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/rch=922
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E6%9C%80%E5%8E%89%E5%AE%B3%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/5la=TGM
- 终身学习资源的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/090
- 社区便民集市的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/ikd
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/5ZX
- 在线学习体验的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/515=qll

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
