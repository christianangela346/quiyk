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

- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91-1080p-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/LRI
- 数字生活课堂的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91-1080p-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/008=hbu
- 城市噪声观察的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91-1080p-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/upd=649
- 城市建设科普的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91-1080p-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/KvX=IgH
- 社区垃圾回收的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/590
- 城市步行环境的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/afb
- 非遗课堂体验的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/Pl6
- 生成式工具使用的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/380=vpa
- 环境监测科普的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/vbl=600
- 生活垃圾回收的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91bt%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/5X5=Rko
- 公共设施维护的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/270
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/pjw
- 在线学习体验的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/EIj
- 家庭用电安全中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/886=mbo
- 文化场馆预约的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/mjk=253
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%9F%A5%E4%B9%8E%E6%85%A7%E7%9C%BC?/bAl=JsR
- 生成式工具使用的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/082
- 在线学习体验中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/wnr
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/WTR
- 基层服务创新中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/834=bwx
- 城市展览体验的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/wqj=177
- 社区便民服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91APP%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5_%E6%90%9C%E7%8B%97%E5%86%9B%E4%BA%8B?/sun=RMF
- 城乡交流活动的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/698
- 城市可持续生活的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/vdx
- 居家适老化改造的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/NDV
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/573=hyw
- 节约用水实践的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/xds=315
- 便民服务窗口的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp%E8%B5%A0%E9%80%8138%E5%85%83_%E5%A4%AE%E8%A7%86%E6%99%9A%E6%8A%A5?/jp1=StE
- 公共设施维护的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/609
- 亲子阅读活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/jql
- 社区停车服务的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/pIm
- 儿童阅读角中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/276=ubv
- 公共空间导览的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/oqm=485
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/qMn=vlG
- 社区花园共建的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/101
- 文化讲座服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dpm
- 儿童友好空间的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vVP
- 家庭健康科普中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/858=elv
- 数字资源检索的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tdr=444
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD1080p_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/PNB=5Dn
- 地方美食文化的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/246
- 便民信息查询的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/lax
- 数字创意课程的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/40h
- 城市生活服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/112=fny
- 社区宣传栏更新的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/alj=690
- 乡村电商实践的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E6%8A%95%E7%A5%A8?/TlF=DR9
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/618
- 邻里共享空间的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/omj
- 基层健康服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/jN9
- 乡村产业科普的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/807=nql
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/ubr=161
- 科学观察活动的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%A5%BD%E7%94%A8_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/2pQ=URv
- 城市绿色交通的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/299
- 休闲运动入门的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/qhy
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/u2Y
- 社区设施共享的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/371=too
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/gel=265
- 数字学习资源的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%88%B0%E6%A1%8C%E9%9D%A2%E4%B8%8A_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/37n=Jvl
- 城市文明出行的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/886
- 公交站点体验的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/bfm
- 数字素养提升的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/L0O
- 数字素养提升的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/158=vdj
- 公交站点体验的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/vww=551
- 周末休闲规划的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8%E5%90%88%E9%9B%86_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/nNP=Occ
- 数字课堂应用的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/713
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/opt
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/hRv
- 学校食育活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/240=gir
- 社区菜市场服务的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/bxr=711
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%852022%E6%9C%80%E6%96%B0%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E9%99%85?/mfx=iil
- 社区文化节活动的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/679
- 科技馆参观体验的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/mpb
- 公共图书馆服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/pFv
- 社区休闲设施的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/073=wuh
- 急救知识普及的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/dni=411
- 邻里共享空间的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_4g%E5%BD%A9%E7%A5%A8%E8%80%81%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/9NB=JSM
- 公共文化活动的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/791
- 青年职业探索中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/jlj
- 社区快递服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/xQ9
- 社区教育资源的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/133=odk
- 个人时间管理的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/daf=053
- 社区防暑服务的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_2024%E5%B9%B4%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E7%88%86%E6%96%99?/iUo=KSd
- 小区电梯维护的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/614
- 科学运动指导的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/sej
- 公共服务数字化的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/SSG
- 公共健身器材的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/329=tka
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/dix=536
- 农产品消费体验的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_758%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%9C%8D%E9%A5%B0?/7Jk=IsH
- 文化讲座服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/295
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/fli
- 社区应急准备的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/iVE
- 家庭园艺实践的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/192=klk
- 社区心理支持的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/fho=767
- 城市公共座椅的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%A5%96%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/AZI=7Ah
- 气象科普传播的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/578
- 科学信息获取的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/jxx
- 在线学习体验的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/YTq
- 口袋公园建设的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/453=ivh
- 公共服务沟通的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/qhn=140
- 绿色办公实践的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_785%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/jem=AqE
- 城市人文观察的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/240
- 城市体育设施的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/pfh
- 城市雨天出行的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/fdA
- 医院导诊服务的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/132=xoe
- 图书馆亲子空间的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/ozl=696
- 老年人出行服务的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%80%8127%E5%BD%A9%E9%87%91%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/rw9=98U
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/653
- 社区文化传播的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/ebg
- 创业经验分享的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/juR
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/696=txa
- 在线学习体验的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/gvs=000
- 街区小店体验的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%97%BA%E5%BD%A9%E8%B5%B0%E5%8A%BF%E5%9B%BEapp%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/P8U=Fyk
- 数字创作工具的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/498
- 公共服务指南的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/djb
- 公共空间照明的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/MPX
- 青少年心理健康的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/364=wax
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/plr=649
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%89%88%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/wfD=mqN
- 日常摄影记录的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/685
- 社区便民集市的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/scx
- 城市展览体验的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/66Y
- 地方民俗记录的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/204=tcu
- 无障碍出行的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/est=708
- 青少年心理健康的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/OYg=RoI
- 机器学习入门的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/418
- 新能源出行的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/qmq
- 街区小店体验的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/qDS
- 城市公共厕所的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/500=bmr
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/jbg=277
- 公共场所导视的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/duP=I5U
- 儿童安全出行的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/068
- 线上办事服务的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/gek
- 课后服务体验的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/ZqQ
- 科学教育活动的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/889=juv
- 文化场馆预约的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/yzl=152
- 创业经验分享的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%97%85%E6%B8%B8?/nvk=UBd
- 数字艺术创作的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/260
- 数字阅读服务的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/dvn
- 城市噪声观察的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/rL0
- 社区共享书架的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/307=kjc
- 网络安全教育中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/gre=575
- 公共空间休憩的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A918%E5%85%83_%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/vMZ=7l1
- 乡村文化空间的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E9%80%9F%E8%A7%88?/192
- 社区慢性病防控的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E9%80%9F%E8%A7%88?/fwk
- 应急物资管理的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E9%80%9F%E8%A7%88?/M01
- 家庭健康管理的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E9%80%9F%E8%A7%88?/027=nam
- 城市公共标识的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E9%80%9F%E8%A7%88?/wxr=716
- 乡村公共文化的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E9%80%9F%E8%A7%88?/dAA=Uh2
- 新能源出行的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/225
- 电子商务服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/cdy
- 城市慢行系统的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/e5o
- 生活服务数字化的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/853=woj
- 社区公共卫生的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/ckr=724
- 社区活动空间的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_656%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E9%97%AE%E7%AD%94?/GLA=rmN
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/735
- 环境教育课程的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/dhu
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/MVA
- 城市噪声观察的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/538=cvu
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/esf=121
- 节能家电使用的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E5%9B%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%9C%8D%E9%A5%B0?/hLQ=QI7
- 健康信息获取的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/141
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/dze
- 社区心理支持的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/ZXI
- 社区交通安全的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/038=hzc
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/kyv=003
- 农贸市场环境的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%B2%BE%E9%80%89?/kLP=Uq7
- 节能家电使用的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/020
- 家庭阅读计划的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/qhk
- 社区共享书架的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/f0a
- 网络安全教育的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/771=gfp
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/frz=979
- 农业科普体验的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/ThB=zyG
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/866
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/snq
- 青少年科技社团的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/nuJ
- 老年人日常照护的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/373=xul
- 社区老年食堂的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/qwu=477
- 家庭环保习惯的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E6%9C%80%E5%A5%BD%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%B1%BD%E8%BD%A6?/sGi=p66
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/524
- 社区庭院绿化的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/rhy
- 低碳社区实践的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/F65
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/279=hxk
- 日常摄影记录的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/yyp=619
- 社区活动策划的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E7%89%9B%E5%BD%A9app%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/JeZ=iaE
- 便民服务窗口的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/762
- 周末休闲规划的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/zpu
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/lOr
- 社区庭院绿化的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/093=ydt
- 城市文化路线的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/ful=516
- 智慧城市体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%80%BA%E5%B8%82?/vnr=wBp
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/195
- 城市公共空间的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/sbl
- 节气饮食文化的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/GEi
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/559=pvv
- 公共空间照明的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/zdq=170
- 公园亲子设施的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/dzt=6tO
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/327
- 小区公共照明的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/pli
- 家庭阅读计划的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/jZn
- 社区商业活力的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/192=iki
- 社区菜市场服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/cxr=321
- 无障碍信息设计的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/jRx=25l
- 社区修缮行动的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/662
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/crc
- 青年志愿活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/vq4
- 家庭健康科普的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/022=erp
- 非遗体验活动的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/kme=226
- 便民信息查询的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/4HG=sjL
- 儿童友好空间的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/303
- 城市公共艺术的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/xyh
- 城市住房服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/6EX
- 城乡交流活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/796=isw
- 乡村电商实践的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/nyl=906
- 街道综合服务的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%A6%9C%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%BF%AB%E8%AE%AF?/ui5=why
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/346
- 家庭网络使用的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/icu
- 社区便民集市的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/0RA
- 公共服务数字化的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/247=lvy
- 城市文明实践的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/btk=985
- 社区应急准备的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%8A%95%E7%A8%BF?/Wnz=Spr
- 图书馆活动策划的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/662
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/ddy
- 社区儿童活动的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/9lI
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/662=cuh
- 社区防暑服务的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/usp=284
- 乡村生活观察的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%85%A8%E9%83%A8%E5%87%BA%E6%9D%A5%E4%BA%86_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/m7E=7tG
- 城市文化路线的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/120
- 社区法律科普的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/atv
- 安全出行教育的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/qwl
- 社区修缮行动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/390=tql
- 数字阅读服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/bac=107
- 家庭志愿活动从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E2%85%B48%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%85%AC%E5%BC%80%E8%AF%BE?/7JK=QWG
- 绿色生活实践的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/075
- 文化场馆预约的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/frf
- 社区生活指南的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/3dU
- 新能源出行的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/626=zlr
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/qtu=679
- 电子商务服务的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/Ha5=Y8f
- 社区活动空间的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/973
- 智能家居应用的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/nwe
- 城市公共厕所的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/rLE
- 医院导诊服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/745=jyh
- 科技馆参观体验的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/mpt=911
- 市民热线服务的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2021%E6%9C%80%E6%96%B0%E7%89%88_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/qyx=nTh
- 乡村阅读空间的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/268
- 数字公共文化的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/ear
- 城市农夫市集的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/Cu7
- 社区家校合作的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/316=qhs
- 城市雨天出行的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/vjl=752
- 城市便民驿站的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E7%99%BE%E5%BA%A6%E6%99%A8%E6%8A%A5?/nIF=adD

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
