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

- 城市建设科普的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/U1K
- 城市住房服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/523=vcx
- 数字政务体验的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/une=622
- 家庭照护支持的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/r6c=r8X
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%85%A8%E5%90%8D_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/013
- 小区公共照明的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%85%A8%E5%90%8D_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/hnl
- 小区停车协商的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%85%A8%E5%90%8D_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/gWH
- 农村环境治理的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%85%A8%E5%90%8D_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/271=hdw
- 健康步道使用的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%85%A8%E5%90%8D_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/qvb=725
- 节能家电使用的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%85%A8%E5%90%8D_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/zeI=f5T
- 开放式学习空间的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%B8%80%E6%AC%BE%E4%BB%80%E4%B9%88%E6%B8%B8%E6%88%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/070
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%B8%80%E6%AC%BE%E4%BB%80%E4%B9%88%E6%B8%B8%E6%88%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/gxk
- 便民服务地图的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%B8%80%E6%AC%BE%E4%BB%80%E4%B9%88%E6%B8%B8%E6%88%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/074
- 图书馆活动策划的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%B8%80%E6%AC%BE%E4%BB%80%E4%B9%88%E6%B8%B8%E6%88%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/022=xsa
- 城乡交流活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%B8%80%E6%AC%BE%E4%BB%80%E4%B9%88%E6%B8%B8%E6%88%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/pwv=300
- 社区公共议事的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E4%B8%80%E6%AC%BE%E4%BB%80%E4%B9%88%E6%B8%B8%E6%88%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/WQs=K1S
- 跨代沟通活动的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9B%BE%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/646
- 家庭科学教育的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9B%BE%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/kbo
- 线上办事服务的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9B%BE%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/NCX
- 乡村教育资源的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9B%BE%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/256=ucn
- 公共文化活动的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9B%BE%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/bfc=217
- 小区公共照明的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E9%9F%A9%E5%9B%BD%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%9B%BE%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/oq7=R4e
- 本地历史资料的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/712
- 社区设施共享的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/ues
- 农贸市场环境的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/eKv
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/787=awm
- 居家防滑改造的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/ukx=153
- 公共交通接驳中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/KGS=nMX
- 科学观察活动的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E4%B8%80%E6%9C%9F_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/130
- 老旧小区改造的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E4%B8%80%E6%9C%9F_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/cdy
- 乡村电商实践有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E4%B8%80%E6%9C%9F_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/qfq
- 青少年科技社团的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E4%B8%80%E6%9C%9F_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/714=rkd
- 城市可持续生活的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E4%B8%80%E6%9C%9F_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/csu=576
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%8C%97%E4%BA%AC%E5%BF%AB3%E5%A4%9A%E9%95%BF%E6%97%B6%E9%97%B4%E4%B8%80%E6%9C%9F_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/Uc2=wMH
- 公交站点体验的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/502
- 老年人日常照护的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/uoc
- 市民意见收集的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/AXG
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/743=csw
- 社区教育资源的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/azf=412
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/ff2=Jli
- 生成式工具使用的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_Welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/581
- 绿色快递包装的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_Welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/hii
- 公共空间照明的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_Welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/oPk
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_Welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/256=hki
- 小微企业服务的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_Welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/kbs=011
- 电动汽车充电的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_Welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/Ztp=KUj
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%90%8D%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/096
- 家庭理财科普的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%90%8D%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/lev
- 便民服务窗口的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%90%8D%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/ax2
- 城市可持续生活的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%90%8D%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/169=cck
- 城市人文观察的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%90%8D%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/qeg=524
- 社区设施共享的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%90%8D%E5%8F%AB%E4%BB%80%E4%B9%88_%E5%BE%97%E7%89%A9%E8%B4%A2%E7%BB%8F?/lyg=a2r
- 社区文化节活动中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/679
- 旧物循环利用的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/bwx
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/rOD
- 城市公共饮水的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/025=mmy
- 数字支付体验的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/ggq=384
- 老旧小区改造的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/REh=NGf
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/993
- 社区艺术活动的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/nof
- 课后服务体验的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/2rI
- 网络安全教育的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/213=gnm
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/beq=767
- 休闲运动入门的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%8F%8C%E8%89%B2%E7%90%83%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/gct=m2L
- 社区共享书架的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8D%95%E6%9C%BA%E5%BF%AB3%E6%B8%B8%E6%88%8F%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/188
- 社区阅读服务的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8D%95%E6%9C%BA%E5%BF%AB3%E6%B8%B8%E6%88%8F%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/yvp
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8D%95%E6%9C%BA%E5%BF%AB3%E6%B8%B8%E6%88%8F%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/LfR
- 个人数据管理的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8D%95%E6%9C%BA%E5%BF%AB3%E6%B8%B8%E6%88%8F%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/363=eej
- 公共空间休憩的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8D%95%E6%9C%BA%E5%BF%AB3%E6%B8%B8%E6%88%8F%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/bph=132
- 社区垃圾回收的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8D%95%E6%9C%BA%E5%BF%AB3%E6%B8%B8%E6%88%8F%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E7%A7%81%E5%8B%9F?/6RQ=AQ8
- 城市地名文化的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%B4%AB%E7%8E%A9%E7%9B%92%E5%AD%90%E5%A4%8D%E5%8F%A41.76_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/459
- 环境监测科普的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%B4%AB%E7%8E%A9%E7%9B%92%E5%AD%90%E5%A4%8D%E5%8F%A41.76_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/npz
- 社区生活指南的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%B4%AB%E7%8E%A9%E7%9B%92%E5%AD%90%E5%A4%8D%E5%8F%A41.76_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/rTF
- 城市慢行系统的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%B4%AB%E7%8E%A9%E7%9B%92%E5%AD%90%E5%A4%8D%E5%8F%A41.76_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/810=jtl
- 跨代沟通活动的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%B4%AB%E7%8E%A9%E7%9B%92%E5%AD%90%E5%A4%8D%E5%8F%A41.76_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/zmq=992
- 家庭收纳实践的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E7%B4%AB%E7%8E%A9%E7%9B%92%E5%AD%90%E5%A4%8D%E5%8F%A41.76_%E7%9F%A5%E4%B9%8E%E6%9C%AD%E8%AE%B0?/WjJ=YH2
- 旧物循环利用的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/872
- 在线学习体验的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/zaw
- 社区邻里服务的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/kdz
- 科普展览体验的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/168=aza
- 社区花园共建的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/zvv=826
- 城市游园体验的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC_%E8%99%8E%E5%97%85%E6%8A%95%E8%B5%84?/4gC=B59
- 街道综合服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%BD%91%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/590
- 健康信息获取的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%BD%91%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/jzm
- 电动汽车充电的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%BD%91%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/dQy
- 食品安全科普的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%BD%91%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/216=kmu
- 城市文明出行的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%BD%91%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/hvf=845
- 非遗体验活动的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%BD%91%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/P8G=A4i
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/981
- 绿色生活实践的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/yle
- 城市步行友好的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/Nqz
- 市民热线服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/408=ocd
- 公共交通接驳的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/zxm=546
- 家庭网络使用的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A6%81%E9%97%BB?/fc4=bRa
- 小微企业服务的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/401
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/zqo
- 乡村阅读活动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/HJP
- 家庭照护支持的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/022=lrs
- 社区便民服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/jtc=506
- 公共服务评价的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%90%97_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/olV=PLD
- 就业技能培训的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8C%A3%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/859
- 社区协商议事的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8C%A3%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/gms
- 社区消防演练的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8C%A3%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/m3a
- 开放数据应用的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8C%A3%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/271=nef
- 网络信息辨识的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8C%A3%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/pms=597
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8C%A3%E9%92%B1_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/Wz8=HpZ
- 消防知识宣传的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E6%88%91%E7%A1%AE%E5%AE%9E%E8%B5%9A%E9%92%B1%E4%BA%86_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/662
- 城市公共厕所的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E6%88%91%E7%A1%AE%E5%AE%9E%E8%B5%9A%E9%92%B1%E4%BA%86_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/frq
- 机器学习入门的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E6%88%91%E7%A1%AE%E5%AE%9E%E8%B5%9A%E9%92%B1%E4%BA%86_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/EzG
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E6%88%91%E7%A1%AE%E5%AE%9E%E8%B5%9A%E9%92%B1%E4%BA%86_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/966=qqf
- 公共设施维护的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E6%88%91%E7%A1%AE%E5%AE%9E%E8%B5%9A%E9%92%B1%E4%BA%86_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/emu=953
- 个人信息保护的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E6%88%91%E7%A1%AE%E5%AE%9E%E8%B5%9A%E9%92%B1%E4%BA%86_%E6%BE%8E%E6%B9%83%E6%B1%BD%E8%BD%A6?/AQQ=cJg
- 街头绿植养护的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/926
- 家庭志愿活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/kxy
- 社区菜市场服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/Kad
- 公共设施使用的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/342=jye
- 智能家居应用的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/cow=609
- 青年志愿活动中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/n7o=Qct
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/459
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/iia
- 城乡交通衔接的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/91Y
- 家庭节能设备的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/199=gaj
- 邻里互助活动的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/pta=127
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%A1%88_%E5%BF%85%E5%BA%94%E5%81%A5%E5%BA%B7?/UKH=FaG
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/104
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/hgj
- 街区绿化养护的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/Mm3
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/220=fbc
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/uep=038
- 城市微更新实践的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/2Fm=Mbt
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E2%80%94%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/957
- 社区停车服务的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E2%80%94%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/mxf
- 社区交通安全的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E2%80%94%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/4wQ
- 网络安全教育的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E2%80%94%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/131=nrc
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E2%80%94%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/fod=255
- 线上办事服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E2%80%94%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_36%E6%B0%AA%E6%99%9A%E6%8A%A5?/b3Y=B8F
- 老年人文化生活的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/373
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/gpq
- 劳动教育实践的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/RQT
- 青少年科普实践的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/738=khw
- 绿色校园实践的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/xjd=541
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92qq%E7%BE%A4_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/AaO=ARc
- 农业科普体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/824
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/afa
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/xsf
- 城市空气科普的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/715=vds
- 灵活就业交流的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/mqv=237
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%BF%85%E5%BA%94%E4%BF%A1%E6%89%98?/naq=5oY
- 城乡公共服务的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BE%AE%E8%81%8A_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/159
- 科普展览体验的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BE%AE%E8%81%8A_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/yeo
- 低碳社区实践的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BE%AE%E8%81%8A_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/aAR
- 节气饮食文化的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BE%AE%E8%81%8A_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/804=hhr
- 小微企业服务的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BE%AE%E8%81%8A_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hlt=722
- 社区防暑服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BE%AE%E8%81%8A_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wA6=h2A
- 城市地名文化的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E5%BF%AB3_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/938
- 乡村生活观察的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E5%BF%AB3_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/xlg
- 数字阅读服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E5%BF%AB3_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/aJZ
- 节能生活方式的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E5%BF%AB3_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/079=nid
- 社区艺术活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E5%BF%AB3_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/bzn=577
- 口袋公园建设的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E5%BF%AB3_%E5%93%94%E5%93%A9%E8%AF%BB%E4%B9%A6?/aOX=Qbf
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/103
- 社区花园共建中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/zmq
- 便民服务地图的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/ytu
- 绿色出行服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/482=rui
- 城乡交流活动的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/nto=888
- 社会体育指导的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BE%AE%E8%81%8A%E7%A6%8F%E5%BD%A9%E5%BF%AB3_%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/Exr=Bh4
- 学校体育活动的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BE%AE%E8%81%8A%E5%BF%AB3%E6%8A%95%E6%B3%A8_360%E8%B5%84%E8%AE%AF?/934
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BE%AE%E8%81%8A%E5%BF%AB3%E6%8A%95%E6%B3%A8_360%E8%B5%84%E8%AE%AF?/hok
- 口袋公园建设的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BE%AE%E8%81%8A%E5%BF%AB3%E6%8A%95%E6%B3%A8_360%E8%B5%84%E8%AE%AF?/i0e
- 儿童运动体验的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BE%AE%E8%81%8A%E5%BF%AB3%E6%8A%95%E6%B3%A8_360%E8%B5%84%E8%AE%AF?/336=qzm
- 小区公共照明的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BE%AE%E8%81%8A%E5%BF%AB3%E6%8A%95%E6%B3%A8_360%E8%B5%84%E8%AE%AF?/oah=027
- 健康信息获取的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BE%AE%E8%81%8A%E5%BF%AB3%E6%8A%95%E6%B3%A8_360%E8%B5%84%E8%AE%AF?/27Q=jPx
- 个人时间管理的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%81%8A%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/457
- 青少年心理健康的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%81%8A%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/kcf
- 城市文明出行的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%81%8A%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/3xN
- 邻里共享空间的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%81%8A%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/294=bfh
- 数字设备回收的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%81%8A%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/xqv=451
- 社区托育服务的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%81%8A%E4%BF%A1_%E7%95%8C%E9%9D%A2%E5%B9%B6%E8%B4%AD?/R9H=RD4
- 城市基础设施的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BE%AE%E5%BD%A9%E7%A5%A8app%E5%BF%AB3_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/016
- 安全出行教育的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BE%AE%E5%BD%A9%E7%A5%A8app%E5%BF%AB3_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/vxx
- 邻里共享空间的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BE%AE%E5%BD%A9%E7%A5%A8app%E5%BF%AB3_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/iQk
- 校园安全教育的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BE%AE%E5%BD%A9%E7%A5%A8app%E5%BF%AB3_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/681=dss
- 儿童友好空间的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BE%AE%E5%BD%A9%E7%A5%A8app%E5%BF%AB3_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/wwl=807
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BE%AE%E5%BD%A9%E7%A5%A8app%E5%BF%AB3_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/8Fq=jwO
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/727
- 农贸市场环境的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/dfr
- 数字素养提升的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/sPg
- 课后服务体验的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/656=iwy
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/vmc=966
- 智能家居应用的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BE%AE%E4%BF%A1_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/aq6=VCJ
- 老年人文化生活的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%BA%A4%E6%B5%81_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/560
- 节假日出行安排的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%BA%A4%E6%B5%81_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/opt
- 老年友好服务的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%BA%A4%E6%B5%81_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/4Tt
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%BA%A4%E6%B5%81_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/518=vmi
- 城市公共艺术的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%BA%A4%E6%B5%81_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/uqa=560
- 电子商务服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%BA%A4%E6%B5%81_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%85%E6%B8%B8?/FYI=sfz
- 节日文化体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/024
- 在线学习体验的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/tfu
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/VpF
- 数字课堂应用的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/407=qoc
- 农业科普体验的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/orj=221
- 家庭用电安全的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E8%99%8E%E6%89%91%E5%8D%9A%E5%AE%A2?/FQ4=1Z5
- 家庭消费规划的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/235
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/fzx
- 个人信息保护的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/E7z
- 乡村教育资源的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/069=rzm
- 家庭环保行动的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/ded=587
- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E4%BC%98%E9%85%B7%E7%88%86%E6%96%99?/7kU=j95
- 社区垃圾回收的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_c%E8%81%8A%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/593
- 老年智能设备的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_c%E8%81%8A%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/oho
- 科学健身方法的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_c%E8%81%8A%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/lYx
- 公共空间照明的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_c%E8%81%8A%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/271=zsy
- 公共空间照明的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_c%E8%81%8A%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/lld=768
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_c%E8%81%8A%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/o22=VXR
- 公共空间导览的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/057
- 市民热线服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/xzz
- 个人信息保护的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/pMG
- 社区学习活动的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/912=igr
- 城市展览体验的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/ife=154
- 开源技术交流的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BF%AB3%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/cFY=XM1
- 乡村阅读活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/482
- 社区防暑服务的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/uhe
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/d7y
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/720=fug
- 公共空间安全的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/tqa=103
- 新能源知识普及的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9C%89%E7%8E%A9%E5%BF%AB3%E7%9A%84%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/UpX=tFx
- 学校体育活动的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%8D%95%E6%9C%9F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/033
- 乡村公共文化的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%8D%95%E6%9C%9F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/hyu
- 骑行路线规划的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%8D%95%E6%9C%9F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/O9n
- 公共服务评价的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%8D%95%E6%9C%9F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/935=rlf
- 公共设施维护的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%8D%95%E6%9C%9F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/exj=376
- 社区艺术活动的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_3%E5%88%86%E5%BF%AB3%E5%8D%95%E6%9C%9F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/7Us=ud0
- 城乡交流活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/714
- 街区更新实践的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/smm
- 数字公共文化的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/Mrw
- 家庭节能实践的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/430=yok
- 无障碍出行的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/eqa=889
- 节日文化体验的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_welcome%E5%A4%A7%E5%8F%91%E5%BF%AB3%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%9C%9F%E8%B4%A7?/9fs=gXs
- 节约用水实践的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8iii_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/322
- 青少年编程学习的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8iii_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/pqa
- 数字设备回收的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8iii_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/3XT
- 社区体育组织的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8iii_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/812=gog
- 数字生活课堂的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8iii_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/div=531
- 校园阅读活动的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8iii_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/I4C=h4I
- 生活服务数字化的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%9C%E6%96%B9%E9%98%BF%E5%AE%9D%E4%BB%8A%E6%99%9A%E7%8B%AC%E8%83%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/169
- 城市绿道建设的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%9C%E6%96%B9%E9%98%BF%E5%AE%9D%E4%BB%8A%E6%99%9A%E7%8B%AC%E8%83%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/rmv
- 城市慢跑路线的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%9C%E6%96%B9%E9%98%BF%E5%AE%9D%E4%BB%8A%E6%99%9A%E7%8B%AC%E8%83%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/aNa
- 小区电梯维护的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%9C%E6%96%B9%E9%98%BF%E5%AE%9D%E4%BB%8A%E6%99%9A%E7%8B%AC%E8%83%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/908=suw
- 科学信息获取的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%9C%E6%96%B9%E9%98%BF%E5%AE%9D%E4%BB%8A%E6%99%9A%E7%8B%AC%E8%83%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/rvf=561
- 生活垃圾回收的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%9C%E6%96%B9%E9%98%BF%E5%AE%9D%E4%BB%8A%E6%99%9A%E7%8B%AC%E8%83%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/ns5=GOJ

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
