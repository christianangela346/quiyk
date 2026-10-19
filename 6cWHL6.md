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

- 家庭照护支持的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%91%8A?/ixn=298
- 户外活动组织的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%91%8A?/1Np=HEq
- 家庭园艺实践的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/022
- 城市住房服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/tiw
- 城市应急科普的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/YUZ
- 基层服务创新的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/586=iok
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/wim=096
- 创业经验分享的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/KmE=SE7
- 家庭食品保存的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/643
- 社区艺术活动的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/weo
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/Yrn
- 社区科普课堂的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/689=mzf
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/ppz=128
- 城市公共标识的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C_%E4%BA%AC%E4%B8%9C%E8%AF%84%E8%AE%BA?/KqZ=o2c
- 创业经验分享的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A62025%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/491
- 居民健康教育的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A62025%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/bmt
- 市民热线服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A62025%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/PVD
- 网络信息辨识的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A62025%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/639=feh
- 数字阅读服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A62025%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/eef=476
- 本地历史资料的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A62025%E6%89%93%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/qSw=duK
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/657
- 在线学习体验的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/mru
- 城市文化路线中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/1zM
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/549=ail
- 数字设备回收的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/vga=430
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6?/2EE=qAv
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/866
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/rkk
- 街道综合服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/p7L
- 乡村公共服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/938=yxn
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/lna=851
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E5%8D%B3%E5%88%BB%E5%85%9A%E5%BB%BA?/VBL=ujV
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/389
- 街区更新实践的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/nka
- 数字阅读服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/J1u
- 个人时间管理的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/546=dqh
- 健康步道使用的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/aso=319
- 社区公共卫生的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/zKw=oLe
- 社区体育组织的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/653
- 校园节能行动的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/czo
- 社区信息发布中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/AM7
- 家庭理财科普的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/338=xqq
- 校园节能行动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/vyv=199
- 在线教育体验的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%AA%97%E5%B1%80_%E5%93%94%E5%93%A9%E6%9B%B2%E8%89%BA?/i0G=UO3
- 公益活动组织的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/908
- 儿童运动体验的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/xfm
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/1zG
- 传统手工艺体验的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/158=pnq
- 城市夜间生活的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/qxz=777
- 公园亲子设施的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/OYM=jRP
- 科学教育活动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E4%BD%93%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/465
- 家庭消费规划的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E4%BD%93%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/cka
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E4%BD%93%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/1OA
- 农业科普体验的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E4%BD%93%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/383=zke
- 儿童安全出行的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E4%BD%93%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/uuk=484
- 社区便利生活的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E4%BD%93%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8A%A1?/ST4=JU5
- 社区教育资源的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91._%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/632
- 传统手工艺体验的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91._%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/jme
- 老年智能设备的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91._%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/VlW
- 家庭用电安全的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91._%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/251=cgl
- 社区托育服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91._%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/tnj=104
- 食品安全科普的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91._%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/lLq=K4H
- 家庭理财科普的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/452
- 社区家校合作的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/iqk
- 节能生活方式的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/RYd
- 城市应急科普的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/650=egg
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/obs=946
- 城市生活记录的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E7%BD%91%E5%9D%80_%E8%99%8E%E5%97%85%E5%9B%9E%E6%9C%9B?/9a6=K14
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/363
- 食品配送体验的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/dcy
- 绿色生活实践的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/Q72
- 城市地名文化的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/180=dab
- 社区休闲设施的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/ydi=007
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%91%8A?/3w7=3E4
- 乡村教育资源的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_2026%E6%96%B0%E8%B5%9B%E8%BD%A6%E6%9E%81%E9%80%9F%E8%B5%9B%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/037
- 社区家校合作的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_2026%E6%96%B0%E8%B5%9B%E8%BD%A6%E6%9E%81%E9%80%9F%E8%B5%9B%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/pno
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_2026%E6%96%B0%E8%B5%9B%E8%BD%A6%E6%9E%81%E9%80%9F%E8%B5%9B%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/Pds
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_2026%E6%96%B0%E8%B5%9B%E8%BD%A6%E6%9E%81%E9%80%9F%E8%B5%9B%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/458=ple
- 智能手机助老的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_2026%E6%96%B0%E8%B5%9B%E8%BD%A6%E6%9E%81%E9%80%9F%E8%B5%9B%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/lxw=912
- 科学教育活动的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_2026%E6%96%B0%E8%B5%9B%E8%BD%A6%E6%9E%81%E9%80%9F%E8%B5%9B%E6%9E%9C%E6%9F%A5%E8%AF%A2%E5%AE%98%E7%BD%91_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/0gz=Lz0
- 家庭安全提示的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/214
- 文化场馆预约的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/uya
- 公共卫生宣传的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/cDp
- 城市可持续生活的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/939=ozy
- 食品安全科普的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/eai=132
- 校园阅读活动的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/2te=hcD
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/414
- 社区消防演练的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/bqp
- 城市应急广播的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/ZVe
- 社区运动空间的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/737=jnz
- 环境教育课程的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/xtr=538
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87_%E5%A4%AE%E8%A7%86%E6%95%B0%E8%AF%BB?/itm=d3o
- 城市运动公园的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/054
- 亲子科普活动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/fgn
- 邻里互助活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/0XR
- 药品使用科普的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/210=pgc
- 城市适老服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/sqq=374
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/8qo=CTp
- 线上阅读资源的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/307
- 通勤路线规划的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/sit
- 科普展览体验的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/Mqp
- 数字阅读服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/822=hpk
- 电子商务服务的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/hgv=946
- 城市公共标识的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E6%9F%A5%E8%AF%A2_%E5%87%A4%E5%87%B0%E6%99%A8%E6%8A%A5?/AUh=SWB
- 城市应急广播中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_360%E7%95%85%E6%B8%B8?/461
- 基层健康档案的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_360%E7%95%85%E6%B8%B8?/mjj
- 家庭健康科普的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_360%E7%95%85%E6%B8%B8?/vfa
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_360%E7%95%85%E6%B8%B8?/587=tyn
- 老年友好服务的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_360%E7%95%85%E6%B8%B8?/vja=021
- 城市文明实践的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_360%E7%95%85%E6%B8%B8?/fFN=ICH
- 城市生活记录的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/390
- 日常摄影记录的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/tzb
- 生活垃圾减量的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/wx7
- 社区便民服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/047=uuh
- 数字设备回收的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/vsj=471
- 地方文化传播的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/fO7=dEr
- 垃圾分类指导的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/212
- 节能家电使用的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/tde
- 儿童安全出行的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/uDa
- 人工智能科普的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/006=uey
- 城市生活记录的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/sqv=747
- 终身学习资源的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/EnN=RWk
- 读书会组织的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/693
- 安全出行教育的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/wfl
- 家庭科学教育的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/cBg
- 公共场馆服务的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/293=imi
- 家庭环保习惯的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/oeh=487
- 日常摄影记录的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E6%96%B9%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/Dc9=iDQ
- 在线学习体验的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/935
- 节约用水实践的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/szj
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/m98
- 城市公共座椅的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/568=gvk
- 乡村电商实践的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/gie=513
- 老年学习活动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_168%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/LAq=9Qc
- 社区邻里服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/273
- 社区菜市场服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/onb
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/tUT
- 急救知识普及的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/236=fzn
- 乡村教育资源的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/qoh=091
- 社区邻里服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/W4u=V0U
- 通勤路线规划的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/468
- 社区共享书架的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/uaq
- 社区安全巡查的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/9ut
- 社区读书角建设的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/402=vtf
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/wst=920
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%B8%80%E5%88%86%E9%92%9F_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/L6h=9qL
- 公共空间照明的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/512
- 节约用水实践的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/dle
- 乡村阅读活动的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/qmH
- 个人时间管理的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/217=avd
- 农产品消费体验的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/khz=529
- 节能家电使用的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/BK6=wCO
- 科学运动指导的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/938
- 乡村文化活动的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/grj
- 城市应急科普的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/ySW
- 公共服务咨询的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/242=nop
- 个人时间管理的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/tva=815
- 校园阅读活动的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%9F%A5%E8%AF%A2%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/Evp=9eJ
- 骑行路线规划的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/686
- 老年运动活动的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/rcr
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/QP5
- 智能手机助老的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/691=atb
- 急救知识普及的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/aiq=348
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%A1%BA%E4%B8%B0%E8%AF%BB%E5%9B%BE?/1Ws=aSm
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/689
- 城市休闲步道的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/pfq
- 城市共享单车的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/mXu
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/863=joj
- 社区学习活动的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/xuu=862
- 青年职业探索的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_168%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E6%89%93%E8%B5%A2%E7%9A%84%E5%87%A0%E7%8E%87%E5%A4%A7_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/rcR=gJP
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/460
- 数据分析入门的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/uvj
- 社区志愿服务的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/DwB
- 运动安全知识的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/606=dmz
- 数字设备回收的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/tbl=530
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%A1%A3%E6%A1%88?/eYe=W2z
- 城市公共厕所的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/395
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/lxz
- 街区小店体验的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/ViE
- 社区安全巡查的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/523=cya
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/ouz=963
- 城市农夫市集的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_168%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%80%BA%E5%B8%82?/8uR=mtI
- 线上办事服务的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/775
- 智能家居应用的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/msl
- 口袋公园建设的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/7lB
- 科学观察活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/920=eky
- 社区协商议事的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/gvw=901
- 公共文化活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F168%E8%B5%9B%E8%BD%A6_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E4%B9%A6?/1H6=wPb
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/189
- 社区生活指南的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/ben
- 社区活动报名的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/9T7
- 社区健康讲座的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/957=myt
- 社区便利生活的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/djf=749
- 农产品消费体验的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/69n=P6c
- 人工智能科普的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/147
- 社区环保活动的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/cxe
- 公共场所导视的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/6q6
- 在线学习体验的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/379=kmm
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/gzh=674
- 药品使用科普的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_168%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/pr2=nxO
- 公共空间照明中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/919
- 公共服务预约的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/mtl
- 乡村生活观察的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/VkG
- 青年就业服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/980=urv
- 社区健康讲座的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/mcz=291
- 基层服务创新的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/PrM=ekx
- 农产品消费体验的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/551
- 家庭用电安全的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/iwe
- 光伏知识科普的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/xL3
- 家庭运动计划的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/552=rny
- 数字创作工具的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/ijq=433
- 城市住房服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E5%90%8C%E6%AD%A5_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/MOD=fZ0
- 便民维修服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/393
- 城市公共标识中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/ufw
- 家庭收纳实践的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/7ss
- 地方美食文化中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/028=tqc
- 家庭节能设备的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/ycr=131
- 社区公共卫生的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_168%E9%A3%9E%E8%89%87_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E8%82%A1?/VDI=Z9G
- 急救知识普及的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/456
- 文化讲座服务的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/dgd
- 城市公共厕所的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/uzp
- 街道综合服务的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/597=vdh
- 数据分析入门的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/tnq=677
- 街区小店体验的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E5%8E%86%E5%8F%B2_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/E1m=u4j
- 生活垃圾回收的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/530
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/pxo
- 应急物资管理的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/hhi
- 青少年职业启蒙的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/294=dtm
- 公共空间照明的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/xkq=384
- 科学健身方法的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_168%E9%A3%9E%E8%89%87%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E8%B0%B7%E6%AD%8C%E6%9C%9F%E8%B4%A7?/QEi=gIQ
- 社区绿色空间的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_360%E7%A7%91%E6%8A%80?/617
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_360%E7%A7%91%E6%8A%80?/lxa
- 公共空间照明的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_360%E7%A7%91%E6%8A%80?/IrK
- 社区信息发布的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_360%E7%A7%91%E6%8A%80?/206=tzq
- 数字学习资源的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_360%E7%A7%91%E6%8A%80?/xgg=873
- 光伏知识科普的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD_360%E7%A7%91%E6%8A%80?/WmW=hRJ
- 城市建设科普的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/759
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/idd
- 智慧停车服务的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/ZTJ
- 科技馆参观体验的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/007=cto
- 社区活动空间的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/gvw=044
- 数字支付体验的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_168%E9%A3%9E%E8%89%874%E7%A0%81%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/MNx=Htf
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/374
- 公共图书馆服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/brp
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/Pdx
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/282=sqs
- 乡村公共文化的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/tqb=396
- 社区家校合作中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5_%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/LhS=aQM
- 家庭节能设备的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%28%E7%99%BB%E5%BD%95%E9%93%BE%E6%8E%A5%29_%E8%99%8E%E5%97%85%E6%85%A7%E7%9C%BC?/976
- 社区活动策划的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_168%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91%28%E7%99%BB%E5%BD%95%E9%93%BE%E6%8E%A5%29_%E8%99%8E%E5%97%85%E6%85%A7%E7%9C%BC?/loi

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
