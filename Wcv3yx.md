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

- 老旧小区改造的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/054
- 绿色校园实践的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/hzw
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/W3P
- 全民阅读推广的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/272=ddp
- 旧物循环利用的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/hut=325
- 机器人科普活动的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%88%E4%BA%8E%E7%A0%B4%E4%BA%8611%E9%80%895%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/hC8=iX4
- 数字阅读服务的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB?/939
- 青少年科普实践的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB?/dax
- 社区公共议事的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB?/GVQ
- 社区休闲设施的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB?/565=dtn
- 传统节日科普的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB?/mkp=384
- 机器学习入门的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A93d%E5%BF%85%E4%B8%AD%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB?/f1P=oWQ
- 基层服务创新的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/755
- 便民服务窗口中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/lxm
- 基层健康服务的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/3qL
- 医院导诊服务的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/572=upb
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/jwf=806
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E9%A1%BA%E4%B8%B0%E5%81%A5%E8%BA%AB?/VIc=IsP
- 休闲运动入门的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/129
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/uyz
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/WxB
- 城市体育设施的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/888=lup
- 绿色生活实践的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/shk=919
- 社区修缮行动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/85I=Qqa
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/074
- 绿色办公实践的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/djp
- 社区生活指南的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/4iy
- 消防知识宣传的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/685=zph
- 邻里互助活动的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/zxe=438
- 社区托育服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/sQ8=x2R
- 儿童阅读角中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/217
- 电子商务服务的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/ery
- 社区活动策划的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/vCR
- 城市展览体验的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/630=nbe
- 志愿服务平台的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/pgd=004
- 城市公共自行车的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E8%A7%84%E5%BE%8B%E8%AE%A1%E7%AE%97_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/5Us=uuu
- 社区科普课堂的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/783
- 公共卫生设施的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/lbg
- 家庭用电安全的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/tbJ
- 城市休闲步道的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/938=dqi
- 药品使用科普的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/dud=950
- 环境监测科普的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8F%8A%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%88%BF%E4%BA%A7?/8U9=O27
- 家庭阅读计划的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/619
- 公交站点体验的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/nvl
- 家庭网络使用的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/n7C
- 城市文化路线的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/162=cit
- 城市公共饮水的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/iqi=311
- 物业服务沟通的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3d%E7%BB%84%E5%85%AD%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/zMQ=U6h
- 终身学习资源的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/341
- 安全出行教育的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/pmv
- 智慧城市体验的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/FDy
- 绿色校园实践的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/868=mrn
- 城市社区治理的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/jao=621
- 家庭志愿活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_3d%E7%99%BE%E4%BD%8D%E8%83%86%E6%96%B9%E6%B3%95100%E5%87%86%E7%A1%AE_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/iCT=B5K
- 无障碍出行中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/660
- 科学健身方法的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/pkc
- 城市公共艺术的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/HxP
- 社区体育组织的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/595=fvw
- 儿童安全出行的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/des=768
- 创业经验分享有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/bHs=4M1
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%95%99%E8%82%B2?/178
- 租房信息服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%95%99%E8%82%B2?/zpe
- 无障碍信息设计的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%95%99%E8%82%B2?/iXn
- 公共服务数字化的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%95%99%E8%82%B2?/050=ijp
- 地方美食文化的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%95%99%E8%82%B2?/iuc=525
- 数字便民地图的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%95%99%E8%82%B2?/R7v=gVx
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/455
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/uat
- 老年学习活动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/9th
- 社区故事采集的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/275=xbl
- 社区安全巡查的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/ewm=000
- 青年就业服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E7%94%A8_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/Fw0=cKM
- 基层服务创新的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/151
- 家庭节能设备的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/zni
- 开源技术交流的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/jTX
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/491=rog
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/kng=496
- 公园休闲体验的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8Fapp_%E6%96%B0%E6%B5%AA%E5%85%9A%E5%BB%BA?/qr4=Ln3
- 社区垃圾分类的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/265
- 城市体育设施的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/nbt
- 城市微更新实践的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/rjR
- 城市展览体验的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/592=qao
- 社区便民集市的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/hni=994
- 街头绿植养护的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%97%85%E6%B8%B8?/VoM=yZx
- 便民维修服务的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_360%E5%8E%86%E5%8F%B2?/562
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_360%E5%8E%86%E5%8F%B2?/tcg
- 社区体育组织的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_360%E5%8E%86%E5%8F%B2?/7If
- 青年就业服务的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_360%E5%8E%86%E5%8F%B2?/460=lnn
- 社区安全巡查的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_360%E5%8E%86%E5%8F%B2?/jis=887
- 数字政务体验的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%8D%95%E5%8F%8C_360%E5%8E%86%E5%8F%B2?/CLr=6tW
- 公园休闲体验的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/604
- 社区活动空间中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/ubp
- 节假日出行安排的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/h7A
- 生成式工具使用的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/033=sdr
- 社区法律科普的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/kzc=387
- 社区慢性病防控的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E7%AE%97%E7%9A%84_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/BOP=sbo
- 城市博物馆服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/519
- 城市建设科普的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/azg
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ZZF
- 公园休闲体验的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/496=axx
- 家庭教育交流的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ocr=689
- 个人时间管理的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C9770%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ht3=FsR
- 老年数字阅读的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/077
- 青少年编程学习的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/zcc
- 便民信息查询的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/6z7
- 乡村生态观察的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/914=kse
- 个人时间管理的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/eyu=142
- 社区公共餐饮的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/Q19=8N6
- 公交站点体验的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/785
- 社区应急准备的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/vrh
- 节能生活方式的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/jVX
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/466=mak
- 城市文化路线的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/ppp=003
- 周末休闲规划的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E8%99%8E%E6%89%91%E5%BD%B1%E8%A7%86?/Jjj=YHf
- 城市水环境观察的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91-welcome_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/247
- 城市噪声观察的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91-welcome_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/kcj
- 城乡交流活动的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91-welcome_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/CXH
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91-welcome_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/326=nhs
- 街区道路维护的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91-welcome_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/gei=762
- 开放式学习空间的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91-welcome_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/egz=gRI
- 公共服务数字化的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/138
- 校园阅读活动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/fjm
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/Hwy
- 公共场所导视的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/769=qar
- 家庭环保习惯的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/bgk=761
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/GTA=6yw
- 家庭消费规划的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/665
- 基层医疗预约的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/mjo
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/a2e
- 城市文明出行的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/095=ped
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/sdm=692
- 城市运动公园的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/ujV=rgS
- 乡村休闲旅游中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/026
- 社区便民集市的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/ezn
- 城市展览体验的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/EqM
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/075=tsv
- 便民服务地图的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/goh=624
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%911.98%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/D6C=VU9
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/385
- 便民服务地图的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/eyq
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/oCZ
- 读书会组织的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/371=vcr
- 城市文明出行中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/zuy=125
- 城市建设科普的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/9UH=GN5
- 个人数据管理的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/333
- 新能源出行的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/hyl
- 农产品消费体验的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/otn
- 社区家政服务的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/974=lul
- 全民阅读推广的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/yyg=350
- 乡村公共阅读的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E8%B4%AD%E5%BD%A9%E4%B8%80%E6%9C%9F%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/WJX=1dl
- 社区消防演练的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/537
- 公共服务咨询的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/dge
- 城市应急广播的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/8wY
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/519=dem
- 运动安全知识的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/bvq=019
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E8%AF%80%E7%AA%8D_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/qen=yQe
- 志愿服务平台的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/430
- 运动安全知识的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/gop
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/SpX
- 家庭节能设备的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/698=kro
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/nel=395
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/osb=TDp
- 社区信息发布的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/083
- 绿色快递包装的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/qmx
- 终身学习资源的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/9C0
- 公共文化活动的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/365=dia
- 家庭安全提示的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/zub=655
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E6%8C%87%E5%AF%BC%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/WUE=r4A
- 邻里互助活动的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/672
- 线上阅读资源的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/bee
- 公共设施使用的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/i1P
- 家庭照护支持的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/019=yjc
- 城市运动公园的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/vob=254
- 家庭运动计划的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E9%BB%84%E5%A4%A7%E4%BB%99%E4%B8%89%E7%A0%81%E4%B8%89%E8%82%96%E5%BF%85%E4%B8%AD%E4%B8%80%E6%9C%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/ak5=hVD
- 运动安全知识的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/225
- 数字创作工具的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/xso
- 小区电梯维护的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/yyj
- 骑行路线规划的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/678=pwd
- 公共服务指南的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/tav=404
- 社区庭院绿化的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6_%E8%B4%A2%E7%BB%8F%E5%A8%B1%E4%B9%90?/Eny=jQn
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/937
- 城市夜间生活的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/etg
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/jrw
- 社区便民集市的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/499=kfu
- 邻里共享空间的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/ivo=455
- 运动安全知识的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E5%9B%9E%E8%A1%80_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/D8g=Y66
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/108
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/kff
- 城乡交通衔接的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/h1J
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/465=mpz
- 社区共享书架的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/aqr=266
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%85%AC%E5%BC%8F_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/D6K=g58
- 城市树木认养的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/573
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/uvt
- 公共设施维护的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/qSE
- 社区宠物管理的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/874=sxz
- 社区垃圾分类的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/kkf=005
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E6%97%85%E6%B8%B8?/MwF=J9C
- 城市可持续生活的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/173
- 城市可持续生活的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/kjx
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/Byr
- 数字政务体验的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/159=eru
- 社区便利生活的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/wbq=728
- 城市绿道建设的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%85%AC%E5%BC%8F_%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/yXt=lSv
- 社区协商议事的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/046
- 社区环保活动的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/nkg
- 城市农夫市集的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/38H
- 社区公共卫生的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/828=mfb
- 公共服务评价的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/soy=562
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BF%AB36%E6%8A%8A%E5%BF%85%E4%B8%AD%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/NHC=T0k
- 环境监测科普的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/026
- 家庭安全提示的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/mwr
- 青少年心理健康的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/sVw
- 公益活动组织的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/012=mhu
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/lzy=456
- 老年人日常照护的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/ibP=fSe
- 公共卫生设施的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/572
- 家庭理财科普的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/iyk
- 乡村产业科普的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/Hl0
- 城市建设科普的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/760=jrm
- 社区艺术活动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/fgv=067
- 绿色办公实践中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%A1%A8_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/tIu=1IH
- 生活垃圾回收的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/993
- 社区停车服务的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/huj
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/NWd
- 家庭养老规划的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/804=spm
- 灵活就业交流的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/gnm=822
- 家庭养老规划的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%90%9C%E7%8B%97%E7%BB%BC%E8%89%BA?/3g1=cLO
- 城市生活服务的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/894
- 文化讲座服务的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/aht
- 日常摄影记录的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/Bxs
- 农产品消费体验的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/583=msv
- 科学教育活动的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/lid=037
- 家庭阅读计划的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%85%AC%E5%BC%8F_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/Ryf=V8M
- 社区邻里服务的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/108
- 健康饮水科普的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/lny
- 社区设施共享的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/SG9
- 网络信息辨识的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/960=tgy
- 跨代沟通活动的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/iyl=596
- 城市公共艺术的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/xm2=R0d
- 机器人科普活动的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/522
- 城市应急科普的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/thi
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/flX
- 青少年户外教育从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/258=syn
- 人工智能科普的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/lmj=011
- 数字创作工具的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E7%BB%9D%E5%87%86%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/hC2=c5z
- 网络安全教育的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/628
- 青少年户外教育中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/lpx
- 城市地名文化的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/n8H
- 城市绿色交通的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BC%80%E5%A5%96%E8%A7%84%E5%BE%8B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%97%B6%E5%B0%9A?/858=muj

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
