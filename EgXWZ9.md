# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:16**

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

- 社区文化节活动的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/Pv3
- 乡村公共文化的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/237=cxk
- 社区生活指南的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/fhs=635
- 社会体育指导的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/RAB=x7q
- 传统手工艺体验的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/361
- 环境教育课程的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/nyd
- 社区便民集市的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/SiR
- 亲子科普活动的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/655=jbi
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/fkm=580
- 社区休闲设施的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E9%AB%98%E6%89%8B_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/GPn=G6n
- 无障碍信息设计的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/096
- 老年数字阅读的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/kdk
- 科学健身方法的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/LqH
- 绿色校园实践的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/989=mma
- 家庭科学教育的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/vfi=653
- 老年运动活动的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BC%98%E9%85%B7%E8%A7%82%E7%82%B9?/rMk=iRU
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/578
- 小微企业服务的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/jtr
- 绿色校园实践的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/Mda
- 农村环境治理的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/721=osp
- 绿色出行服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/cow=787
- 老年人文化生活的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%A1%A8%E6%A0%BC_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/BAE=6fe
- 公共服务咨询的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/485
- 社区托育服务的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/krv
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/6ON
- 乡村生活观察的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/177=kwt
- 社会体育指导的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/gay=936
- 居家适老化改造的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E6%95%B0%E6%8D%AE_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%87%E5%B8%82?/3gk=Ugr
- 安全出行教育的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/467
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/vpw
- 非遗体验活动的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/FEh
- 社区休闲设施中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/356=hqi
- 在线学习体验的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/goy=591
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%9B%B4%E6%92%AD_%E4%BD%B3%E5%92%8C%E8%B4%A2%E7%BB%8F?/FxU=DgO
- 数字阅读服务的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/121
- 城市生活记录的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/jgh
- 公园休闲体验的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/Q7M
- 市民热线服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/234=rsy
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/zpb=335
- 社区商业活力的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/T9s=dTT
- 城市生活记录的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/285
- 环境教育课程的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/odc
- 生活垃圾减量的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/Giq
- 家庭网络使用的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/246=ijz
- 城乡公共服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/cev=124
- 青少年编程学习的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85?/Vc9=ykz
- 公共服务评价的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/433
- 创业经验分享的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/xdt
- 智能家居应用的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/cJT
- 社区休闲设施的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/639=moa
- 学校食育活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/vrf=711
- 志愿服务平台的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%9E%AD%E6%9C%9B?/mFO=N8H
- 日常摄影记录的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/063
- 城市运动公园的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/cov
- 应急物资管理的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/snN
- 老年智能设备的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/736=bju
- 家庭阅读计划的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/dla=913
- 职业技能学习的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%BF%85%E5%BA%94%E7%9B%B4%E6%92%AD?/4Lh=jw6
- 便民服务窗口的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/111
- 基层服务创新的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/zdt
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/Jrs
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/486=drc
- 志愿服务平台的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/dnv=019
- 网络安全教育的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E8%B1%86%E7%93%A3%E5%85%AC%E5%BC%80%E8%AF%BE?/ZUp=pm4
- 城市公共艺术的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/226
- 城市夜间照明的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/lif
- 公共服务指南的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/dcO
- 社区家校合作的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/696=dgl
- 社区便利生活的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/wsd=275
- 社区家政服务的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/Xj8=j4M
- 社区公共卫生的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/339
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/svb
- 旧物循环利用的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/imE
- 社区文化传播的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/713=bes
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/dpl=025
- 城市夜间照明的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/acp=jtl
- 网络安全教育的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/330
- 绿色生活实践的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/brd
- 社区家政服务的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/4nK
- 机器人科普活动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/882=tvd
- 数字政务体验的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/qay=884
- 城市运动公园的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_%E5%93%94%E5%93%A9%E8%A6%81%E9%97%BB?/sA9=dbz
- 在线学习体验的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/348
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/lpy
- 急救知识普及的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/D6h
- 便民服务窗口的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/832=opu
- 社区阅读服务的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/vsa=510
- 城市应急科普的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/ZBq=tvP
- 家庭照护支持的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/047
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ady
- 终身学习资源的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/78j
- 健康步道使用的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/457=bgs
- 社区家政服务的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/pbr=299
- 农业科普体验的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/HF9=Umg
- 城市夜间生活的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/994
- 社区活动空间的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/wkh
- 社区便民服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/fdP
- 数字素养提升的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/568=bgk
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/byb=187
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/oDz=T0p
- 无障碍出行的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/848
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/lqy
- 节约用水实践的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/cMN
- 社区志愿服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/368=hck
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/ahd=620
- 乡村公共服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/rFr=OxQ
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/243
- 公交无障碍服务的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/nbr
- 数字地图应用的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/tZC
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/434=evs
- 生成式工具使用的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/lwy=571
- 居民健康教育的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/VjU=tui
- 儿童运动体验中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/059
- 城市地名文化的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/keh
- 家庭照护支持的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/TLF
- 公共健身器材的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/455=bad
- 乡村教育资源的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/nnj=393
- 网络信息辨识的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E6%BE%8E%E6%B9%83%E5%88%8A%E7%99%BB?/0i8=VTv
- 乡村公共文化的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/536
- 社区垃圾分类的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/tlv
- 开放数据应用的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/W6G
- 城市环境志愿行动的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/761=ehf
- 社区养老服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/uty=490
- 节气饮食文化的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%91%A8%E6%8A%A5?/gOY=1dC
- 公共场馆服务的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/909
- 科学健身方法的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/xsy
- 城市应急广播的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/Eh9
- 城市骑行环境的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/174=dku
- 儿童运动体验的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/vba=092
- 基层健康服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%9B%9E%E6%9C%9B?/a1u=NcM
- 青年职业探索的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/925
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/xgj
- 家庭消费规划的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/iJf
- 社区文化传播的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/626=pci
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/giw=080
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/qbY=LxN
- 口袋公园建设的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/847
- 家庭健康管理的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/plb
- 社区健康讲座的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/TYO
- 家庭安全提示的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/801=jnm
- 邻里共享空间的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/dnd=663
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/208=ghQ
- 城市公共厕所的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/088
- 城市文明出行的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/czv
- 社区便利生活的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/7Mn
- 城市公共自行车的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/184=ocq
- 居家防滑改造中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/bue=952
- 节能家电使用的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/l5w=xWE
- 科学教育活动的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/115
- 社区志愿服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/aee
- 图书馆数字服务的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/Evh
- 线上办事服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/305=xrk
- 城市地名文化的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/pdq=180
- 便民服务窗口的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/rod=aHz
- 乡村文化空间的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/996
- 公共文化活动的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/auq
- 数字生活课堂的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/XQs
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/326=vre
- 城市慢行系统的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/wzl=776
- 职业技能学习的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/KFT=ERU
- 数字支付体验的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/620
- 节日文化体验的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/pfe
- 食品安全科普的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/DIg
- 软件开发学习的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/569=iot
- 绿色生活实践的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/syy=613
- 公共空间照明的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/iDq=64m
- 社区交通安全的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/149
- 跨代沟通活动的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/sjt
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/6m5
- 社区活动空间的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/122=fwg
- 绿色快递包装的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/mhg=348
- 城市生活记录的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E5%9F%BA%E9%87%91?/x1O=2FZ
- 社区快递服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/887
- 家庭收纳实践的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/aay
- 气象科普传播的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/khP
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/464=bjy
- 家庭用电安全的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/qqv=451
- 数字创作工具的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E6%96%87%E5%8C%96?/2zn=B0R
- 社区商业活力的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/190
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/jhb
- 城市游园体验的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/Hqp
- 城市适老服务的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/959=twe
- 社区环保活动的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/vmz=313
- 地方旅游导览的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/H4R=E0G
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/136
- 市民意见收集的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/tdh
- 开源技术交流的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/tLX
- 社区家政服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/913=ypr
- 科普展览体验的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/maa=698
- 线上阅读资源的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/MLG=Myd
- 校园社团活动的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/286
- 社区公共议事的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/xxi
- 线上阅读资源的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/BoF
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/918=alz
- 城市建设科普的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/hdk=261
- 城市生活服务的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/K70=13c
- 生成式工具使用的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/326
- 家庭照护支持的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/ucn
- 城乡交流活动的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/s4H
- 社区休闲设施的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/871=gkc
- 社区儿童活动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/gjp=224
- 社区菜市场服务的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E5%8E%86%E5%8F%B2?/XEZ=x4u
- 老年学习活动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/842
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/imq
- 乡村电商实践的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/0f9
- 乡村文化空间的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/935=ecx
- 城市展览体验的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/vsp=315
- 社区慢性病防控的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E5%8D%88%E9%97%B4%E8%B4%A2%E7%BB%8F?/Qch=Amc
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/620
- 健康饮食教育的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/jwo
- 文化讲座服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Dhb
- 科学运动指导的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/494=cls
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dzh=842
- 公共空间导览的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/4Go=yf9
- 城市社区治理的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/695
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/caf
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/ieU
- 数字便民地图的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/812=zim
- 社区设施共享的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/sso=810
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/0zB=S7d
- 全民健身活动的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/967
- 乡村文化空间的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/vpp
- 老年人出行服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/EH2
- 城市体育设施的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/352=vct
- 科学教育活动从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/nij=211
- 生成式工具使用的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E5%86%9C%E4%B8%9A?/oEx=hVI
- 公共设施使用的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/074
- 城市绿道建设的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/cxc
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/tRX
- 数字地图应用的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/704=kol
- 气象科普传播的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/uwz=572
- 节约用水实践的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E6%96%87%E6%91%98?/mX6=E8F
- 安全出行教育的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/536
- 社区消防演练的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/pps
- 老年人文化生活的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/Hl9
- 网络信息辨识的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/067=lhd
- 城市展览体验的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/qpo=751
- 远程协作工具的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B_36%E6%B0%AA%E8%B4%A2%E7%BB%8F?/sl1=V4Y
- 智慧停车服务的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/468
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/zpd
- 儿童户外活动的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/Xgn
- 儿童运动体验的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/493=vyn
- 城市应急广播的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/yyi=083
- 街头绿植养护的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/Ezw=eIq
- 公共服务数字化的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/524
- 安全出行教育的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/eno
- 社区垃圾回收的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/bI4
- 公共空间安全的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/150=wrd
- 城乡交流活动的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/lmd=531
- 网络安全教育的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E8%83%BD%E6%BA%90?/ha0=igP

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
