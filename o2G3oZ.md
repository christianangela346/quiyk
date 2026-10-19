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

- 家庭环保行动的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/BZA
- 居民健康教育的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/262=yfr
- 绿色出行服务的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/lsf=770
- 志愿者培训交流的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A10%E5%A4%A7%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E4%BA%A7?/dkY=0dI
- 城市博物馆活动的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/490
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/bdn
- 家庭网络使用的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/eMe
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/714=kfh
- 社区文化节活动的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/xcd=041
- 健康步道使用中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/5lZ=qfS
- 无障碍信息设计的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/411
- 社区活动策划的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/bpt
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/kgk
- 城市公共饮水的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/947=rmk
- 线上阅读资源中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/gib=846
- 休闲运动入门中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8CAPP%E6%8E%A8%E8%8D%90%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/8ER=uZP
- 城乡交通衔接的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/843
- 老年人文化生活的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/slv
- 科学健身方法的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/ZX9
- 口袋公园建设的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/808=cfi
- 青少年户外教育的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/rpm=315
- 安全出行教育的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%85%B1%E4%BA%AB%E8%B4%A2%E7%BB%8F?/7Tn=bsw
- 城市夜间照明的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8CAPP_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/076
- 小区停车协商的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8CAPP_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/ras
- 地方文化传播的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8CAPP_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/Mfy
- 城市社区治理的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8CAPP_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/179=vdj
- 邻里互助活动的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8CAPP_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/azz=866
- 社区应急准备的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8CAPP_%E8%85%BE%E8%AE%AF%E9%97%AE%E5%8D%B7?/ksE=m5Q
- 社区绿色空间的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/708
- 社区消防演练的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/neb
- 城市公共座椅的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/45z
- 社区读书角建设的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/190=tls
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/dvm=424
- 周末休闲规划的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/Iz4=dTg
- 社区儿童活动的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/377
- 儿童安全出行的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/osu
- 医院导诊服务的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/zbl
- 家庭环保行动的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/277=mpb
- 周末休闲规划的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/zmq=626
- 社区公共餐饮的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%A4%A7%E5%85%A8%E5%9B%BE%E8%A7%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/V3G=YJ0
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%87%AA%E5%88%9B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/128
- 家庭养老规划的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%87%AA%E5%88%9B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/hwo
- 乡村生态观察的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%87%AA%E5%88%9B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/ICp
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%87%AA%E5%88%9B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/440=vyb
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%87%AA%E5%88%9B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/qgb=697
- 城乡交流活动的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%87%AA%E5%88%9B%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/tCq=OAf
- 数字生活课堂的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/968
- 社区协商议事的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/cje
- 儿童友好空间的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/rcq
- 城市博物馆活动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/095=ifj
- 远程协作工具的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/dxz=253
- 城市共享单车的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8E%8B%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C%E5%8F%A3%E8%AF%80_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/2ln=3CJ
- 老年人日常照护的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96%E7%9A%84%E6%89%93%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/422
- 食品安全科普的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96%E7%9A%84%E6%89%93%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/psn
- 智能家居应用的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96%E7%9A%84%E6%89%93%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/JSu
- 老年友好服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96%E7%9A%84%E6%89%93%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/996=hvo
- 家庭运动计划的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96%E7%9A%84%E6%89%93%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/hcm=195
- 科学运动指导的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96%E7%9A%84%E6%89%93%E6%B3%95_%E7%99%BE%E5%BA%A6%E5%AE%89%E9%98%B2?/Te4=h3O
- 街区道路维护的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%8D%95%E4%BB%BB%E5%8A%A1%E7%BA%A6%E8%A2%AB%E9%AA%97%E4%BA%86%E4%B8%80%E4%B8%87%E4%B8%89_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/905
- 街区更新实践的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%8D%95%E4%BB%BB%E5%8A%A1%E7%BA%A6%E8%A2%AB%E9%AA%97%E4%BA%86%E4%B8%80%E4%B8%87%E4%B8%89_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/oow
- 城市建设科普的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%8D%95%E4%BB%BB%E5%8A%A1%E7%BA%A6%E8%A2%AB%E9%AA%97%E4%BA%86%E4%B8%80%E4%B8%87%E4%B8%89_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/HG1
- 城市空气科普的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%8D%95%E4%BB%BB%E5%8A%A1%E7%BA%A6%E8%A2%AB%E9%AA%97%E4%BA%86%E4%B8%80%E4%B8%87%E4%B8%89_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/535=zyl
- 城市应急科普的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%8D%95%E4%BB%BB%E5%8A%A1%E7%BA%A6%E8%A2%AB%E9%AA%97%E4%BA%86%E4%B8%80%E4%B8%87%E4%B8%89_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/eru=424
- 数字学习资源的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B8%89%E5%8D%95%E4%BB%BB%E5%8A%A1%E7%BA%A6%E8%A2%AB%E9%AA%97%E4%BA%86%E4%B8%80%E4%B8%87%E4%B8%89_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/HTc=dmO
- 家庭科学教育的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%97%A0%E6%9C%AC%E9%87%91%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/660
- 个人时间管理的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%97%A0%E6%9C%AC%E9%87%91%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/jrb
- 家庭节能设备的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%97%A0%E6%9C%AC%E9%87%91%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/ZoO
- 家庭园艺实践的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%97%A0%E6%9C%AC%E9%87%91%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/689=iyd
- 公共文化活动的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%97%A0%E6%9C%AC%E9%87%91%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/eyw=615
- 城市公共厕所的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E6%97%A0%E6%9C%AC%E9%87%91%E4%B8%80%E5%A4%A9%E8%B5%9A500_%E8%99%8E%E6%89%91%E8%83%BD%E6%BA%90?/FLe=lIm
- 开放式学习空间的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%842%EF%BD%9E3%E4%B8%87%E5%B0%8F%E7%94%9F%E6%84%8F_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/301
- 智慧城市体验的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%842%EF%BD%9E3%E4%B8%87%E5%B0%8F%E7%94%9F%E6%84%8F_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/xjv
- 无障碍出行的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%842%EF%BD%9E3%E4%B8%87%E5%B0%8F%E7%94%9F%E6%84%8F_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/LsK
- 个人信息保护的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%842%EF%BD%9E3%E4%B8%87%E5%B0%8F%E7%94%9F%E6%84%8F_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/561=jud
- 公共设施使用的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%842%EF%BD%9E3%E4%B8%87%E5%B0%8F%E7%94%9F%E6%84%8F_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/vlx=404
- 家庭食品保存的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%8A%95%E8%B5%842%EF%BD%9E3%E4%B8%87%E5%B0%8F%E7%94%9F%E6%84%8F_%E5%BF%AB%E6%89%8B%E7%BE%8E%E9%A3%9F?/z31=AiV
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/122
- 乡村公共阅读的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/edx
- 社区文化节活动的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/woB
- 科普展览体验的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/280=oug
- 青少年户外教育的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/phx=812
- 社区科普课堂的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E8%84%89%E8%84%89%E8%82%A1%E7%A5%A8?/KmT=V0y
- 学校食育活动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BC%80%E6%88%B7%E9%80%8188%E5%85%83%E4%BD%93%E9%AA%8C%E9%87%91_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/230
- 城市展览体验的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BC%80%E6%88%B7%E9%80%8188%E5%85%83%E4%BD%93%E9%AA%8C%E9%87%91_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/dbr
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BC%80%E6%88%B7%E9%80%8188%E5%85%83%E4%BD%93%E9%AA%8C%E9%87%91_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/iRj
- 家庭照护支持的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BC%80%E6%88%B7%E9%80%8188%E5%85%83%E4%BD%93%E9%AA%8C%E9%87%91_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/070=iqm
- 社区快递服务的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BC%80%E6%88%B7%E9%80%8188%E5%85%83%E4%BD%93%E9%AA%8C%E9%87%91_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/xda=858
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BC%80%E6%88%B7%E9%80%8188%E5%85%83%E4%BD%93%E9%AA%8C%E9%87%91_%E5%A4%B4%E6%9D%A1%E7%95%85%E6%B8%B8?/zhU=kDr
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%8410%E5%85%83%E6%8A%95%E8%B5%84%E4%B9%B0%E6%B6%A8%E4%B9%B0%E8%B7%8C%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/630
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%8410%E5%85%83%E6%8A%95%E8%B5%84%E4%B9%B0%E6%B6%A8%E4%B9%B0%E8%B7%8C%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/ycm
- 社区应急准备的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%8410%E5%85%83%E6%8A%95%E8%B5%84%E4%B9%B0%E6%B6%A8%E4%B9%B0%E8%B7%8C%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/e16
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%8410%E5%85%83%E6%8A%95%E8%B5%84%E4%B9%B0%E6%B6%A8%E4%B9%B0%E8%B7%8C%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/460=tcn
- 数字便民地图的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%8410%E5%85%83%E6%8A%95%E8%B5%84%E4%B9%B0%E6%B6%A8%E4%B9%B0%E8%B7%8C%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/cdj=258
- 口袋公园建设的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%8410%E5%85%83%E6%8A%95%E8%B5%84%E4%B9%B0%E6%B6%A8%E4%B9%B0%E8%B7%8C%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/kCo=iqw
- 数字创意课程的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8F%AD%E7%A7%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/509
- 图书馆活动策划的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8F%AD%E7%A7%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/rhr
- 城市雨天出行的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8F%AD%E7%A7%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/9yl
- 运动安全知识的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8F%AD%E7%A7%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/290=eaw
- 骑行路线规划的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8F%AD%E7%A7%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/kzy=835
- 数据分析入门的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8F%AD%E7%A7%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/kA7=cec
- 城市公共自行车的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/146
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/nja
- 家庭食品保存的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/zFA
- 青少年心理健康的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/606=osr
- 绿色消费选择的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/qhk=491
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%9B%BE%E8%A7%A3_%E4%BA%AC%E4%B8%9C%E7%A7%81%E5%8B%9F?/x1p=93c
- 公共卫生设施的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/587
- 城市微更新实践的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/ojg
- 公共设施维护的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/nsQ
- 应急物资管理的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/410=toq
- 社区养老服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/dei=331
- 家庭健康管理中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90%E6%96%B9%E6%A1%88_%E8%B4%A2%E7%BB%8F%E8%BF%B0%E8%AF%84?/FyY=YMm
- 公共场所导视的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/381
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/myl
- 乡村生态观察的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/aNU
- 通勤路线规划的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/342=gpp
- 乡村生态观察的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/bod=308
- 儿童友好空间的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/lxL=8p1
- 城市博物馆服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%A8%B3%E5%AE%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/265
- 城市应急科普的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%A8%B3%E5%AE%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/onw
- 乡村文化空间的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%A8%B3%E5%AE%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/jER
- 家庭照护支持的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%A8%B3%E5%AE%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/950=szu
- 课后服务体验的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%A8%B3%E5%AE%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/vvk=789
- 街区道路维护中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%A8%B3%E5%AE%9A%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8D%9A%E5%AE%A2?/jOy=RX4
- 儿童阅读角的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/041
- 便民服务地图的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/tur
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/Spx
- 社区花园共建的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/938=wiq
- 在线教育体验的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/zkd=365
- 街区更新实践的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/tDM=oan
- 城市公共座椅的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F%E6%80%8E%E4%B9%88%E5%8E%8B_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/512
- 数字政务体验的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F%E6%80%8E%E4%B9%88%E5%8E%8B_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/omu
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F%E6%80%8E%E4%B9%88%E5%8E%8B_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/zbr
- 城市噪声观察的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F%E6%80%8E%E4%B9%88%E5%8E%8B_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/837=jvr
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F%E6%80%8E%E4%B9%88%E5%8E%8B_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/lsx=140
- 社区家政服务的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E4%B8%A4%E6%9C%9F%E6%80%8E%E4%B9%88%E5%8E%8B_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/dpU=vas
- 公共空间照明的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E7%A8%B3%E8%B5%9A%E5%90%97_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/246
- 家庭环保行动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E7%A8%B3%E8%B5%9A%E5%90%97_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/sfs
- 城市慢行系统的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E7%A8%B3%E8%B5%9A%E5%90%97_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/ppa
- 城市应急科普的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E7%A8%B3%E8%B5%9A%E5%90%97_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/731=gea
- 数字便民地图的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E7%A8%B3%E8%B5%9A%E5%90%97_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/wws=424
- 地方文化传播的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E7%A8%B3%E8%B5%9A%E5%90%97_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/DYE=Hq3
- 便民服务窗口的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/102
- 城市公共空间的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/khr
- 科学观察活动的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/iYb
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/233=kdy
- 社区活动策划的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/wju=238
- 小区停车协商的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/ioS=ITI
- 社区共享书架的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%8A%B1%E6%97%97%E9%AA%B0%E8%AF%A6%E7%BB%86%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/597
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%8A%B1%E6%97%97%E9%AA%B0%E8%AF%A6%E7%BB%86%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/efu
- 数字支付体验的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%8A%B1%E6%97%97%E9%AA%B0%E8%AF%A6%E7%BB%86%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/Gbr
- 租房信息服务的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%8A%B1%E6%97%97%E9%AA%B0%E8%AF%A6%E7%BB%86%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/770=dda
- 骑行路线规划中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%8A%B1%E6%97%97%E9%AA%B0%E8%AF%A6%E7%BB%86%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/adm=229
- 基层健康服务的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%8A%B1%E6%97%97%E9%AA%B0%E8%AF%A6%E7%BB%86%E7%8E%A9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/Yvr=R7c
- 数字生活课堂的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/640
- 社区文化传播的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/nex
- 绿色生活实践的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/mta
- 城市公共厕所的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/333=dgs
- 城市博物馆服务的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/ejn=851
- 社区邻里服务的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BD%91%E8%B5%8C%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E5%9D%9A%E6%8C%81%E4%B8%89%E5%B9%B4_%E5%8D%B3%E5%88%BB%E6%96%87%E6%91%98?/apr=zcL
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/900
- 科学教育活动的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/aud
- 电子商务服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/Lq1
- 老年智能设备的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/384=owp
- 社区心理支持的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/mfd=588
- 家庭健康科普中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%8A%95%E8%B5%845000%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%94%B6%E7%9B%8A%E9%AA%97%E5%B1%80_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/s8Z=dUu
- 乡村电商实践的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/649
- 科学观察活动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/tjt
- 乡村文化空间的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/IjI
- 城市生活服务的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/773=pjy
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/lxi=757
- 网络安全教育的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%A5%96%E5%BF%AB3%E5%BF%85%E4%B8%AD%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/ehk=81e
- 骑行路线规划的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F?/553
- 城市公共座椅的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F?/jgc
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F?/NoD
- 公交站点体验的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F?/775=qdb
- 社区老年食堂的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F?/ejb=889
- 儿童阅读角的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%BB%8B%E7%BB%8D_%E8%B4%A2%E7%BB%8F?/gEX=2wZ
- 邻里互助活动的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/414
- 青少年科普实践的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/uof
- 城市公共座椅的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/0PB
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/905=voh
- 绿色生活实践的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ypz=677
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/9bc=afY
- 街道综合服务从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/964
- 科学信息获取的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/ktv
- 社区便民集市的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/x4G
- 社区阅读服务的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/038=hfq
- 城市公共自行车的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/iwg=037
- 邻里共享空间的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E4%BD%9C%E5%BC%8A%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/jjY=fYb
- 街头绿植养护的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/026
- 校园安全教育的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/xys
- 职业技能学习的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/gJc
- 社区应急准备的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/265=agp
- 生活垃圾减量的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/jmu=317
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%A3%E7%A0%81%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/ft5=00k
- 城市绿道建设的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/998
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/nan
- 公共服务咨询的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/Ykk
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/760=bgf
- 社区共享书架的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/hvj=560
- 社区便民集市的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E7%BE%8E%E5%A6%86?/mka=Tas
- 城市住房服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/333
- 城乡交流活动的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/sid
- 学校食育活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/5NJ
- 街道综合服务的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/289=gbs
- 数字素养提升的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/qip=767
- 社区应急准备的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/f2D=fOY
- 老年数字阅读中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/592
- 城市适老服务的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/tdr
- 乡村教育资源的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/JU3
- 家庭养老规划的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/084=cmj
- 生活技能分享的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/yxl=783
- 便民服务地图的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E9%A2%84%E6%B5%8B_%E7%99%BE%E5%BA%A6%E5%BD%B1%E8%A7%86?/JFs=AYI
- 信息无障碍体验的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/671
- 农贸市场环境的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/wxe
- 亲子科普活动的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/u2s
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/995=lzt
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/xhm=604
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/GiH=sY6
- 运动安全知识的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/612
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/ois
- 物业服务沟通的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/RMD
- 绿色办公实践的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/903=xis
- 社区健康讲座的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/koj=387
- 居家防滑改造的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E7%95%8C%E9%9D%A2%E5%BF%AB%E6%8A%A5?/kWc=CUN
- 城市绿道建设的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/740
- 乡村阅读空间的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/pnk
- 图书借阅体验的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/nnI
- 公共服务预约的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/355=dgg
- 儿童友好空间的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/ish=074
- 家庭用电安全的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%BE_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/LFR=vns
- 课后服务体验的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/511
- 志愿者培训交流的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/oqt
- 城市步行友好的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/AJF
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/730=caz
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/qaw=958
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%8B%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/lxZ=VPA
- 社区便利生活的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/098
- 低碳社区实践中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/mlw
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/74C
- 数字设备回收的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/506=psi
- 社区活动空间的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/biz=344
- 节约用水实践的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%9B%9E%E6%9C%9B?/Mw4=7TJ
- 城市骑行环境的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/163
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/rdh
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/zmM
- 科学观察活动的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/077=ivc
- 城市展览体验的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/cww=291
- 乡村产业科普的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%86%85%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/kdp=MJf

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
