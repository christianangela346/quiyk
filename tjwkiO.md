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

- 乡村阅读活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/814
- 家庭环保行动的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/xla
- 城市建设科普的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/UOM
- 城市应急科普的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/978=xeu
- 青少年编程学习的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/vpn=545
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96-%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/AuJ=M49
- 街头绿植养护的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D-%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/939
- 儿童友好空间的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D-%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/fss
- 数字支付体验的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D-%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/P0s
- 家庭阅读计划的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D-%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/851=rru
- 通勤路线规划的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D-%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/trh=151
- 节约用水实践的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D-%E5%87%A4%E5%87%B0%E7%BB%BC%E8%89%BA?/BDT=gam
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/850
- 校园社团活动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/tjv
- 社区安全巡查的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/no5
- 家庭环保习惯的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/530=fjn
- 生活垃圾回收的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/ddg=414
- 个人时间管理的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E6%B3%95%E5%BE%8B?/2xI=b0Z
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/465
- 消防知识宣传的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/yiw
- 老年友好服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/GmR
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/844=zhc
- 社区运动空间的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/wgv=476
- 线上阅读资源的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/spA=nRF
- 社区便民集市的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/665
- 数字学习资源的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/zxf
- 市民热线服务的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/LCj
- 社区活动报名的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/684=nyw
- 邻里共享空间的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/rxa=779
- 家庭环保行动的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/fuj=eyW
- 老旧小区改造的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/747
- 小区公共照明的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/qbf
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/byC
- 社区老年食堂的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/681=cqc
- 校园节能行动的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/zwe=296
- 节假日出行安排的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91-%E5%8D%B3%E5%88%BB%E6%85%A7%E7%9C%BC?/ijz=Wrg
- 家庭安全提示的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/738
- 青年职业探索的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/eir
- 公园休闲体验的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/49Y
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/792=jll
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/nqf=480
- 户外活动组织的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92-%E5%BF%AB%E6%89%8B%E5%9C%B0%E4%BA%A7?/zVt=P8V
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2-%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/399
- 社区共享书架的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2-%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/faz
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2-%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/1YR
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2-%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/164=rhz
- 城市公共自行车的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2-%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/fxl=098
- 城市人文观察的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2-%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/E5I=9Qg
- 数字公共文化中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/270
- 社区应急准备的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/ldp
- 社区信息发布的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/ffK
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/324=gdi
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/kpn=471
- 文化讲座服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA-%E8%84%89%E8%84%89%E7%A4%BE%E8%AE%BA?/qL7=6dn
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%89%8B%E8%AE%B0?/108
- 线上办事服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%89%8B%E8%AE%B0?/eya
- 社区生活指南的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%89%8B%E8%AE%B0?/P1h
- 创业经验分享的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%89%8B%E8%AE%B0?/421=azz
- 老年数字阅读的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%89%8B%E8%AE%B0?/hpb=116
- 节假日出行安排的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%89%8B%E8%AE%B0?/HQI=YDj
- 社区应急准备的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82-%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/770
- 城市噪声观察的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82-%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/ell
- 全民健身活动的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82-%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/jDa
- 图书借阅体验的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82-%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/558=cwd
- 社区家校合作的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82-%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/wxi=661
- 课后服务体验的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82-%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/XGD=tVI
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/120
- 社区应急准备的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/wqu
- 数字便民地图的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/5MZ
- 城市便民驿站中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/080=fdy
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/koi=862
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9C%88%E5%AD%90?/NU2=kaA
- 社区安全巡查的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/014
- 老年人日常照护的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/ton
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/Sjw
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/880=ixa
- 社区科普课堂的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/mht=508
- 老年人文化生活的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E6%96%B0%E6%B5%AA%E8%A7%A3%E5%AF%86?/YcM=gZB
- 亲子科普活动的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93-%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/815
- 乡村文化活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93-%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/chf
- 社区便利生活的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93-%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/piG
- 社区宠物管理的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93-%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/147=ark
- 青年志愿活动的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93-%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/biy=783
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93-%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/HDE=0Ho
- 公共健身器材的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/403
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/fst
- 居民健康教育的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/IwA
- 社区心理支持的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/112=lxg
- 社区养老服务的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/uvq=880
- 社区协商议事的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/VfC=DK8
- 社区环保活动的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/596
- 非遗体验活动的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/opk
- 城市生活记录的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/P9L
- 社区活动报名的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/263=cha
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/wzv=082
- 街道综合服务的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/nbS=hou
- 节日文化体验中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B-%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/175
- 科技馆参观体验的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B-%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/vzd
- 城市文明实践的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B-%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/Ow1
- 数据分析入门中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B-%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/762=abt
- 城市展览体验的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B-%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/hdc=203
- 家庭园艺实践的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B-%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%9C%9B?/gIA=2lP
- 城市农夫市集的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90-360%E8%AF%BB%E4%B9%A6?/082
- 绿色生活实践的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90-360%E8%AF%BB%E4%B9%A6?/pox
- 开源技术交流的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90-360%E8%AF%BB%E4%B9%A6?/DM4
- 公共服务沟通的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90-360%E8%AF%BB%E4%B9%A6?/422=amd
- 科学观察活动的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90-360%E8%AF%BB%E4%B9%A6?/rkq=879
- 社区故事采集的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90-360%E8%AF%BB%E4%B9%A6?/YDR=Iz9
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/235
- 家庭用电安全的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/kqw
- 食品配送体验的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/unt
- 社区休闲设施的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/271=sfn
- 城市体育设施的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/qfa=916
- 学校食育活动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/RFk=Wds
- 城市运动公园的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/399
- 城市应急广播的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/ozk
- 城市文明出行的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/vlG
- 绿色出行服务的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/535=awn
- 社区邻里服务的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/wta=703
- 社区托育服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%9D%E9%99%A9?/EAk=ArR
- 老年人出行服务的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/797
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/eje
- 校园节能行动的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/VMv
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/552=xur
- 家庭环保行动的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/xgm=311
- 社区生活指南的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/L4r=a96
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010-360%E5%8A%A8%E6%BC%AB?/368
- 儿童户外活动的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010-360%E5%8A%A8%E6%BC%AB?/elt
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010-360%E5%8A%A8%E6%BC%AB?/eLb
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010-360%E5%8A%A8%E6%BC%AB?/628=gdv
- 数字档案服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010-360%E5%8A%A8%E6%BC%AB?/yxx=917
- 校园节能行动的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010-360%E5%8A%A8%E6%BC%AB?/f8h=nyM
- 开源技术交流的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD-%E9%A1%BA%E4%B8%B0%E4%BC%97%E6%B5%8B?/994
- 社区快递服务的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD-%E9%A1%BA%E4%B8%B0%E4%BC%97%E6%B5%8B?/ivk
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD-%E9%A1%BA%E4%B8%B0%E4%BC%97%E6%B5%8B?/vKP
- 老年智能设备的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD-%E9%A1%BA%E4%B8%B0%E4%BC%97%E6%B5%8B?/563=bdr
- 社区手工活动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD-%E9%A1%BA%E4%B8%B0%E4%BC%97%E6%B5%8B?/ueu=791
- 社区安全巡查的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD-%E9%A1%BA%E4%B8%B0%E4%BC%97%E6%B5%8B?/Jzo=VLi
- 数字阅读服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/011
- 地方旅游导览的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/xif
- 青少年职业启蒙的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/cPv
- 网络安全教育的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/216=uwl
- 安全出行教育的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/jpa=725
- 市民意见收集的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Fa9=B4O
- 乡村公共文化中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2_-%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/677
- 终身学习资源的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2_-%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/vem
- 家庭用电安全的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2_-%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/xk5
- 智慧停车服务的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2_-%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/583=qzu
- 城市文明实践的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2_-%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/iar=422
- 儿童友好空间的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%AE%98%E7%BD%91168%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E4%B8%80%E5%8E%86%E5%8F%B2_-%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/41U=N3v
- 便民信息查询中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/420
- 城市步行环境的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/whq
- 居民健康教育的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/EFe
- 青少年科技社团的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/475=kcf
- 开源技术交流的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/nhi=926
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E7%9A%84%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E7%A8%8E%E5%8A%A1?/frD=hQD
- 居民健康教育的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97_-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/122
- 读书会组织的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97_-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/vtr
- 全民阅读推广的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97_-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/EuL
- 家庭环保习惯的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97_-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/186=fpg
- 老年友好服务的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97_-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/xtn=079
- 公共卫生设施的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%9C%89%E5%9B%BA%E5%AE%9A%E8%A7%84%E5%BE%8B%E5%90%97_-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/LQT=XDE
- 农贸市场环境的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80-%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/388
- 城市应急广播的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80-%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/sbw
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80-%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/zxB
- 农贸市场环境的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80-%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/947=fvb
- 绿色快递包装的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80-%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/ivp=282
- 生成式工具使用的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E4%BC%9A%E4%B8%8D%E4%BC%9A%E8%A2%AB%E7%82%B9%E6%9D%80-%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/uzU=Zcf
- 城乡公共服务的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2-%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/132
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2-%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/arj
- 社区快递服务的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2-%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/7T9
- 乡村公共服务的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2-%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/810=pce
- 社区邻里服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2-%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/era=687
- 农产品消费体验的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%91%A2-%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/0u9=8B9
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F-%E5%8D%B3%E5%88%BB?/386
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F-%E5%8D%B3%E5%88%BB?/wvp
- 人工智能科普的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F-%E5%8D%B3%E5%88%BB?/cP0
- 街区更新实践的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F-%E5%8D%B3%E5%88%BB?/970=uzk
- 家庭理财科普的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F-%E5%8D%B3%E5%88%BB?/plj=188
- 户外活动组织的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%87%A0%E7%82%B9%E5%BC%80%E5%A7%8B%E5%87%A0%E7%82%B9%E7%BB%93%E6%9D%9F-%E5%8D%B3%E5%88%BB?/fvn=Ckg
- 公共设施维护的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/498
- 社区宣传栏更新的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/qbw
- 城市地名文化的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/LrD
- 数字创作工具的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/356=kbe
- 家庭用电安全的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/mje=679
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_168%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91-%E9%A1%BA%E4%B8%B0%E7%89%B9%E7%A8%BF?/k7U=7eg
- 数字政务体验的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_PC28-%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/558
- 小区停车协商的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_PC28-%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/lso
- 家庭健康管理的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_PC28-%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/sJI
- 开放数据应用的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_PC28-%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/214=prm
- 家庭园艺实践的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_PC28-%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/vgq=573
- 无障碍出行的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_PC28-%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/4Bg=3C4
- 家庭节能实践中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/558
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/byt
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/QzB
- 社区体育组织的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/688=tuu
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/wnh=154
- 公共场所导视的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E7%AE%97%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%97%B6%E6%8A%A5?/VcW=Y5M
- 社区家校合作的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org-%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/039
- 数字创意课程中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org-%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/pnb
- 街区道路维护的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org-%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/D7m
- 居民健康教育的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org-%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/111=czg
- 安全出行教育的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org-%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/abu=013
- 科学观察活动中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955-org-%E8%99%8E%E6%89%91%E8%AE%B2%E5%9D%9B?/ZYh=9Wy
- 校园节能行动的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc2805-%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/666
- 公交站点体验的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc2805-%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/cty
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc2805-%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/0St
- 智慧城市体验的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc2805-%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/197=fwk
- 非遗体验活动的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc2805-%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/ovg=446
- 家庭饮食安排的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_pc2805-%E8%8A%92%E6%9E%9C%E5%B9%B6%E8%B4%AD?/1ZY=PPb
- 社区设施共享的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91-%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/756
- 老年智能设备的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91-%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/lvs
- 光伏知识科普的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91-%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/ZYw
- 社区应急准备的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91-%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/386=fbr
- 乡村生态旅游的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91-%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/kty=883
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_pc28%E6%9C%80%E6%96%B0%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91-%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/JFG=2qj
- 家庭用电安全的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF-%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/612
- 街区更新实践的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF-%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/jbs
- 城市公共厕所的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF-%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/xHr
- 机器学习入门的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF-%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/907=guv
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF-%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/tvg=422
- 社区便民集市的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%80%8E%E4%B9%88%E7%9C%8B%E8%B5%B0%E5%8A%BF-%E8%B1%86%E7%93%A3%E5%91%A8%E6%8A%A5?/Zbe=let
- 安全出行教育的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/658
- 家庭科学教育的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/msg
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/o4o
- 节约用水实践的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/151=cre
- 儿童安全出行的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/sxq=538
- 社区体育组织的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_pc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/u7l=pPg
- 社区交通安全的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95-%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/347
- 老年数字阅读的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95-%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/uyd
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95-%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/9gE
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95-%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/952=fzr
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95-%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/hcn=621
- 城市公共饮水的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_pc28%E5%BC%80%E5%A5%96500%E6%9C%9F%E8%AE%B0%E5%BD%95-%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/dxC=qOo
- 绿色生活实践的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/951
- 社区便民集市的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/kcz
- 无障碍出行的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/myX
- 公共服务咨询的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/043=atz
- 城市公共空间的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/pit=427
- 城市公共厕所的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_pc28%E9%A2%84%E6%B5%8B%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/oYJ=9Xa
- 邻里共享空间的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/198
- 数字档案服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/dbo
- 图书馆数字服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/wLw
- 开源技术交流的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/196=zkk
- 光伏知识科普的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/qmh=050
- 地方美食文化的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E6%89%8B%E5%8A%A8%E5%BD%95%E5%85%A5a955org-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/3It=zkk
- 社区消防演练的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/041
- 公共设施维护的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/szr
- 公共空间休憩的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/Nqu
- 物业服务沟通中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B-%E5%A4%B4%E6%9D%A1%E8%AF%BB%E5%9B%BE?/636=kto

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
