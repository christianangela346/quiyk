# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 城市地名文化的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/afb=100
- 城市适老服务的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app_%E7%99%BE%E5%BA%A6%E6%97%B6%E8%AF%84?/adx=Jhs
- 气象科普传播的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/725
- 全民健身活动的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/wsq
- 街区小店体验的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/mej
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/464=yps
- 乡村产业科普的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/tqj=961
- 家庭陪伴活动从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/Dkx=Tvh
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/258
- 绿色办公实践的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/eee
- 城市可持续生活的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/h70
- 家庭节能设备的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/510=yga
- 儿童阅读角的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/tuj=338
- 科学信息获取的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E4%BA%AC%E4%B8%9C%E8%83%BD%E6%BA%90?/jZ9=us4
- 网络安全教育的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/107
- 机器学习入门的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/awb
- 家庭防灾准备的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/XaI
- 家庭饮食安排的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/945=muv
- 健康信息获取的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/bnt=555
- 城市游园体验的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%B4%A2%E7%BB%8F%E5%91%A8%E6%8A%A5?/GSW=Oaj
- 公共设施使用的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/849
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/bgt
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/HVm
- 智能手机助老的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/494=kfo
- 城市水环境观察的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/adg=936
- 食品配送体验的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_36%E6%B0%AA%E8%AE%BF%E8%B0%88?/z8k=yZG
- 城市便民驿站中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/917
- 通勤路线规划的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/fyb
- 数字创作工具的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/VV3
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/020=skz
- 数字政务体验的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/aia=495
- 数字支付体验的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B4%A2%E7%BB%8F%E5%81%A5%E5%BA%B7?/hWG=zsE
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/022
- 健康信息获取的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/pfb
- 生成式工具使用中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/u4P
- 社区消防演练的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/033=hmt
- 文化场馆预约的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/bkg=652
- 城市文明出行的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/FB5=CM2
- 公共空间休憩的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/017
- 青少年心理健康的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/vnr
- 校园节能行动的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/mMs
- 消防知识宣传的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/677=fmz
- 家庭健康科普的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/yql=502
- 城市步行友好的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/lvZ=2iJ
- 信息无障碍体验的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/314
- 开源技术交流的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/jzg
- 网络信息辨识的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/RFe
- 便民维修服务的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/068=yrf
- 公园亲子设施的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/bbk=645
- 便民服务窗口的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/lG3=BNp
- 乡村公共服务的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%80%BA%E5%B8%82?/081
- 社区商业活力的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%80%BA%E5%B8%82?/lmw
- 城市公共空间的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%80%BA%E5%B8%82?/RYJ
- 本地消费场景的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%80%BA%E5%B8%82?/791=cfe
- 非遗课堂体验的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%80%BA%E5%B8%82?/abg=386
- 社区文化节活动的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%80%BA%E5%B8%82?/bi5=Knq
- 数字地图应用的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/335
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/qgp
- 城市地名文化的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/Zek
- 家庭教育交流的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/424=yah
- 老年学习活动的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/msq=375
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%B4%E6%92%AD?/6b6=WHc
- 乡村公共服务的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/714
- 家庭消费规划的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/fkt
- 农业科普体验的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/9jb
- 家庭环保行动的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/933=kml
- 老旧小区改造的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/cgu=213
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/vFs=qUz
- 城市适老服务的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/304
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dnh
- 职业技能学习的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/G4a
- 城市雨天出行的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/983=jit
- 便民维修服务的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vao=189
- 社区便民服务的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lRe=LSK
- 非遗体验活动的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/447
- 人工智能科普的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/wyr
- 城市绿色交通中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/XJK
- 人工智能科普的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/541=ttj
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/nky=838
- 家庭健康科普的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/6B0=bio
- 社区商业活力的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/985
- 校园节能行动的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/vpu
- 文明养宠科普的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/NLs
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/536=dcm
- 智慧停车服务的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/hkr=946
- 科普展览体验的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/xZL=Os3
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/683
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/xye
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/LQg
- 生成式工具使用的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/830=whl
- 周末休闲规划的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/rmt=028
- 社区活动策划的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/yDL=QzZ
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/496
- 老年人文化生活的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/yru
- 老年智能设备的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/aHS
- 公共空间安全的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/857=jde
- 低碳社区实践的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/yup=663
- 数字艺术创作的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E8%8A%92%E6%9E%9C%E6%88%B7%E5%A4%96?/awm=MWG
- 城市公共座椅的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/362
- 家庭教育交流的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/xsf
- 社区应急准备的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/aO6
- 社区托育服务的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/243=gmi
- 社区设施共享的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/jls=203
- 家庭防灾准备的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/Hg9=mBR
- 基层医疗预约的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/815
- 社区信息发布的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/ayo
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/E6e
- 人工智能科普的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/171=cvc
- 儿童友好空间的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/rhg=423
- 公共文化活动的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E8%85%BE%E8%AE%AF%E9%97%AE%E7%AD%94?/Qhr=pd0
- 生成式工具使用的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/129
- 社区健康讲座的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/xbt
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/0D1
- 数字艺术创作的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/652=yyn
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/bgu=479
- 绿色校园实践的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/4G0=bo9
- 智慧停车服务的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/790
- 社区活动报名的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/aoe
- 数字生活课堂的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/O7v
- 数字素养提升的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/857=kmi
- 公共服务数字化的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/xux=683
- 社区托育服务的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/Ij6=lk2
- 环境监测科普的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/806
- 健康信息获取的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/mlt
- 数字阅读服务的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/tIj
- 生活技能分享的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/822=hah
- 社区消防演练的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/any=033
- 健康步道使用的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/0jp=5sb
- 青年志愿活动的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/659
- 骑行路线规划的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/tsj
- 农产品消费体验的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/xy9
- 数字设备回收的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/147=ytv
- 城市可持续生活的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/vod=391
- 公共空间导览的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%95%8C%E9%9D%A2%E6%92%AD%E6%8A%A5?/bqo=6Zt
- 家庭节能设备的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/663
- 口袋公园建设的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/hgd
- 公共健身器材的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/leQ
- 社区文化节活动的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/900=ztw
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/rlq=796
- 城市运动公园的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/n5p=4tO
- 乡村阅读空间的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/726
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/yxp
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/DRH
- 家庭网络使用的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/717=eqo
- 节能生活方式的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/tbp=649
- 社区邻里服务的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/jtR=Wtr
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/360
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/gvs
- 儿童安全出行的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/8bM
- 食品配送体验的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/945=swq
- 骑行路线规划中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/drk=584
- 老年数字阅读的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%86%9B%E4%BA%8B?/DTB=N0p
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/973
- 节气饮食文化的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/dbf
- 数字公共文化的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/v0t
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/937=qhb
- 基层健康档案的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/oie=091
- 家庭健康管理的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/Dzh=0XE
- 公园休闲体验的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/127
- 科学运动指导的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/eqk
- 儿童友好空间的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/kEb
- 公益活动组织的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/788=aqy
- 公共空间导览的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/flp=860
- 公共卫生设施的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E8%B1%86%E7%93%A3%E5%9B%BE%E9%89%B4?/wjw=JKH
- 社区文化节活动的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/516
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/drm
- 社区休闲设施的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/I2d
- 城市噪声观察的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/111=olw
- 城市树木认养的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/xgp=407
- 社区健康讲座的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/MgF=uZx
- 公园无障碍服务的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/003
- 社区家校合作的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/mrr
- 社区活动策划的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/u18
- 社区休闲设施的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/850=rnc
- 社区教育资源的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/crv=720
- 青少年心理健康的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/2Vo=8X3
- 社区邻里服务的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/099
- 家庭照护支持的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/ewe
- 邻里互助活动的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/dvA
- 生活垃圾回收的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/775=cke
- 城市便民驿站的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/jos=013
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%97%B6%E5%B0%9A?/Qmw=kW2
- 网络信息辨识的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/587
- 公共服务咨询的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/cql
- 基层健康服务的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/Pbk
- 家庭急救准备的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/294=vhq
- 邻里共享空间的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/cxp=848
- 便民服务地图的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%9118813_%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/J9x=KxP
- 社区环保活动的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/417
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/jcv
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/ZCv
- 小区停车协商的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/527=smh
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/kvx=540
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/h0z=QA1
- 城市夜间照明的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/288
- 城市夜间生活的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/crj
- 基层服务创新的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/iLL
- 家庭运动计划的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/690=qmx
- 线上办事服务的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/vea=943
- 公共服务预约的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BF%85%E5%8F%91%E5%AE%98%E7%BD%91APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E4%B9%A6?/Bff=ghI
- 地方民俗记录的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/418
- 开放数据应用的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/dyx
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/T1K
- 数据分析入门的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/263=luz
- 青少年编程学习的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/hco=296
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%88%A9%E5%BD%A9%E5%8F%91%E8%A1%8C%E4%B8%AD%E5%BF%83_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/mBB=nt1
- 图书馆数字服务的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/924
- 老年友好服务的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/xlb
- 小区公共照明的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/G0e
- 家庭陪伴活动的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/525=rak
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/eqf=743
- 社区快递服务的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E6%88%B7_%E5%BF%85%E5%BA%94%E7%A8%8E%E5%8A%A1?/p4l=d77
- 节气饮食文化的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/110
- 城市地名文化的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/kgy
- 日常摄影记录的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/G8K
- 开源技术交流的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/070=fdn
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hiy=950
- 租房信息服务的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E8%81%9A%E5%AF%8C%E8%B4%A2%E7%BB%8F?/e2Z=BLY
- 社区活动空间的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/091
- 居民健康教育的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/sei
- 家庭运动计划的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/LSv
- 公共设施使用的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/368=yaq
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/dyp=529
- 无障碍出行的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/kXd=1hB
- 家庭食品保存的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/675
- 便民服务窗口的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/zjn
- 公益活动组织的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/UiO
- 公共服务评价的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/135=vuy
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/khn=997
- 节约用水实践的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8APP_%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/mAX=EdW
- 城市住房服务的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/873
- 社区便利生活的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/obk
- 街区小店体验的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/D4m
- 社区应急准备的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/560=blv
- 小微企业服务的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/ufg=086
- 城市共享单车的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E6%81%AD%E5%96%9C%E5%B1%B1%E4%B8%9C%E9%99%88%E5%85%88%E7%94%9F%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD108%E4%B8%87_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/ueS=Du5
- 社区教育资源的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/146
- 社区环保活动的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/vff
- 公共服务预约的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/84W
- 公共场所导视的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/315=rxb
- 休闲运动入门的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/cnd=683
- 城市公共标识的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E6%81%AD%E5%96%9C%E5%B9%BF%E4%B8%9C%E8%8B%8F%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD88%E4%B8%87_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/Fso=H5p
- 软件开发学习的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/618
- 传统手工艺体验的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/qur
- 城市博物馆活动的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/RzK
- 社区菜市场服务的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/480=lbj
- 家庭科学教育的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/wqm=686
- 城市应急科普的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E6%81%AD%E5%96%9C%E6%B1%9F%E8%8B%8F%E6%9D%8E%E5%A5%B3%E5%A3%AB%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B8%E6%B3%95?/Dsj=t4M
- 城市噪声观察的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/137
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%81%AD%E5%96%9C%E5%B9%BF%E8%A5%BF%E8%B5%B5%E5%B0%8F%E5%A7%90%E5%9C%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%96%9C%E4%B8%AD188%E4%B8%87_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/phh

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
