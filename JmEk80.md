# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 地方文化传播的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_5%E8%82%96%E5%A4%8D%E5%BC%8F3%E8%BF%9E%E8%82%96%E6%9C%89%E5%87%A0%E7%BB%84-%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/393
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_5%E8%82%96%E5%A4%8D%E5%BC%8F3%E8%BF%9E%E8%82%96%E6%9C%89%E5%87%A0%E7%BB%84-%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/sww
- 数字创作工具的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_5%E8%82%96%E5%A4%8D%E5%BC%8F3%E8%BF%9E%E8%82%96%E6%9C%89%E5%87%A0%E7%BB%84-%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/7zV
- 家庭志愿活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_5%E8%82%96%E5%A4%8D%E5%BC%8F3%E8%BF%9E%E8%82%96%E6%9C%89%E5%87%A0%E7%BB%84-%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/488=uzw
- 家庭环保行动的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_5%E8%82%96%E5%A4%8D%E5%BC%8F3%E8%BF%9E%E8%82%96%E6%9C%89%E5%87%A0%E7%BB%84-%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/ryk=460
- 市民热线服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_5%E8%82%96%E5%A4%8D%E5%BC%8F3%E8%BF%9E%E8%82%96%E6%9C%89%E5%87%A0%E7%BB%84-%E8%8A%92%E6%9E%9C%E6%B8%AF%E8%82%A1?/0cg=Zfy
- 城市展览体验的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%9C%B0%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%85%A8%E9%83%A8-%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/140
- 社区运动空间的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%9C%B0%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%85%A8%E9%83%A8-%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/fdq
- 社区老年食堂的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%9C%B0%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%85%A8%E9%83%A8-%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/PAS
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%9C%B0%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%85%A8%E9%83%A8-%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/291=ssu
- 线上办事服务中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%9C%B0%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%85%A8%E9%83%A8-%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/puy=075
- 城市公共饮水的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%9C%B0%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%85%A8%E9%83%A8-%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/ue1=OG6
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/490
- 智能家居应用的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/ppi
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/lTK
- 文化讲座服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/630=tis
- 公共卫生宣传的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/ybh=787
- 基层健康服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E5%A4%AE%E8%A7%86%E7%89%B9%E7%A8%BF?/QJd=x2a
- 城市公共标识的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%8D%9A%E5%AE%A2?/230
- 家庭用电安全的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%8D%9A%E5%AE%A2?/nwu
- 社区文化传播的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%8D%9A%E5%AE%A2?/64t
- 社区便民集市的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%8D%9A%E5%AE%A2?/985=dua
- 社区商业活力的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%8D%9A%E5%AE%A2?/oju=980
- 公共场所导视的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%B9%B3%C2%B7%E5%8F%B0-360%E5%8D%9A%E5%AE%A2?/Wo0=Iou
- 学校食育活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/462
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/nvc
- 社区设施共享的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/QgV
- 基层健康服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/032=wpv
- 城市公共饮水的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/bjo=380
- 家庭用电安全的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF-%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/Gw8=IBz
- 环境监测科普的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/743
- 就业技能培训的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rts
- 农村环境治理的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Ljc
- 城市微更新实践的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/127=tdx
- 城市夜间照明的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/mst=991
- 租房信息服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/f7Y=nW3
- 社区学习活动的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%BD%91%E7%AB%99-%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/992
- 校园节能行动的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%BD%91%E7%AB%99-%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/ydu
- 社区手工活动的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%BD%91%E7%AB%99-%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/ofF
- 节能生活方式的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%BD%91%E7%AB%99-%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/673=rvn
- 社区活动空间的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%BD%91%E7%AB%99-%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/kls=047
- 家庭网络使用的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%96%B0%E7%BD%91%E7%AB%99-%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/jyW=21e
- 社区便民服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E5%BF%AB3-%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/563
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E5%BF%AB3-%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/tuf
- 公共服务沟通的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E5%BF%AB3-%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/f5D
- 志愿服务平台的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E5%BF%AB3-%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/415=caz
- 乡村公共服务的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E5%BF%AB3-%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/cra=695
- 学校体育活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E4%B8%AD%E5%9B%BD%E5%BF%AB3-%E4%BA%AC%E4%B8%9C%E5%9C%B0%E4%BA%A7?/f5u=pIk
- 社区安全巡查的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%BB%E7%BA%BF-%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/000
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%BB%E7%BA%BF-%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/eau
- 城乡公共服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%BB%E7%BA%BF-%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/waB
- 乡村阅读空间的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%BB%E7%BA%BF-%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/933=ija
- 智慧停车服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%BB%E7%BA%BF-%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/vij=386
- 无障碍出行的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%BB%E7%BA%BF-%E8%84%89%E8%84%89%E6%99%A8%E6%8A%A5?/ZRp=zH8
- 社区设施共享的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/154
- 城市雨天出行的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/ocg
- 社区公共餐饮的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/Pak
- 绿色办公实践的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/927=lyv
- 基层服务创新的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/qus=069
- 乡村公共文化的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B024%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%90%9C%E7%8B%97%E5%BD%A9%E7%A5%A8?/tuN=0S2
- 终身学习资源的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%B3%A8%E5%86%8C%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/232
- 科学健身方法的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%B3%A8%E5%86%8C%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/iwl
- 家庭用电安全的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%B3%A8%E5%86%8C%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/6hb
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%B3%A8%E5%86%8C%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/772=ovi
- 社区故事采集的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%B3%A8%E5%86%8C%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/wdh=649
- 公共空间照明的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BF%AB3%E7%BD%91%E7%AB%99%E6%B3%A8%E5%86%8C%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/q1g=fV5
- 公共服务预约的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E5%9D%80%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/792
- 青少年科技社团的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E5%9D%80%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/vbg
- 物业服务沟通的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E5%9D%80%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/gHm
- 食品安全科普的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E5%9D%80%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/324=iio
- 家庭健康科普的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E5%9D%80%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/cwv=775
- 线上阅读资源的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E7%BD%91%E5%9D%80%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/DI4=kgG
- 城市适老服务中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%BD%91%E5%9D%80%E7%99%BB%E5%BD%95-%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/861
- 光伏知识科普的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%BD%91%E5%9D%80%E7%99%BB%E5%BD%95-%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/rwd
- 生活垃圾减量的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%BD%91%E5%9D%80%E7%99%BB%E5%BD%95-%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/niz
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%BD%91%E5%9D%80%E7%99%BB%E5%BD%95-%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/084=fqc
- 线上办事服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%BD%91%E5%9D%80%E7%99%BB%E5%BD%95-%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/uqh=391
- 社区信息发布的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%BD%91%E5%9D%80%E7%99%BB%E5%BD%95-%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/wP9=hgu
- 本地旅行体验的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/931
- 老年人日常照护的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/tbd
- 社区儿童活动的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/ZQC
- 家庭食品保存的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/768=shd
- 农村环境治理的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/hdz=597
- 城市公共标识的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%9A%84%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/TIO=rqK
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/318
- 地方民俗记录的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/rml
- 社区快递服务中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/zMM
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/118=qzs
- 新能源知识普及的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/aeq=317
- 家庭食品保存的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/Le5=iuC
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E7%AE%80%E5%8D%95%E5%B9%B3%E7%A0%81%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95-%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/296
- 社区心理支持的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E7%AE%80%E5%8D%95%E5%B9%B3%E7%A0%81%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95-%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/gzg
- 农业科普体验的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E7%AE%80%E5%8D%95%E5%B9%B3%E7%A0%81%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95-%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/NKO
- 老年数字阅读的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E7%AE%80%E5%8D%95%E5%B9%B3%E7%A0%81%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95-%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/937=gsi
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E7%AE%80%E5%8D%95%E5%B9%B3%E7%A0%81%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95-%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/rjw=657
- 社区防暑服务的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9C%80%E7%AE%80%E5%8D%95%E5%B9%B3%E7%A0%81%E5%85%AC%E5%BC%8F%E7%AE%97%E6%B3%95-%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/lcE=OYG
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/761
- 生活垃圾回收的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/lxx
- 公共设施使用的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/qEV
- 绿色出行服务的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/210=geu
- 社区体育组织的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/gjb=818
- 生活技能分享的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92-%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/zZo=V8n
- 街区绿化养护的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/520
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/kyg
- 职业技能学习的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/H3w
- 智慧停车服务的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/435=mae
- 电子商务服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/sba=575
- 社区阅读服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/sis=54b
- 城市博物馆服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/034
- 城市便民驿站的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/vkn
- 城市空气科普的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/voM
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/895=boo
- 老年数字阅读的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/hqu=403
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5-%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/hMp=bGp
- 城市便民驿站的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/565
- 青年志愿活动中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/nag
- 社区活动报名的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/TsM
- 城市夜间照明的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/476=nvm
- 便民服务地图的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/zeo=100
- 基层服务创新的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/kD2=4oP
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E5%BF%AB3-%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/645
- 城市步行环境的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E5%BF%AB3-%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/fup
- 城市地名文化的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E5%BF%AB3-%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/bkH
- 社区停车服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E5%BF%AB3-%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/017=kaf
- 青少年编程学习的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E5%BF%AB3-%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/lfx=963
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%AE%98%E6%96%B9%E5%BF%AB3-%E8%84%89%E8%84%89%E7%9E%AD%E6%9C%9B?/vFF=hoX
- 家庭收纳实践的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/135
- 青年志愿活动的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/ypv
- 本地旅行体验的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/fg7
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/623=utp
- 文化讲座服务的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/nea=252
- 社区环保活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/aAV=sIO
- 健康饮水科普的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A5%E5%8F%A3-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/821
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A5%E5%8F%A3-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/tlh
- 智能家居应用的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A5%E5%8F%A3-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/V6e
- 学校体育活动的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A5%E5%8F%A3-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/452=htr
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A5%E5%8F%A3-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/rfb=540
- 电动汽车充电的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%A5%E5%8F%A3-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/FYQ=d1S
- 急救知识普及的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%8F%AB%E4%BB%80%E4%B9%88%E5%90%8D%E5%AD%97-%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/464
- 科学观察活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%8F%AB%E4%BB%80%E4%B9%88%E5%90%8D%E5%AD%97-%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/soa
- 数字档案服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%8F%AB%E4%BB%80%E4%B9%88%E5%90%8D%E5%AD%97-%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/5zv
- 生成式工具使用的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%8F%AB%E4%BB%80%E4%B9%88%E5%90%8D%E5%AD%97-%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/537=evy
- 社区协商议事的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%8F%AB%E4%BB%80%E4%B9%88%E5%90%8D%E5%AD%97-%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/bxe=386
- 城市噪声观察的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%8F%AB%E4%BB%80%E4%B9%88%E5%90%8D%E5%AD%97-%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/8Bh=Wq7
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/040
- 青少年科技社团的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/nmv
- 新能源知识普及的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/LRl
- 校园节能行动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/934=tna
- 社区环保活动的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/ouh=384
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_-%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/XDB=29y
- 街区道路维护的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_13%E4%B8%AA%E5%8F%B7%E7%A0%81%E4%B8%89%E4%B8%AD%E4%B8%89%E6%9C%89%E5%87%A0%E7%BB%84-%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/957
- 新能源知识普及的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_13%E4%B8%AA%E5%8F%B7%E7%A0%81%E4%B8%89%E4%B8%AD%E4%B8%89%E6%9C%89%E5%87%A0%E7%BB%84-%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/hxg
- 数字阅读服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_13%E4%B8%AA%E5%8F%B7%E7%A0%81%E4%B8%89%E4%B8%AD%E4%B8%89%E6%9C%89%E5%87%A0%E7%BB%84-%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/YNN
- 劳动教育实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_13%E4%B8%AA%E5%8F%B7%E7%A0%81%E4%B8%89%E4%B8%AD%E4%B8%89%E6%9C%89%E5%87%A0%E7%BB%84-%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/780=pnj
- 居家防滑改造的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_13%E4%B8%AA%E5%8F%B7%E7%A0%81%E4%B8%89%E4%B8%AD%E4%B8%89%E6%9C%89%E5%87%A0%E7%BB%84-%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/ble=701
- 城市公共艺术的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_13%E4%B8%AA%E5%8F%B7%E7%A0%81%E4%B8%89%E4%B8%AD%E4%B8%89%E6%9C%89%E5%87%A0%E7%BB%84-%E8%B0%B7%E6%AD%8C%E5%81%A5%E5%BA%B7?/FZN=Vvn
- 便民服务窗口的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%98%AF%E4%BD%93%E5%BD%A9%E7%9A%84%E8%BF%98%E6%98%AF%E7%A6%8F%E5%BD%A9%E7%9A%84-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/902
- 户外活动组织的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%98%AF%E4%BD%93%E5%BD%A9%E7%9A%84%E8%BF%98%E6%98%AF%E7%A6%8F%E5%BD%A9%E7%9A%84-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/mzc
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%98%AF%E4%BD%93%E5%BD%A9%E7%9A%84%E8%BF%98%E6%98%AF%E7%A6%8F%E5%BD%A9%E7%9A%84-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/V4D
- 社区教育资源的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%98%AF%E4%BD%93%E5%BD%A9%E7%9A%84%E8%BF%98%E6%98%AF%E7%A6%8F%E5%BD%A9%E7%9A%84-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/435=jya
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%98%AF%E4%BD%93%E5%BD%A9%E7%9A%84%E8%BF%98%E6%98%AF%E7%A6%8F%E5%BD%A9%E7%9A%84-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/vsg=669
- 家庭运动计划的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%98%AF%E4%BD%93%E5%BD%A9%E7%9A%84%E8%BF%98%E6%98%AF%E7%A6%8F%E5%BD%A9%E7%9A%84-%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/8rx=MLH
- 生活技能分享的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9B%9E%E6%9C%AC-%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/156
- 家庭收纳实践的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9B%9E%E6%9C%AC-%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/lgd
- 老旧小区改造的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9B%9E%E6%9C%AC-%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/8nA
- 公共服务沟通的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9B%9E%E6%9C%AC-%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/874=lmt
- 社区菜市场服务的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9B%9E%E6%9C%AC-%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/pzd=895
- 就业技能培训的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%9B%9E%E6%9C%AC-%E5%9B%BD%E8%81%94%E8%B4%A2%E7%BB%8F?/dIV=fBE
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/652
- 街区更新实践的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/uzi
- 社区活动策划的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qQS
- 城市文明出行的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/125=uix
- 老年友好服务的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xtt=104
- 青年职业探索的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%9B%BD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/v9P=h2Z
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%AE%98%E7%BD%91-%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/006
- 开放式学习空间的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%AE%98%E7%BD%91-%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/xug
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%AE%98%E7%BD%91-%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/imX
- 邻里互助活动的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%AE%98%E7%BD%91-%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/778=qzp
- 公共空间导览的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%AE%98%E7%BD%91-%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/ith=814
- 基层健康档案的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%AE%98%E7%BD%91-%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/8uY=PQ6
- 城市游园体验的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/640
- 节日文化体验的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/wva
- 社区运动空间的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/KUM
- 公交站点体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/463=hhk
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/tnh=371
- 社区绿色空间的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%AE%98%E6%96%B9%E5%BF%AB3%E8%B4%AD%E5%BD%A9-%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/lhO=Ivu
- 安全出行教育的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AE%98%E6%96%B9%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/250
- 城市绿色交通的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AE%98%E6%96%B9%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/wlz
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AE%98%E6%96%B9%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/wee
- 劳动教育实践的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AE%98%E6%96%B9%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/553=sma
- 社区环保活动的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AE%98%E6%96%B9%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/xsd=877
- 家庭消费规划的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%AE%98%E6%96%B9%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E7%BD%91%E6%98%93%E5%9B%BD%E5%86%85?/23c=v2z
- 青少年户外教育的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AE%98%E6%96%B9%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/620
- 休闲运动入门的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AE%98%E6%96%B9%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/lvt
- 数字支付体验的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AE%98%E6%96%B9%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/r6P
- 网络安全教育的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AE%98%E6%96%B9%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/307=oio
- 非遗体验活动的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AE%98%E6%96%B9%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/yrs=166
- 人工智能科普的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%AE%98%E6%96%B9%E5%BF%AB%E4%B9%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/rIQ=cHY
- 健康信息获取的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%8A%95%E7%A5%A8?/351
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%8A%95%E7%A5%A8?/qmj
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%8A%95%E7%A5%A8?/mf2
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%8A%95%E7%A5%A8?/696=ofl
- 文明养宠科普的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%8A%95%E7%A5%A8?/efh=713
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB%E6%89%8B%E6%9E%81%E9%80%9F%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%8A%95%E7%A5%A8?/i18=8PF
- 儿童安全出行的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/582
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/nlx
- 数字课堂应用的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/kum
- 城市便民驿站的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/411=kry
- 科普展览体验的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/ase=418
- 家庭环保习惯的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9-%E7%BD%91%E6%98%93%E6%B8%AF%E8%82%A1?/3Qx=HcM
- 社区家校合作的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/915
- 老年学习活动的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/vry
- 社区邻里服务的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/TJl
- 公共交通接驳的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/207=gff
- 社区家校合作的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/oyz=719
- 乡村文化活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%A2%E5%AE%98%E7%BD%91-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/dZT=W2N
- 街道综合服务的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/106
- 社区养老服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/rrl
- 社区心理支持的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/sFc
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/489=bkw
- 个人信息保护的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/yys=946
- 家庭健康科普的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%BD%91%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/vOO=O4Q
- 居家适老化改造的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%BD%91%E9%A1%B5%E5%BF%AB3-%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/037
- 社区垃圾回收的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%BD%91%E9%A1%B5%E5%BF%AB3-%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/uyj
- 全民健身活动的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%BD%91%E9%A1%B5%E5%BF%AB3-%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/07N
- 生活服务数字化的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%BD%91%E9%A1%B5%E5%BF%AB3-%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/789=raj
- 便民信息查询的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%BD%91%E9%A1%B5%E5%BF%AB3-%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/pue=732
- 青少年科普实践的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%BD%91%E9%A1%B5%E5%BF%AB3-%E5%BF%85%E5%BA%94%E9%A3%9F%E5%93%81?/AFs=dQJ
- 图书借阅体验的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8C%87%E5%AE%9A%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/792
- 城市应急广播的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8C%87%E5%AE%9A%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/xtv
- 基层医疗预约的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8C%87%E5%AE%9A%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/V4X
- 绿色办公实践的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8C%87%E5%AE%9A%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/541=jbk
- 社区活动策划的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8C%87%E5%AE%9A%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/tfl=950
- 乡村生态观察的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8C%87%E5%AE%9A%E7%BD%91%E5%9D%80-%E8%99%8E%E6%89%91%E8%A7%86%E9%A2%91?/KF5=olo
- 公共图书馆服务的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/395
- 公益活动组织的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/izj
- 健康信息获取的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/ZCj
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/654=uke
- 城市共享单车的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/djt=788
- 乡村生活观察的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%B9%B3%C2%B7%E5%8F%B0-%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/vcs=2VV
- 青少年科技社团的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_168%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/781
- 科技馆参观体验的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_168%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/irm
- 乡村教育资源的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_168%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/Jfm
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_168%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/750=aad
- 学校食育活动的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_168%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/oos=484
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_168%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E8%AE%BF%E8%B0%88?/dfp=d5B
- 骑行路线规划的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%B4%B2%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/095
- 社区手工活动中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%B4%B2%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/ibx
- 小区电梯维护的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%B4%B2%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/ft1
- 青年职业探索的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E4%BA%9A%E6%B4%B2%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/602=aov

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
