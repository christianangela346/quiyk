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

- 公共服务沟通的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E8%B6%85%E8%BF%87%E4%B8%80%E4%B8%87%E4%BA%A4%E7%A8%8E%E5%90%97_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/xif=114
- 租房信息服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E8%B6%85%E8%BF%87%E4%B8%80%E4%B8%87%E4%BA%A4%E7%A8%8E%E5%90%97_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/TPb=DQx
- 校园节能行动的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E5%92%8C%E8%BF%BD%E5%8A%A0%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/178
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E5%92%8C%E8%BF%BD%E5%8A%A0%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/edi
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E5%92%8C%E8%BF%BD%E5%8A%A0%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/FEG
- 城市树木认养的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E5%92%8C%E8%BF%BD%E5%8A%A0%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/116=uhl
- 城市夜间生活的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E5%92%8C%E8%BF%BD%E5%8A%A0%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/wfp=373
- 生活技能分享的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E5%92%8C%E8%BF%BD%E5%8A%A0%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB_%E8%99%8E%E6%89%91%E7%BB%BC%E8%89%BA?/iKn=FKJ
- 周末休闲规划的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E6%9C%80%E9%AB%98%E5%A5%96%E9%87%91%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/065
- 本地旅行体验的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E6%9C%80%E9%AB%98%E5%A5%96%E9%87%91%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/fxl
- 乡村文化空间的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E6%9C%80%E9%AB%98%E5%A5%96%E9%87%91%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/nUk
- 远程协作工具的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E6%9C%80%E9%AB%98%E5%A5%96%E9%87%91%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/943=nrl
- 社区法律科普的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E6%9C%80%E9%AB%98%E5%A5%96%E9%87%91%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/vuo=062
- 社区停车服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E6%9C%80%E9%AB%98%E5%A5%96%E9%87%91%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B?/eCR=j6V
- 街区小店体验的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/652
- 科学信息获取的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/mtv
- 乡村生活观察的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/2R2
- 城市游园体验的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/539=wwe
- 公共设施使用的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/gkx=742
- 社区慢性病防控的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/q3i=j81
- 社区停车服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/763
- 数字创意课程的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/lbh
- 机器人科普活动中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/hve
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/007=bpg
- 城市地名文化中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/mga=716
- 社区活动空间的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E7%89%B9%E7%A8%BF?/ukg=zlh
- 社区艺术活动的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/565
- 城市博物馆活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/zvn
- 节日文化体验的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/RrG
- 公共场所导视的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/105=ils
- 老年学习活动的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/zff=327
- 公共空间安全的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%90%88%E9%9B%86%E5%A4%A7%E5%85%A8_%E5%93%94%E5%93%A9%E5%BF%AB%E8%AE%AF?/wFq=FQl
- 口袋公园建设的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/860
- 社区共享书架的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/vdy
- 数字生活课堂的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/J1G
- 邻里互助活动的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/103=mdy
- 儿童友好空间的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/zhh=615
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%97%AE%E7%AD%94?/PNT=VD9
- 药品使用科普的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B1%87%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/583
- 青少年科普实践的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B1%87%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/nhq
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B1%87%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/yqc
- 开源技术交流的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B1%87%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/920=fdd
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B1%87%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/ptr=773
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B1%87%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/dfY=jaR
- 社区消防演练的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85www_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/726
- 科学健身方法的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85www_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/bwc
- 光伏知识科普的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85www_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/Isp
- 城市博物馆活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85www_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/370=ylx
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85www_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/dde=872
- 个人信息保护的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85www_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/za3=Hvl
- 城市雨天出行中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9D%80%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/672
- 个人时间管理的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9D%80%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/mig
- 社区教育资源的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9D%80%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/n76
- 社区花园共建的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9D%80%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/078=vmp
- 本地消费场景的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9D%80%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/txb=137
- 社区生活指南的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%9D%80%E8%B5%9A%E9%92%B1_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/dwO=jrn
- 城市慢跑路线的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/218
- 农村环境治理的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/iki
- 消防知识宣传的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/uFy
- 在线学习体验的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/521=ljm
- 社区科普课堂的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/bxi=653
- 绿色消费选择的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/Jnu=HKT
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E4%B8%AD%E5%9B%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/242
- 急救知识普及的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E4%B8%AD%E5%9B%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/yvw
- 公益活动组织的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E4%B8%AD%E5%9B%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/KX3
- 基层健康档案的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E4%B8%AD%E5%9B%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/602=egv
- 小区电梯维护的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E4%B8%AD%E5%9B%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/jsu=257
- 青年职业探索的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E4%B8%AD%E5%9B%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/TXe=ZWW
- 智能家居应用的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/737
- 社区手工活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/frp
- 城市游园体验的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/oOP
- 休闲运动入门的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/242=oww
- 在线学习体验的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/lii=110
- 农贸市场环境的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/BE4=pCo
- 电子商务服务的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E4%BD%A3%E9%87%91_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/788
- 健康饮水科普的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E4%BD%A3%E9%87%91_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/apu
- 公共交通接驳的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E4%BD%A3%E9%87%91_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/F4y
- 骑行路线规划的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E4%BD%A3%E9%87%91_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/873=bhd
- 家庭健康管理的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E4%BD%A3%E9%87%91_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/uvw=366
- 无障碍出行的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E4%BD%A3%E9%87%91_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/5PP=SAf
- 低碳社区实践的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%85%BC%E8%81%8C_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/810
- 家庭网络使用的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%85%BC%E8%81%8C_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/tst
- 公益活动组织的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%85%BC%E8%81%8C_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/aHp
- 社区活动策划的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%85%BC%E8%81%8C_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/295=kyn
- 个人数据管理的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%85%BC%E8%81%8C_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/uiv=360
- 终身学习资源的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%85%BC%E8%81%8C_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/LN5=BtE
- 租房信息服务的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/731
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/ypp
- 数字政务体验的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/tUv
- 社区知识分享的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/721=xbd
- 网络安全教育的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/wgo=948
- 乡村文化活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/has=j6v
- 家庭健康科普的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/201
- 乡村教育资源的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/lax
- 社区健康讲座中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/Pup
- 社区故事采集的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/859=lsu
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/xrt=575
- 生成式工具使用的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8C%A3%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E5%97%85%E6%88%BF%E4%BA%A7?/ywX=viv
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/724
- 运动安全知识的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/ded
- 城市基础设施中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/NmN
- 数字设备回收的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/575=cwk
- 科学观察活动的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/wps=898
- 本地历史资料的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A8%BF?/8dV=BKM
- 青少年编程学习的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9C%9F%E5%AE%9E%E6%A1%88%E4%BE%8B_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/713
- 节能家电使用的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9C%9F%E5%AE%9E%E6%A1%88%E4%BE%8B_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/ffn
- 社会体育指导的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9C%9F%E5%AE%9E%E6%A1%88%E4%BE%8B_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/7I3
- 科学教育活动的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9C%9F%E5%AE%9E%E6%A1%88%E4%BE%8B_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/205=wtz
- 智能家居应用的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9C%9F%E5%AE%9E%E6%A1%88%E4%BE%8B_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/gmi=452
- 智慧城市体验的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E7%9C%9F%E5%AE%9E%E6%A1%88%E4%BE%8B_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E8%82%A1?/tAO=9aL
- 乡村教育资源的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%8A%80%E6%9C%AF%E5%90%A7_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/489
- 城市人文观察的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%8A%80%E6%9C%AF%E5%90%A7_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/cae
- 市民热线服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%8A%80%E6%9C%AF%E5%90%A7_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/daz
- 城市应急广播的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%8A%80%E6%9C%AF%E5%90%A7_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/210=ybt
- 青少年户外教育的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%8A%80%E6%9C%AF%E5%90%A7_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/lzj=340
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E6%8A%80%E6%9C%AF%E5%90%A7_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/560=HKV
- 儿童运动体验的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E8%9B%8B%E8%9B%8B%E5%B0%BD%E4%BA%AB%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/470
- 城市可持续生活的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E8%9B%8B%E8%9B%8B%E5%B0%BD%E4%BA%AB%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/xxe
- 家庭教育交流的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E8%9B%8B%E8%9B%8B%E5%B0%BD%E4%BA%AB%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/Xbn
- 就业技能培训的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E8%9B%8B%E8%9B%8B%E5%B0%BD%E4%BA%AB%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/587=oya
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E8%9B%8B%E8%9B%8B%E5%B0%BD%E4%BA%AB%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/cju=836
- 节日文化体验的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E8%9B%8B%E8%9B%8B%E5%B0%BD%E4%BA%AB%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/A19=R1p
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E6%A8%A1%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/566
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E6%A8%A1%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/jkn
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E6%A8%A1%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/3Gn
- 环境教育课程的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E6%A8%A1%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/967=qbk
- 居家适老化改造的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E6%A8%A1%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/aiu=384
- 城市共享单车的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_pc28%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87%E6%A8%A1%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%92%AD%E6%8A%A5?/46N=0Ae
- 公共服务评价的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%88%AE%E5%A5%96%E5%92%AA%E7%89%8C_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/346
- 乡村公共阅读的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%88%AE%E5%A5%96%E5%92%AA%E7%89%8C_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/kyq
- 通勤路线规划的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%88%AE%E5%A5%96%E5%92%AA%E7%89%8C_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/4jv
- 学校食育活动的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%88%AE%E5%A5%96%E5%92%AA%E7%89%8C_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/414=ovo
- 电子商务服务的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%88%AE%E5%A5%96%E5%92%AA%E7%89%8C_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/sca=410
- 城市体育设施的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_pc28%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%88%AE%E5%A5%96%E5%92%AA%E7%89%8C_%E4%BA%AC%E4%B8%9C%E4%BF%A1%E6%89%98?/0sp=Eor
- 乡村生态观察的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/687
- 乡村文化活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/plk
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/zrk
- 城市休闲步道的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/361=jnn
- 志愿服务平台的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/vnm=483
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E8%9B%8B%E8%9B%8Bpc28%E9%A2%84%E6%B5%8B_%E5%AE%8F%E6%99%AF%E8%B4%A2%E7%BB%8F?/sAf=kh3
- 基层医疗预约的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A7P28%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/735
- 公交站点体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A7P28%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/qiy
- 社区设施共享的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A7P28%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/e3M
- 家庭照护支持的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A7P28%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/067=qja
- 家庭科学教育的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A7P28%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/vua=319
- 社区停车服务的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A7P28%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/vES=xKg
- 数字资源检索的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/163
- 公交站点体验的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/zpk
- 数字便民地图的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/BqI
- 社区志愿服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/126=pir
- 城市建设科普的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/atz=640
- 线上阅读资源的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk10%E8%B5%9B%E8%BD%A6_%E9%9B%85%E8%99%8E%E5%BD%B1%E8%A7%86?/kj0=2BF
- 城市共享单车的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/875
- 城市文明实践的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/wzv
- 老年友好服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/KAT
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/140=vgh
- 社区商业活力的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/ayr=729
- 在线学习体验中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%A4%A7%E5%85%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%BF%E5%9F%9F?/qY7=ZEM
- 个人时间管理的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6pK10%E5%85%AC%E4%BC%97%E5%8F%B7_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/038
- 社区活动报名的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6pK10%E5%85%AC%E4%BC%97%E5%8F%B7_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ckr
- 线上阅读资源的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6pK10%E5%85%AC%E4%BC%97%E5%8F%B7_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/IAR
- 街区绿化养护的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6pK10%E5%85%AC%E4%BC%97%E5%8F%B7_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/536=xpn
- 科学观察活动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6pK10%E5%85%AC%E4%BC%97%E5%8F%B7_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ozd=917
- 开源技术交流的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E8%B5%9B%E8%BD%A6pK10%E5%85%AC%E4%BC%97%E5%8F%B7_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/CZn=dkf
- 青少年科技社团的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%BE%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/754
- 社区停车服务的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%BE%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/zwb
- 家庭环保习惯的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%BE%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/fL1
- 家庭环保行动的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%BE%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/493=afe
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%BE%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/nfs=745
- 城市噪声观察的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%BE%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/1Ek=NaF
- 非遗体验活动的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E6%88%91%E4%B8%80%E4%B8%8B_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/872
- 新能源出行的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E6%88%91%E4%B8%80%E4%B8%8B_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/zmm
- 志愿者培训交流的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E6%88%91%E4%B8%80%E4%B8%8B_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/H4o
- 城市公共空间的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E6%88%91%E4%B8%80%E4%B8%8B_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/002=unv
- 城市人文观察的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E6%88%91%E4%B8%80%E4%B8%8B_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/asp=772
- 乡村公共服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E8%B0%81%E6%9C%89%E8%B5%9B%E8%BD%A6%E7%BE%A4%E6%8B%89%E6%88%91%E4%B8%80%E4%B8%8B_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/lJ2=o8M
- 城市共享单车的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/674
- 邻里互助活动的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/ala
- 社区活动策划的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/8Kt
- 社区公共餐饮的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/588=srt
- 社区文化节活动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/uby=360
- 农业科普体验的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%93%AA%E9%87%8C%E6%89%BEpk10%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/VsZ=DY1
- 生活技能分享的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/978
- 老年人日常照护的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/hvx
- 户外活动组织的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/K1F
- 家庭环保行动的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/050=xgv
- 青年志愿活动的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/pmd=121
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E8%B0%81%E6%9C%89%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/Cev=VnS
- 安全出行教育的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%BE%A4_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/901
- 食品配送体验的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%BE%A4_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/ham
- 个人数据管理的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%BE%A4_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/KgO
- 公共空间照明的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%BE%A4_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/232=anf
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%BE%A4_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/pjg=704
- 文化讲座服务的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E8%B5%9B%E8%BD%A6%E6%9C%80%E6%96%B0%E7%BE%A4_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/H4l=XNW
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E7%BE%A4qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/787
- 社区商业活力的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E7%BE%A4qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/ksl
- 节约用水实践的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E7%BE%A4qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/xzw
- 公共空间导览的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E7%BE%A4qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/213=muz
- 开放式学习空间的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E7%BE%A4qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/jxk=747
- 老年友好服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%B5%9B%E8%BD%A6%E7%BE%A4qq%E7%BE%A4_%E6%96%B0%E6%B5%AA%E4%BF%A1%E8%AE%BF?/Pgv=fBM
- 街头绿植养护的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/487
- 线上阅读资源的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/ddh
- 终身学习资源的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/iSw
- 街道综合服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/012=azn
- 公共空间休憩的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/yei=725
- 就业技能培训的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E4%BF%A1%E8%AE%BF?/TGH=dVJ
- 公共场馆服务的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/913
- 节气饮食文化的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ldt
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/lUh
- 无障碍出行的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/808=xcm
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/vqz=301
- 社区托育服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%AD%A3%E8%A7%84%E5%8F%AF%E9%9D%A0%E8%B5%9B%E8%BD%A6%E7%BE%A4_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/Gan=wyL
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%BF%83%E5%BE%97_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/116
- 本地消费场景的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%BF%83%E5%BE%97_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/grg
- 社区科普课堂中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%BF%83%E5%BE%97_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/hzv
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%BF%83%E5%BE%97_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/839=vmj
- 城市绿色交通的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%BF%83%E5%BE%97_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/mje=444
- 社区艺术活动的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%80%8E%E4%B9%88%E6%8E%A8%E7%AE%97%E5%BF%83%E5%BE%97_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/RF2=id4
- 公共场所导视的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/430
- 休闲运动入门的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/mil
- 城市农夫市集的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/8EP
- 公共卫生设施的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/452=mma
- 城市公共饮水的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/cpq=264
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E5%88%9B%E6%8A%95?/VJH=Lvl
- 城市树木认养的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%BA%E5%9D%9B_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/270
- 社区休闲设施的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%BA%E5%9D%9B_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/pez
- 开源技术交流的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%BA%E5%9D%9B_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/WP4
- 开放式学习空间的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%BA%E5%9D%9B_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/284=ixn
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%BA%E5%9D%9B_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/yos=323
- 个人数据管理的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%AE%BA%E5%9D%9B_%E4%BA%AC%E4%B8%9C%E5%8F%B7%E5%A4%96?/7Ty=YKd
- 农产品消费体验的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/482
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/jtj
- 校园阅读活动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/s63
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/936=lgb
- 气象科普传播的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/jah=725
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E6%80%8E%E4%B9%88%E7%9C%8B%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%9B%BE%E8%A7%A3_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/Otm=Wu2
- 乡村公共文化的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%86%B3%E8%B5%9B%E6%89%93%E4%B8%80%E5%92%8C%E5%80%BC_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/969
- 社区阅读服务的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%86%B3%E8%B5%9B%E6%89%93%E4%B8%80%E5%92%8C%E5%80%BC_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/ozp
- 社区公共卫生的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%86%B3%E8%B5%9B%E6%89%93%E4%B8%80%E5%92%8C%E5%80%BC_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/plt
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%86%B3%E8%B5%9B%E6%89%93%E4%B8%80%E5%92%8C%E5%80%BC_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/928=eqi
- 社区垃圾分类的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%86%B3%E8%B5%9B%E6%89%93%E4%B8%80%E5%92%8C%E5%80%BC_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/fqb=609
- 社区心理支持的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%86%A0%E4%BA%9A%E5%86%B3%E8%B5%9B%E6%89%93%E4%B8%80%E5%92%8C%E5%80%BC_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/zQ2=Hpm
- 社区休闲设施的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%86%A0%E5%86%9B%E6%89%93%E4%B8%80%E4%B8%AA%E5%92%8C%E5%80%BC_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/780
- 物业服务沟通的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%86%A0%E5%86%9B%E6%89%93%E4%B8%80%E4%B8%AA%E5%92%8C%E5%80%BC_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/fdu
- 社区花园共建的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%86%A0%E5%86%9B%E6%89%93%E4%B8%80%E4%B8%AA%E5%92%8C%E5%80%BC_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/jyV
- 城乡公共服务的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%86%A0%E5%86%9B%E6%89%93%E4%B8%80%E4%B8%AA%E5%92%8C%E5%80%BC_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/403=hcl
- 职业技能学习的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%86%A0%E5%86%9B%E6%89%93%E4%B8%80%E4%B8%AA%E5%92%8C%E5%80%BC_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/cbs=877
- 节约用水实践的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%86%A0%E5%86%9B%E6%89%93%E4%B8%80%E4%B8%AA%E5%92%8C%E5%80%BC_%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/GAb=8Au
- 街区绿化养护的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%86%A0%E4%BA%9A%E5%AD%A3%E5%90%88%E5%8D%95%E5%8F%8C%E6%9C%80%E5%87%86%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/512
- 公交站点体验的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%86%A0%E4%BA%9A%E5%AD%A3%E5%90%88%E5%8D%95%E5%8F%8C%E6%9C%80%E5%87%86%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/adq

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
