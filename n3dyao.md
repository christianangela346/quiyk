# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 开源技术交流的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E3%80%8A%E6%9E%81%E9%80%9F%E9%A3%9E%E8%BD%A6%E3%80%8B%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/Kdm
- 个人信息保护的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E3%80%8A%E6%9E%81%E9%80%9F%E9%A3%9E%E8%BD%A6%E3%80%8B%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/451=kjp
- 家庭用电安全的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E3%80%8A%E6%9E%81%E9%80%9F%E9%A3%9E%E8%BD%A6%E3%80%8B%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/ihc=720
- 青少年科普实践的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E3%80%8A%E6%9E%81%E9%80%9F%E9%A3%9E%E8%BD%A6%E3%80%8B%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/xaB=mni
- 城市公共自行车的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_2%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_36%E6%B0%AA%E8%A6%81%E9%97%BB?/911
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_2%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_36%E6%B0%AA%E8%A6%81%E9%97%BB?/fsd
- 读书会组织的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_2%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_36%E6%B0%AA%E8%A6%81%E9%97%BB?/2xt
- 在线教育体验的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_2%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_36%E6%B0%AA%E8%A6%81%E9%97%BB?/111=qfm
- 数字档案服务的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_2%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_36%E6%B0%AA%E8%A6%81%E9%97%BB?/kgd=667
- 节能生活方式的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_2%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%97%A0%E6%95%8C%E8%BD%A6%E5%9E%8B_36%E6%B0%AA%E8%A6%81%E9%97%BB?/yt0=JEz
- 社区花园共建中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BD%91--1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/579
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BD%91--1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/pyc
- 街头绿植养护的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BD%91--1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/KJj
- 街头绿植养护的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BD%91--1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/949=pze
- 家庭健康科普的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BD%91--1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/wuj=570
- 城市展览体验的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BD%91--1_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/kk1=twe
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/324
- 老旧小区改造的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/xbk
- 城市文明出行的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/UXo
- 社区文化节活动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/510=yob
- 科学信息获取的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/rum=682
- 社区宠物管理的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/dxh=z1Y
- 公共交通信息服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/173
- 社区绿色空间的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/wqr
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/caJ
- 就业技能培训的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/758=ies
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/art=899
- 便民服务窗口的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/DH3=ZKn
- 社区心理支持的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%90%9C%E7%8B%97?/098
- 乡村阅读空间从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%90%9C%E7%8B%97?/zqo
- 老年友好服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%90%9C%E7%8B%97?/6tA
- 家庭照护支持中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%90%9C%E7%8B%97?/192=qxt
- 城市可持续生活的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%90%9C%E7%8B%97?/nzb=372
- 城市骑行环境的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%99%BB%E5%BD%95%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%90%9C%E7%8B%97?/0cp=nHC
- 公共服务评价中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/781
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/xeq
- 社区环保活动的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/sdw
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/475=ilv
- 公共服务评价的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/aoy=613
- 科学运动指导的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E8%84%89%E8%84%89%E6%9C%9F%E8%B4%A7?/FHt=69U
- 城市公共标识的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/080
- 数字生活课堂的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/rbs
- 口袋公园建设的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/MYQ
- 邻里互助活动的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/646=wvb
- 老年人日常照护的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/ibc=801
- 地方旅游导览的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AF%BB%E5%9B%BE?/Eda=0FS
- 社区应急准备的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E5%90%97_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/349
- 社区互助网络的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E5%90%97_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/fhz
- 骑行路线规划的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E5%90%97_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/G4K
- 城市农夫市集的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E5%90%97_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/098=yed
- 社区应急准备的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E5%90%97_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/qpv=586
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%89%E5%AE%98%E7%BD%91%E5%90%97_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/2WX=MoL
- 公园无障碍服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E6%8E%A2%E5%BA%97?/852
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E6%8E%A2%E5%BA%97?/uxq
- 城市农夫市集的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E6%8E%A2%E5%BA%97?/iQ7
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E6%8E%A2%E5%BA%97?/788=lix
- 家庭环保习惯的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E6%8E%A2%E5%BA%97?/usv=580
- 儿童友好空间的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E6%8E%A2%E5%BA%97?/pN0=xYq
- 社区环保活动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E9%BB%91%E6%B4%9E%E8%BD%A6%E5%9E%8B_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/608
- 公交无障碍服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E9%BB%91%E6%B4%9E%E8%BD%A6%E5%9E%8B_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/pxz
- 亲子阅读活动的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E9%BB%91%E6%B4%9E%E8%BD%A6%E5%9E%8B_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/K7z
- 家庭健康科普的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E9%BB%91%E6%B4%9E%E8%BD%A6%E5%9E%8B_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/481=ebb
- 城市公共空间的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E9%BB%91%E6%B4%9E%E8%BD%A6%E5%9E%8B_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/tel=172
- 城市建设科普的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E9%BB%91%E6%B4%9E%E8%BD%A6%E5%9E%8B_%E8%99%8E%E6%89%91%E6%89%8B%E8%AE%B0?/Cpi=9Z5
- 农村环境治理的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%B4%E5%8D%87%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/352
- 社区阅读服务的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%B4%E5%8D%87%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/xjg
- 城市文明出行的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%B4%E5%8D%87%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/pDy
- 科学教育活动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%B4%E5%8D%87%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/655=wbo
- 城市慢跑路线的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%B4%E5%8D%87%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/sjs=406
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%B4%E5%8D%87%E6%9C%BA_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/5Ae=uI3
- 儿童户外活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E8%B5%9B%E5%8D%9A%E5%A5%97%E8%A3%85_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/618
- 科学健身方法的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E8%B5%9B%E5%8D%9A%E5%A5%97%E8%A3%85_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/lly
- 城市休闲步道的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E8%B5%9B%E5%8D%9A%E5%A5%97%E8%A3%85_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/pQi
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E8%B5%9B%E5%8D%9A%E5%A5%97%E8%A3%85_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/099=zvo
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E8%B5%9B%E5%8D%9A%E5%A5%97%E8%A3%85_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/axd=314
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E8%B5%9B%E5%8D%9A%E5%A5%97%E8%A3%85_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/hkc=5d4
- 社区花园共建的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%A9%BA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/532
- 城市公共饮水的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%A9%BA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/mhp
- 城市绿色交通的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%A9%BA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/luW
- 家庭阅读计划的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%A9%BA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/713=arz
- 社区共享书架的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%A9%BA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/zir=847
- 地方美食文化的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A9%E7%A9%BA%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E7%9F%A5%E4%B9%8E%E5%A4%B4%E6%9D%A1?/MXI=xQD
- 公共服务咨询的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E9%92%BB%E7%9F%B3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/643
- 户外活动组织的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E9%92%BB%E7%9F%B3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/btn
- 数字支付体验的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E9%92%BB%E7%9F%B3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/SJj
- 劳动教育实践的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E9%92%BB%E7%9F%B3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/872=apo
- 科普展览体验的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E9%92%BB%E7%9F%B3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/zrt=094
- 开放数据应用的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%A0%B4%E8%A7%A3%E7%89%88%E9%92%BB%E7%9F%B3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%81%E5%8B%9F?/Qos=bq1
- 公共交通接驳的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/763
- 社区停车服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kdr
- 创业经验分享的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Q9s
- 青年就业服务的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/593=ffb
- 乡村阅读活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zez=242
- 数字艺术创作的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E4%B8%8B%E8%BD%BD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lYk=vah
- 电子商务服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/670
- 环境监测科普的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/utx
- 校园社团活动的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/XjW
- 社区绿色空间的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/420=fft
- 就业技能培训的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/agn=031
- 物业服务沟通的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E5%AE%A0%E7%89%A9%E5%B8%81%E6%80%8E%E4%B9%88%E8%B5%9A_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/ICf=Atn
- 个人数据管理的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/853
- 城乡交通衔接的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/koe
- 社区读书角建设的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/U93
- 老年人日常照护的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/132=xkd
- 非遗体验活动的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/ycc=721
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%9B%86%E6%A0%BD%E8%A2%AB%E5%90%88%E6%88%90%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/OgL=9vZ
- 公共场馆服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/902
- 社区环保活动的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/qyz
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/n2u
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/436=itb
- 个人数据管理的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/tsp=310
- 社区活动报名的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B8%93%E6%A0%8F?/z1r=PwI
- 数字政务体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/094
- 物业服务沟通的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/njc
- 节约用水实践的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/oSf
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/584=agc
- 开源技术交流的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/hiu=383
- 城市建设科普的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/kzp=eq5
- 社区防暑服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/955
- 青少年户外教育的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/cul
- 生成式工具使用的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/aZL
- 网络安全教育的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/521=ysb
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/iqa=987
- 安全出行教育的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/s55=6To
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/658
- 文化讲座服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/dsf
- 社区知识分享的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/fWx
- 健康信息获取的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/720=qym
- 光伏知识科普的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/qyo=476
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_168%E9%A3%9E%E8%89%87%E6%98%AF%E5%90%A6%E6%AD%A3%E8%A7%84_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/blQ=Y5Z
- 城市骑行环境的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/181
- 生活服务数字化的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/gci
- 公共服务预约的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/aIB
- 城市游园体验的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/220=qha
- 城市空气科普的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/xrw=684
- 公共服务指南的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87%E6%AD%A3%E8%A7%84%E5%90%97__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/PRn=hgs
- 社区活动空间的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/380
- 社区便利生活的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/uqv
- 数字便民地图的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Bkl
- 全民阅读推广的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/952=ynz
- 本地历史资料的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qpw=987
- 公共图书馆服务的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E9%A3%9E%E8%89%87%E6%8A%80%E5%B7%A7_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/6av=0YY
- 社区便民服务的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/406
- 小区公共照明的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/gqv
- 公园亲子设施的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/TuB
- 社区文化节活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/770=vvd
- 休闲运动入门的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/ycd=714
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_168%E9%A3%9E%E8%89%87%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/5xK=5xU
- 科学健身方法的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/594
- 科学教育活动的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/xdq
- 数字便民地图的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/G7g
- 乡村公共服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/174=ihe
- 城市运动公园的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/prk=526
- 地方戏曲体验的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%A3%9E%E8%89%87168%E7%BD%91%E7%AB%99%E5%A4%9A%E5%B0%91_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AE%AF?/E7y=498
- 城市水环境观察的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/921
- 新能源知识普及的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/idl
- 全民健身活动的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/NXT
- 家庭节能设备的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/667=kmf
- 城市可持续生活的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/xzz=577
- 光伏知识科普的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_168%E9%A3%9E%E8%89%87%E6%9C%89%E6%8A%80%E5%B7%A7%E5%90%97_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/JOm=iuY
- 家庭用电安全的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/796
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/smd
- 城市公共饮水的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/Usv
- 乡村文化空间的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/186=spt
- 城市慢行系统的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/lcn=409
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E9%A3%9E%E8%89%87168%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/cgU=DAW
- 街道综合服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/521
- 在线学习体验的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/plf
- 城市公共自行车的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/tTg
- 社区环保活动的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/915=xpj
- 休闲运动入门的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/ket=188
- 课后服务体验的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E9%A3%9E%E8%89%87%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/WQr=Tqe
- 城市适老服务的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/060
- 社区故事采集的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/ykl
- 社区便民集市的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/7HK
- 社区防暑服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/735=xdz
- 科学教育活动的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/guv=500
- 绿色校园实践的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_168%E9%A3%9E%E8%89%87%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/kZa=QIa
- 读书会组织的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/415
- 公共服务咨询的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/hgu
- 户外活动组织的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/uzV
- 老年人文化生活的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/792=zjo
- 城市树木认养的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/xgl=454
- 社区防暑服务的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/ahi=EW5
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/459
- 农村环境治理的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/pgq
- 社区文化节活动的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/6sG
- 劳动教育实践的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/372=smw
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/mwj=809
- 生活垃圾回收的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_168%E5%AE%98%E6%96%B9%E5%B9%B8%E8%BF%905%E6%BE%B3%E6%B4%B2%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%81%8C%E5%9C%BA?/ljv=Swl
- 安全出行教育的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/597
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/inh
- 城市步行环境的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/29k
- 社区志愿服务的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/020=gxq
- 远程协作工具的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/wvl=146
- 就业技能培训的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90168%E5%AE%98%E7%BD%91%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/kdp=noh
- 数字生活课堂的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/690
- 城市微更新实践的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/dps
- 社区信息发布的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/Ph6
- 公共服务评价的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/907=bvq
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/yyi=925
- 创业经验分享的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4_%E5%87%A4%E5%87%B0%E6%9C%AD%E8%AE%B0?/UFp=lEj
- 无障碍信息设计的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/470
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/zcm
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/ORu
- 骑行路线规划的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/073=eyu
- 居家适老化改造的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/yau=988
- 食品配送体验的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_168%E8%B5%9B%E8%BD%A6%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/yvB=94b
- 家庭园艺实践的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/777
- 数据分析入门中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/qgu
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/llA
- 文明养宠科普的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/182=bsh
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/whe=685
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_168%E8%B5%9B%E8%BD%A6%E8%80%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%89%8B%E8%AE%B0?/Z5w=i4Z
- 社区养老服务的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/328
- 家庭科学教育的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/thk
- 小区电梯维护的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/NYB
- 数字创意课程中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/934=xmt
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/jrm=327
- 文化讲座服务的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/p5l=3Ej
- 数字设备回收的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/980
- 社区便民集市的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/fzh
- 地方美食文化的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/Epm
- 公共场馆服务的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/635=mtr
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/ckf=667
- 社区信息发布的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/ZEY=d2B
- 市民热线服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/493
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/xpv
- 街道综合服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/1UA
- 网络安全教育中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/706=iew
- 社区知识分享的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/iax=960
- 图书馆数字服务的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A8%E7%BD%91%E7%BB%9F%E4%B8%80_%E5%A4%B4%E6%9D%A1%E5%AE%8F%E8%A7%82?/zuP=J5j
- 绿色消费选择的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/988
- 城市骑行环境的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/dwq
- 健康饮食教育中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/1XR
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/827=ybp
- 公共设施使用的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/uha=781
- 社区科普课堂的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%99%8E%E5%97%85%E5%9B%AD%E8%89%BA?/hvi=cec
- 农产品消费体验的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/263
- 数字生活课堂的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/yep
- 基层健康档案的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/oSD
- 机器人科普活动的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/538=nhg
- 物业服务沟通的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/cam=093
- 软件开发学习的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/IRQ=4za
- 社区互助网络的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/788
- 乡村文化空间的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/znu
- 节约用水实践的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/2K1
- 便民信息查询的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/008=gid
- 节假日出行安排的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/tqa=894
- 城市步行环境的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%95%85%E6%B8%B8?/DTN=hBV

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
