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

- 低碳社区实践的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/j6p
- 绿色出行服务的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/571=ukv
- 社区阅读服务的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/czn=825
- 图书借阅体验的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F?/Fvd=dAT
- 社区家校合作的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/253
- 社区宣传栏更新的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/akt
- 公共文化活动的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/uFk
- 家庭健康管理的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/895=kow
- 邻里互助活动的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/biy=342
- 小区公共照明的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/u2q=2Jq
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/918
- 数字阅读服务的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/hsm
- 社区养老服务的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/CkK
- 城市公共艺术的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/193=ekm
- 物业服务沟通的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/icy=467
- 网络安全教育的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E4%BC%97%E6%B5%8B?/pAX=JYG
- 城市文明出行的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/250
- 公共交通接驳的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/asm
- 药品使用科普的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/pwg
- 城市农夫市集的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/178=qwm
- 低碳社区实践的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/nrc=475
- 城市公共艺术的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%9A%E5%BB%BA?/bDt=Njm
- 开源技术交流的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/687
- 老年运动活动的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/nxt
- 光伏知识科普的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/KKk
- 青少年编程学习的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/742=fls
- 环境教育课程的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/zae=947
- 公共空间导览的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%91%84%E5%BD%B1?/IEw=BgF
- 校园社团活动的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%A4%BE%E5%8C%BA?/460
- 医院导诊服务的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%A4%BE%E5%8C%BA?/jsr
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%A4%BE%E5%8C%BA?/74m
- 小微企业服务的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%A4%BE%E5%8C%BA?/742=ovc
- 食品配送体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%A4%BE%E5%8C%BA?/uxj=778
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E7%A4%BE%E5%8C%BA?/7A6=uYu
- 环境教育课程的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92app_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/515
- 志愿服务平台的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92app_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/yvf
- 城市文明出行的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92app_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/0zR
- 乡村公共文化中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92app_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/305=ypu
- 城市可持续生活的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92app_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/fod=758
- 乡村文化空间的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92app_%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/vB6=nTd
- 公共空间照明的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/247
- 儿童安全出行的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/sny
- 城市公共自行车的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/uVs
- 个人数据管理的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/205=hns
- 社区文化节活动的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/qnx=161
- 基层医疗预约的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/FrI=BEC
- 数字设备回收的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/522
- 智能家居应用的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/ech
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/OEA
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/709=cwt
- 社区托育服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/fvi=228
- 生活垃圾减量的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%B1%86%E7%93%A3%E5%88%B8%E5%95%86?/O8M=koj
- 家庭用电安全的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/250
- 光伏知识科普的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/qgd
- 校园社团活动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/ciP
- 社区庭院绿化的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/660=qqw
- 开放式学习空间的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/neb=057
- 数字艺术创作的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/ljj=3PJ
- 居家适老化改造的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/023
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/jsk
- 城市体育设施的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/S9u
- 图书借阅体验的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/181=uhi
- 小区停车协商的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/rsp=275
- 青少年科普实践的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/8OC=AAZ
- 儿童安全出行的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/328
- 本地历史资料的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/xsh
- 休闲运动入门的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/oeP
- 青少年科技社团的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/695=kxq
- 健康饮水科普的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/qnc=066
- 智能家居应用的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/vWf=9ux
- 社区法律科普的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A8%B3%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/452
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A8%B3%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/glm
- 城市公共饮水的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A8%B3%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/Kmf
- 老年人日常照护的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A8%B3%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/817=hab
- 社区便民服务的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A8%B3%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/wro=519
- 数字设备回收的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E7%A8%B3%E8%B5%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%9C%9B?/Agb=aoV
- 数字政务体验的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/007
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/ewv
- 绿色建筑理念的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/e9N
- 个人信息保护的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/096=wso
- 社区体育组织的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/pqm=226
- 青年志愿活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/Hyn=6bb
- 本地旅行体验的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/536
- 科学观察活动中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/jek
- 城市博物馆服务的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/HNF
- 数字支付体验的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/376=dec
- 家庭环保行动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/jyj=564
- 城市文明出行的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/qll=Yjb
- 城市应急广播的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%AA%97%E6%9C%AF_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/288
- 城市公共饮水的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%AA%97%E6%9C%AF_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/jxh
- 学校食育活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%AA%97%E6%9C%AF_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/7Ku
- 家庭用电安全的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%AA%97%E6%9C%AF_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/374=mle
- 青少年户外教育的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%AA%97%E6%9C%AF_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/mak=479
- 软件开发学习的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%9B%A2%E9%98%9F%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E9%AA%97%E6%9C%AF_%E7%95%8C%E9%9D%A2%E5%9C%88%E5%AD%90?/LVx=WSZ
- 无障碍出行的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%B9%B3%E5%88%B7%E7%8E%8B%E8%80%85%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/679
- 数字档案服务的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%B9%B3%E5%88%B7%E7%8E%8B%E8%80%85%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/rfq
- 街区小店体验中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%B9%B3%E5%88%B7%E7%8E%8B%E8%80%85%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/tfE
- 社区消防演练的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%B9%B3%E5%88%B7%E7%8E%8B%E8%80%85%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/619=hge
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%B9%B3%E5%88%B7%E7%8E%8B%E8%80%85%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/uym=092
- 光伏知识科普的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%B9%B3%E5%88%B7%E7%8E%8B%E8%80%85%E8%AE%A1%E5%88%92app_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/0rB=kJA
- 社区邻里服务的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%BE%B3%E6%B4%B210%E4%BA%BA%E5%B7%A5%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/666
- 城市应急科普的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%BE%B3%E6%B4%B210%E4%BA%BA%E5%B7%A5%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/fge
- 开源技术交流的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%BE%B3%E6%B4%B210%E4%BA%BA%E5%B7%A5%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/sr5
- 城市休闲步道的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%BE%B3%E6%B4%B210%E4%BA%BA%E5%B7%A5%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/273=cui
- 社区法律科普的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%BE%B3%E6%B4%B210%E4%BA%BA%E5%B7%A5%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/xnf=842
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%BE%B3%E6%B4%B210%E4%BA%BA%E5%B7%A5%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%85%AC%E5%BC%80%E8%AF%BE?/LPE=NOp
- 家庭安全提示的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%87%AA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B7%9F%E5%8D%95%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/689
- 科学健身方法的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%87%AA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B7%9F%E5%8D%95%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/abe
- 老年数字阅读的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%87%AA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B7%9F%E5%8D%95%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/pNv
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%87%AA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B7%9F%E5%8D%95%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/815=psn
- 城市博物馆服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%87%AA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B7%9F%E5%8D%95%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/utc=553
- 消防知识宣传中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E8%87%AA%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B7%9F%E5%8D%95%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/74E=1rL
- 社会体育指导的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/571
- 传统节日科普的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/feg
- 家庭园艺实践的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/yGW
- 家庭健康科普的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/973=ylf
- 城市公共空间的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/mju=390
- 学校食育活动的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/6vx=8zT
- 新能源知识普及的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E9%9A%BE%E5%90%97_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/974
- 社区公共餐饮的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E9%9A%BE%E5%90%97_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/xbx
- 在线教育体验的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E9%9A%BE%E5%90%97_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/TUR
- 乡村生态观察的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E9%9A%BE%E5%90%97_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/372=hjl
- 社区托育服务的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E9%9A%BE%E5%90%97_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/cau=342
- 社区垃圾分类的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_1000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E9%9A%BE%E5%90%97_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/11t=Xsr
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%B8%E6%88%8F?/319
- 社区科普课堂的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%B8%E6%88%8F?/yva
- 垃圾分类指导的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%B8%E6%88%8F?/ar7
- 街区绿化养护的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%B8%E6%88%8F?/635=mmc
- 食品安全科普的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%B8%E6%88%8F?/ayg=415
- 城市水环境观察的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%B8%B8%E6%88%8F?/6ke=eZU
- 地方美食文化的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%A8%B3_%E6%90%9C%E7%8B%90?/180
- 家庭运动计划的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%A8%B3_%E6%90%9C%E7%8B%90?/cht
- 生活垃圾减量的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%A8%B3_%E6%90%9C%E7%8B%90?/H46
- 公交无障碍服务的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%A8%B3_%E6%90%9C%E7%8B%90?/403=kbc
- 社区文化传播的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%A8%B3_%E6%90%9C%E7%8B%90?/fzb=694
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%A8%B3_%E6%90%9C%E7%8B%90?/YuQ=6MJ
- 街区小店体验的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/497
- 乡村文化空间的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/usm
- 城市公共空间的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/rZ4
- 软件开发学习的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/949=jti
- 街区绿化养护的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/oui=276
- 社区生活指南的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/cNZ=gRL
- 城乡公共服务的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/550
- 在线教育体验的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/fjh
- 生活服务数字化的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/GFi
- 城市博物馆服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/979=jjx
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/hnu=741
- 街区小店体验的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95_%E9%9B%85%E8%99%8E%E8%AF%84%E8%AE%BA?/n4X=Zwj
- 在线学习体验的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E7%A8%B3%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/420
- 公共空间休憩的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E7%A8%B3%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/glt
- 乡村公共服务的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E7%A8%B3%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/fLt
- 农产品消费体验的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E7%A8%B3%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/797=ggc
- 数字阅读服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E7%A8%B3%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/wwg=749
- 小区电梯维护的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E7%A8%B3%E8%B5%A2_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/Mmf=lYg
- 节日文化体验的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/186
- 社区生活指南的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/gxx
- 城市展览体验的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/jLD
- 社区体育组织的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/779=gef
- 绿色校园实践中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/aag=683
- 社区设施共享的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/NcK=zex
- 文化场馆预约的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/450
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/moj
- 公共设施使用的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/A00
- 数字创意课程的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/665=ejl
- 城市建设科普的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/gcz=484
- 电动汽车充电的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/f3G=EC8
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/580
- 药品使用科普的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/pas
- 数字生活课堂的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/E3q
- 开放式学习空间的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/699=ous
- 社区应急准备的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/oer=901
- 社区交通安全的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/p6z=glQ
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/777
- 社区修缮行动的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/vjl
- 气象科普传播的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/tOT
- 青年职业探索的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/119=lwa
- 公共交通接驳的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/noc=298
- 公园休闲体验的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8D%95%E5%A4%A7%E5%8F%8C%E5%B0%8F%E5%8F%8C_%E9%93%B6%E4%B8%B0%E8%B4%A2%E7%BB%8F?/wG8=Tbe
- 小区电梯维护的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/897
- 老旧小区改造的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/mxd
- 市民意见收集的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/vDP
- 城市社区治理的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/319=orx
- 节日文化体验的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/ess=551
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95_%E7%BA%A2%E5%88%A9%E8%B4%A2%E7%BB%8F?/2xz=4T4
- 数字设备回收的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%A1%BA%E9%BE%99%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/537
- 网络安全教育的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%A1%BA%E9%BE%99%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/kzn
- 文化场馆预约的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%A1%BA%E9%BE%99%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/Oyr
- 老年运动活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%A1%BA%E9%BE%99%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/447=zol
- 街道综合服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%A1%BA%E9%BE%99%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/flg=973
- 公共服务评价的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E9%A1%BA%E9%BE%99%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A5%A8?/A7N=fOd
- 公共服务沟通的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/469
- 社区信息发布中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/msp
- 农业科普体验的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/9SV
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/578=oix
- 便民信息查询中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/jzi=577
- 城市住房服务的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB%E4%B8%89%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/0rA=Jeb
- 家庭节能实践的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%96%A9%E9%BE%99%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/975
- 社区环保活动的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%96%A9%E9%BE%99%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/pua
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%96%A9%E9%BE%99%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/p7t
- 乡村公共文化的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%96%A9%E9%BE%99%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/490=ssu
- 药品使用科普的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%96%A9%E9%BE%99%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/swr=337
- 文化场馆预约的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%96%A9%E9%BE%99%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/Yws=uY4
- 社区应急准备的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%BE%99%E8%99%8E%E5%92%8C%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/232
- 社区设施共享的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%BE%99%E8%99%8E%E5%92%8C%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/tik
- 老年友好服务的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%BE%99%E8%99%8E%E5%92%8C%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/NUT
- 生活技能分享的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%BE%99%E8%99%8E%E5%92%8C%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/681=fro
- 城市夜间照明的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%BE%99%E8%99%8E%E5%92%8C%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/mgx=647
- 家庭健康科普的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%BE%99%E8%99%8E%E5%92%8C%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/y1Y=wVs
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/035
- 儿童安全出行的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/kjj
- 健康饮水科普的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/H6K
- 数字生活课堂中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/741=mlu
- 科学信息获取的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/coe=138
- 非遗体验活动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/0Jt=lYV
- 社区宣传栏更新有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_168%E8%AE%A1%E5%88%92%E5%BC%80%E5%A5%96%E7%8E%B0%E5%9C%BA%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/151
- 家庭运动计划的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_168%E8%AE%A1%E5%88%92%E5%BC%80%E5%A5%96%E7%8E%B0%E5%9C%BA%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/bqi
- 医院导诊服务的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_168%E8%AE%A1%E5%88%92%E5%BC%80%E5%A5%96%E7%8E%B0%E5%9C%BA%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/kmN
- 绿色生活实践中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_168%E8%AE%A1%E5%88%92%E5%BC%80%E5%A5%96%E7%8E%B0%E5%9C%BA%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/565=fmx
- 社区安全巡查的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_168%E8%AE%A1%E5%88%92%E5%BC%80%E5%A5%96%E7%8E%B0%E5%9C%BA%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/fzq=040
- 学校食育活动的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_168%E8%AE%A1%E5%88%92%E5%BC%80%E5%A5%96%E7%8E%B0%E5%9C%BA%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/VPD=12m
- 运动安全知识的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/063
- 口袋公园建设的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/vcv
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/2Dc
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/314=dmc
- 城市展览体验的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/jjw=959
- 乡村生态观察的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/lRk=SMS
- 智能手机助老的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/002
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/nvu
- 街道综合服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/34t
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/512=mki
- 读书会组织的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/mwk=104
- 社区宠物管理的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_168%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/rcM=RO6
- 城市人文观察的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%9C%80%E4%B8%93%E4%B8%9A%E7%9A%84%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/337
- 家庭消费规划的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%9C%80%E4%B8%93%E4%B8%9A%E7%9A%84%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/vbm
- 青少年心理健康的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%9C%80%E4%B8%93%E4%B8%9A%E7%9A%84%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/iDN
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%9C%80%E4%B8%93%E4%B8%9A%E7%9A%84%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/281=gpd
- 社区邻里服务的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%9C%80%E4%B8%93%E4%B8%9A%E7%9A%84%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/zcg=950
- 校园节能行动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%9C%80%E4%B8%93%E4%B8%9A%E7%9A%84%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B8%88_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/NR9=yKp
- 个人信息保护的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%BE%B3%E6%B4%B2_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/429
- 绿色出行服务的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%BE%B3%E6%B4%B2_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/pmv
- 城市共享单车的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%BE%B3%E6%B4%B2_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/ujy
- 网络信息辨识的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%BE%B3%E6%B4%B2_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/997=zqt
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%BE%B3%E6%B4%B2_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/cju=058
- 文化讲座服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E8%AE%A1%E5%88%92%E7%BD%91%E6%BE%B3%E6%B4%B2_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/Izr=3d2
- 儿童友好街区的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_168%E8%AE%A1%E5%88%92%E7%BD%91%E4%BA%BA%E5%B7%A5%E7%89%88%E4%BD%BF%E7%94%A8_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/478
- 课后服务体验的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_168%E8%AE%A1%E5%88%92%E7%BD%91%E4%BA%BA%E5%B7%A5%E7%89%88%E4%BD%BF%E7%94%A8_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/ric
- 家庭健康科普的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_168%E8%AE%A1%E5%88%92%E7%BD%91%E4%BA%BA%E5%B7%A5%E7%89%88%E4%BD%BF%E7%94%A8_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/jDA
- 生成式工具使用的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_168%E8%AE%A1%E5%88%92%E7%BD%91%E4%BA%BA%E5%B7%A5%E7%89%88%E4%BD%BF%E7%94%A8_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/939=ufx
- 地方旅游导览的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_168%E8%AE%A1%E5%88%92%E7%BD%91%E4%BA%BA%E5%B7%A5%E7%89%88%E4%BD%BF%E7%94%A8_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/bop=708
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_168%E8%AE%A1%E5%88%92%E7%BD%91%E4%BA%BA%E5%B7%A5%E7%89%88%E4%BD%BF%E7%94%A8_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/7y4=xWu

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
