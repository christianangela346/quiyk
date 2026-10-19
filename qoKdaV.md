# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 城市水环境观察的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%85%A8%E5%A4%A9%E6%9C%80%E5%87%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922994_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/704
- 乡村公共阅读的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%85%A8%E5%A4%A9%E6%9C%80%E5%87%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922994_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/qvw
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%85%A8%E5%A4%A9%E6%9C%80%E5%87%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922994_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/dEP
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%85%A8%E5%A4%A9%E6%9C%80%E5%87%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922994_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/128=onm
- 机器人科普活动的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%85%A8%E5%A4%A9%E6%9C%80%E5%87%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922994_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/txf=522
- 公交站点体验中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%85%A8%E5%A4%A9%E6%9C%80%E5%87%86%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%922994_%E6%96%B0%E6%B5%AA%E5%9C%88%E5%AD%90?/lMV=dnM
- 城市树木认养的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AE%9D%E5%AE%9D%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/455
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AE%9D%E5%AE%9D%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/quf
- 家庭阅读计划的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AE%9D%E5%AE%9D%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/bai
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AE%9D%E5%AE%9D%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/932=xzq
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AE%9D%E5%AE%9D%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/slr=931
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%AE%9D%E5%AE%9D%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92app%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/YN4=rZV
- 街区小店体验的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/966
- 城市生活记录的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/urb
- 城市绿色交通的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/cP3
- 老年数字阅读的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/671=ydg
- 地方旅游导览的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/osa=124
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%AE%89%E9%98%B2?/Qsf=182
- 机器人科普活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/409
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/sxt
- 老年人日常照护的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/N6d
- 社区学习活动的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/659=rkx
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/vdh=048
- 家庭照护支持的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B8%AF%E8%82%A1?/XK3=zoi
- 社区消防演练的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/795
- 街区道路维护中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/zws
- 乡村公共服务的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/00v
- 家庭照护支持的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/592=nug
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/txk=001
- 社区花园共建的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%85%AC%E5%BC%8F%E5%9B%BE%E8%A7%A3_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/oCf=vL7
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/961
- 青少年科普实践的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/ddr
- 社区手工活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/jNV
- 食品配送体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/859=cjl
- 远程协作工具的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/rqm=479
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/OLW=Tj7
- 社区文化节活动的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/555
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/cue
- 家庭用电安全的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/Rsz
- 公园无障碍服务的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/011=xfu
- 校园安全教育的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/gwd=030
- 乡村产业科普的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/EEZ=drV
- 乡村教育资源的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/688
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/uyg
- 开放数据应用的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/pG2
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/073=jef
- 公共服务评价的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/rfv=106
- 公园无障碍服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BD%91_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/qPg=5oA
- 社区生活指南从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/879
- 城市文明实践的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/jhc
- 数字设备回收的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/M06
- 社区交通安全的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/494=fut
- 城市游园体验的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/all=761
- 社区故事采集的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/HI8=s9W
- 社区健康讲座的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/078
- 乡村公共文化的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/ufc
- 本地旅行体验的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/EnJ
- 城市基础设施的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/920=vfb
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/lbq=942
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/U8Y=Efm
- 公园亲子设施的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/684
- 社区休闲设施的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/dej
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/uYV
- 公共图书馆服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/691=ebz
- 社区信息发布的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/ubd=804
- 电动汽车充电的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/Hk0=gfZ
- 儿童户外活动的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/424
- 城市噪声观察的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/hyg
- 休闲运动入门的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/A0t
- 乡村生态观察的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/646=nog
- 环境教育课程中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/wme=894
- 社区慢性病防控的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/yMK=hNb
- 社区休闲设施的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%80%8E%E6%A0%B7%E5%88%86%E6%9E%90_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/946
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%80%8E%E6%A0%B7%E5%88%86%E6%9E%90_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/qbp
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%80%8E%E6%A0%B7%E5%88%86%E6%9E%90_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/pn2
- 校园安全教育的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%80%8E%E6%A0%B7%E5%88%86%E6%9E%90_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/684=eis
- 社会体育指导的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%80%8E%E6%A0%B7%E5%88%86%E6%9E%90_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/bzw=825
- 社区艺术活动的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E6%80%8E%E6%A0%B7%E5%88%86%E6%9E%90_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/n4z=WTT
- 城市水环境观察的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/361
- 城市绿色交通的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/msc
- 休闲运动入门的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/BSi
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/624=jhu
- 青年志愿活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/kdv=583
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%8D%E8%B4%B9%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/1E9=9JG
- 口袋公园建设的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/083
- 个人时间管理的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/oce
- 社区故事采集的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/uG7
- 农产品品牌传播的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/894=dtq
- 公共图书馆服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/tjw=183
- 公共空间安全的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/ef3=hil
- 城市绿色交通的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/681
- 图书馆数字服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/vcf
- 社区防暑服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/Q33
- 数字创意课程的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/593=zmy
- 青少年科普实践的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/zsc=983
- 社区安全巡查的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%98%AF%E4%BB%80%E4%B9%88_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/boh=tDR
- 社区养老服务的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/249
- 公共场馆服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/qcl
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/RrC
- 校园节能行动的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/294=llt
- 社区花园共建的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/uvr=627
- 社区科普课堂的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%96%B0%E6%B5%AA%E6%91%84%E5%BD%B1?/1S6=O8H
- 亲子阅读活动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E5%AE%9E%E5%90%97_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/557
- 城市空气科普的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E5%AE%9E%E5%90%97_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/oyw
- 周末休闲规划的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E5%AE%9E%E5%90%97_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/tC6
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E5%AE%9E%E5%90%97_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/025=xtj
- 城市骑行环境的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E5%AE%9E%E5%90%97_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/vez=103
- 城市慢跑路线的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E5%AE%9E%E5%90%97_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/HR1=pMw
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/154
- 校园社团活动的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/nhr
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/7XV
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/324=ziw
- 城市公共座椅的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/gvk=134
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/sHf=kvs
- 青年职业探索的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/070
- 生成式工具使用的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/srm
- 亲子科普活动的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/xkU
- 社区手工活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/861=jda
- 日常摄影记录的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/dsj=218
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%B4%B7?/jRQ=2PE
- 城市博物馆活动的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/715
- 城市应急广播的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/tlk
- 家庭食品保存的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/LJk
- 学校食育活动的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/864=ieg
- 社区法律科普中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/xiu=036
- 城市微更新实践中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%A4%9A%E5%B0%91%E9%92%B1_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/2GG=xeD
- 家庭养老规划的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/268
- 乡村公共文化中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/ojx
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/O19
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/168=yao
- 人工智能科普的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/ugh=337
- 家庭消费规划的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA%E8%AE%BA%E5%9D%9B?/CPv=cvd
- 线上办事服务的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9C%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/987
- 公共卫生宣传的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9C%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/uop
- 生活服务数字化的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9C%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/NtA
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9C%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/615=uld
- 社区家校合作的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9C%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/gcu=176
- 乡村生活观察的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%9C%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/GHU=NSQ
- 城市公共标识的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/702
- 农业科普体验的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/ejp
- 城市公共空间的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/lm2
- 城市夜间生活的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/887=lsp
- 社区便利生活的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/fha=561
- 城市公共空间的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/U6V=uGz
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/131
- 社区环保活动的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/sal
- 公益活动组织的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/OYp
- 社区公共卫生的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/588=ven
- 社区便民集市的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/vqp=451
- 气象科普传播的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92go%E8%A7%86%E9%A2%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%9A%E5%BB%BA?/NqN=hdU
- 城乡公共服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/582
- 日常摄影记录的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/avl
- 社区手工活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/R61
- 科技馆参观体验的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/871=myk
- 社区信息发布的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/ciy=395
- 文化场馆预约的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E6%8A%96%E9%9F%B3%E4%BD%93%E8%82%B2?/XGT=PqG
- 公交无障碍服务的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/120
- 城市应急广播的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/ngp
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/gUp
- 社区活动报名的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/249=ixc
- 城市绿道建设的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/uiz=235
- 社区生活指南的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E8%BF%9B_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/dMy=1XL
- 儿童运动体验的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/612
- 生活技能分享的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/ucf
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/8Xh
- 社区家政服务的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/769=kwh
- 社区休闲设施的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/elj=745
- 个人时间管理的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E7%BE%A4%E6%80%8E%E4%B9%88%E5%8A%A0%E5%85%A5_%E8%B4%A2%E7%BB%8F%E9%A3%9F%E5%93%81?/OLS=4Lf
- 城市绿色交通的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A46_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/319
- 图书馆数字服务的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A46_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/qzz
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A46_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/4TJ
- 社区活动策划的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A46_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/428=mvg
- 生活垃圾减量的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A46_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/ueg=463
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A46_%E7%99%BE%E5%BC%BA%E8%B4%A2%E7%BB%8F?/ScL=OGH
- 无障碍信息设计的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/029
- 生活垃圾回收的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/gcq
- 居家适老化改造的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/nBw
- 城市文明出行的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/537=wyg
- 社区手工活动的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/wwd=791
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/kXW=TcA
- 无障碍信息设计的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/170
- 城乡公共服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/sxi
- 城市便民驿站的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/XgJ
- 社区文化节活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/843=ioj
- 急救知识普及的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/tie=613
- 公园休闲体验的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/zFv=5kJ
- 市民热线服务的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/777
- 智慧停车服务的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/nss
- 地方民俗记录的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/B9p
- 乡村产业科普的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/099=snv
- 城市体育设施的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/sfq=998
- 家庭安全提示的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%8E%A9%E4%BA%8C%E7%BB%B4%E7%A0%81_%E7%99%BE%E5%BA%A6%E9%80%9A%E4%BF%A1?/AFK=Wph
- 开放数据应用的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E9%A3%9E%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/623
- 城市公共饮水的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E9%A3%9E%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/yxm
- 社区法律科普的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E9%A3%9E%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/G9g
- 校园阅读活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E9%A3%9E%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/378=pao
- 城市基础设施的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E9%A3%9E%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/kyd=823
- 无障碍出行的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E9%A3%9E%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%96%87%E6%91%98?/CW1=qGx
- 节能家电使用的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/170
- 青少年户外教育的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/rke
- 公共服务咨询的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/wx5
- 便民服务窗口的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/070=rvr
- 城市博物馆服务的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/upf=662
- 乡村生活观察的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mJi=laE
- 机器人科普活动的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A44s%E5%BA%97%E4%BF%9D%E5%85%BB_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/777
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A44s%E5%BA%97%E4%BF%9D%E5%85%BB_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/lyl
- 药品使用科普的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A44s%E5%BA%97%E4%BF%9D%E5%85%BB_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/z3t
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A44s%E5%BA%97%E4%BF%9D%E5%85%BB_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/355=izr
- 数字课堂应用的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A44s%E5%BA%97%E4%BF%9D%E5%85%BB_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/gud=637
- 城市生活服务的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A44s%E5%BA%97%E4%BF%9D%E5%85%BB_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/o7t=NCO
- 城市公共自行车的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/331
- 公共服务指南的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/nyl
- 数字便民地图的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/0yp
- 软件开发学习的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/036=hhe
- 社区儿童活动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/vji=528
- 地方民俗记录的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%AE%9E%E5%8A%9B%E5%85%AC%E4%BC%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/yJG=yqF
- 公共空间导览的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%99%BE%E5%BA%A6%E8%B4%B4%E5%90%A7_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/815
- 家庭运动计划的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%99%BE%E5%BA%A6%E8%B4%B4%E5%90%A7_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/esq
- 儿童友好空间的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%99%BE%E5%BA%A6%E8%B4%B4%E5%90%A7_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/5KO
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%99%BE%E5%BA%A6%E8%B4%B4%E5%90%A7_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/929=zpr
- 城市应急科普的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%99%BE%E5%BA%A6%E8%B4%B4%E5%90%A7_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/kut=091
- 社区信息发布的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E7%99%BE%E5%BA%A6%E8%B4%B4%E5%90%A7_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/nZt=tyK
- 城市噪声观察的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/778
- 数字设备回收的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/dzv
- 科学教育活动的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/4fX
- 口袋公园建设的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/288=cnb
- 租房信息服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/pjl=066
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E6%9C%80%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/WPu=9Db
- 公共交通信息服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/781
- 城市游园体验的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/znh
- 社区设施共享的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/8zI
- 节能生活方式的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/438=glf
- 城市公共艺术的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/byv=040
- 城市公共饮水的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%BE%AE%E4%BF%A1%E7%BE%A4%E5%85%AC%E4%BC%97%E5%8F%B7%E5%AE%9E%E5%8A%9B%E7%BE%A4_%E5%A4%B4%E6%9D%A1%E4%BC%97%E6%B5%8B?/hkF=7I0
- 软件开发学习的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/602
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/opu
- 数字生活课堂的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/yIQ
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/768=pwe
- 老年人出行服务的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/yia=982
- 社区绿色空间的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/v5k=r2u
- 社区邻里服务的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/006
- 家庭运动计划的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/uzr
- 社区休闲设施的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/4fq
- 绿色出行服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/126=pca
- 街区更新实践的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/yip=799
- 社区科普课堂的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%AC%E4%BC%97%E5%8F%B7_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/J0A=oKH
- 电子商务服务的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%BC%80%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/400
- 科学健身方法的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%BC%80%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/jsd
- 市民热线服务的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%BC%80%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/dAw
- 数据分析入门的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%9C%89%E6%B2%A1%E6%9C%89%E5%BC%80%E8%BD%A6%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/523=vtx

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
