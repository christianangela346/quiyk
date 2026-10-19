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

- 健康饮食教育的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C-%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/sfa=012
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C-%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/BSI=RU2
- 文明养宠科普的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5-%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/035
- 家庭园艺实践的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5-%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/gqs
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5-%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/g9g
- 气象科普传播的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5-%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/486=zye
- 基层医疗预约的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5-%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/may=221
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5-%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/htj=R9X
- 城市应急科普的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84-%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/475
- 智能家居应用的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84-%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/wxi
- 城市公共艺术的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84-%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/sZk
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84-%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/959=rkm
- 无障碍信息设计的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84-%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/cop=258
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84-%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/eVa=KYU
- 生活垃圾减量的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/149
- 社区休闲设施的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/roh
- 公共设施维护的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/NJh
- 乡村文化活动的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/472=ziw
- 青年志愿活动的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/wuf=356
- 骑行路线规划的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/UUJ=IH7
- 健康饮水科普的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/703
- 无障碍出行的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/nco
- 居民健康教育的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/h4M
- 公共空间导览的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/340=gno
- 农业科普体验的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/zyo=741
- 青少年科技社团的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9A%E4%BF%A1?/iXz=xXd
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/694
- 家庭运动计划的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/phj
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/Fug
- 就业技能培训的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/585=man
- 社区绿色空间的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/sdx=452
- 文化场馆预约中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/MU2=Ou1
- 城市体育设施的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F-%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/543
- 家庭用电安全的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F-%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/scn
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F-%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/5DS
- 城市绿道建设的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F-%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/300=lgo
- 社区生活指南的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F-%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/dij=615
- 家庭用电安全的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F-%E9%A1%BA%E4%B8%B0%E6%9C%8D%E9%A5%B0?/eQD=Wwv
- 数据分析入门的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80-%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/523
- 口袋公园建设的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80-%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/igv
- 社区活动策划的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80-%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/5Pl
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80-%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/584=foz
- 数字支付体验的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80-%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/dcb=089
- 社区故事采集的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80-%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/4rx=6Ao
- 非遗体验活动的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/168
- 老年人出行服务的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/hcz
- 药品使用科普的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/8vV
- 街道综合服务的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/917=fin
- 社区商业活力的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/prd=123
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/8gh=Wid
- 生活垃圾回收的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/901
- 开放式学习空间的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/bvu
- 健康信息获取的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/TFN
- 食品安全科普的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/623=wij
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/qze=381
- 节气饮食文化的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/yPy=EQi
- 社区家政服务的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/552
- 学校食育活动的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/rvi
- 社区交通安全的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/3FL
- 居家防滑改造的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/410=ufx
- 社区手工活动的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/qhj=971
- 数据分析入门的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95-%E5%BF%AB%E6%89%8B%E4%BF%A1%E8%B4%B7?/KQf=Plu
- 儿童安全出行的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/604
- 老旧小区改造的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/xap
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/oYo
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/122=ghk
- 邻里共享空间的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/yas=419
- 口袋公园建设的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/vPZ=84h
- 个人信息保护的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/324
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/gva
- 急救知识普及的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/7kO
- 青年志愿活动的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/094=jur
- 日常摄影记录的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/zqx=782
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E5%9B%AD%E8%89%BA?/HA2=vYv
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/942
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/reh
- 便民维修服务的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/Y7X
- 公交站点体验的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/362=rhm
- 周末休闲规划中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/wjy=254
- 公共空间休憩的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%8D%9A%E5%AE%A2?/046=wbT
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/837
- 通勤路线规划的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/nif
- 光伏知识科普的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/Tmr
- 城市生活记录的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/761=xhr
- 城市公共厕所的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/fox=328
- 社区便民服务的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E8%84%89%E8%84%89%E8%83%BD%E6%BA%90?/7JC=n3Y
- 志愿服务平台的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/861
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/jhb
- 公共卫生宣传的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/pwl
- 无障碍出行的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/426=wsi
- 社区垃圾分类的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/kzp=044
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/xz1=7RI
- 城市水环境观察的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/102
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/wao
- 城市应急科普的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/A6a
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/776=kha
- 社区生活指南的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/ruu=149
- 社区花园共建的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/MJB=2d3
- 社区手工活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/715
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/lgv
- 数字公共文化的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/2PV
- 家庭志愿活动的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/644=jaz
- 节日文化体验的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/crw=512
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/iTZ=mdt
- 社区家政服务的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/402
- 城市地名文化的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/nyt
- 电动汽车充电的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/uuo
- 公共服务咨询的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/405=fyg
- 公交无障碍服务的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/etc=970
- 街区道路维护的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8A%A1?/Iki=mII
- 开放式学习空间的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/360
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/zsl
- 老年数字阅读的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/eAx
- 老年运动活动的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/703=gkl
- 社区垃圾分类的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/mov=154
- 城市公共空间的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E8%A7%A3%E5%AF%86?/LyC=a8Q
- 城市生活记录的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/033
- 基层健康服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/jrh
- 环境教育课程的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/Tjg
- 便民信息查询的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/072=pkr
- 口袋公园建设的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/zzv=759
- 社区互助网络的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B-%E4%B8%B0%E6%B3%BD%E8%B4%A2%E7%BB%8F?/E3g=zAn
- 社区手工活动的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80-%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/306
- 农业科普体验的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80-%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/bsn
- 科普展览体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80-%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/Ryi
- 城市休闲步道的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80-%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/644=uhe
- 社区故事采集的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80-%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/hus=940
- 小区电梯维护的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80-%E6%BE%8E%E6%B9%83%E6%9C%8D%E9%A5%B0?/fDr=6Dm
- 社区健康讲座的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5-%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/576
- 公园无障碍服务的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5-%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/yxi
- 城市运动公园的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5-%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/ymt
- 小微企业服务中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5-%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/879=zpq
- 公益活动组织的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5-%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/nnl=392
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5-%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/P90=PQB
- 本地消费场景的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/376
- 数字阅读服务的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/lyp
- 公共空间休憩中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/BFV
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/221=uyo
- 基层健康服务的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/qad=430
- 科学观察活动的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0-%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/uok=PHF
- 本地消费场景的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/106
- 数字支付体验的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/bol
- 消防知识宣传的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/r16
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/243=pge
- 公交无障碍服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/cni=604
- 数字生活课堂的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E6%99%9A%E6%8A%A5?/J9O=g21
- 节约用水实践的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023-%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/876
- 社区应急准备的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023-%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/imb
- 社区儿童活动的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023-%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/mny
- 城市便民驿站的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023-%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/806=poh
- 数字便民地图的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023-%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/nhx=336
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2023-%E5%BF%85%E5%BA%94%E6%B0%91%E7%94%9F?/Iy1=Wjp
- 本地旅行体验的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/367
- 青年就业服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/off
- 就业技能培训的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/yNE
- 社区心理支持的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/937=wta
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/ith=148
- 户外活动组织的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BF%AB31%E5%88%86%E5%BF%AB3%E6%8E%A8%E8%8D%90%E5%B9%B3%C2%B7%E5%8F%B0-%E8%99%8E%E5%97%85%E4%BC%97%E6%B5%8B?/pgM=fzB
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/442
- 社区养老服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/jbr
- 社区休闲设施的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/bXx
- 数字支付体验的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/026=mli
- 安全出行教育的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/hhz=445
- 儿童阅读角的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6-%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/rNB=eDO
- 农产品品牌传播的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/081
- 数字档案服务的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/ujy
- 课后服务体验的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/GyM
- 科技馆参观体验的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/912=xim
- 基层健康档案中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/sac=122
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/oSS=8ho
- 开源技术交流的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/916
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/gxs
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/q5f
- 科普展览体验的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/783=sha
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/cig=993
- 气象科普传播的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/CVj=Nwg
- 数字课堂应用的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/364
- 图书馆活动策划的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/xgx
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/SNK
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/709=odu
- 社区应急准备的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/cfs=441
- 街道综合服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E8%8B%B9%E6%9E%9C%E7%89%88-%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/0Z8=2ZH
- 旧物循环利用中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/642
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/swr
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/A9O
- 软件开发学习的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/500=yua
- 城市文明实践的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/spn=475
- 绿色办公实践的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%9F%E6%9C%9F%E5%BF%85%E4%B8%AD-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/Hp0=HmC
- 公共服务预约的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/010
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/ddk
- 非遗体验活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/lEo
- 城市农夫市集的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/968=byg
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/wmv=832
- 社区读书角建设的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/mr7=zJK
- 公共设施维护的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/246
- 节假日出行安排的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/qbq
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/6nL
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/749=kap
- 社区交通安全的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/yfz=657
- 社区花园共建的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/7Tz=e1D
- 文化讲座服务的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/021
- 城乡交通衔接的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/zuy
- 校园阅读活动的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/ME6
- 社区体育组织的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/986=pbj
- 城市绿道建设的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/ryj=916
- 应急物资管理的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/wBj=nLJ
- 公交站点体验的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/632
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/zbt
- 城市生活服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/0zJ
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/639=lse
- 市民意见收集的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/mei=546
- 小区公共照明中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E8%BD%AF%E4%BB%B6-%E8%B1%86%E7%93%A3%E9%80%9F%E8%A7%88?/PhW=DSK
- 科学教育活动的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD-360%E5%9F%BA%E9%87%91?/968
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD-360%E5%9F%BA%E9%87%91?/nmk
- 户外活动组织的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD-360%E5%9F%BA%E9%87%91?/HOb
- 数字资源检索的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD-360%E5%9F%BA%E9%87%91?/078=znl
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD-360%E5%9F%BA%E9%87%91?/hqr=503
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD-360%E5%9F%BA%E9%87%91?/xWc=anN
- 便民服务窗口的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/969
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/tfw
- 城市步行友好的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/KgO
- 家庭理财科普的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/282=vus
- 乡村文化空间的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/agx=838
- 家庭科学教育的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E8%85%BE%E8%AE%AF%E6%97%85%E6%B8%B8?/dlR=TQ4
- 周末休闲规划的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/338
- 社区绿色空间的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/stt
- 青少年户外教育的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/VSP
- 公共交通接驳的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/119=ytk
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lgj=273
- 老年人文化生活的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/CGb=RWK
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9-36%E6%B0%AA%E6%BC%AB%E8%AF%84?/636
- 社区公共议事的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9-36%E6%B0%AA%E6%BC%AB%E8%AF%84?/xjx
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9-36%E6%B0%AA%E6%BC%AB%E8%AF%84?/WPP
- 青年职业探索的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9-36%E6%B0%AA%E6%BC%AB%E8%AF%84?/707=wmk
- 街区绿化养护的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9-36%E6%B0%AA%E6%BC%AB%E8%AF%84?/cbu=876
- 社区环保活动的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B5%8C%E9%92%B1%E8%BD%AF%E4%BB%B61%E5%85%83%E5%8F%AF%E4%BB%A5%E7%8E%A9-36%E6%B0%AA%E6%BC%AB%E8%AF%84?/6le=HNd
- 街区小店体验的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/035
- 城市空气科普的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/egl
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/x00
- 街区更新实践的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/822=eob
- 城市慢跑路线的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/lui=212
- 城市夜间照明的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%BF%AB3%E9%80%81%E5%BD%A9%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/paC=C0o
- 数字档案服务的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/517
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/dle
- 公共空间安全的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/stn
- 家庭健康科普的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/915=xri
- 生活服务数字化中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/ats=071
- 新能源知识普及中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B9%B0%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%B2%BE%E5%87%86%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/uHL=q8m
- 应急物资管理的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B-%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/727
- 消防知识宣传的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B-%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/xog

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
