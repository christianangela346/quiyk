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

- 节能生活方式的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ksn=275
- 城市文明出行的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/zFw=8Wk
- 社区读书角建设的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/296
- 生活垃圾减量的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/tez
- 数字便民地图的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/POB
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/101=gbh
- 生活服务数字化的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/yoj=108
- 社区知识分享的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%E5%A4%A7%E5%85%A8_%E8%B0%B7%E6%AD%8C%E6%94%BF%E5%8D%8F?/RPm=l6M
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8%E6%80%A7%E8%A7%A3%E6%9E%90_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/830
- 小区停车协商的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8%E6%80%A7%E8%A7%A3%E6%9E%90_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/buo
- 节能生活方式的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8%E6%80%A7%E8%A7%A3%E6%9E%90_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/9le
- 城市公共标识的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8%E6%80%A7%E8%A7%A3%E6%9E%90_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/881=dmb
- 家庭消费规划的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8%E6%80%A7%E8%A7%A3%E6%9E%90_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/mec=590
- 口袋公园建设的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%85%A8%E6%80%A7%E8%A7%A3%E6%9E%90_%E7%BD%91%E6%98%93%E6%88%BF%E4%BA%A7?/FEh=e0M
- 科学健身方法的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%8E%A8%E8%8D%90_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/034
- 公共空间照明的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%8E%A8%E8%8D%90_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/qpg
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%8E%A8%E8%8D%90_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/Y4b
- 本地旅行体验的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%8E%A8%E8%8D%90_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/802=vgc
- 家庭养老规划的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%8E%A8%E8%8D%90_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/qkh=539
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E6%8E%A8%E8%8D%90_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/TBe=v4T
- 便民信息查询的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E6%90%9C%E7%8B%90%E4%BA%B2%E5%AD%90?/395
- 城市人文观察的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E6%90%9C%E7%8B%90%E4%BA%B2%E5%AD%90?/ney
- 线上办事服务的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E6%90%9C%E7%8B%90%E4%BA%B2%E5%AD%90?/Drw
- 药品使用科普的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E6%90%9C%E7%8B%90%E4%BA%B2%E5%AD%90?/984=ema
- 公共服务评价从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E6%90%9C%E7%8B%90%E4%BA%B2%E5%AD%90?/qlq=706
- 城乡公共服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%BD%AF%E4%BB%B6%E5%8A%A9%E6%89%8B_%E6%90%9C%E7%8B%90%E4%BA%B2%E5%AD%90?/yDg=s0u
- 数字档案服务的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/986
- 便民服务窗口的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/arb
- 口袋公园建设的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/6mg
- 生活垃圾回收的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/295=bri
- 家庭健康管理中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/jtk=905
- 乡村阅读空间的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/iFE=fQL
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/515
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/xuo
- 数字设备回收的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/s0W
- 数字档案服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/954=qhr
- 绿色快递包装的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/sfz=949
- 邻里共享空间的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/Lm3=PQi
- 急救知识普及的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/105
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/fvz
- 数字地图应用的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/8U2
- 运动安全知识的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/289=uap
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/mvg=594
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/lir=nEG
- 城市文明实践的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/656
- 地方旅游导览的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/bfb
- 终身学习资源的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/DQo
- 家庭科学教育的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/113=aoo
- 社区故事采集的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/qus=821
- 社区活动空间的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/KT0=Ey0
- 城市生活记录的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/035
- 老年学习活动的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/vps
- 社区心理支持的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/JH6
- 社区便民服务的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/635=cir
- 节日文化体验的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/rmi=934
- 数字支付体验的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E8%AE%B2%E5%9D%9B?/ge1=qrd
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/457
- 儿童运动体验的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/vlc
- 邻里互助活动的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/SlX
- 绿色办公实践的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/448=srb
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/sez=376
- 人工智能科普的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/lI6=QNc
- 城市绿色交通的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9VI%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/505
- 公共健身器材的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9VI%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/nvj
- 线上办事服务的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9VI%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/97M
- 科学健身方法的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9VI%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/362=yvs
- 公园亲子设施的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9VI%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/ikd=676
- 消防知识宣传的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9VI%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/lKJ=edR
- 公共空间照明的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%85%AC%E5%8F%B8_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/378
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%85%AC%E5%8F%B8_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/jzs
- 城市公共饮水的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%85%AC%E5%8F%B8_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/pLH
- 家庭安全提示的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%85%AC%E5%8F%B8_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/589=uku
- 数字学习资源的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%85%AC%E5%8F%B8_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/aqp=835
- 便民维修服务的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%85%AC%E5%8F%B8_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/iDK=Y7j
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%A4%A7%E6%8F%AD%E7%A7%98_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/819
- 城市可持续生活的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%A4%A7%E6%8F%AD%E7%A7%98_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/vwt
- 社区生活指南的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%A4%A7%E6%8F%AD%E7%A7%98_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/b5N
- 城市公共标识的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%A4%A7%E6%8F%AD%E7%A7%98_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/870=ywq
- 环境教育课程的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%A4%A7%E6%8F%AD%E7%A7%98_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/cmz=185
- 青少年科普实践的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99%E5%A4%A7%E6%8F%AD%E7%A7%98_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/ytZ=iSk
- 个人时间管理的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/448
- 社区公共卫生的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/oms
- 文化讲座服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/uih
- 课后服务体验的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/983=fiv
- 社区科普课堂的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/axg=234
- 机器人科普活动的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/Fa6=eXx
- 周末休闲规划的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/521
- 乡村生活观察的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/hom
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/2nt
- 社区环保活动的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/037=yqp
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/kon=703
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E5%81%A5%E5%BA%B7?/krU=Dyc
- 家庭节能设备的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/423
- 地方文化传播的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/ldy
- 社区体育组织的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/rcf
- 农业科普体验的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/507=wll
- 本地历史资料的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/vej=803
- 城市休闲步道的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_168%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B3%95%E5%BE%8B?/SlR=mZZ
- 图书借阅体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/806
- 科学观察活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/jqt
- 开源技术交流的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/CCS
- 小区电梯维护的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/353=wxu
- 个人信息保护的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/yqh=635
- 科学健身方法的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%85%8D%E8%B4%B9168%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E9%A2%98?/h0I=gfz
- 家庭健康管理的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BE%A4_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/104
- 城市展览体验的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BE%A4_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/cgj
- 灵活就业交流中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BE%A4_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/apu
- 城市树木认养的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BE%A4_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/790=maz
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BE%A4_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/kin=585
- 乡村产业科普的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E7%BE%A4_%E8%B1%86%E7%93%A3%E4%B8%93%E9%A2%98?/ygT=WTc
- 本地旅行体验的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/770
- 乡村生态旅游的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/fej
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/zhq
- 骑行路线规划的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/053=chk
- 公共服务预约的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/ltk=392
- 市民意见收集的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E4%B9%A6?/mqM=bYs
- 城市骑行环境中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/068
- 社会体育指导的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/lmn
- 科学观察活动的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/h3m
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/411=mlp
- 校园社团活动的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/kjo=707
- 社区手工活动的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_168%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E5%8D%8F?/ZKz=mEH
- 社区学习活动的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/809
- 公共服务评价的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/hxt
- 城市可持续生活的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/tsS
- 网络安全教育的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/465=jtw
- 公共交通信息服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/nmn=369
- 口袋公园建设的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9_%E5%BE%97%E7%89%A9%E6%99%A8%E6%8A%A5?/F3Q=0TE
- 数字公共文化的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/423
- 智慧城市体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/qsn
- 社区教育资源的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/JVp
- 便民信息查询的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/671=wnb
- 公共空间照明的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/sao=140
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%BD%91%E7%AB%99%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E6%B1%BD%E8%BD%A6?/TU4=KnO
- 儿童户外活动的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/882
- 灵活就业交流的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/rgc
- 数字设备回收的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/0If
- 志愿服务平台的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/935=hzr
- 街道综合服务的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/hiq=457
- 城市骑行环境的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BE%8E%E5%A6%86?/sBg=9Nc
- 社区文化节活动的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/093
- 终身学习资源的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/kop
- 图书借阅体验的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/5iJ
- 节约用水实践的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/465=cre
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/slq=651
- 社区便利生活的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/Las=aUZ
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/732
- 家庭健康管理的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/axy
- 老年运动活动的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/IWP
- 社区环保活动的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/767=cnp
- 公共场馆服务的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/xcy=589
- 家庭急救准备的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/0lB=GNn
- 社区志愿服务的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/530
- 科普展览体验的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/onl
- 线上阅读资源的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/8Y2
- 公园亲子设施的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/082=wdl
- 医院导诊服务的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/zwq=667
- 线上办事服务的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/rO7=nfd
- 城市基础设施的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/658
- 乡村产业科普的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/buw
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/5FO
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/137=lxk
- 开放式学习空间的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/det=763
- 科普展览体验的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/W9l=Gag
- 校园社团活动中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/226
- 公共服务预约的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/iut
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/1Vc
- 数字便民地图的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/554=mdg
- 校园节能行动中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/nwi=597
- 居家防滑改造的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%82%A1%E7%A5%A8?/d3g=Wr1
- 公共卫生宣传的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/594
- 社区活动报名的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/pht
- 绿色快递包装中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/EmZ
- 社区知识分享的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/312=emd
- 城市步行环境的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/fix=573
- 社区交通安全的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E7%90%86%E8%B4%A2?/yLl=mZS
- 口袋公园建设的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%87%BA%E5%8F%B7_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/048
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%87%BA%E5%8F%B7_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/jdj
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%87%BA%E5%8F%B7_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/CEC
- 老年友好服务的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%87%BA%E5%8F%B7_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/402=tzd
- 街头绿植养护的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%87%BA%E5%8F%B7_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/mgr=266
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E5%87%BA%E5%8F%B7_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Fh7=7Xw
- 城市住房服务的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/990
- 社区绿色空间的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/wiw
- 数字学习资源的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/fHy
- 青少年心理健康的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/626=gtu
- 应急物资管理的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/ugg=954
- 社区庭院绿化的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E5%9B%AD%E8%89%BA?/dxY=O1a
- 旧物循环利用的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/680
- 城市基础设施的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/ikt
- 节日文化体验的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/ncg
- 个人信息保护的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/046=gma
- 青少年编程学习的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/tfn=051
- 通勤路线规划的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/Mkg=Hnp
- 基层健康档案的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/538
- 公共空间休憩的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/moa
- 城市便民驿站的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/fDV
- 邻里共享空间的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/524=sop
- 社区儿童活动的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/xnw=675
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/yvJ=6HR
- 电动汽车充电的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/677
- 全民阅读推广的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/qtu
- 机器学习入门的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/70q
- 社区文化传播的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/665=zmt
- 应急物资管理的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/qie=582
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1_%E7%BD%91%E6%98%93%E6%B8%B8%E6%88%8F?/CYf=KmL
- 公共健身器材的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/723
- 公共空间休憩的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/gep
- 城市夜间照明的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/KPB
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/717=erl
- 小区停车协商的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/vri=991
- 乡村电商实践的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F_%E5%A4%AE%E8%A7%86%E5%A4%B4%E6%9D%A1?/YNP=0ms
- 节日文化体验的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%83%B3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/484
- 光伏知识科普的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%83%B3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/uqu
- 城市应急科普的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%83%B3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/u5G
- 就业技能培训的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%83%B3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/683=nbc
- 城市游园体验的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%83%B3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/syg=836
- 居家防滑改造的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E6%83%B3%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E5%9C%A8%E5%93%AA%E9%87%8C%E6%89%BE_%E8%8A%92%E6%9E%9C%E7%BE%8E%E8%82%A1?/sV7=2jH
- 非遗体验活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9F%B9%E6%8A%95_360%E7%9B%B4%E6%92%AD?/364
- 社区应急准备的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9F%B9%E6%8A%95_360%E7%9B%B4%E6%92%AD?/qll
- 个人时间管理的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9F%B9%E6%8A%95_360%E7%9B%B4%E6%92%AD?/lQO
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9F%B9%E6%8A%95_360%E7%9B%B4%E6%92%AD?/516=edp
- 公共服务沟通的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9F%B9%E6%8A%95_360%E7%9B%B4%E6%92%AD?/mae=431
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9F%B9%E6%8A%95_360%E7%9B%B4%E6%92%AD?/p9x=LnN
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%B8%A6%E8%B5%9A_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/449
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%B8%A6%E8%B5%9A_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/uhs
- 儿童友好空间的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%B8%A6%E8%B5%9A_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/HmK
- 文化讲座服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%B8%A6%E8%B5%9A_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/269=wdh
- 街区绿化养护的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%B8%A6%E8%B5%9A_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/jog=793
- 信息无障碍体验的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%B8%A6%E8%B5%9A_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/NiY=teu
- 环境教育课程的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/793
- 街区更新实践的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/hlk
- 居家防滑改造的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/Rrf
- 便民服务窗口的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/362=bpc
- 创业经验分享中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/pjy=047
- 家庭安全提示的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%95%B0%E7%A0%81?/lOs=wcs
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/772
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/eio
- 社区花园共建的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/8mT
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/141=fwy
- 城乡交流活动从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/whu=937
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/Tmy=J7j
- 社区便利生活的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/473
- 科学信息获取的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/cjo
- 节假日出行安排的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/DQP
- 社区心理支持的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/213=lco
- 街道综合服务的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/icb=176
- 街区道路维护的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%8A%A5%E9%81%93?/yGV=KS2
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E8%83%BD%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E7%9A%84%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%88%8A%E7%99%BB?/188
- 地方戏曲体验的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E8%83%BD%E7%A8%B3%E5%AE%9A%E8%B5%9A%E9%92%B1%E7%9A%84%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%88%8A%E7%99%BB?/pgu

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
