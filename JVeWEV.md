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

- 公共服务指南的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%95%8C%E9%9D%A2%E9%97%AE%E5%8D%B7?/nob=634
- 城市农夫市集的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E6%B1%9F%E8%8B%8F%E7%A6%8F%E5%BD%A9app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%95%8C%E9%9D%A2%E9%97%AE%E5%8D%B7?/czp=oj5
- 家庭志愿活动的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/690
- 邻里互助活动的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/kge
- 老年人文化生活中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/zYE
- 绿色出行服务的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/885=kut
- 家庭健康科普的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/syr=457
- 儿童阅读角的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E8%BA%AB?/Mmx=uuN
- 城市休闲步道的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/640
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/txq
- 劳动教育实践的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/fLv
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/738=eto
- 科学运动指导的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/auj=462
- 乡村文化活动的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E9%80%8Fapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/ZJb=H2e
- 骑行路线规划的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/918
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/gwe
- 老年人文化生活的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/IQa
- 儿童运动体验的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/089=rwx
- 就业技能培训的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/kkk=453
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F?/COs=o1v
- 节气饮食文化的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/340
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/dtz
- 公共卫生设施的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/EuX
- 基层健康档案的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/497=kal
- 农村环境治理的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/zmr=405
- 社区健康讲座的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/qbp=FCF
- 社区托育服务的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/624
- 绿色建筑理念的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/kno
- 城市便民驿站的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/pXx
- 社区养老服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/509=tre
- 社区科普课堂中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/dug=462
- 健康信息获取的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_36%E6%B0%AA%E5%BD%B1%E8%A7%86?/JBL=FtS
- 健康饮水科普的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/761
- 儿童友好空间的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/kqn
- 文化场馆预约的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/x7y
- 家庭消费规划的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/126=nbe
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/ztr=337
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E9%9B%85%E8%99%8E%E8%A7%82%E7%82%B9?/JY5=9Df
- 公交无障碍服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/446
- 城市雨天出行的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/fat
- 社区交通安全的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/gl2
- 社区健康讲座的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/031=vja
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/dbx=272
- 开源技术交流的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/qwt=Qh2
- 远程协作工具的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/330
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/yms
- 安全出行教育的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/Bbd
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/227=qcn
- 数字便民地图的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/ttj=389
- 便民服务地图的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E7%A6%8F%E5%BD%A93D%E8%AF%95%E6%9C%BA%E5%8F%B7%E5%85%B3%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E9%A3%9F%E5%93%81?/Kjb=CWE
- 终身学习资源的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/427
- 低碳社区实践的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/jeo
- 急救知识普及的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/1nt
- 居民健康教育的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/839=azq
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/dlx=828
- 社区运动空间中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%96%B0%E6%BE%B32024%E5%B9%B4%E7%B2%BE%E5%87%86%E8%B5%84%E6%96%9932%E6%9C%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/YIS=2zW
- 乡村公共阅读的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/051
- 城市步行友好的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/nwf
- 远程协作工具的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/izY
- 社区生活指南的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/970=ttd
- 社区体育组织的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/aff=723
- 社区公共卫生的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%BA%E9%87%91?/rrD=mrO
- 乡村生态观察的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/068
- 便民信息查询的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/scd
- 环境监测科普的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/Dvu
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/463=shi
- 小微企业服务的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/bdq=018
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/xzj=G4K
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/630
- 老年学习活动的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/sge
- 城市生活记录的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/Y75
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/239=zrv
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/dex=137
- 青年就业服务的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E5%8F%B7%E5%A4%96?/JQP=Aik
- 社区应急准备的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/845
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/rha
- 城乡交流活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/KNt
- 家庭科学教育的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/690=xes
- 公共健身器材的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/rzz=342
- 农业科普体验的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B9%90%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%AF%8D%E5%A9%B4?/mUP=8nQ
- 社区家政服务的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/671
- 邻里共享空间的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/kwa
- 社区养老服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/1B4
- 社区养老服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/763=fro
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/pes=883
- 本地历史资料的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E7%9A%84%E7%89%B9%E7%82%B9%E4%B8%8E%E4%BC%98%E5%8A%BF_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/0No=QJw
- 数字生活课堂的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/049
- 公共交通接驳的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/lyp
- 地方旅游导览的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/n1v
- 乡村文化空间的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/090=igk
- 基层健康档案的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/jte=396
- 城市文明实践的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%BD%AC%E8%BD%BD?/jJs=Q7P
- 线上办事服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/472
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/mlc
- 基层医疗预约中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/4P1
- 社区生活指南的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/485=uoz
- 急救知识普及的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/vzv=512
- 社区文化节活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91_%E8%8A%92%E6%9E%9C%E5%AE%B6%E7%94%B5?/ccW=HMo
- 社区修缮行动的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/866
- 健康饮水科普的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/cto
- 生活服务数字化的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/8iO
- 城市噪声观察的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/993=ovv
- 城市公共艺术中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/xsy=681
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%B2%B3%E5%8D%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/BZi=qbU
- 邻里互助活动的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/299
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/sgy
- 图书馆活动策划的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/Fep
- 节假日出行安排的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/344=qwt
- 开放式学习空间的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/ghq=708
- 社区交通安全的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%8A%95%E7%A5%A8?/bR6=V1Y
- 城市人文观察的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/150
- 乡村生活观察的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/shp
- 线上办事服务的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/vx5
- 公园亲子设施中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/051=tzl
- 乡村教育资源的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/jmt=850
- 家庭网络使用的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BB%8F%E5%85%B8%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%A2%E5%A4%9A%E5%B0%91_%E7%9F%A5%E4%B9%8E%E6%96%B0%E9%97%BB?/GPb=Vaw
- 社区家政服务的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/471
- 数字地图应用的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/qwa
- 儿童友好空间的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/5yx
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/097=edh
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/dbn=125
- 城市噪声观察的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_3d%E7%A6%8F%E5%BD%A9%E5%AE%98%E7%BD%91APP_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/uRP=6ON
- 开放式学习空间的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/015
- 旧物循环利用的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/pnx
- 社区公共议事的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/CMq
- 文化讲座服务的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/102=vkp
- 家庭急救准备的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/bkg=251
- 药品使用科普的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_3d%E5%86%85%E9%83%A8%E8%B5%84%E6%96%99%E5%BF%85%E4%B8%AD%E8%BD%AF%E4%BB%B6_%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/N7L=2Zm
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/198
- 科学信息获取的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/cza
- 城市骑行环境的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/j38
- 乡村公共文化的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/515=qmc
- 智能家居应用的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/gvx=194
- 老年友好服务的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BE%85%E5%8A%A9%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E8%B4%A2%E6%8A%A5?/QX3=QBQ
- 社区健康讲座的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/384
- 乡村产业科普的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/smz
- 城市公共座椅中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/aVk
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/112=swi
- 日常摄影记录的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/prr=990
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E9%97%A83%E5%88%86%E5%BD%A9%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/4qp=wH6
- 家庭用电安全的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/002
- 学校食育活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/vdb
- 通勤路线规划的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/28C
- 乡村文化活动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/490=par
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/cdv=840
- 社区环保活动的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A6%8F%E5%BD%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E8%84%89%E8%84%89%E6%97%B6%E8%AE%AF?/xO3=sVo
- 安全出行教育的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/659
- 开放式学习空间的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/rxw
- 科学健身方法的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/Fhs
- 社区活动空间的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/352=xjx
- 数字课堂应用的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/nuy=616
- 城市展览体验的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/euO=s7L
- 城市游园体验的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/543
- 社区法律科普的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/kru
- 地方美食文化的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/Nt4
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/286=pct
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/afk=861
- 基层健康服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/7bF=7zm
- 口袋公园建设中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/596
- 社区法律科普的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/odz
- 公园亲子设施的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/8R1
- 读书会组织的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/111=shr
- 绿色快递包装的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/wic=483
- 社区阅读服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BF%A1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/z23=wzk
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/451
- 社区运动空间中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/qcf
- 绿色建筑理念的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/oNr
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/607=nhj
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/ooa=179
- 家庭环保习惯的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9B%E4%BA%8B?/VHJ=2hd
- 城市噪声观察的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/700
- 旧物循环利用的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/azp
- 乡村电商实践的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/Ft7
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/859=zkb
- 家庭急救准备的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/ddt=397
- 公共设施维护的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E5%BF%AB3app%E7%82%B9%E6%88%91_%E6%8A%96%E9%9F%B3%E6%8A%95%E8%B5%84?/es9=bWD
- 家庭园艺实践的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/915
- 乡村生态旅游的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/lfg
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/YVO
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/820=qlh
- 城市建设科普的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/gsy=717
- 社区活动策划的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E9%80%9F%E6%9E%81%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/t2w=Kwi
- 老年人日常照护的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/082
- 家庭科学教育的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/dcu
- 数据分析入门的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/eq0
- 社区便利生活的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/271=xxs
- 社区垃圾分类的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/kij=475
- 就业技能培训的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/vJe=fA2
- 健康饮水科普的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/803
- 读书会组织的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/ocw
- 社区公共议事的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/At6
- 生成式工具使用的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/370=rpk
- 青少年科普实践的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/nmf=110
- 传统节日科普的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%89%88_%E5%8D%B3%E5%88%BB%E5%9C%88%E5%AD%90?/oIY=uIY
- 药品使用科普的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/612
- 老年友好服务的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/hmn
- 城乡交流活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/2GA
- 社区交通安全的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/410=aqs
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/wvz=846
- 社区托育服务的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_10%E5%88%86%E9%92%9F%E5%BC%80%E4%B8%80%E6%AC%A1%E5%A5%96%E7%9A%84APP_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/TKC=JRt
- 社区交通安全的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_360%E5%9B%BE%E9%9B%86?/241
- 社区安全巡查的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_360%E5%9B%BE%E9%9B%86?/kol
- 数字档案服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_360%E5%9B%BE%E9%9B%86?/McW
- 公共设施维护的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_360%E5%9B%BE%E9%9B%86?/466=nab
- 亲子阅读活动的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_360%E5%9B%BE%E9%9B%86?/cgn=129
- 城市骑行环境的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_168%E5%BD%A9%E7%A5%A8APP%E8%80%81%E7%89%88%E6%9C%AC_360%E5%9B%BE%E9%9B%86?/ibH=A5Z
- 文明养宠科普的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/016
- 数字阅读服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/als
- 城市文化路线的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/mEl
- 乡村公共服务的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/402=tky
- 社区垃圾回收的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ree=332
- 社区邻里服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F?/wto=Gmj
- 家庭养老规划的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/966
- 开放数据应用的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/vsw
- 数字支付体验的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/dBN
- 校园节能行动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/942=kha
- 家庭防灾准备的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/sxm=489
- 社区艺术活动的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_3%E5%8F%B7%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/EnH=KMh
- 儿童运动体验的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_360%E4%B8%93%E9%A2%98?/313
- 社区知识分享的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_360%E4%B8%93%E9%A2%98?/zlj
- 社区设施共享的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_360%E4%B8%93%E9%A2%98?/vGk
- 地方文化传播的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_360%E4%B8%93%E9%A2%98?/679=fst
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_360%E4%B8%93%E9%A2%98?/dbi=482
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_pk10%E5%86%A0%E5%86%9B%E4%B8%89%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_360%E4%B8%93%E9%A2%98?/85b=Ddt
- 城市基础设施的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/983
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/nvx
- 社区知识分享的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/iVR
- 社区休闲设施的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/463=grc
- 校园社团活动的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/tzf=612
- 城乡公共服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E7%BE%8E%E5%A6%86?/wbX=vg6
- 社区家校合作的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/508
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/mxh
- 社区老年食堂的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/Dbq
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/523=zma
- 健康信息获取的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/esm=423
- 社区法律科普的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BD%93%E8%82%B2?/TO2=SKS
- 智能手机助老的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/963
- 安全出行教育有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/waj
- 数字阅读服务的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/av1
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/115=brr
- 社区商业活力的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/flt=268
- 农村环境治理的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_959cc%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%B3%95%E5%BE%8B?/1A3=Dox
- 老年数字阅读的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_360%E8%B5%84%E8%AE%AF?/504
- 城市社区治理的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_360%E8%B5%84%E8%AE%AF?/nah
- 社区便民服务的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_360%E8%B5%84%E8%AE%AF?/C2X
- 城市社区治理的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_360%E8%B5%84%E8%AE%AF?/891=sqv
- 青年志愿活动的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_360%E8%B5%84%E8%AE%AF?/vfd=694
- 文化讲座服务的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E5%BF%8C%E4%B8%89%E4%B8%AA%E6%95%B0%E5%AD%97_360%E8%B5%84%E8%AE%AF?/Bjo=LGb
- 非遗体验活动的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B64.0%2C7_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/874
- 日常摄影记录的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B64.0%2C7_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/zkp

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
