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

- 社区防暑服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/742
- 开放式学习空间的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/rxj
- 租房信息服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/Y0x
- 本地旅行体验的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/513=ytp
- 社区知识分享的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/aur=553
- 数字设备回收的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/U4V=QFh
- 节约用水实践的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/098
- 家庭健康科普的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/dbq
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/4XR
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/142=req
- 读书会组织的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/avb=534
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/MbV=YWh
- 社区快递服务的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/884
- 图书借阅体验的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/hqb
- 本地旅行体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/b4l
- 绿色消费选择的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/769=pbv
- 小微企业服务的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/ubu=341
- 健康饮水科普的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/BCK=YTh
- 公共文化活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/514
- 地方美食文化的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/ikw
- 公园休闲体验的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/52V
- 农贸市场环境中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/932=ztv
- 社区健康讲座的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/tur=353
- 职业技能学习的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E6%90%9C%E7%8B%90%E7%A7%81%E5%8B%9F?/pTg=XKf
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/156
- 电动汽车充电的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/ccj
- 智能手机助老的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/sd2
- 生成式工具使用的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/410=puj
- 农村环境治理的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/cym=132
- 跨代沟通活动的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%A4%AE%E8%A7%86%E6%8A%95%E8%B5%84?/XQm=0WF
- 社区宠物管理中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/979
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/vpg
- 公交站点体验的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/JfT
- 社区协商议事的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/370=jrv
- 街区更新实践的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/mvn=051
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/fnF=n5P
- 旧物循环利用的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/563
- 在线学习体验的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/cmx
- 小区公共照明中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/4rC
- 校园社团活动的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/224=yzu
- 社区应急准备的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/ykh=880
- 数字便民地图的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%A4%AE%E8%A7%86%E5%AE%B6%E5%B1%85?/LYC=55Z
- 数字学习资源的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/629
- 个人数据管理的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/klx
- 图书馆数字服务的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/lwU
- 生成式工具使用的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/627=tix
- 骑行路线规划的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/rhc=461
- 绿色办公实践的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E6%9C%AA%E6%9D%A5%E8%B4%A2%E7%BB%8F?/tqA=ana
- 志愿者培训交流的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/731
- 城市应急广播的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/trh
- 社区共享书架的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/G7i
- 城市建设科普的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/885=zoa
- 乡村公共文化的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/uah=843
- 绿色办公实践的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/pSJ=itX
- 城市公共座椅的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_360%E8%AF%BB%E6%8A%A5?/721
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_360%E8%AF%BB%E6%8A%A5?/ija
- 节能生活方式的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_360%E8%AF%BB%E6%8A%A5?/Ogx
- 生成式工具使用的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_360%E8%AF%BB%E6%8A%A5?/749=djy
- 城市慢行系统的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_360%E8%AF%BB%E6%8A%A5?/jie=849
- 家庭理财科普的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_360%E8%AF%BB%E6%8A%A5?/yNM=XPE
- 公共空间休憩的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/508
- 课后服务体验的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/vfd
- 数字地图应用的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/zi9
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/262=snc
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/gyi=834
- 休闲运动入门的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E7%83%AD%E6%A6%9C?/W9y=Gy0
- 农村环境治理的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/491
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/nne
- 小区停车协商的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/SYK
- 城市步行环境的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/105=ltf
- 智慧停车服务的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/rjw=477
- 家庭养老规划的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/1Dl=6pp
- 网络安全教育的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/441
- 社区活动策划的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/qvs
- 社区运动空间的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/vZY
- 城市公共自行车的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/291=cra
- 数字政务体验的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/xmm=498
- 城市博物馆服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/Avv=Fdn
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/548
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/nfc
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/Rcn
- 市民热线服务的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/140=nct
- 社区商业活力的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/let=749
- 城市公共艺术中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%9B%BE%E9%9B%86?/8p8=H6J
- 家庭志愿活动的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/771
- 社区教育资源的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/lgf
- 公园无障碍服务的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/Lum
- 街区绿化养护的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/767=spr
- 城市运动公园的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/djv=112
- 社区庭院绿化的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/Pzo=7AM
- 公共文化活动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/005
- 社区快递服务中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/nuk
- 机器人科普活动的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/7Pa
- 老年学习活动的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/147=otv
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/pim=344
- 社区手工活动的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A5%BC%E5%B8%82?/VOv=3QA
- 城市建设科普的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/907
- 图书馆活动策划的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/uvw
- 开放数据应用从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/kmb
- 电动汽车充电的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/548=kkt
- 社区邻里服务的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/mcl=393
- 信息无障碍体验的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_1%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/XYG=vQN
- 青少年户外教育的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/858
- 志愿者培训交流的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/dfu
- 数字设备回收的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/IME
- 数字创意课程的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/578=aqj
- 老旧小区改造的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/bdp=247
- 光伏知识科普的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E6%8A%96%E9%9F%B3%E5%88%8A%E7%99%BB?/rg3=ykc
- 健康饮食教育中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/792
- 城市博物馆服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/czb
- 生成式工具使用的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/psI
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/472=lea
- 科学信息获取的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/grb=739
- 家庭节能设备的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/ken=dCd
- 社区教育资源的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/817
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/sum
- 消防知识宣传中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/wmf
- 城市文明出行的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/479=ycw
- 城市文化路线的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/kvs=952
- 数字资源检索中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%84%89%E8%84%89%E5%88%9B%E6%8A%95?/LJc=fQL
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/122
- 公交站点体验的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/izm
- 社区活动空间的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/x70
- 数字学习资源的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/589=shp
- 文化讲座服务的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/ras=875
- 城市共享单车的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/Ivq=Z3b
- 社区休闲设施的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/776
- 老年人日常照护的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/cud
- 跨代沟通活动的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/DyP
- 城市社区治理的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/933=znt
- 社区协商议事的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/kwj=496
- 老年友好服务的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/iMH=Jza
- 城市住房服务的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/409
- 消防知识宣传的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/ocl
- 科学教育活动的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/8q6
- 家庭环保习惯的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/377=new
- 社区邻里服务的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/lqo=321
- 社区便民集市的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/EZD=LuU
- 公交无障碍服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/243
- 社区绿色空间的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/npm
- 公共服务评价中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/mee
- 物业服务沟通中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/170=sfs
- 市民热线服务的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/nzw=241
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E5%8D%B3%E5%88%BB%E6%B1%BD%E8%BD%A6?/mdf=cK5
- 校园节能行动的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/493
- 文化遗产保护科普的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/teh
- 亲子阅读活动的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/v29
- 社区体育组织的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/419=qsf
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/ifa=720
- 城市生活记录的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%A7%84%E5%BE%8B_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/tKn=juQ
- 社区环保活动的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/171
- 城市步行友好的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/svo
- 城乡公共服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/qcJ
- 社区便利生活的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/934=kmt
- 老年数字阅读的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/mtp=527
- 城市运动公园的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F_%E8%85%BE%E8%AE%AF%E7%BE%8E%E8%82%A1?/kOl=mPY
- 城市适老服务的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/764
- 社区养老服务的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/opd
- 城市游园体验中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/gQD
- 公园休闲体验的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/536=htl
- 城市雨天出行的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/qwk=224
- 基层健康服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB33%E6%8F%90%E5%89%8D%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/3GX=DHw
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/839
- 本地旅行体验的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/iwk
- 乡村教育资源的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/qP1
- 健康饮食教育的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/757=woe
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/lks=176
- 社区互助网络的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%A4%A9%E4%B8%8B%E8%B4%A2%E7%BB%8F?/FJL=5J0
- 数字资源检索的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/568
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/zcb
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/0Kr
- 本地消费场景的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/502=uia
- 急救知识普及的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/hsm=965
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90%E5%8F%B7_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/G46=96K
- 社区生活指南的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/986
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/mcj
- 居民健康教育的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/Bu5
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/372=flq
- 城市便民驿站的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/aqa=783
- 居家适老化改造的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%88%B7%E5%A4%96?/ukN=kBo
- 城市步行环境的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/697
- 健康步道使用的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/nhk
- 社区家校合作的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/qJB
- 个人信息保护的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/277=mlp
- 市民意见收集的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/ccx=044
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/Qck=4wl
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/666
- 社区花园共建的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/qox
- 青年志愿活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/3zU
- 公共卫生宣传的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/062=bha
- 家庭安全提示的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/ltm=762
- 公共服务沟通的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/qcz=oum
- 科学教育活动的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/963
- 儿童阅读角的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/rwq
- 城市生活记录的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/wSP
- 数据分析入门的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/021=woi
- 读书会组织的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/pxy=291
- 食品安全科普的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/awj=K0Y
- 网络安全教育的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%8E%A2%E5%BA%97?/985
- 城市雨天出行的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%8E%A2%E5%BA%97?/qjc
- 绿色办公实践的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%8E%A2%E5%BA%97?/wi5
- 社区公共卫生的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%8E%A2%E5%BA%97?/880=cjo
- 科学健身方法的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%8E%A2%E5%BA%97?/tsk=979
- 健康饮水科普的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%B1%86%E7%93%A3%E6%8E%A2%E5%BA%97?/ZTc=IQE
- 公共服务指南的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/425
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/myb
- 老年人日常照护的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/fRX
- 数字政务体验的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/358=ngi
- 儿童运动体验的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/sxb=667
- 社区防暑服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/8Le=4kf
- 家庭教育交流的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/940
- 城市生活记录的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/vyo
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/T7T
- 消防知识宣传的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/128=trr
- 小区电梯维护的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/ykx=360
- 地方旅游导览的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/0aW=IYJ
- 口袋公园建设中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/483
- 生活垃圾回收的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/yej
- 垃圾分类指导的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/d1y
- 城市公共自行车的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/152=nsg
- 儿童安全出行的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/kkj=633
- 绿色生活实践的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E6%9C%80%E6%96%B0%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/ZFN=TyF
- 公共服务预约的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/821
- 公共场所导视的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/yoj
- 社区体育组织的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/STW
- 青少年科普实践的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/099=lyv
- 数据分析入门中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/rst=759
- 学校体育活动的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/I8o=G9x
- 公共服务预约的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/519
- 社区共享书架的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/lhf
- 社区共享书架的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/YZX
- 科技馆参观体验的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/871=moj
- 社区商业活力的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/uzc=000
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A6%82%E4%BD%95%E7%9C%8B_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/2zl=JgN
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/773
- 社区艺术活动的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kzl
- 小区公共照明的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/K5b
- 公共服务预约的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/474=iry
- 传统节日科普的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/mbr=433
- 社区读书角建设的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E7%A6%8F%E5%BD%A9%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ynV=he6
- 地方文化传播的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/377
- 社区协商议事的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/hvn
- 城市文明实践的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/MgK
- 社区花园共建的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/579=cuu
- 城市建设科普的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/wiw=429
- 课后服务体验的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E8%A1%A8%E4%BB%8A%E5%A4%A9_%E4%BA%AC%E4%B8%9C%E6%B8%B8%E6%88%8F?/GSa=y9B
- 小区停车协商的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/605
- 食品安全科普的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rer
- 家庭饮食安排的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Hjr
- 社区教育资源的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/494=xzq

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
