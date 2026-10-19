# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 日常摄影记录的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B4%9F%E5%80%BA%E4%B8%8A%E5%B2%B8%E7%BE%A4_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/ItG
- 公共服务指南的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B4%9F%E5%80%BA%E4%B8%8A%E5%B2%B8%E7%BE%A4_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/137=xtk
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B4%9F%E5%80%BA%E4%B8%8A%E5%B2%B8%E7%BE%A4_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/mkk=020
- 基层健康档案的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E8%B4%9F%E5%80%BA%E4%B8%8A%E5%B2%B8%E7%BE%A4_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/lod=C9H
- 社区商业活力的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AF%84?/801
- 健康信息获取的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AF%84?/zle
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AF%84?/Ri5
- 城市农夫市集的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AF%84?/746=lvz
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AF%84?/nha=331
- 农产品消费体验的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%B6%E8%AF%84?/FIT=JpG
- 城乡交流活动的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E7%99%BC-%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/050
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E7%99%BC-%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/ngz
- 城市树木认养的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E7%99%BC-%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/bi1
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E7%99%BC-%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/246=aiy
- 软件开发学习的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E7%99%BC-%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/qve=705
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E7%99%BC-%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/7rc=NG1
- 数字便民地图的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BF%AB-%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/159
- 社区养老服务的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BF%AB-%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/gve
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BF%AB-%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/C9p
- 城市住房服务中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BF%AB-%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/699=byo
- 科学运动指导的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BF%AB-%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/bsr=840
- 社区邻里服务的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BF%AB-%E4%B8%80%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%89%8B%E8%AE%B0?/6Ck=wye
- 青少年科技社团的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/459
- 社区文化节活动的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/fec
- 公共场所导视的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/aKh
- 城市农夫市集的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/745=sci
- 城乡交流活动的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/qya=635
- 城乡公共服务的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%B8%89%E5%88%86%E5%BF%AB3%E6%9C%9F%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/3Ag=3KI
- 城市微更新实践的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%98%9F%E5%86%A0%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/549
- 老年人日常照护的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%98%9F%E5%86%A0%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/wzm
- 乡村教育资源的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%98%9F%E5%86%A0%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/Wnp
- 安全出行教育的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%98%9F%E5%86%A0%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/813=oyy
- 在线教育体验的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%98%9F%E5%86%A0%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/yhl=115
- 老年人文化生活的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E6%98%9F%E5%86%A0%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%88%AA%E7%A9%BA%E8%B4%A2%E7%BB%8F?/aZU=uA8
- 绿色消费选择的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E9%80%80%E4%BA%8C%E6%8C%82%E8%BF%9B%E4%B8%80%E5%80%8D%E6%8A%95%E6%B3%95_360%E5%88%B8%E5%95%86?/512
- 新能源知识普及的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E9%80%80%E4%BA%8C%E6%8C%82%E8%BF%9B%E4%B8%80%E5%80%8D%E6%8A%95%E6%B3%95_360%E5%88%B8%E5%95%86?/xfd
- 机器学习入门的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E9%80%80%E4%BA%8C%E6%8C%82%E8%BF%9B%E4%B8%80%E5%80%8D%E6%8A%95%E6%B3%95_360%E5%88%B8%E5%95%86?/VYO
- 儿童运动体验的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E9%80%80%E4%BA%8C%E6%8C%82%E8%BF%9B%E4%B8%80%E5%80%8D%E6%8A%95%E6%B3%95_360%E5%88%B8%E5%95%86?/031=uqh
- 城市博物馆服务的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E9%80%80%E4%BA%8C%E6%8C%82%E8%BF%9B%E4%B8%80%E5%80%8D%E6%8A%95%E6%B3%95_360%E5%88%B8%E5%95%86?/ayt=010
- 数字艺术创作的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%AD%E9%80%80%E4%BA%8C%E6%8C%82%E8%BF%9B%E4%B8%80%E5%80%8D%E6%8A%95%E6%B3%95_360%E5%88%B8%E5%95%86?/Tnk=F4G
- 乡村教育资源的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/136
- 健康信息获取的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/uco
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/ykV
- 个人时间管理中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/719=glf
- 社区安全巡查的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/cdu=670
- 志愿者培训交流的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/fzU=mRk
- 公共卫生设施的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E4%B8%80%E5%A4%A9%E8%B5%A23%E4%B8%87%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/860
- 社区公共卫生的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E4%B8%80%E5%A4%A9%E8%B5%A23%E4%B8%87%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/uuq
- 青少年科技社团的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E4%B8%80%E5%A4%A9%E8%B5%A23%E4%B8%87%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/ke1
- 节日文化体验的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E4%B8%80%E5%A4%A9%E8%B5%A23%E4%B8%87%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/983=kzt
- 儿童安全出行的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E4%B8%80%E5%A4%A9%E8%B5%A23%E4%B8%87%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/kwo=372
- 社区公共卫生的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E9%A3%9E%E8%89%87%E4%B8%80%E5%A4%A9%E8%B5%A23%E4%B8%87%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E6%8E%A2%E5%BA%97?/K7m=Fhr
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_360%E7%BE%8E%E5%A6%86?/688
- 社区活动策划的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_360%E7%BE%8E%E5%A6%86?/fco
- 社区艺术活动的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_360%E7%BE%8E%E5%A6%86?/SJ4
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_360%E7%BE%8E%E5%A6%86?/795=rsk
- 节能生活方式的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_360%E7%BE%8E%E5%A6%86?/bnn=290
- 儿童友好空间的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_360%E7%BE%8E%E5%A6%86?/ZMQ=TIY
- 城市公共自行车的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/647
- 本地消费场景的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/erp
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/DpB
- 社区应急准备的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/350=ovt
- 小区电梯维护的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/rod=381
- 社区快递服务的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E5%9B%BE_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/03t=DJq
- 家庭科学教育的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_360%E8%A7%86%E9%A2%91?/289
- 公共卫生设施的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_360%E8%A7%86%E9%A2%91?/qzl
- 机器人科普活动的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_360%E8%A7%86%E9%A2%91?/IpA
- 老年人出行服务的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_360%E8%A7%86%E9%A2%91?/179=kks
- 城市文化路线的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_360%E8%A7%86%E9%A2%91?/yxs=553
- 社区交通安全的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E5%9D%9A%E6%8C%8112%E6%9C%9F_360%E8%A7%86%E9%A2%91?/wwF=x14
- 城市文化路线的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/552
- 居家防滑改造的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/kae
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/wMV
- 网络信息辨识的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/201=son
- 电动汽车充电的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/kst=915
- 街道综合服务的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_1000%E6%9C%AC%E9%87%91%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/sgx=X3S
- 社区花园共建中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92%E5%80%8D%E6%8A%95%E5%8D%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/847
- 城市公共饮水的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92%E5%80%8D%E6%8A%95%E5%8D%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/cmw
- 校园安全教育的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92%E5%80%8D%E6%8A%95%E5%8D%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/jKl
- 社区慢性病防控的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92%E5%80%8D%E6%8A%95%E5%8D%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/586=sod
- 社区协商议事的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92%E5%80%8D%E6%8A%95%E5%8D%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/xey=727
- 地方旅游导览的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92%E5%80%8D%E6%8A%95%E5%8D%95_%E7%BD%91%E6%98%93%E6%94%BF%E5%8D%8F?/GfM=YlM
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A10%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/907
- 数字创意课程的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A10%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/vsd
- 城市噪声观察的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A10%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/Po7
- 文明养宠科普的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A10%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/599=elr
- 科学信息获取的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A10%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/cpk=632
- 节能生活方式的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A10%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/FOi=y8P
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%A4%A9%E8%B5%A2500%E8%BF%9E%E7%BB%AD800%E5%A4%A9%E7%BD%91%E8%B5%8C_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/085
- 城市应急广播的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%A4%A9%E8%B5%A2500%E8%BF%9E%E7%BB%AD800%E5%A4%A9%E7%BD%91%E8%B5%8C_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/ebm
- 学校食育活动的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%A4%A9%E8%B5%A2500%E8%BF%9E%E7%BB%AD800%E5%A4%A9%E7%BD%91%E8%B5%8C_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/16U
- 课后服务体验的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%A4%A9%E8%B5%A2500%E8%BF%9E%E7%BB%AD800%E5%A4%A9%E7%BD%91%E8%B5%8C_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/893=bqq
- 社区故事采集的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%A4%A9%E8%B5%A2500%E8%BF%9E%E7%BB%AD800%E5%A4%A9%E7%BD%91%E8%B5%8C_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/kns=828
- 开放式学习空间的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%A4%A9%E8%B5%A2500%E8%BF%9E%E7%BB%AD800%E5%A4%A9%E7%BD%91%E8%B5%8C_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/NhR=crp
- 家庭健康科普中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_2000%E5%9D%97%E6%9C%AC%E9%87%91%E8%A1%A5%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/385
- 城市文明实践的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_2000%E5%9D%97%E6%9C%AC%E9%87%91%E8%A1%A5%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/oax
- 地方旅游导览的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_2000%E5%9D%97%E6%9C%AC%E9%87%91%E8%A1%A5%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/VkX
- 乡村生活观察的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_2000%E5%9D%97%E6%9C%AC%E9%87%91%E8%A1%A5%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/309=eoo
- 数字便民地图的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_2000%E5%9D%97%E6%9C%AC%E9%87%91%E8%A1%A5%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/yqv=239
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_2000%E5%9D%97%E6%9C%AC%E9%87%91%E8%A1%A5%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%B8%E5%95%86?/6G1=wlK
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%8D%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/390
- 公共卫生设施的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%8D%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/qev
- 文明养宠科普的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%8D%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/vd7
- 社区读书角建设的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%8D%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/775=fep
- 城市应急广播的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%8D%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/auq=205
- 青年就业服务的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%8F%8D%E5%80%8D%E6%8A%95%E7%9A%84%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E5%91%A8%E6%8A%A5?/iHO=MWs
- 社会体育指导的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8D%E5%BE%97%E4%B8%8D%E7%9C%8B%E7%9A%84%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/195
- 网络安全教育的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8D%E5%BE%97%E4%B8%8D%E7%9C%8B%E7%9A%84%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/mij
- 老年数字阅读的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8D%E5%BE%97%E4%B8%8D%E7%9C%8B%E7%9A%84%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/Bd6
- 课后服务体验的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8D%E5%BE%97%E4%B8%8D%E7%9C%8B%E7%9A%84%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/367=uox
- 健康步道使用的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8D%E5%BE%97%E4%B8%8D%E7%9C%8B%E7%9A%84%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/ejh=914
- 城市慢跑路线的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8D%E5%BE%97%E4%B8%8D%E7%9C%8B%E7%9A%84%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/sBj=NE5
- 校园节能行动的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/284
- 科学教育活动的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/olw
- 社区休闲设施的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/9mR
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/804=jjv
- 数字支付体验的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/hcg=534
- 城市公共饮水的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%93%8D%E4%BD%9C%E7%9A%84_%E8%8A%92%E6%9E%9C%E6%B0%91%E7%94%9F?/ukD=215
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/417
- 传统节日科普的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/qit
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/FEB
- 家庭环保习惯的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/639=oiy
- 非遗体验活动中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/ocl=968
- 城市夜间照明的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E6%B3%95%E5%BE%8B?/qCY=O0y
- 社区交通安全的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8F%8D%E5%80%8D%E6%8A%95%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/872
- 城市公共空间的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8F%8D%E5%80%8D%E6%8A%95%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/suv
- 气象科普传播的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8F%8D%E5%80%8D%E6%8A%95%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/TWj
- 城市公共饮水中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8F%8D%E5%80%8D%E6%8A%95%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/764=ixd
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8F%8D%E5%80%8D%E6%8A%95%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/fif=890
- 亲子科普活动的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%8F%8D%E5%80%8D%E6%8A%95%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E4%BA%AC%E4%B8%9C%E6%9B%B2%E8%89%BA?/eBs=xce
- 小区电梯维护的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_360%E6%95%99%E8%82%B2?/431
- 街区小店体验的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_360%E6%95%99%E8%82%B2?/ksn
- 绿色消费选择中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_360%E6%95%99%E8%82%B2?/t0L
- 文化讲座服务的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_360%E6%95%99%E8%82%B2?/044=txh
- 光伏知识科普的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_360%E6%95%99%E8%82%B2?/mdz=054
- 在线学习体验的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_360%E6%95%99%E8%82%B2?/f9L=d4J
- 在线学习体验的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%9B%BE%E8%A7%A3%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/638
- 应急物资管理的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%9B%BE%E8%A7%A3%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/ufv
- 社区志愿服务的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%9B%BE%E8%A7%A3%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/UQN
- 城市地名文化的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%9B%BE%E8%A7%A3%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/397=oaj
- 城市生活记录的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%9B%BE%E8%A7%A3%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/lvt=961
- 乡村生态观察的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%9B%BE%E8%A7%A3%E4%B8%8D%E6%80%95%E8%BF%9E%E6%8C%82%E7%9A%84%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E6%97%85%E6%B8%B8?/eJ5=2ot
- 公园无障碍服务的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%8F%8D%E5%80%8D%E6%8A%95%E5%9B%BE%E8%A7%A3_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/918
- 校园阅读活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%8F%8D%E5%80%8D%E6%8A%95%E5%9B%BE%E8%A7%A3_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/xoq
- 日常摄影记录的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%8F%8D%E5%80%8D%E6%8A%95%E5%9B%BE%E8%A7%A3_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/yV5
- 社区养老服务的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%8F%8D%E5%80%8D%E6%8A%95%E5%9B%BE%E8%A7%A3_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/187=tro
- 数字便民地图的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%8F%8D%E5%80%8D%E6%8A%95%E5%9B%BE%E8%A7%A3_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/pel=874
- 城市地名文化的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%8F%8D%E5%80%8D%E6%8A%95%E5%9B%BE%E8%A7%A3_%E4%BC%98%E9%85%B7%E8%83%BD%E6%BA%90?/sER=ITU
- 老年数字阅读的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/930
- 智能家居应用的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/kvu
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/tG5
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/921=nhi
- 公园休闲体验的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/cuq=733
- 家庭消费规划的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/BUB=DSB
- 公园休闲体验的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/300
- 老年数字阅读的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/red
- 就业技能培训的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/tpC
- 光伏知识科普的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/772=csq
- 绿色快递包装的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/pfx=054
- 节气饮食文化的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%B3%95%E5%AE%9E%E6%88%98_%E6%96%B0%E6%B5%AA%E4%BF%A1%E6%89%98?/pAq=0x6
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%88%B7%E6%B5%81%E6%B0%B4%E8%96%85%E7%BE%8A%E6%AF%9B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/848
- 基层服务创新的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%88%B7%E6%B5%81%E6%B0%B4%E8%96%85%E7%BE%8A%E6%AF%9B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/qzb
- 社区活动报名的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%88%B7%E6%B5%81%E6%B0%B4%E8%96%85%E7%BE%8A%E6%AF%9B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/m35
- 家庭志愿活动的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%88%B7%E6%B5%81%E6%B0%B4%E8%96%85%E7%BE%8A%E6%AF%9B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/339=eir
- 无障碍信息设计的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%88%B7%E6%B5%81%E6%B0%B4%E8%96%85%E7%BE%8A%E6%AF%9B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/hko=106
- 社区应急准备的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%88%B7%E6%B5%81%E6%B0%B4%E8%96%85%E7%BE%8A%E6%AF%9B%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BF%E8%B0%88?/u8U=34Z
- 社区修缮行动的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%95%99%E4%BD%A0%E4%B8%80%E4%B8%AA%E9%80%A2%E8%B5%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%8A%9E%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/885
- 社区安全巡查的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%95%99%E4%BD%A0%E4%B8%80%E4%B8%AA%E9%80%A2%E8%B5%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%8A%9E%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/kje
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%95%99%E4%BD%A0%E4%B8%80%E4%B8%AA%E9%80%A2%E8%B5%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%8A%9E%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/84h
- 校园节能行动的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%95%99%E4%BD%A0%E4%B8%80%E4%B8%AA%E9%80%A2%E8%B5%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%8A%9E%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/770=mih
- 户外活动组织的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%95%99%E4%BD%A0%E4%B8%80%E4%B8%AA%E9%80%A2%E8%B5%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%8A%9E%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/reb=221
- 社区便民集市的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E6%95%99%E4%BD%A0%E4%B8%80%E4%B8%AA%E9%80%A2%E8%B5%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%8A%9E%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/onA=ve4
- 社区科普课堂的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%8D%81%E8%B5%8C%E4%B9%9D%E8%B5%A2%E7%9A%84%E5%B0%8F%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/176
- 城市体育设施的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%8D%81%E8%B5%8C%E4%B9%9D%E8%B5%A2%E7%9A%84%E5%B0%8F%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/esb
- 社区共享书架的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%8D%81%E8%B5%8C%E4%B9%9D%E8%B5%A2%E7%9A%84%E5%B0%8F%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/BkW
- 农业科普体验的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%8D%81%E8%B5%8C%E4%B9%9D%E8%B5%A2%E7%9A%84%E5%B0%8F%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/238=fhz
- 农业科普体验的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%8D%81%E8%B5%8C%E4%B9%9D%E8%B5%A2%E7%9A%84%E5%B0%8F%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/dcl=272
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%8D%81%E8%B5%8C%E4%B9%9D%E8%B5%A2%E7%9A%84%E5%B0%8F%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E5%BD%B1%E8%A7%86?/CmK=cxM
- 数字设备回收的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E4%B8%AD%E5%A4%A7%E4%BA%8E%E6%8C%82%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/154
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E4%B8%AD%E5%A4%A7%E4%BA%8E%E6%8C%82%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/mku
- 青年就业服务的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E4%B8%AD%E5%A4%A7%E4%BA%8E%E6%8C%82%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/Qjq
- 社区养老服务的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E4%B8%AD%E5%A4%A7%E4%BA%8E%E6%8C%82%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/084=krn
- 健康饮水科普的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E4%B8%AD%E5%A4%A7%E4%BA%8E%E6%8C%82%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/ucl=643
- 基层健康服务的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E4%B8%AD%E5%A4%A7%E4%BA%8E%E6%8C%82%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%A7%82%E7%82%B9?/b3M=QkT
- 社区邻里服务中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B0%B8%E4%B8%8D%E8%BE%93%E7%9A%845%E5%80%8D%E6%8A%95%E6%B3%95%E6%8A%80%E5%B7%A7%E4%B8%8E%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/642
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B0%B8%E4%B8%8D%E8%BE%93%E7%9A%845%E5%80%8D%E6%8A%95%E6%B3%95%E6%8A%80%E5%B7%A7%E4%B8%8E%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/byo
- 城市地名文化的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B0%B8%E4%B8%8D%E8%BE%93%E7%9A%845%E5%80%8D%E6%8A%95%E6%B3%95%E6%8A%80%E5%B7%A7%E4%B8%8E%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/dKU
- 社区科普课堂的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B0%B8%E4%B8%8D%E8%BE%93%E7%9A%845%E5%80%8D%E6%8A%95%E6%B3%95%E6%8A%80%E5%B7%A7%E4%B8%8E%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/222=srv
- 数字素养提升的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B0%B8%E4%B8%8D%E8%BE%93%E7%9A%845%E5%80%8D%E6%8A%95%E6%B3%95%E6%8A%80%E5%B7%A7%E4%B8%8E%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/nka=386
- 公共场馆服务的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B0%B8%E4%B8%8D%E8%BE%93%E7%9A%845%E5%80%8D%E6%8A%95%E6%B3%95%E6%8A%80%E5%B7%A7%E4%B8%8E%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E5%A4%B4%E6%9D%A1%E5%9F%BA%E9%87%91?/EBD=vQw
- 文化讲座服务的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E6%98%AF%E6%9C%80%E6%84%9A%E8%A0%A2%E7%9A%84%E6%96%B9%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/199
- 信息无障碍体验的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E6%98%AF%E6%9C%80%E6%84%9A%E8%A0%A2%E7%9A%84%E6%96%B9%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/zww
- 城市建设科普的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E6%98%AF%E6%9C%80%E6%84%9A%E8%A0%A2%E7%9A%84%E6%96%B9%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/GXA
- 药品使用科普的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E6%98%AF%E6%9C%80%E6%84%9A%E8%A0%A2%E7%9A%84%E6%96%B9%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/196=kma
- 青少年心理健康的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E6%98%AF%E6%9C%80%E6%84%9A%E8%A0%A2%E7%9A%84%E6%96%B9%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/snu=760
- 社区共享书架的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E6%98%AF%E6%9C%80%E6%84%9A%E8%A0%A2%E7%9A%84%E6%96%B9%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/mya=6ZC
- 社区家政服务的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_100%E8%B5%B7%E6%AD%A512%E6%9C%9F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/665
- 乡村教育资源的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_100%E8%B5%B7%E6%AD%A512%E6%9C%9F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/uwl
- 医院导诊服务的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_100%E8%B5%B7%E6%AD%A512%E6%9C%9F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/92q
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_100%E8%B5%B7%E6%AD%A512%E6%9C%9F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/228=nea
- 社区花园共建的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_100%E8%B5%B7%E6%AD%A512%E6%9C%9F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/pmt=709
- 口袋公园建设的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_100%E8%B5%B7%E6%AD%A512%E6%9C%9F%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/8re=ThV
- 智能手机助老的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%AF%8F%E5%A4%A9%E4%B9%B0%E7%BB%84%E5%85%AD%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/546
- 生活服务数字化的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%AF%8F%E5%A4%A9%E4%B9%B0%E7%BB%84%E5%85%AD%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/jpw
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%AF%8F%E5%A4%A9%E4%B9%B0%E7%BB%84%E5%85%AD%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/bl5
- 社区绿色空间的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%AF%8F%E5%A4%A9%E4%B9%B0%E7%BB%84%E5%85%AD%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/628=kda
- 街区小店体验的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%AF%8F%E5%A4%A9%E4%B9%B0%E7%BB%84%E5%85%AD%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/tgo=713
- 城乡公共服务的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%AF%8F%E5%A4%A9%E4%B9%B0%E7%BB%84%E5%85%AD%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E9%9B%85%E8%99%8E%E4%BA%BA%E7%89%A9?/uTM=VKz
- 社区消防演练的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E7%89%87_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/304
- 休闲运动入门的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E7%89%87_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/diu
- 城市公共艺术的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E7%89%87_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/IYS
- 数字支付体验的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E7%89%87_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/904=gqr
- 社区健康讲座的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E7%89%87_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/aak=347
- 家庭科学教育的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E7%89%87_%E8%8A%92%E6%9E%9C%E5%8E%86%E5%8F%B2?/UeE=Kaj
- 家庭照护支持的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/454
- 生活垃圾减量的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/vct
- 农村环境治理的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/uea
- 便民服务地图的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/412=ava
- 开放数据应用的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/vgq=328
- 小区停车协商的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/O3z=4mB
- 乡村公共阅读的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/911
- 城市夜间照明的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/bij
- 公共服务指南的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/kiA
- 劳动教育实践的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/519=roa
- 社区老年食堂的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/tjd=986
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_1000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E7%89%87_%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1?/VIL=bYT
- 青少年科普实践的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E8%B5%8C%E6%98%AF%E7%82%B9%E6%9D%80%E8%BF%98%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/979
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E8%B5%8C%E6%98%AF%E7%82%B9%E6%9D%80%E8%BF%98%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/ans
- 旧物循环利用的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E8%B5%8C%E6%98%AF%E7%82%B9%E6%9D%80%E8%BF%98%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/pS4
- 社区快递服务的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E8%B5%8C%E6%98%AF%E7%82%B9%E6%9D%80%E8%BF%98%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/459=sdu
- 生活垃圾减量的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E8%B5%8C%E6%98%AF%E7%82%B9%E6%9D%80%E8%BF%98%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/csj=609
- 城市应急广播中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%BD%91%E8%B5%8C%E6%98%AF%E7%82%B9%E6%9D%80%E8%BF%98%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F_%E8%99%8E%E6%89%91%E6%97%B6%E8%AE%AF?/3jR=GZZ
- 街区绿化养护的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E6%B3%95%E5%BE%8B?/748
- 基层健康服务的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E6%B3%95%E5%BE%8B?/vpp
- 环境监测科普的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E6%B3%95%E5%BE%8B?/uVB
- 新能源知识普及的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E6%B3%95%E5%BE%8B?/631=rkf
- 小微企业服务的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E6%B3%95%E5%BE%8B?/ytm=617
- 文化场馆预约的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%8D%83%E6%9C%AC%E9%87%91%E5%81%9A12%E6%9C%9F%E5%80%8D%E6%8A%95%E5%9B%BE%E5%85%AC%E5%BC%8F_360%E6%B3%95%E5%BE%8B?/y3W=Nbq
- 城市夜间照明的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_90%E5%90%8E%E5%88%A9%E7%94%A8Ag%E6%8A%80%E5%B7%A7%E8%B5%A2%E4%BA%86%E5%87%A0%E5%8D%83%E4%B8%87_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/598
- 数字支付体验的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_90%E5%90%8E%E5%88%A9%E7%94%A8Ag%E6%8A%80%E5%B7%A7%E8%B5%A2%E4%BA%86%E5%87%A0%E5%8D%83%E4%B8%87_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/phb
- 便民服务窗口的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_90%E5%90%8E%E5%88%A9%E7%94%A8Ag%E6%8A%80%E5%B7%A7%E8%B5%A2%E4%BA%86%E5%87%A0%E5%8D%83%E4%B8%87_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/dZX
- 青少年科技社团的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_90%E5%90%8E%E5%88%A9%E7%94%A8Ag%E6%8A%80%E5%B7%A7%E8%B5%A2%E4%BA%86%E5%87%A0%E5%8D%83%E4%B8%87_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/287=agz
- 城市应急广播的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_90%E5%90%8E%E5%88%A9%E7%94%A8Ag%E6%8A%80%E5%B7%A7%E8%B5%A2%E4%BA%86%E5%87%A0%E5%8D%83%E4%B8%87_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/tvk=906
- 终身学习资源的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_90%E5%90%8E%E5%88%A9%E7%94%A8Ag%E6%8A%80%E5%B7%A7%E8%B5%A2%E4%BA%86%E5%87%A0%E5%8D%83%E4%B8%87_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/hXr=izT
- 健康饮水科普从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%923000%E5%85%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/184
- 社区活动空间的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%923000%E5%85%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/ocn
- 智慧停车服务的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%923000%E5%85%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/Y5c
- 文化场馆预约的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%923000%E5%85%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/393=pkq
- 城市水环境观察的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%923000%E5%85%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/dhn=683
- 在线学习体验的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_12%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%923000%E5%85%83_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/JRG=1eK

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
