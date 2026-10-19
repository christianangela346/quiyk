# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/lxk
- 志愿者培训交流的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/257=vqm
- 家庭饮食安排的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/tze=429
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%94%BE?/3LM=Oev
- 社区科普课堂的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/627
- 科学教育活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/rqn
- 公共交通接驳的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/Q2a
- 街区道路维护的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/180=ajf
- 儿童友好街区的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/zdq=770
- 社区文化传播的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E6%97%85%E6%B8%B8?/G4b=oUU
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D%E8%AF%A6%E7%BB%86_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/814
- 无障碍出行的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D%E8%AF%A6%E7%BB%86_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/pbm
- 机器学习入门的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D%E8%AF%A6%E7%BB%86_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/SOT
- 便民维修服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D%E8%AF%A6%E7%BB%86_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/822=ltr
- 社区知识分享的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D%E8%AF%A6%E7%BB%86_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/ifi=928
- 食品配送体验的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D%E8%AF%A6%E7%BB%86_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/ylz=jhV
- 环境监测科普的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E4%BF%A1%E6%89%98?/927
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E4%BF%A1%E6%89%98?/aoa
- 社区休闲设施的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E4%BF%A1%E6%89%98?/W4R
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E4%BF%A1%E6%89%98?/328=bsu
- 软件开发学习中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E4%BF%A1%E6%89%98?/kdy=467
- 城乡交流活动的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%8D%B3%E5%88%BB%E4%BF%A1%E6%89%98?/qER=Cfr
- 公共文化活动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/965
- 老年友好服务的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/shn
- 小区停车协商的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/WVk
- 公共卫生设施的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/843=alv
- 城市展览体验的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/xbh=800
- 社区养老服务的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3500%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/TNi=Sbw
- 数字学习资源的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/866
- 公共设施使用的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/rjo
- 社区公共卫生的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/5Lk
- 儿童户外活动的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/503=lfo
- 亲子科普活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/eun=222
- 社区阅读服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/ZdF=DPq
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/657
- 健康步道使用的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/xbn
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/lXn
- 旧物循环利用的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/105=zxk
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/mqr=734
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%AD%E8%89%BA?/Pgg=9M3
- 家庭网络使用的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89app%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/609
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89app%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/qrj
- 绿色建筑理念的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89app%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/YH2
- 公共文化活动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89app%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/966=bvm
- 节气饮食文化的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89app%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/han=145
- 社区菜市场服务的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89app%E5%A4%A7%E5%85%A8_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/bqQ=jsH
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8%E8%AE%A1%EF%BC%8F%E5%88%92_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/094
- 社区心理支持的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8%E8%AE%A1%EF%BC%8F%E5%88%92_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/xdp
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8%E8%AE%A1%EF%BC%8F%E5%88%92_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/DPx
- 户外活动组织的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8%E8%AE%A1%EF%BC%8F%E5%88%92_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/963=rcz
- 绿色生活实践的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8%E8%AE%A1%EF%BC%8F%E5%88%92_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/ver=994
- 城市人文观察的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB%EF%BC%8F3%E5%BD%A9%E7%A5%A8%E8%AE%A1%EF%BC%8F%E5%88%92_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/QSU=r3Y
- 家庭防灾准备的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/349
- 数字档案服务的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/vpt
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/04I
- 城市住房服务中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/069=yvw
- 学校体育活动的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/osj=947
- 青年职业探索的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/Nfd=LS8
- 便民维修服务的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/846
- 数字学习资源的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/hqz
- 通勤路线规划的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/sPY
- 城市公共饮水的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/804=xvk
- 公共卫生宣传的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/ckl=102
- 乡村文化活动的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%B0%B7%E6%AD%8C%E6%88%B7%E5%A4%96?/05I=aAM
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/972
- 社区活动策划的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/awo
- 家庭教育交流的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/Eqm
- 数字艺术创作的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/380=cyl
- 市民热线服务的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/jdg=642
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B8%89_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/te2=HRp
- 信息无障碍体验的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB36%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_36%E6%B0%AA%E6%97%B6%E8%AF%84?/927
- 社区花园共建的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB36%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_36%E6%B0%AA%E6%97%B6%E8%AF%84?/bhk
- 城市应急科普的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB36%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_36%E6%B0%AA%E6%97%B6%E8%AF%84?/HjE
- 社区儿童活动的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB36%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_36%E6%B0%AA%E6%97%B6%E8%AF%84?/221=lfh
- 城市绿色交通的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB36%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_36%E6%B0%AA%E6%97%B6%E8%AF%84?/emb=432
- 通勤路线规划的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB36%E7%A0%81%E9%98%B6%E6%A2%AF%E5%BC%8F%E8%B6%85%E7%BA%A7%E5%80%8D%E6%8A%95%E6%B3%95_36%E6%B0%AA%E6%97%B6%E8%AF%84?/bsH=MsN
- 课后服务体验的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/758
- 老年数字阅读的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/xne
- 社区体育组织的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/csU
- 日常摄影记录中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/793=qwd
- 节能家电使用的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/eyv=512
- 小区停车协商的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/xUc=qD6
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/518
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/vqq
- 城市文明实践的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/Zbe
- 地方民俗记录的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/616=bro
- 电子商务服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/xmy=786
- 在线学习体验的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86%E5%BD%A9app%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E5%91%A8%E6%8A%A5?/Jg8=bL2
- 公园亲子设施的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_360%E6%98%9F%E5%BA%A7?/889
- 公共服务咨询的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_360%E6%98%9F%E5%BA%A7?/wdq
- 城市文化路线的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_360%E6%98%9F%E5%BA%A7?/ASQ
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_360%E6%98%9F%E5%BA%A7?/359=ogq
- 街区小店体验的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_360%E6%98%9F%E5%BA%A7?/ted=958
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app_360%E6%98%9F%E5%BA%A7?/HeG=DU8
- 健康饮水科普的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E5%BD%A9%E7%9A%84%E5%A5%97%E8%B7%AF1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/355
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E5%BD%A9%E7%9A%84%E5%A5%97%E8%B7%AF1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/bwg
- 农村环境治理的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E5%BD%A9%E7%9A%84%E5%A5%97%E8%B7%AF1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/cMe
- 绿色办公实践的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E5%BD%A9%E7%9A%84%E5%A5%97%E8%B7%AF1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/856=ceq
- 家庭饮食安排的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E5%BD%A9%E7%9A%84%E5%A5%97%E8%B7%AF1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/zft=601
- 公共设施使用的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E4%BA%94%E5%88%86%E5%BD%A9%E7%9A%84%E5%A5%97%E8%B7%AF1%E5%88%86%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%85%A7%E7%9C%BC?/s40=O9F
- 儿童户外活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/413
- 软件开发学习的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/mxf
- 城市步行友好的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/CeI
- 生成式工具使用的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/561=duq
- 家庭安全提示的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/dnt=199
- 家庭安全提示的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%A6%82%E4%BD%95%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/SV3=LK4
- 居民健康教育的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88app_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/409
- 社区消防演练的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88app_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ebo
- 公共空间照明的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88app_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/wZU
- 健康信息获取的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88app_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/431=ann
- 街区小店体验的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88app_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/jlc=866
- 社区庭院绿化的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%94%A8%E4%BB%80%E4%B9%88app_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/FUX=pSV
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/286
- 城市运动公园的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/vir
- 家庭急救准备的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/U3U
- 城市公共艺术的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/025=qys
- 社区法律科普的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/dnh=849
- 租房信息服务的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/ATd=fQ0
- 社区交通安全的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/578
- 传统节日科普的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/puu
- 乡村阅读空间的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/Ma6
- 居家防滑改造中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/540=nno
- 基层服务创新的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/nhn=811
- 城市公共饮水的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E4%B8%93%E9%A2%98?/xVZ=dSj
- 节约用水实践的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/358
- 城市共享单车的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/yzd
- 租房信息服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/DR7
- 乡村生态观察的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/759=vbl
- 儿童运动体验的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/yii=886
- 急救知识普及的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E7%95%85%E6%B8%B8?/aUP=pmD
- 乡村文化活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E8%AE%B0%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/088
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E8%AE%B0%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/tcg
- 数字档案服务中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E8%AE%B0%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/BYh
- 基层服务创新的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E8%AE%B0%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/855=ewl
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E8%AE%B0%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/stq=235
- 乡村公共服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B0%8A%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E8%AE%B0%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/rKd=e4m
- 市民意见收集的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%882-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/046
- 社区家政服务的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%882-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/fzu
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%882-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/tVB
- 户外活动组织的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%882-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/259=zqn
- 公共交通接驳的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%882-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/eai=266
- 机器学习入门的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%882-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/D0b=BXp
- 急救知识普及的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A6%82%E6%84%8F%E5%BD%A9-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/699
- 数字地图应用的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A6%82%E6%84%8F%E5%BD%A9-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/txm
- 青少年心理健康的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A6%82%E6%84%8F%E5%BD%A9-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/jEn
- 气象科普传播的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A6%82%E6%84%8F%E5%BD%A9-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/206=nnm
- 急救知识普及的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A6%82%E6%84%8F%E5%BD%A9-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/uzs=035
- 城市文明出行的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A6%82%E6%84%8F%E5%BD%A9-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/Xmm=7Mo
- 城市生活服务的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/953
- 城市住房服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/npl
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/aIV
- 家庭节能实践的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/693=onb
- 老年数字阅读的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/asy=731
- 生活技能分享的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/Y2n=15E
- 街道综合服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%85%8D%E8%B4%B9%E7%89%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/171
- 街区小店体验的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%85%8D%E8%B4%B9%E7%89%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/ywi
- 社区活动空间的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%85%8D%E8%B4%B9%E7%89%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/MGe
- 城市便民驿站的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%85%8D%E8%B4%B9%E7%89%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/515=bdv
- 数字学习资源的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%85%8D%E8%B4%B9%E7%89%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/ies=537
- 消防知识宣传的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%85%8D%E8%B4%B9%E7%89%88_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/l5x=rxs
- 城市公共艺术的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E5%A4%A7?/829
- 青少年户外教育的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E5%A4%A7?/vtf
- 公共服务指南的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E5%A4%A7?/Sya
- 社区儿童活动的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E5%A4%A7?/159=fit
- 线上阅读资源的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E5%A4%A7?/rwx=813
- 社区便利生活的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9Welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E4%BA%BA%E5%A4%A7?/XU6=cVE
- 城市生活服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%B1%E5%BA%A6%E6%B7%B1%E6%8C%96%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/720
- 社区停车服务的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%B1%E5%BA%A6%E6%B7%B1%E6%8C%96%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/ajh
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%B1%E5%BA%A6%E6%B7%B1%E6%8C%96%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/DPo
- 社区信息发布的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%B1%E5%BA%A6%E6%B7%B1%E6%8C%96%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/095=gqt
- 志愿者培训交流的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%B1%E5%BA%A6%E6%B7%B1%E6%8C%96%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/pch=126
- 青年志愿活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%B7%B1%E5%BA%A6%E6%B7%B1%E6%8C%96%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E5%AE%89%E5%8D%93%E6%9C%80%E6%96%B0%E7%89%88_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/4md=mw3
- 公共场馆服务的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/729
- 社区托育服务的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/plv
- 社区养老服务的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/y5T
- 社区垃圾分类的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/447=nbi
- 青少年编程学习的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/qet=195
- 城市社区治理的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9welcome%E9%A6%96%E9%A1%B5_%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F?/lpa=o9r
- 日常摄影记录的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%B1%87welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/360
- 人工智能科普的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%B1%87welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/pot
- 机器学习入门的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%B1%87welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/gdq
- 城乡公共服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%B1%87welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/013=fof
- 智慧城市体验的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%B1%87welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/imd=436
- 低碳社区实践的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E6%B1%87welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/v80=amM
- 城市绿道建设的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/835
- 街区小店体验的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/zev
- 街区更新实践的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/I43
- 全民阅读推广的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/734=hec
- 课后服务体验的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/yec=707
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E5%85%A8%E6%B0%91%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%85%AC%E5%91%8A?/8FK=riN
- 城市夜间照明的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/510
- 老年人出行服务的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/gej
- 智能手机助老的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/EgF
- 社区快递服务的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/391=nlu
- 社区消防演练的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/vfd=701
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%AB%9E%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%B9%B6%E8%B4%AD?/euc=oAX
- 开放数据应用的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/868
- 健康饮水科普的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/kjv
- 骑行路线规划的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/K6k
- 城市步行友好的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/497=tdq
- 邻里共享空间的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/vxk=655
- 网络安全教育的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%9A%E6%8A%A5%E8%B4%A2%E7%BB%8F?/bgD=RHb
- 公共卫生设施的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8APP._%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/534
- 家庭网络使用的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8APP._%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/xnm
- 城市步行环境的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8APP._%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/E4e
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8APP._%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/104=wkd
- 家庭运动计划的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8APP._%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/eod=931
- 休闲运动入门的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%AE%89%E5%85%A8%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8APP._%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/r8I=dbS
- 家庭收纳实践的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E6%9C%80%E5%AE%89%E5%85%A8%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/377
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E6%9C%80%E5%AE%89%E5%85%A8%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/fbw
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E6%9C%80%E5%AE%89%E5%85%A8%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/LEv
- 公共服务沟通的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E6%9C%80%E5%AE%89%E5%85%A8%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/370=eae
- 数字便民地图的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E6%9C%80%E5%AE%89%E5%85%A8%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/jpn=606
- 社区活动策划的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E6%9C%80%E5%AE%89%E5%85%A8%E5%BD%A9%E7%A5%A8app_%E5%A4%AE%E8%A7%86%E6%99%A8%E6%8A%A5?/Klz=TsF
- 家庭食品保存的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/889
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/qhu
- 城市公共空间的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/69U
- 环境监测科普的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/760=mlc
- 城市公共自行车的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/yng=219
- 科学观察活动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/5ne=SHk
- 农产品消费体验的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B8%A6_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/790
- 社区公共议事中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B8%A6_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/uik
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B8%A6_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/yAf
- 城市微更新实践的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B8%A6_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/033=bqp
- 公共服务评价的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B8%A6_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/miw=180
- 公交站点体验的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B8%A6_%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/i6H=sh5
- 生活垃圾回收的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/650
- 公益活动组织的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/vxs
- 城市博物馆服务的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/dDi
- 城市雨天出行的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/281=kfq
- 青年志愿活动的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/cdy=922
- 社区商业活力的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/BJH=9M7
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/133
- 图书馆数字服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/hnt
- 街道综合服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/rRa
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/971=iui
- 城市地名文化的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/ogk=229
- 校园阅读活动的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/7PE=2cM
- 家庭园艺实践的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/141
- 社区文化节活动的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/suv
- 骑行路线规划的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/dbB
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/169=rgs
- 数字创作工具的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/mdj=175
- 社区协商议事的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E5%81%A5%E8%BA%AB?/EKF=2Su
- 校园阅读活动的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/533
- 非遗课堂体验的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/jpc
- 社区环保活动的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/R3d
- 数字生活课堂的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/769=fbv
- 城市绿色交通的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/ncz=199
- 公共服务指南的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/FRE=H68

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
