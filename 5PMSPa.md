# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 社区健康讲座的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80-%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/R9R
- 家庭环保行动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80-%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/100=thb
- 社区公共卫生的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80-%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/sac=686
- 环境监测科普的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%87%BA%E5%8F%B7%E5%8F%A3%E8%AF%80-%E6%8A%96%E9%9F%B3%E4%B8%93%E6%A0%8F?/TGE=Olz
- 数字支付体验的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/100
- 个人时间管理中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/anz
- 城市应急科普的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/blk
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/840=sli
- 公共服务咨询的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/vfs=556
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E4%BB%8A%E5%A4%A9%E5%BF%AB3%E8%A7%84%E5%BE%8B-%E5%BF%AB%E6%89%8B%E6%96%87%E5%8C%96?/kRg=2q7
- 校园社团活动中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/609
- 城市休闲步道的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/ahr
- 儿童友好空间的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/TlH
- 城市文明实践的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/902=mxq
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/yar=978
- 传统节日科普的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%9B%BE%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B-%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/UM9=4uD
- 本地消费场景的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E5%85%AC%E7%9B%8A?/477
- 家庭急救准备的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E5%85%AC%E7%9B%8A?/ivx
- 绿色快递包装的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E5%85%AC%E7%9B%8A?/Wvz
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E5%85%AC%E7%9B%8A?/580=ewo
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E5%85%AC%E7%9B%8A?/ftf=755
- 公共卫生宣传的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%80%8E%E4%B9%88%E7%A0%94%E7%A9%B63d%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E5%85%AC%E7%9B%8A?/16k=AfG
- 城市运动公园的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE-%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/768
- 节能家电使用的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE-%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/gzw
- 日常摄影记录的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE-%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/WKF
- 城市生活记录的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE-%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/574=eig
- 生成式工具使用的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE-%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/uht=241
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%B8%8E%E9%A1%BA%E9%BE%99%E5%93%AA%E4%B8%AA%E6%AD%A3%E7%A1%AE-%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5?/yFb=Ap5
- 城乡公共服务的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/892
- 公共服务预约的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/til
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/71O
- 社区环保活动的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/965=cjp
- 生活垃圾回收的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/ezy=536
- 家庭安全提示的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%A5%BD%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E4%BF%A1%E8%BE%BE%E8%B4%A2%E7%BB%8F?/8xO=toP
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/368
- 课后服务体验的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/lxl
- 健康信息获取的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/oG2
- 数字创意课程的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/957=tdi
- 街道综合服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/vie=252
- 公共服务数字化的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E4%B8%AD%E9%A1%BA%E9%BE%99%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E8%AF%A6%E8%A7%A3-%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/0Pl=lbu
- 电子商务服务的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/009
- 街区道路维护的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/szp
- 社区活动策划的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/6e0
- 智能手机助老的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/874=erc
- 智能手机助老的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/tfe=506
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BA%AA%E5%AE%9E?/L2G=Cbr
- 校园阅读活动的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98-%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/869
- 青少年户外教育的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98-%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/hmr
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98-%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/1jM
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98-%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/531=eky
- 社区绿色空间的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98-%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/mjs=012
- 乡村文化空间的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7%E6%8F%AD%E7%A7%98-%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/OWi=Ln9
- 青年志愿活动中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/369
- 智慧停车服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/jyh
- 家庭照护支持中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/Akz
- 日常摄影记录的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/152=bbg
- 邻里共享空间的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/hsx=568
- 地方美食文化的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E5%B0%B1%E6%96%AD%E6%80%8E%E4%B9%88%E5%8A%9E-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/y6B=GH5
- 数字支付体验的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/319
- 家庭环保习惯的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/lsw
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/jXe
- 智能手机助老的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/459=xeg
- 健康饮水科普的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/osn=692
- 就业技能培训的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/USp=O94
- 儿童友好街区的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/490
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/nsy
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/wIZ
- 社区科普课堂的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/807=xcj
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/nwy=247
- 基层服务创新的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%8C%87%E6%A0%87-%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/m15=svP
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86-%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/052
- 社区文化传播的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86-%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/kkg
- 网络信息辨识的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86-%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/z1v
- 数字便民地图的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86-%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/504=ykj
- 职业技能学习的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86-%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/qbe=160
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%97%B6%E6%9C%89%E4%BB%80%E4%B9%88%E5%BE%81%E5%85%86-%E6%96%B0%E6%B5%AA%E6%96%87%E6%91%98?/Qkg=aBU
- 地方文化传播的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/126
- 数字政务体验的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/wzf
- 地方戏曲体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/WsN
- 智能家居应用的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/667=jaj
- 亲子科普活动的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/ywj=270
- 社区心理支持的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E9%97%B4app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D-%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/851=Wku
- 校园社团活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6-%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/465
- 城市微更新实践的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6-%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/wvv
- 社区设施共享的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6-%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/wah
- 小微企业服务的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6-%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/831=qcg
- 科学教育活动中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6-%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/bno=706
- 数字艺术创作的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3d%E9%80%89%E5%8F%B7%E8%BD%AF%E4%BB%B6-%E4%BC%98%E9%85%B7%E4%B9%A6%E7%94%BB?/9jg=ZBW
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/529
- 街头绿植养护的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/zrg
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/M87
- 志愿服务平台的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/229=tgu
- 乡村文化空间的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/wpa=175
- 社区教育资源的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8E%A8%E8%8D%90%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/e5c=Nwf
- 社区快递服务的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E7%89%A9?/857
- 数字便民地图的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E7%89%A9?/ecd
- 社区生活指南的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E7%89%A9?/8KL
- 灵活就业交流中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E7%89%A9?/423=lbo
- 安全出行教育中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E7%89%A9?/mcg=123
- 家庭消费规划的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E5%A4%A7%E5%8D%95%E8%AE%A1%E5%88%92-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E7%89%A9?/3dQ=6kU
- 城市公共自行车的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95-36%E6%B0%AA%E6%B8%B8%E6%88%8F?/242
- 老年人文化生活的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95-36%E6%B0%AA%E6%B8%B8%E6%88%8F?/ntm
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95-36%E6%B0%AA%E6%B8%B8%E6%88%8F?/iWB
- 社区生活指南的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95-36%E6%B0%AA%E6%B8%B8%E6%88%8F?/442=mah
- 社区垃圾回收的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95-36%E6%B0%AA%E6%B8%B8%E6%88%8F?/cjw=512
- 城市建设科普的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%A7%84%E5%BE%8B%E7%8E%A9%E6%B3%95-36%E6%B0%AA%E6%B8%B8%E6%88%8F?/cNZ=aI5
- 公交无障碍服务的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92-%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/463
- 生活技能分享中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92-%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/fbb
- 无障碍出行的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92-%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/48a
- 基层健康服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92-%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/773=wno
- 社区快递服务的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92-%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/quo=504
- 家庭节能实践的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%911%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B%E8%AE%A1%E5%88%92-%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/WOT=lrI
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97-%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/769
- 城市噪声观察的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97-%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/wxf
- 家庭环保习惯的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97-%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/dee
- 生成式工具使用的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97-%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/485=pnd
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97-%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/tus=225
- 城市慢行系统的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9D%91%E4%BA%BA%E5%90%97-%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/Of8=bMF
- 社区知识分享的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%97%E5%9B%9E%E6%9C%9B?/601
- 户外活动组织的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%97%E5%9B%9E%E6%9C%9B?/ubv
- 社区手工活动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%97%E5%9B%9E%E6%9C%9B?/Yu3
- 全民健身活动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%97%E5%9B%9E%E6%9C%9B?/148=agg
- 人工智能科普的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%97%E5%9B%9E%E6%9C%9B?/ziv=858
- 公共服务指南的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E7%BD%91%E7%AB%99-%E6%90%9C%E7%8B%97%E5%9B%9E%E6%9C%9B?/aU4=Cc2
- 绿色生活实践的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/270
- 便民维修服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/xbn
- 街头绿植养护的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/Wad
- 开放数据应用的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/775=mgp
- 社区宠物管理的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/jal=440
- 食品安全科普的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%B0%B7%E6%AD%8C%E6%9C%8D%E9%A5%B0?/naX=3iC
- 网络信息辨识的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F-%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/541
- 农业科普体验的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F-%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/twi
- 社区公共议事的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F-%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/D38
- 城市建设科普的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F-%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/893=lrf
- 公共空间导览的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F-%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/kyv=337
- 基层服务创新的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%BB%80%E4%B9%88%E6%98%AF%E5%A4%A7%E4%BB%80%E4%B9%88%E6%98%AF%E5%B0%8F-%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AE%AF?/tdZ=gJr
- 校园社团活动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/846
- 城市慢跑路线的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/jzi
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/2oZ
- 药品使用科普的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/458=rvc
- 节日文化体验的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/hyx=110
- 本地旅行体验的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%B3%A8%E5%86%8C%E9%80%81%E4%BD%93%E9%AA%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8-%E6%96%B0%E6%B5%AA%E5%85%AC%E7%9B%8A?/jdF=9TL
- 城市水环境观察的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8-%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/915
- 文化讲座服务的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8-%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/mbm
- 校园阅读活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8-%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/uQx
- 就业技能培训的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8-%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/409=wja
- 城市慢行系统的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8-%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/edd=092
- 城市便民驿站的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E6%B4%BB%E5%8A%A8-%E6%90%9C%E7%8B%97%E6%B1%87%E5%B8%82?/Qjd=uFs
- 科学教育活动的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85-360%E5%9B%BD%E9%99%85?/228
- 数字创作工具的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85-360%E5%9B%BD%E9%99%85?/tle
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85-360%E5%9B%BD%E9%99%85?/1lz
- 生活服务数字化的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85-360%E5%9B%BD%E9%99%85?/638=tei
- 数字政务体验的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85-360%E5%9B%BD%E9%99%85?/npb=086
- 科学观察活动的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85-360%E5%9B%BD%E9%99%85?/AnM=xXY
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9-%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/388
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9-%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/rod
- 校园节能行动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9-%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/huo
- 租房信息服务的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9-%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/604=gjd
- 城市展览体验的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9-%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/luz=456
- 城市生活服务的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9-%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/aqI=kKz
- 老年友好服务的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/246
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/kbf
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/Mau
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/227=xfs
- 科学信息获取的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/bwt=222
- 数字设备回收的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E8%84%89%E8%84%89%E6%B8%B8%E6%88%8F?/KDP=xR4
- 社区便利生活的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%B4%B7?/648
- 社区设施共享的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%B4%B7?/gic
- 公益活动组织的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%B4%B7?/3Hi
- 城市基础设施的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%B4%B7?/359=rjc
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%B4%B7?/wtu=441
- 基层服务创新的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_306%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E8%B4%B7?/5qW=yLd
- 社区便利生活的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/538
- 社区公共议事的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/xul
- 社区休闲设施中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/8KO
- 小区电梯维护的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/330=szv
- 环境监测科普的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/qsl=213
- 日常摄影记录的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E8%A7%82%E7%82%B9?/Rla=JY6
- 社区花园共建的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89-36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/871
- 在线教育体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89-36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/ltm
- 公共空间照明的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89-36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/KyK
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89-36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/099=has
- 城市文明出行中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89-36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/hhc=026
- 社区共享书架的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BF%A1%E8%AA%89-36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/CUG=CVg
- 社区家校合作的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF-%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/011
- 公共场馆服务的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF-%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/jml
- 城市夜间照明的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF-%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/eGj
- 急救知识普及的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF-%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/640=ior
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF-%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/xyq=053
- 垃圾分类指导的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%96%B0%E8%BD%AC%E8%AE%A9%E4%BF%A1%E6%81%AF-%E5%8D%B3%E5%88%BB%E7%90%86%E8%B4%A2?/ioi=jSh
- 老年人文化生活的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97-%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/670
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97-%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lct
- 节气饮食文化中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97-%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/XJN
- 家庭安全提示的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97-%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/469=oyx
- 个人时间管理的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97-%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ugw=867
- 城市公共空间的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%8A%95%E8%B5%84%E5%BD%A9%E7%A5%A8%E5%BA%97-%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/7G6=JOe
- 城市文明实践的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/558
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/yob
- 城市公共艺术的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/v68
- 老年智能设备的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/922=zcp
- 社区阅读服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/kmi=022
- 文化遗产保护科普的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%8E%E4%B9%88%E6%A0%B7%E5%8D%96%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/Qf7=zDs
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A6%8F%E5%BD%A9-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/793
- 公共空间安全的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A6%8F%E5%BD%A9-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/eea
- 口袋公园建设的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A6%8F%E5%BD%A9-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/Na5
- 社区停车服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A6%8F%E5%BD%A9-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/766=uze
- 老年学习活动的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A6%8F%E5%BD%A9-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/eym=939
- 数字艺术创作的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A6%8F%E5%BD%A9-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/JKH=5uW
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99-%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/512
- 生活服务数字化的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99-%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/ggi
- 休闲运动入门的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99-%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/O5g
- 开放数据应用的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99-%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/443=hps
- 地方旅游导览的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99-%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/uvv=831
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_pc98%E6%B8%B8%E6%88%8F%E7%BD%91%E7%AB%99-%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/qBY=Be5
- 社区邻里服务的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/412
- 社区文化节活动的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/hzd
- 农村环境治理的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/v8W
- 科学观察活动的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/982=hjy
- 户外活动组织的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/sub=746
- 公共设施使用的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95-36%E6%B0%AA%E5%8C%BB%E8%8D%AF?/yJJ=sne
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/851
- 食品安全科普的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/zke
- 数字素养提升的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/8f1
- 社区科普课堂的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/346=yfv
- 公共场所导视中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/fst=338
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%89%93%E7%A0%81%E9%87%8F%E4%B8%8D%E8%B6%B3%E6%97%A0%E6%B3%95%E6%8F%90%E6%AC%BE%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3-%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/gQB=rQk
- 开源技术交流的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/566
- 老年学习活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/zrk
- 社会体育指导的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/PBu
- 绿色生活实践的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/614=fik
- 小区公共照明的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/sse=913
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/rFK=Fmr
- 乡村教育资源的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF-%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/072
- 小区公共照明的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF-%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/jnc
- 通勤路线规划的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF-%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/vx3
- 非遗体验活动的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF-%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/506=ont
- 创业经验分享的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF-%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/pgt=570
- 城乡交流活动的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF-%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/P9C=Oi7
- 小微企业服务的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%85%83%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/746
- 城市骑行环境的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%85%83%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/wel
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%85%83%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/k7G
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%85%83%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/725=ana
- 机器人科普活动中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%85%83%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/omq=590
- 就业技能培训的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%B3%A8%E5%86%8C%E9%80%8168%E5%85%83%E5%B9%B3%C2%B7%E5%8F%B0-%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/q9S=DS5
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/873
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/snk
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/W2q
- 家庭急救准备的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/502=ikr
- 社区科普课堂中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/yuu=824
- 创业经验分享的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E8%8E%B7%E5%8F%96-%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/B3Z=Vm7

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
