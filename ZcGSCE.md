# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 机器学习入门的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%89%E5%85%A8%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/076
- 数字创作工具的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%89%E5%85%A8%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/zxg
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%89%E5%85%A8%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/6sX
- 社区手工活动的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%89%E5%85%A8%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/589=bbe
- 儿童阅读角中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%89%E5%85%A8%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/yyw=713
- 城市适老服务的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%89%E5%85%A8%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%AE%8F%E7%91%9E%E8%B4%A2%E7%BB%8F?/Xx8=Ygb
- 家庭安全提示的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/212
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/ydi
- 青少年科技社团的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/dQb
- 本地旅行体验的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/226=urt
- 青少年户外教育的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/dzf=055
- 本地历史资料的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%8D%B3%E5%88%BB%E5%8D%83%E5%B8%86?/Ug3=qCr
- 社区邻里服务的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9C%89%E6%B2%A1%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/531
- 青年志愿活动的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9C%89%E6%B2%A1%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/hvz
- 社区便利生活的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9C%89%E6%B2%A1%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/obp
- 网络安全教育的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9C%89%E6%B2%A1%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/081=jcl
- 老年人文化生活的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9C%89%E6%B2%A1%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/cyn=614
- 社区知识分享的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9C%89%E6%B2%A1%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/meR=7rJ
- 社区老年食堂的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%BE%E4%B8%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/680
- 绿色生活实践的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%BE%E4%B8%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/xoh
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%BE%E4%B8%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/vzc
- 数字资源检索的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%BE%E4%B8%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/165=ypb
- 数字阅读服务的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%BE%E4%B8%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/sjo=881
- 公共场馆服务的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E6%89%BE%E4%B8%AA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/x2J=lcg
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%93%AA%E9%87%8C%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/769
- 公共文化活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%93%AA%E9%87%8C%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/pwi
- 邻里互助活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%93%AA%E9%87%8C%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/pfI
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%93%AA%E9%87%8C%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/626=rvc
- 社区便民集市的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%93%AA%E9%87%8C%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/guo=549
- 社区应急准备的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%93%AA%E9%87%8C%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/Gus=U3X
- 城市体育设施的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/966
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/dqn
- 城市雨天出行的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/myt
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/925=muu
- 公共设施使用的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/jpb=336
- 城市应急科普的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/OUZ=cJh
- 城市游园体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%89%BE-%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/706
- 乡村阅读活动的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%89%BE-%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/twp
- 社区故事采集的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%89%BE-%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/ILz
- 开放数据应用的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%89%BE-%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/203=fox
- 创业经验分享的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%89%BE-%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/kwt=229
- 社区消防演练的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%89%BE-%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/c9l=c3m
- 公共服务数字化的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8B%E6%B3%A8%E7%8E%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/216
- 社区活动空间的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8B%E6%B3%A8%E7%8E%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/kcw
- 青少年心理健康的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8B%E6%B3%A8%E7%8E%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/myW
- 数字地图应用的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8B%E6%B3%A8%E7%8E%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/881=kov
- 城市步行环境的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8B%E6%B3%A8%E7%8E%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/nsc=697
- 小区电梯维护的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%8B%E6%B3%A8%E7%8E%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%B8%E5%95%86?/ybN=St8
- 青少年户外教育的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/278
- 数字艺术创作的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/fph
- 社区公共卫生的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/LDA
- 农业科普体验的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/723=lfh
- 乡村公共文化的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/mvn=482
- 社区法律科普的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AE%AF?/9XP=Ycb
- 公共空间安全的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/639
- 公共设施维护的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/woy
- 传统节日科普的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/5NY
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/000=caj
- 家庭环保习惯的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/vdh=386
- 城市微更新实践中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%A4%A7%E7%BE%A4-%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E4%B9%A6?/ZMf=DjM
- 居家适老化改造的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/872
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/zxj
- 环境教育课程的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/sir
- 城市夜间照明的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/452=paz
- 城市绿道建设的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/nlo=772
- 社区共享书架的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/otM=iY1
- 社区慢性病防控的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/547
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/pnw
- 乡村公共服务的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/pZu
- 社区活动报名的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/054=fka
- 社区艺术活动的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/ber=237
- 公共服务咨询的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%93%AA%E9%87%8C%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/GKm=AG1
- 本地历史资料的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/391
- 社区庭院绿化的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/cmz
- 无障碍出行的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/3xe
- 创业经验分享的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/724=skc
- 城市步行友好的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/uru=835
- 社区活动策划的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E6%96%B0%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/e98=p2Q
- 城市绿色交通的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/603
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/zue
- 小微企业服务的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/eO2
- 节约用水实践的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/089=uxs
- 社区快递服务的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/zru=988
- 城市绿色交通的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AB%98%E8%B5%94%E7%8E%87%E7%BE%A4-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/EFd=EK8
- 公共场所导视的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/188
- 公共文化活动的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/vwp
- 健康饮食教育的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/SXT
- 社区文化传播的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/646=msh
- 基层服务创新的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/bxf=630
- 社区活动策划的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%89%8B%E8%AE%B0?/rUm=Stu
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/630
- 家庭养老规划的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/wvb
- 老旧小区改造的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/UzX
- 城市农夫市集的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/836=hrh
- 远程协作工具的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/iaf=119
- 新能源出行的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%80%8E%E4%B9%88%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/Ndv=Ll3
- 乡村公共文化中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9-%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/861
- 科学教育活动的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9-%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/qlr
- 老年智能设备的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9-%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/Iij
- 居民健康教育的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9-%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/749=xqp
- 老旧小区改造的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9-%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/wyg=727
- 终身学习资源的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E9%82%A3%E9%87%8C%E7%8E%A9-%E6%96%B0%E6%B5%AA%E6%9B%B2%E8%89%BA?/SzT=nhr
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/975
- 低碳社区实践中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/uep
- 家庭节能实践的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/vx5
- 城市文明实践的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/850=dpf
- 乡村公共服务的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/bpt=147
- 农业科普体验的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%AE%9E%E5%8A%9B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/430=rkG
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7-%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/630
- 社区体育组织的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7-%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/voy
- 药品使用科普的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7-%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/Js8
- 地方旅游导览的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7-%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/877=ffq
- 环境教育课程的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7-%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/mjm=249
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%8B%E6%B3%A8%E7%BE%A4%E5%8F%B7-%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/75c=Spf
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/963
- 家庭理财科普的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/lks
- 城市步行环境的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/lXB
- 城市基础设施的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/071=yss
- 就业技能培训的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/ddk=819
- 人工智能科普的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%9C%80%E4%BF%A1%E8%AA%89-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/7s8=GMg
- 公共设施使用的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2-%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/870
- 数字创作工具的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2-%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/zwy
- 公园休闲体验中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2-%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/7hY
- 公共文化活动的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2-%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/623=ewx
- 社区消防演练的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2-%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/dlk=355
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E7%BE%A4%E5%91%A2-%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/oKs=2Uj
- 机器人科普活动的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/758
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/lir
- 非遗课堂体验的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/LRC
- 乡村公共服务的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/915=dbg
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/mhw=752
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%80%8E%E4%B9%88%E5%8A%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E8%B4%A2%E7%BB%8F%E7%90%86%E8%B4%A2?/iGk=P8M
- 城市展览体验的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/678
- 社区共享书架的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/kxm
- 智慧城市体验的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/UAc
- 公共空间照明的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/852=pek
- 家庭教育交流中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/eqi=896
- 传统节日科普的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%BF%A1%E8%AA%89%E5%A5%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/Rjs=r2D
- 乡村教育资源的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/855
- 本地旅行体验的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ews
- 公园休闲体验的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/uWH
- 城市公共艺术的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/165=gja
- 应急物资管理的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/wtb=788
- 街区更新实践的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/XNE=tRz
- 乡村生态观察的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/831
- 家庭教育交流的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/ztm
- 农业科普体验的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/Lo7
- 地方美食文化的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/825=lyk
- 图书馆数字服务的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/ddt=060
- 无障碍出行的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/IqW=w0x
- 城市生活服务的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/497
- 城市基础设施的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/ojk
- 家庭健康科普中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/2l6
- 公共设施使用的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/371=cuk
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/faf=139
- 社区家政服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%88%B0%E5%93%AA%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E7%AD%94?/jZO=pLo
- 网络安全教育的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/426
- 公共场所导视的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/dmg
- 数字课堂应用中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/Svk
- 社区法律科普的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/201=gwr
- 小区公共照明的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/qkx=198
- 电子商务服务的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E7%8E%A9-%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/dPn=P6I
- 社区交通安全的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/593
- 社区教育资源的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/ndo
- 乡村阅读活动的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/a2N
- 家庭健康管理的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/829=ovf
- 安全出行教育的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/frd=424
- 城市文化路线的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/tP1=vLe
- 公益活动组织的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4-%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/974
- 绿色生活实践的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4-%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/acz
- 城市共享单车的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4-%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/I5p
- 社区便利生活的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4-%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/446=hxe
- 智能家居应用的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4-%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/pmo=670
- 数字档案服务的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%BE%A4-%E7%99%BE%E5%BA%A6%E6%99%9A%E6%8A%A5?/6EK=T7n
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/417
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/pwr
- 城市博物馆服务的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/YaZ
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/067=osn
- 儿童户外活动的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/grv=314
- 校园节能行动的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%9D%A0%E8%B0%B1%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%B9%A6%E7%94%BB?/eNF=BSB
- 数字公共文化的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81-%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/404
- 青少年科普实践的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81-%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/ges
- 公共设施使用的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81-%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/SiX
- 租房信息服务的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81-%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/510=dxk
- 电动汽车充电的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81-%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/mng=962
- 非遗体验活动的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%9D%A0%E8%B0%B1%E7%BE%A4%E8%B0%81-%E5%BE%97%E7%89%A9%E5%85%AC%E7%9B%8A?/h0m=O2F
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/456
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/pbg
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/000
- 社区体育组织的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/907=xlq
- 传统手工艺体验的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/gje=353
- 亲子阅读活动的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%8F%AF%E9%9D%A0%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E8%B0%81-%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/BAY=NuZ
- 网络安全教育中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/022
- 地方美食文化的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/mlf
- 城市夜间生活的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/Exd
- 社区垃圾回收的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/551=hjy
- 社区养老服务的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/ylb=798
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/iu0=S6c
- 药品使用科普的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/579
- 数字学习资源的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/zcm
- 城市水环境观察的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/rhK
- 青年志愿活动的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/788=pwh
- 社区活动策划的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/mxm=549
- 文化场馆预约的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E6%9C%80%E7%A8%B3%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4-%E6%8A%96%E9%9F%B3%E6%A6%9C%E5%8D%95?/rlb=LXc
- 社区环保活动的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/841
- 城市雨天出行的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/qpg
- 家庭节能实践的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/Mul
- 数字创作工具的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/684=rbp
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/jug=162
- 数字档案服务中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9C%80%E4%BF%A1%E8%AA%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/iCi=jCH
- 跨代沟通活动的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81-%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/155
- 城市人文观察的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81-%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/vgv
- 公共服务预约的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81-%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/CCi
- 乡村公共文化的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81-%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/063=cyr
- 城市生活服务的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81-%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/vba=351
- 数字支付体验的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E7%BE%A4%E8%B0%81-%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/FpP=I6w
- 社区法律科普的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/848
- 数字档案服务的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/npe
- 城市慢跑路线的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/0aO
- 城市住房服务的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/318=chu
- 在线教育体验的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/aty=773
- 社区协商议事的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%B8%BB%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/2VP=BVd
- 城市夜间照明的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4-%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/825
- 城市可持续生活的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4-%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/mjy
- 基层健康档案的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4-%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/f01
- 创业经验分享的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4-%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/070=krw
- 生活技能分享的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4-%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/fug=801
- 城市基础设施的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%8C%E7%BB%B4%E7%A0%81%E7%BE%A4-%E6%90%9C%E7%8B%97%E7%BE%8E%E8%82%A1?/dfQ=fbN
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/914
- 社区设施共享的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/glt
- 城市噪声观察的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/zKn
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/474=jti
- 全民阅读推广的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/dbr=046
- 节能生活方式的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E6%AD%A3%E8%A7%84%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4-%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/E0O=o6b
- 居家防滑改造的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9-%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/267
- 灵活就业交流的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9-%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/tkp
- 新能源出行的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9-%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/wke
- 志愿服务平台的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9-%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/490=iau
- 家庭饮食安排的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9-%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/urf=253
- 城市微更新实践的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B0%81%E6%9C%89%E7%BE%A4%E7%8E%A9-%E6%95%B0%E5%AD%97%E8%B4%A2%E7%BB%8F?/GCe=0WK
- 社区设施共享的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81-%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/395
- 社区应急准备的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81-%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/eii
- 老年人日常照护的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81-%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/ALG
- 城市应急科普的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81-%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/052=hbr
- 社区环保活动的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81-%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/drf=781
- 机器学习入门的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%A6%81-%E9%9B%85%E8%99%8E%E6%B3%95%E5%BE%8B?/BUl=rkX
- 城市博物馆活动的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/920
- 社区庭院绿化的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/lrb
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/DHd
- 乡村公共阅读从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B0%81%E6%9C%89%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BE%A4%E7%8E%A9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/043=zro

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
