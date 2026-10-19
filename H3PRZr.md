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

- 乡村公共文化的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E5%B8%88%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/450
- 小区停车协商的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E5%B8%88%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/yxd
- 老年友好服务的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E5%B8%88%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/Eub
- 社区商业活力的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E5%B8%88%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/678=mqf
- 志愿服务平台的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E5%B8%88%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/min=333
- 个人信息保护的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%81%E5%B8%88%E5%B8%A6%E6%89%93%E5%BD%A9%E7%A5%A8%E5%8F%AF%E9%9D%A0%E5%90%97_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/B8R=tNh
- 公共空间休憩的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/222
- 公共服务咨询的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/aoy
- 老旧小区改造的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/TUC
- 新能源知识普及的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/788=sil
- 口袋公园建设的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/dpc=077
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E8%85%BE%E8%AE%AF%E5%81%A5%E5%BA%B7?/xuZ=9am
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/105
- 生活垃圾减量的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/uml
- 安全出行教育的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/HdC
- 公共服务咨询的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/524=rat
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/icl=323
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B1%86%E7%93%A3%E5%81%A5%E8%BA%AB?/s5b=TRQ
- 乡村公共阅读的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/984
- 社区家校合作中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/qbp
- 个人数据管理的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/RQV
- 社区知识分享的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/539=ucq
- 数据分析入门的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/hzy=233
- 公共空间安全的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E4%B8%93%E6%A0%8F?/q81=Bi3
- 家庭志愿活动的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/539
- 街道综合服务的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/qar
- 社区花园共建的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/3G6
- 绿色快递包装的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/589=xnp
- 乡村公共阅读的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/crc=572
- 绿色办公实践的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/C32=R6P
- 家庭环保行动的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_50%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/859
- 便民信息查询的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_50%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/tqn
- 城市基础设施的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_50%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/b87
- 家庭环保行动的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_50%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/484=mum
- 社区花园共建的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_50%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/oxu=934
- 城市步行友好的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_50%E6%9C%AC%E9%87%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E8%B5%9A_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/h6V=XZ8
- 终身学习资源的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/116
- 城市共享单车的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/bil
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/kJ6
- 居家适老化改造的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/662=guh
- 数字课堂应用的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/mrr=374
- 志愿者培训交流的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E4%BA%A7?/eME=Jcr
- 社区环保活动的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/196
- 街区道路维护中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/ztw
- 家庭饮食安排的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/kPw
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/406=wit
- 开源技术交流的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/ehq=583
- 居民健康教育的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E6%9C%80%E6%9C%89%E5%AE%9E%E5%8A%9B%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/sh2=5uB
- 乡村公共阅读的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/552
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/hef
- 数字资源检索的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/nDb
- 社区花园共建的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/266=ohy
- 文化场馆预约的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/eme=167
- 社区消防演练的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E8%84%89%E8%84%89%E8%BD%AC%E8%BD%BD?/caj=grm
- 智能家居应用中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/051
- 节气饮食文化的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/tzy
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/MwN
- 户外活动组织的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/975=qgi
- 家庭急救准备的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/idn=313
- 社区公共卫生的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E4%B8%93%E4%B8%9A%E5%9B%9E%E8%A1%80%E5%B8%A6%E4%B8%8A%E5%B2%B8%E5%AF%BC%E5%B8%88QQ_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/zsA=rbG
- 智能手机助老的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/430
- 科普展览体验的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/vfu
- 数字便民地图的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/JpM
- 数字政务体验的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/115=uwm
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/tnw=319
- 小区公共照明的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_1%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%97%B6%E6%8A%A5?/j0s=NxO
- 乡村生态观察的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/529
- 基层服务创新的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/igw
- 家庭健康管理的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/89W
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/966=ssd
- 家庭志愿活动的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/ixm=286
- 城市绿色交通的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E5%BE%AE%E4%BF%A1_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/sqf=Cad
- 便民维修服务的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/644
- 社区安全巡查的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/dvt
- 周末休闲规划的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/Q02
- 社区消防演练的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/085=svu
- 社区教育资源的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/oph=143
- 青少年户外教育的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9A%E8%AE%A1%E5%88%92%E7%BE%A4%E8%B7%9F%E7%9D%80%E5%AF%BC%E5%B8%88%E8%B5%B0_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/OhE=Kus
- 老年人出行服务的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/626
- 社区生活指南的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/bcd
- 社区公共议事的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/HBc
- 数字学习资源的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/464=nlf
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/jmr=779
- 街区更新实践的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88_%E9%A9%AC%E6%9D%A5%E8%B4%A2%E7%BB%8F?/e14=DiD
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/312
- 新能源出行的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/qzx
- 社区停车服务的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/N9x
- 社区故事采集的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/573=pfd
- 科学信息获取中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/vrq=217
- 居家防滑改造中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC%E7%9B%88%E5%88%A9_%E8%B1%86%E7%93%A3%E5%8D%83%E5%B8%86?/Ptd=CGA
- 校园安全教育的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/181
- 学校食育活动中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/fex
- 运动安全知识的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/ZKx
- 公共交通接驳的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/065=aea
- 老年人文化生活的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/wwl=527
- 公共服务预约的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%AE%9E%E5%BD%95?/0lD=5K2
- 社区垃圾分类的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/485
- 创业经验分享的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/kwi
- 节假日出行安排的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/gL9
- 社区交通安全的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/622=eou
- 科普展览体验的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/yui=996
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/lmz=dhu
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/967
- 乡村公共服务的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/pfh
- 学校体育活动的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/Pr4
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/346=opr
- 城市地名文化的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/kjc=800
- 城市可持续生活的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E9%A1%BA%E4%B8%B0%E6%BC%AB%E8%AF%84?/Esh=NQz
- 小微企业服务的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/607
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/spy
- 本地历史资料的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/dHC
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/457=aeq
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/llf=477
- 地方旅游导览的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/knB=R4w
- 气象科普传播的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/379
- 人工智能科普的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/srz
- 社区知识分享的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/Znc
- 城市生活服务的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/241=zww
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/xeb=050
- 街头绿植养护的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%87%A4%E5%87%B0%E7%9B%B4%E6%92%AD?/lqf=mzB
- 青少年心理健康的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/346
- 城市公共艺术的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/ppa
- 软件开发学习的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/LA2
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/382=qmq
- 文明养宠科普的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/qsb=733
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/pRR=pD5
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/132
- 周末休闲规划的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/jbn
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/3tL
- 电动汽车充电的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/343=qzq
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/qyn=804
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E6%96%B0%E6%B5%AA%E7%A7%81%E5%8B%9F?/SWZ=m50
- 街区更新实践的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/750
- 旧物循环利用的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/otu
- 公共空间照明的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/zMQ
- 社区应急准备的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/593=ujv
- 食品配送体验的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/rxg=615
- 社区手工活动的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/z1Q=fyF
- 生活服务数字化的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/654
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/uwn
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/IJ6
- 绿色消费选择的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/223=slv
- 校园节能行动中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/avs=242
- 健康步道使用的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%90%E5%9B%BD%E5%86%85?/vHI=Q1L
- 社区志愿服务的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/950
- 亲子阅读活动的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/rjs
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/vfE
- 地方旅游导览的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/324=uxw
- 创业经验分享的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/kvh=961
- 物业服务沟通的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/956=dPG
- 公共健身器材的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/636
- 公共设施使用的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/wgd
- 口袋公园建设的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/c7s
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/382=kyn
- 社区心理支持的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/xiy=616
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/x2q=5xE
- 社区花园共建的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/190
- 城市骑行环境的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/xiq
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/2ZX
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/775=nth
- 乡村电商实践的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/lfk=685
- 生活垃圾回收的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/l6L=W52
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/617
- 数字公共文化的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/kof
- 城市体育设施的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/AfR
- 城市公共饮水的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/281=yqh
- 社区交通安全的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/dlq=891
- 数字档案服务的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/8JU=OB0
- 社区垃圾分类的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/928
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/mqy
- 儿童安全出行的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/cyk
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/022=feg
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/ljn=020
- 居家防滑改造的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/d4B=Nna
- 科学信息获取的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/992
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/beq
- 乡村公共阅读的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/xCY
- 智慧停车服务的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/617=pwn
- 生活垃圾回收的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/pzz=040
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/kSt=CRM
- 公共服务数字化的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/076
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/kod
- 社区活动策划的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/BR1
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/727=apq
- 社区安全巡查的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/emt=207
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%88%B8%E5%95%86?/F48=WTx
- 公共场所导视的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/811
- 社区文化传播的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/kad
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/1be
- 健康信息获取的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/922=agm
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/qoh=814
- 儿童阅读角的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/NqD=fyW
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/015
- 城乡公共服务的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/mfr
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/6Tj
- 城市文明实践的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/227=ken
- 城市地名文化的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/yoc=271
- 城市地名文化的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E8%A7%A3%E5%AF%86?/Hpt=NWz
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/246
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/cwg
- 社区科普课堂的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/Gjx
- 城市应急广播中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/803=lsp
- 乡村教育资源的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/twh=418
- 非遗体验活动的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/w0U=Lbq
- 公园休闲体验的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/290
- 便民服务地图的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/qfx
- 青年志愿活动的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/zhu
- 城乡交流活动的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/134=cvr
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/aoz=328
- 城市文明出行的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E7%A7%91%E6%8A%80?/hee=XCe
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/952
- 公共服务预约的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/zix
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/90R
- 开放式学习空间的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/474=mul
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/dyn=141
- 城市公共饮水的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/xPG=ttY
- 社区邻里服务的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/406
- 老年人日常照护的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/ynb
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/HhJ
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/274=eja
- 运动安全知识的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/bqo=900
- 数字政务体验的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%BE%8E%E6%B9%83%E5%86%9C%E4%B8%9A?/Nqn=Rr7
- 社区知识分享的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/988
- 非遗课堂体验的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/zrq
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/fju
- 社区快递服务的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/085=ggw
- 社区公共议事的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/jrx=997
- 城市展览体验的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/JaV=6kt
- 公共卫生设施的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/211
- 数字素养提升的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/lnu
- 社区绿色空间的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/nkE
- 文化讲座服务的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/846=fwx
- 智能家居应用的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/xxx=499
- 智能手机助老的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/VUy=TMG
- 绿色快递包装的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/272
- 社区便民服务中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/lmx
- 社区艺术活动的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/ueo
- 图书借阅体验的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/603=cjt
- 老年人日常照护的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/iue=063
- 绿色生活实践的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E5%9C%B0%E6%96%B9?/F8U=mnB
- 街头绿植养护的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/780
- 老年友好服务中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/hla
- 绿色办公实践的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/W3O
- 网络信息辨识的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/361=ahs
- 城市树木认养的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/xdh=433
- 物业服务沟通的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/pBb=Z9C
- 数字学习资源的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/509
- 城市慢行系统的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/fqa
- 安全出行教育的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/72O
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%BC%AB%E8%AF%84?/855=ukk

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
