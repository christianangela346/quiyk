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

- 社区家校合作中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%90%E4%BA%B2%E5%AD%90?/apc=512
- 家庭环保习惯的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E6%90%9C%E7%8B%90%E4%BA%B2%E5%AD%90?/gNO=5M1
- 居家防滑改造中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/180
- 城市农夫市集的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/lhe
- 绿色出行服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/6AR
- 课后服务体验的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/881=frx
- 数字学习资源的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/veo=841
- 环境教育课程的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E4%BB%A3%E6%89%93%E5%BD%A9%E7%A5%A8%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0-%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/kdx=e70
- 基层服务创新的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/443
- 公交无障碍服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/ulc
- 志愿服务平台的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/nRY
- 数字档案服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/664=yhp
- 青少年户外教育的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/pug=300
- 家庭急救准备的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/P4C=FsE
- 社区志愿服务的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/449
- 健康饮水科普的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/byi
- 农产品消费体验的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/wia
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/994=nkt
- 城市适老服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/lql=576
- 便民维修服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E5%81%9A%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/ReV=rAh
- 社区消防演练的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/784
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/tje
- 线上办事服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/7WZ
- 社区文化传播的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/669=mhk
- 文化场馆预约的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/dpt=502
- 农业科普体验的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E9%A3%9F%E5%93%81?/LY6=F1U
- 社区托育服务的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/509
- 社区家校合作的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/ziy
- 城乡交流活动的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/To0
- 亲子科普活动的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/027=jta
- 消防知识宣传的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/lai=788
- 社区健康讲座的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%9A%E5%BD%A9%E8%81%94%E7%9B%9F%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E6%97%B6%E5%B0%9A?/REs=3Va
- 社区艺术活动的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E6%94%BF%E5%8D%8F?/776
- 绿色消费选择的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E6%94%BF%E5%8D%8F?/jdl
- 社区故事采集的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E6%94%BF%E5%8D%8F?/E8g
- 乡村公共阅读的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E6%94%BF%E5%8D%8F?/859=chc
- 城市步行友好的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E6%94%BF%E5%8D%8F?/dej=385
- 新能源出行的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F-36%E6%B0%AA%E6%94%BF%E5%8D%8F?/YZI=0W3
- 邻里共享空间的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/256
- 乡村公共服务的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/egm
- 农产品品牌传播的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/ujc
- 就业技能培训的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/773=mvc
- 地方文化传播的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/okw=457
- 人工智能科普的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E4%BD%93%E5%BD%A9%E4%BD%A3%E9%87%91%E8%A1%A8%E4%B8%80%E8%A7%88%E8%A1%A8-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/tkk=8NZ
- 公园休闲体验中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6-%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/327
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6-%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/wgr
- 创业经验分享的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6-%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/XqK
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6-%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/378=sjc
- 家庭安全提示的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6-%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/goy=419
- 周末休闲规划的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BD%E5%AB%9619%E4%B8%AA36%E5%85%83%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6-%E8%B4%A2%E7%BB%8F%E9%A2%91%E9%81%93?/Qbh=4GK
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9-%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/594
- 便民信息查询中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9-%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/lxm
- 节能生活方式的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9-%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/s2e
- 休闲运动入门的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9-%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/796=iii
- 便民信息查询的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9-%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/mlh=878
- 亲子阅读活动的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%A6%82%E4%BD%95%E4%BB%A3%E7%90%86%E5%BD%A9%E7%A5%A8%E9%94%80%E5%94%AE%E7%82%B9-%E8%B4%A2%E7%BB%8F%E6%99%BA%E5%BA%93?/QJV=XEC
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80-%E4%BA%9A%E9%A9%AC%E9%80%8A?/408
- 个人数据管理的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80-%E4%BA%9A%E9%A9%AC%E9%80%8A?/tlh
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80-%E4%BA%9A%E9%A9%AC%E9%80%8A?/U53
- 乡村教育资源的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80-%E4%BA%9A%E9%A9%AC%E9%80%8A?/022=bcr
- 乡村文化空间的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80-%E4%BA%9A%E9%A9%AC%E9%80%8A?/tmb=006
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E7%A7%BB%E5%8A%A8%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E5%BC%80-%E4%BA%9A%E9%A9%AC%E9%80%8A?/8CQ=FtE
- 线上阅读资源的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/312
- 公共服务沟通的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/wqq
- 社区协商议事的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/JLI
- 街区道路维护的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/051=mtu
- 市民热线服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/xfe=728
- 社会体育指导的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E4%BD%A3%E9%87%91100%E5%85%BC%E8%81%8C%E7%BE%A4-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/Ybw=lNd
- 社区生活指南的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94-%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/768
- 无障碍出行的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94-%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/yuc
- 老年人日常照护的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94-%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/tXY
- 绿色消费选择的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94-%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/834=gzu
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94-%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/xsb=707
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8C%85%E8%B5%94-%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/YUN=fof
- 地方美食文化中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/112
- 健康步道使用的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/erp
- 城市应急广播的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/XcL
- 公交无障碍服务的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/613=enp
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/xul=041
- 公共空间照明的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/Hhg=GiX
- 公益活动组织的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8-%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/423
- 城市微更新实践的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8-%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/lrs
- 老年运动活动的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8-%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/FC5
- 家庭节能实践的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8-%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/963=oli
- 小区电梯维护的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8-%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/wvw=935
- 电动汽车充电的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8-%E7%9F%A5%E4%B9%8E%E6%8E%A2%E5%BA%97?/aMR=vTb
- 地方民俗记录的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/479
- 节气饮食文化的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/obj
- 公共图书馆服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/oGi
- 儿童阅读角的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/174=qqo
- 城市住房服务的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/uoo=671
- 城市运动公园的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%8F%B8%E6%B3%95?/bwX=XKD
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF-%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/713
- 职业技能学习中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF-%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/dmr
- 社区艺术活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF-%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/WCN
- 街区小店体验的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF-%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/542=ban
- 老年友好服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF-%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/len=459
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%9C%A8%E7%BA%BF-%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/yqI=3ef
- 绿色生活实践的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/389
- 社区老年食堂的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/mbs
- 个人信息保护中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/OKn
- 旧物循环利用的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/939=msp
- 城市人文观察的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/fuv=770
- 城市住房服务的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84%E7%BA%A2%E5%8C%85-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/rIl=XXn
- 社区公共卫生的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/472
- 城市基础设施的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/yxl
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/ojz
- 社区活动策划的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/127=kqn
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/ahk=254
- 社区文化节活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%88%8A%E7%99%BB?/GRt=Dhn
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/167
- 便民服务窗口的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/lmo
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/sZ6
- 健康饮食教育的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/246=zfj
- 公共文化活动的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/wzp=010
- 零废弃生活尝试的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%B6%E5%BD%A9%E8%AE%A1%E5%88%92-%E7%91%9E%E5%85%B8%E8%B4%A2%E7%BB%8F?/I6H=jjl
- 校园社团活动的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD-%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/953
- 社区手工活动的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD-%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/bnp
- 社区公共议事的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD-%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/QVl
- 家庭教育交流的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD-%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/487=fqn
- 绿色生活实践的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD-%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/bth=968
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD-%E6%90%9C%E7%8B%90%E7%88%86%E6%96%99?/igg=ZFy
- 在线学习体验的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/083
- 市民意见收集的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/edf
- 社区宠物管理的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/DIF
- 城市噪声观察的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/565=vdl
- 个人时间管理的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/cql=631
- 农业科普体验的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%94%90%E8%AF%84?/wia=Twe
- 乡村阅读活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6-%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/298
- 社区知识分享的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6-%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/ofb
- 数字学习资源的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6-%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/1ZY
- 城市公共饮水的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6-%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/777=iea
- 家庭健康科普的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6-%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/ibj=399
- 乡村生态观察的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6-%E5%BE%97%E7%89%A9%E5%BF%AB%E8%AE%AF?/iZJ=GbM
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/503
- 乡村产业科普的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/zzw
- 在线学习体验的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/IlK
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/195=qts
- 社区公共议事的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/jgq=746
- 绿色出行服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/eLn=GaD
- 城市生活服务的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/648
- 数字设备回收的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/mpt
- 校园节能行动的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/9AL
- 校园阅读活动的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/023=xky
- 数字设备回收的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/kpp=528
- 青少年科普实践的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/FB2=ysa
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/539
- 市民意见收集的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/bcs
- 社区运动空间的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/dHc
- 健康饮食教育的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/283=dxn
- 气象科普传播的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/acy=911
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF-%E5%8D%97%E9%9D%9E%E8%B4%A2%E7%BB%8F?/920=yUc
- 城市雨天出行的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/069
- 城市微更新实践中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/sqd
- 城市应急广播的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/gYA
- 城市夜间生活的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/958=dya
- 城乡交通衔接的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/nig=402
- 绿色快递包装的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E6%85%A7%E7%9C%BC?/pvf=BD5
- 城市文明出行的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/704
- 生活服务数字化中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/zay
- 光伏知识科普中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/cdR
- 便民服务窗口的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/809=jln
- 城市展览体验的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/spc=415
- 社区修缮行动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/U6l=OMc
- 机器学习入门的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/707
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/lfo
- 青年志愿活动的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/JbV
- 老年学习活动的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/588=goq
- 便民维修服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/foy=934
- 小区停车协商的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/rI4=7Xj
- 公共场所导视的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/784
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/wrj
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/ev8
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/462=leg
- 数字素养提升的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/cox=578
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7-%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/mGF=esE
- 公共交通接驳的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/893
- 数字艺术创作的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/ydy
- 网络安全教育的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/b6m
- 农业科普体验的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/086=lsm
- 乡村公共服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/xpr=757
- 社区绿色空间的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91-%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/ijZ=Umf
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/973
- 节能生活方式的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/ldf
- 城市生活服务的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/UHw
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/998=lyl
- 青少年科普实践的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/vyz=996
- 数字公共文化的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8B%E8%BD%BD-%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/OtK=gOJ
- 公共服务指南的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/139
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/tdp
- 数字档案服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/so9
- 图书借阅体验的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/443=luq
- 公共服务沟通的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/lyi=899
- 乡村电商实践的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E8%B5%9B%E8%BD%A6%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/77L=wfp
- 在线教育体验的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/229
- 就业技能培训中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/wkh
- 通勤路线规划的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/cAW
- 无障碍出行的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/358=pqi
- 科学教育活动的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/gai=567
- 全民健身活动的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E9%A3%9E%E8%89%87%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/DK4=JQc
- 社区协商议事的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/990
- 绿色快递包装的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/lzx
- 社区共享书架的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/nCO
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/027=qjl
- 公益活动组织的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/vjl=352
- 社区学习活动的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/XO8=Si6
- 家庭健康科普的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/103
- 家庭用电安全的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/uvf
- 乡村产业科普的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/TAT
- 城市雨天出行的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/658=ugy
- 城市微更新实践的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/tny=269
- 数字阅读服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%9028%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/vTJ=NMH
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/585
- 城市公共厕所的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/sqq
- 公共服务数字化的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/ppd
- 租房信息服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/372=qim
- 数据分析入门中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/apb=618
- 农村环境治理的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/T8f=qBF
- 城市应急科普的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95-36%E6%B0%AA%E9%A3%9F%E5%93%81?/834
- 公共设施维护的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95-36%E6%B0%AA%E9%A3%9F%E5%93%81?/pfs
- 公共设施使用的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95-36%E6%B0%AA%E9%A3%9F%E5%93%81?/PdL
- 城市文明出行的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95-36%E6%B0%AA%E9%A3%9F%E5%93%81?/474=ymn
- 校园社团活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95-36%E6%B0%AA%E9%A3%9F%E5%93%81?/qqa=480
- 社区绿色空间的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95-36%E6%B0%AA%E9%A3%9F%E5%93%81?/Qeh=pFu
- 城市应急科普的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F-%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/990
- 科学教育活动的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F-%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/yvd
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F-%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/uBL
- 城市慢行系统的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F-%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/148=jyt
- 公共场所导视的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F-%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/okf=025
- 应急物资管理的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%80%8D%E6%8A%951000%E5%85%83%E5%8D%81%E4%BA%94%E6%9C%9F-%E8%85%BE%E8%AE%AF%E6%91%84%E5%BD%B1?/OAM=SLF
- 智能手机助老的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/242
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/rsk
- 个人时间管理的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/ygv
- 社区托育服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/959=heg
- 数字学习资源的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/yxq=635
- 节气饮食文化的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99-%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/0OF=iIl
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8-%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/918
- 家庭志愿活动的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8-%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/tke
- 生活垃圾回收的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8-%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/X6F
- 社区绿色空间的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8-%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/449=jlw
- 户外活动组织的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8-%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/olf=401
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%951.3.8.15.24%E7%9B%88%E5%88%A9%E8%A1%A8-%E8%84%89%E8%84%89%E8%A1%8C%E6%83%85?/F1g=JxL
- 软件开发学习的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F-%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/417
- 数字生活课堂的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F-%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/nro
- 社区故事采集的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F-%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/7Xd
- 社区互助网络的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F-%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/973=eiu
- 数字地图应用的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F-%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/tgm=520
- 数字支付体验的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%80%8D%E6%8A%95%E7%8E%8B%E9%A2%84%E6%B5%8B%E5%A4%A7%E4%B9%90%E9%80%8F-%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/ygh=MG5
- 志愿者培训交流的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E7%8E%8B%E5%8F%8C%E8%89%B2%E7%90%83%E9%A2%84%E6%B5%8B-%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/986
- 青少年心理健康的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E7%8E%8B%E5%8F%8C%E8%89%B2%E7%90%83%E9%A2%84%E6%B5%8B-%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/jph

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
