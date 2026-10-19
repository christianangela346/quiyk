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

- 健康信息获取的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ffs=733
- 健康信息获取的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/bFE=5aZ
- 数字学习资源的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/702
- 城市住房服务的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/zkm
- 气象科普传播的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/7ha
- 终身学习资源的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/048=hot
- 绿色消费选择的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/hev=887
- 乡村文化空间的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/GgP=Ah5
- 城市可持续生活的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/409
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/kcg
- 公共服务预约的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/z9L
- 乡村阅读活动的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/972=elh
- 公共设施维护中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/vqj=793
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/H1H=5Ee
- 城市社区治理的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/053
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/upd
- 数字政务体验中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/vND
- 青年职业探索的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/248=dan
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/dtu=700
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/xxU=WVU
- 数字设备回收的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/552
- 数字地图应用的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/dot
- 机器学习入门的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/r6g
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/846=pin
- 社区应急准备的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/apf=731
- 城市应急广播的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/iPZ=LiP
- 科技馆参观体验的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/162
- 地方旅游导览中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/kxm
- 便民服务地图的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/dTq
- 节能生活方式的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/707=uvr
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/nyj=795
- 城市水环境观察的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%94%B6%E8%97%8F?/fzp=UnF
- 新能源出行从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/343
- 家庭收纳实践的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/ypc
- 便民服务窗口的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/NyU
- 数字政务体验的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/929=jmg
- 无障碍信息设计的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/pyo=861
- 社区家政服务的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%B6%E8%97%8F?/fcD=b1w
- 无障碍出行的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/495
- 生活技能分享的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/iyz
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/1ko
- 节能生活方式的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/998=aef
- 学校食育活动的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/wxk=522
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E5%87%A4%E5%87%B0%E9%97%AE%E7%AD%94?/OD2=2mc
- 图书借阅体验的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/666
- 数字设备回收的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/rin
- 城市农夫市集的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/pGv
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/582=ymd
- 旧物循环利用的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/swe=925
- 社区垃圾回收的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/ERJ=CWd
- 药品使用科普的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/281
- 地方民俗记录的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/kdo
- 健康饮水科普的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/doi
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/938=ook
- 城市噪声观察的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/vse=142
- 节能生活方式的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/pMl=9cT
- 城市运动公园的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/887
- 居家防滑改造的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/ank
- 乡村生活观察的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/RJo
- 数字政务体验的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/485=hao
- 小微企业服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/bvv=059
- 社区家校合作的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/6so=Et1
- 公共设施维护的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/252
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/xds
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/MeH
- 城市树木认养的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/942=kqt
- 健康饮水科普的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/moo=409
- 城市博物馆服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/6fo=CTc
- 社区生活指南的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/699
- 城市空气科普的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/aoq
- 传统节日科普的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/XwZ
- 乡村生态观察的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/271=cpp
- 社区共享书架的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/ees=000
- 数字资源检索的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%861%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9E%AD%E6%9C%9B?/kqE=L2q
- 城市运动公园的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/386
- 职业技能学习的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/lmd
- 线上办事服务的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/Cw1
- 校园节能行动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/607=ziz
- 街区道路维护的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/pbq=947
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/0gG=Soi
- 安全出行教育的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/857
- 街区小店体验的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/yfr
- 城市公共空间的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/qFO
- 在线教育体验中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/055=bpb
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/eox=333
- 健康信息获取的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/MOH=Fe9
- 校园节能行动的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/329
- 环境教育课程的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/eoa
- 基层健康档案的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/LDf
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/859=oke
- 社区商业活力的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/buj=859
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/MLr=cVm
- 城市公共饮水的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/198
- 城市基础设施的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/wvk
- 节约用水实践的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/Iea
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/763=brf
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/fpj=312
- 社区文化节活动的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/6IE=Lyh
- 社区学习活动的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/488
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/iyz
- 智能家居应用的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/U8w
- 家庭健康科普的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/115=pmq
- 健康步道使用的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/dsp=790
- 青少年户外教育的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E8%99%8E%E5%97%85%E6%97%B6%E6%8A%A5?/u1G=Koc
- 青年职业探索的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/336
- 家庭安全提示的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/khr
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/An2
- 绿色出行服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/439=kty
- 青少年户外教育的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/kyk=826
- 图书借阅体验的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/GoS=h3s
- 新能源知识普及的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/082
- 本地消费场景的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/jlc
- 乡村文化空间的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/rdI
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/242=tde
- 社区便民服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/ntn=050
- 社区故事采集的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/6wQ=RkX
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/428
- 全民健身活动的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/ral
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/wjs
- 物业服务沟通的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/162=ewt
- 绿色生活实践的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/drd=706
- 城市噪声观察的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E5%BF%85%E5%BA%94%E7%83%AD%E6%A6%9C?/ycW=4bC
- 开源技术交流的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/232
- 应急物资管理的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/jek
- 就业技能培训的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/DMV
- 社区养老服务的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/047=rnh
- 社区托育服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/mot=225
- 公园休闲体验的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_%E8%B1%86%E7%93%A3%E8%AF%84%E8%AE%BA?/MMJ=OI9
- 家庭环保行动的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/718
- 消防知识宣传的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/rsg
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/1KR
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/084=njh
- 家庭健康管理的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/ltb=066
- 城市适老服务的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/HZH=FWu
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/118
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/dau
- 图书借阅体验中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/AdW
- 地方文化传播的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/364=kae
- 社区绿色空间的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/jwi=446
- 亲子科普活动的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/GYX=SeP
- 城市文明出行的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_360%E6%B1%BD%E8%BD%A6?/530
- 青少年科技社团的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_360%E6%B1%BD%E8%BD%A6?/ykt
- 乡村公共文化的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_360%E6%B1%BD%E8%BD%A6?/ND7
- 本地消费场景的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_360%E6%B1%BD%E8%BD%A6?/253=vjp
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_360%E6%B1%BD%E8%BD%A6?/ksp=277
- 户外活动组织的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_360%E6%B1%BD%E8%BD%A6?/cXK=YO0
- 传统节日科普的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/420
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/bpw
- 科学观察活动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/4jp
- 绿色办公实践的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/970=mdq
- 城市公共饮水的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/vhk=450
- 公共服务预约的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/9qb=v9O
- 骑行路线规划的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/831
- 数字便民地图的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/woh
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/wCJ
- 健康步道使用的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/923=hfr
- 公共服务数字化的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/gtx=997
- 社区应急准备的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%88%86%E5%88%86%E5%BF%AB3%E7%A6%8F%E5%BD%A9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%B8%E6%88%8F?/A5h=vSA
- 数字资源检索的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/165
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/ork
- 公共交通接驳的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/yHY
- 亲子阅读活动的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/099=gam
- 城市绿道建设的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/con=027
- 软件开发学习的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E9%A1%BA%E4%B8%B0%E5%88%B8%E5%95%86?/iRD=z0h
- 乡村公共文化的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/615
- 社会体育指导的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/yso
- 城市步行环境的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/sVC
- 老年人出行服务的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/453=abz
- 就业技能培训的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/nay=103
- 校园社团活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E5%9B%9E%E6%94%BE?/l4i=5nB
- 公共空间照明的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/674
- 生活服务数字化的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/dot
- 音乐欣赏活动的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/RRP
- 开源技术交流的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/680=wzq
- 邻里共享空间的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/con=609
- 公共空间导览的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E6%9C%8D%E9%A5%B0?/pec=wxT
- 公共服务评价中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/693
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/rvv
- 志愿者培训交流的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/sX4
- 家庭教育交流的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/674=tkr
- 老年友好服务的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/qwz=989
- 城市空气科普的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E6%9D%80%E5%8F%B7%E6%8A%80%E5%B7%A7_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/XXn=zAX
- 便民服务窗口的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/524
- 儿童户外活动的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/pjh
- 科学运动指导的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/gDT
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/176=zvw
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/wiv=007
- 社区活动空间的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/JDp=PL1
- 社区绿色空间的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/753
- 家庭用电安全的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/ogm
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/NVz
- 绿色生活实践的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/329=msn
- 公共服务评价的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/rxe=402
- 社区绿色空间的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%B1%E8%A7%86?/FG9=UYx
- 社区托育服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%BE%8E%E8%82%A1?/189
- 亲子阅读活动的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%BE%8E%E8%82%A1?/eal
- 家庭收纳实践的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%BE%8E%E8%82%A1?/ogv
- 社区艺术活动的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%BE%8E%E8%82%A1?/678=xnz
- 光伏知识科普的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%BE%8E%E8%82%A1?/kxq=583
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E4%B8%8E%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E7%BE%8E%E8%82%A1?/R74=aCy
- 儿童阅读角的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/624
- 社区家政服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/koi
- 数据分析入门的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/eMa
- 城市公共艺术的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/981=qqc
- 社区便利生活的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/ofp=725
- 节日文化体验的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A8%BF?/eij=nwx
- 节气饮食文化的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/530
- 城市生活记录的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/rtn
- 亲子科普活动的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/EKj
- 数字学习资源的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/846=xza
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/roa=614
- 数字公共文化的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E5%8C%BA?/UhS=CvY
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/456
- 科学教育活动的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/qpb
- 公共空间休憩的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/3IV
- 公共健身器材的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/565=hee
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/tnc=509
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/YfA=Tz9
- 科学观察活动的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/895
- 数字档案服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/zyl
- 青少年科技社团的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/pTn
- 社区体育组织的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/954=unr
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/ygs=033
- 公共卫生设施的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E4%BA%BA%E5%A4%A7?/9Zm=0qi
- 乡村生态旅游的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/201
- 社区应急准备的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/qtx
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/e81
- 公共空间安全的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/098=vtq
- 青少年编程学习中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/pgp=329
- 就业技能培训的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/AMB=lWf
- 家庭阅读计划的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/577
- 人工智能科普的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/uzz
- 社区庭院绿化的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/ZSu
- 社区运动空间的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/627=tjz
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/ajc=809
- 社区公共议事的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E7%95%8C%E9%9D%A2%E6%B8%AF%E8%82%A1?/DGT=7PR
- 公共卫生宣传的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/350
- 城市博物馆服务的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/iwg
- 街道综合服务的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/Qdl
- 地方美食文化的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/222=ydj
- 健康步道使用的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/zpq=779
- 城市农夫市集的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%99%8E%E5%97%85%E7%A4%BE%E8%AE%BA?/3gU=IPv
- 智慧城市体验的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/652
- 城市微更新实践的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/egw
- 城市公共自行车的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/ew9
- 街道综合服务的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/972=zca
- 个人信息保护的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/jkp=596
- 数字阅读服务中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E7%95%8C%E9%9D%A2%E6%96%87%E6%91%98?/O5i=tGP
- 社区垃圾分类的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/809
- 校园节能行动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/jrt

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
