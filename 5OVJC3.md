# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 数字素养提升从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/kan=806
- 城市应急科普的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E7%9A%84_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E8%AE%AF?/lx1=PqM
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/936
- 社区公共卫生的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/dxh
- 公共图书馆服务的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/CgV
- 城市共享单车的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/461=oqz
- 市民热线服务的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/lti=036
- 乡村公共服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E8%84%89%E8%84%89%E5%9B%BD%E9%99%85?/TuJ=jyL
- 城市步行环境的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB?/181
- 社区家校合作的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB?/rmg
- 城市微更新实践的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB?/UQx
- 新能源知识普及的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB?/359=ljv
- 社区教育资源的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB?/hnk=736
- 城市骑行环境的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB?/Nzb=c3B
- 科普展览体验的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0__%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/704
- 城市博物馆活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0__%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/cty
- 公园无障碍服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0__%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/EHz
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0__%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/772=kwq
- 老年智能设备的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0__%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/ysn=220
- 城市住房服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0__%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/ntQ=Wa6
- 便民服务地图的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/527
- 老年友好服务的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/ser
- 家庭科学教育的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/53b
- 本地历史资料的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/419=toz
- 邻里共享空间的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/nxa=185
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%9C%89%E5%93%AA%E4%BA%9B%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/Ip0=LLe
- 社区交通安全的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/390
- 社区活动空间的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/qjv
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/RJx
- 公共服务数字化的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/850=akh
- 家庭环保行动的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/bub=844
- 读书会组织的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%8D%81%E5%88%86%E5%BF%AB3%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E7%99%BE%E5%BA%A6%E6%9C%9F%E8%B4%A7?/4i5=CLn
- 社区信息发布的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%90%88%E6%B3%95%E5%90%97_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/295
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%90%88%E6%B3%95%E5%90%97_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/jfe
- 生活服务数字化的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%90%88%E6%B3%95%E5%90%97_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/273
- 家庭网络使用的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%90%88%E6%B3%95%E5%90%97_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/486=vvx
- 农产品消费体验的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%90%88%E6%B3%95%E5%90%97_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/xhb=677
- 老年数字阅读中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8D%81%E5%88%86%E5%BF%AB3%E5%90%88%E6%B3%95%E5%90%97_%E5%A4%B4%E6%9D%A1%E8%A6%81%E9%97%BB?/fKH=1VQ
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_10%E5%88%86%E5%BF%AB3%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%85%AC%E8%AE%A4%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/105
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_10%E5%88%86%E5%BF%AB3%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%85%AC%E8%AE%A4%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/jng
- 家庭用电安全的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_10%E5%88%86%E5%BF%AB3%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%85%AC%E8%AE%A4%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/N4U
- 文化讲座服务的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_10%E5%88%86%E5%BF%AB3%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%85%AC%E8%AE%A4%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/777=pyo
- 绿色快递包装的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_10%E5%88%86%E5%BF%AB3%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%85%AC%E8%AE%A4%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/syk=255
- 青少年科普实践的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_10%E5%88%86%E5%BF%AB3%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%85%AC%E8%AE%A4%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/Q7B=lii
- 小区停车协商的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/251
- 基层健康档案的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/iqa
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/wmL
- 数字创意课程的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/118=rwa
- 社区垃圾分类的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/mbd=930
- 读书会组织的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_10%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB?/Aio=NMI
- 儿童友好街区的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%9010%E5%88%86%E5%AE%98%E6%96%B9%E4%B8%93%E5%AE%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/825
- 乡村产业科普的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%9010%E5%88%86%E5%AE%98%E6%96%B9%E4%B8%93%E5%AE%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/jel
- 数字政务体验的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%9010%E5%88%86%E5%AE%98%E6%96%B9%E4%B8%93%E5%AE%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/q1l
- 应急物资管理的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%9010%E5%88%86%E5%AE%98%E6%96%B9%E4%B8%93%E5%AE%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/028=okc
- 城市便民驿站的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%9010%E5%88%86%E5%AE%98%E6%96%B9%E4%B8%93%E5%AE%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/rxs=166
- 社区修缮行动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E4%B9%9010%E5%88%86%E5%AE%98%E6%96%B9%E4%B8%93%E5%AE%B6%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/6bv=ieU
- 社区宠物管理的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/317
- 城市骑行环境的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/oho
- 农产品消费体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/3WW
- 家庭健康科普的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/159=rjt
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/nci=451
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8F%B7%E5%A4%96?/WH4=7Ui
- 老年学习活动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eviii%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/210
- 城市慢行系统的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eviii%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/gvd
- 社区邻里服务的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eviii%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/TWL
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eviii%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/053=mai
- 市民热线服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eviii%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/acr=568
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Eviii%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%9F%B3%E4%B9%90?/Dq1=nE4
- 城市基础设施的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/373
- 公共设施使用的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/ruc
- 社区运动空间的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/oFc
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/114=eof
- 家庭阅读计划的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/axp=517
- 家庭教育交流的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/NhQ=Gi9
- 城市慢行系统的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8035app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/929
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8035app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/pkt
- 健康步道使用的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8035app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/Vfy
- 乡村阅读活动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8035app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/869=cmx
- 城市绿色交通的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8035app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/rbr=986
- 城市休闲步道的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8035app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/wNz=FSj
- 社区互助网络的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/615
- 非遗体验活动的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/jdm
- 数字公共文化的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/GCE
- 信息无障碍体验的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/934=shv
- 城市公共艺术的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/ijr=803
- 社区生活指南的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/Ms5=4e0
- 生成式工具使用的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BDapp_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/493
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BDapp_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/lrz
- 急救知识普及的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BDapp_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/wqL
- 城市游园体验的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BDapp_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/338=spk
- 传统节日科普的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BDapp_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/wlm=776
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9EI%E4%B8%8B%E8%BD%BDapp_%E5%87%A4%E5%87%B0%E8%AF%84%E8%AE%BA?/v7Q=uiX
- 基层健康档案的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%A4%A7%E6%B8%AF%E6%BE%B3app%E4%B8%8B%E8%BD%BD_360%E5%9B%BE%E9%89%B4?/174
- 绿色办公实践的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%A4%A7%E6%B8%AF%E6%BE%B3app%E4%B8%8B%E8%BD%BD_360%E5%9B%BE%E9%89%B4?/hlx
- 公共交通接驳的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%A4%A7%E6%B8%AF%E6%BE%B3app%E4%B8%8B%E8%BD%BD_360%E5%9B%BE%E9%89%B4?/3Wx
- 物业服务沟通的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%A4%A7%E6%B8%AF%E6%BE%B3app%E4%B8%8B%E8%BD%BD_360%E5%9B%BE%E9%89%B4?/631=ndd
- 社区儿童活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%A4%A7%E6%B8%AF%E6%BE%B3app%E4%B8%8B%E8%BD%BD_360%E5%9B%BE%E9%89%B4?/jqv=724
- 公共场馆服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BD%A9%E6%B0%91%E4%B9%8B%E5%AE%B6%E5%A4%A7%E6%B8%AF%E6%BE%B3app%E4%B8%8B%E8%BD%BD_360%E5%9B%BE%E9%89%B4?/Lee=H3v
- 老年人日常照护的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/886
- 公共服务指南的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/tjl
- 乡村生态旅游的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/Cra
- 家庭节能实践的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/560=luc
- 个人信息保护的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/loi=095
- 绿色出行服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/5cH=Pz6
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E4%BA%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/434
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E4%BA%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/tiy
- 公共场馆服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E4%BA%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/egM
- 节日文化体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E4%BA%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/638=pjb
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E4%BA%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/lir=097
- 家庭食品保存的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E4%BA%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/IX3=rkk
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/871
- 科学健身方法的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/uac
- 户外活动组织的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/vNr
- 文明养宠科普的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/660=zby
- 邻里互助活动的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/gtl=579
- 公共服务沟通的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/QZA=MI7
- 居民健康教育的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Eios%E4%B8%8B%E8%BD%BDapp_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/481
- 社区运动空间中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Eios%E4%B8%8B%E8%BD%BDapp_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/mbt
- 旧物循环利用的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Eios%E4%B8%8B%E8%BD%BDapp_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/OCJ
- 城市建设科普的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Eios%E4%B8%8B%E8%BD%BDapp_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/417=htl
- 社区信息发布的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Eios%E4%B8%8B%E8%BD%BDapp_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/ppq=441
- 城市社区治理的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9Eios%E4%B8%8B%E8%BD%BDapp_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/vrR=SYg
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eios_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/194
- 文化场馆预约的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eios_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/ezd
- 节约用水实践的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eios_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/RS7
- 数字生活课堂的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eios_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/490=rcu
- 数字公共文化的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eios_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/egh=445
- 科学运动指导中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Eios_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/cw0=qwZ
- 节假日出行安排中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/931
- 家庭理财科普的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/mvy
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/R6y
- 社区便民服务的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/563=blu
- 本地旅行体验的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/noe=094
- 数字支付体验的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9E8%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/0ps=SEC
- 线上阅读资源的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eiv%E4%B8%8B%E8%BD%BDapp_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/201
- 家庭运动计划的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eiv%E4%B8%8B%E8%BD%BDapp_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/kpd
- 人工智能科普的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eiv%E4%B8%8B%E8%BD%BDapp_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/56g
- 基层健康档案中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eiv%E4%B8%8B%E8%BD%BDapp_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/669=dgu
- 社区生活指南中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eiv%E4%B8%8B%E8%BD%BDapp_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/qva=031
- 劳动教育实践的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9Eiv%E4%B8%8B%E8%BD%BDapp_%E6%96%B0%E6%B5%AA%E6%96%B0%E9%97%BB?/6KB=7Cf
- 传统节日科普的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BF%AB3v%E5%A4%A7%E5%8E%85%E6%96%B0%E9%A1%B5%E9%9D%A2.%E6%96%B0%E5%AE%89%E5%8D%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/823
- 社区家校合作的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BF%AB3v%E5%A4%A7%E5%8E%85%E6%96%B0%E9%A1%B5%E9%9D%A2.%E6%96%B0%E5%AE%89%E5%8D%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/qcj
- 小区电梯维护的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BF%AB3v%E5%A4%A7%E5%8E%85%E6%96%B0%E9%A1%B5%E9%9D%A2.%E6%96%B0%E5%AE%89%E5%8D%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/0ds
- 环境教育课程中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BF%AB3v%E5%A4%A7%E5%8E%85%E6%96%B0%E9%A1%B5%E9%9D%A2.%E6%96%B0%E5%AE%89%E5%8D%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/130=sib
- 邻里互助活动的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BF%AB3v%E5%A4%A7%E5%8E%85%E6%96%B0%E9%A1%B5%E9%9D%A2.%E6%96%B0%E5%AE%89%E5%8D%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/zlg=979
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%BF%AB3v%E5%A4%A7%E5%8E%85%E6%96%B0%E9%A1%B5%E9%9D%A2.%E6%96%B0%E5%AE%89%E5%8D%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BA%AA%E5%AE%9E?/G2z=nsl
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/116
- 公共交通接驳的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/rba
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/O9z
- 公共服务数字化的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/560=qsm
- 小区公共照明的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/rzx=267
- 软件开发学习的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/H1S=T0r
- 街区更新实践的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/794
- 社区庭院绿化的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/lbx
- 儿童友好空间的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/CvI
- 软件开发学习的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/493=ntr
- 城市文明出行的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/pmh=461
- 老旧小区改造的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/LiH=txF
- 创业经验分享的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%A5%A52026%E5%A4%A9%E5%A4%A9%E5%BC%80%E5%A5%BD%E5%BD%A9%E5%A4%A7%E4%B9%90%E9%80%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/732
- 乡村阅读活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%A5%A52026%E5%A4%A9%E5%A4%A9%E5%BC%80%E5%A5%BD%E5%BD%A9%E5%A4%A7%E4%B9%90%E9%80%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/sat
- 社区花园共建的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%A5%A52026%E5%A4%A9%E5%A4%A9%E5%BC%80%E5%A5%BD%E5%BD%A9%E5%A4%A7%E4%B9%90%E9%80%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/W0p
- 城市公共空间的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%A5%A52026%E5%A4%A9%E5%A4%A9%E5%BC%80%E5%A5%BD%E5%BD%A9%E5%A4%A7%E4%B9%90%E9%80%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/843=vjx
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%A5%A52026%E5%A4%A9%E5%A4%A9%E5%BC%80%E5%A5%BD%E5%BD%A9%E5%A4%A7%E4%B9%90%E9%80%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/pib=755
- 邻里互助活动的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E6%96%B0%E5%A5%A52026%E5%A4%A9%E5%A4%A9%E5%BC%80%E5%A5%BD%E5%BD%A9%E5%A4%A7%E4%B9%90%E9%80%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/Eli=oj0
- 家庭园艺实践的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E9%A6%99%E6%B8%AF%E6%BE%B3%E9%97%A8%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%85%AC%E5%BC%80%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/258
- 儿童户外活动的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E9%A6%99%E6%B8%AF%E6%BE%B3%E9%97%A8%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%85%AC%E5%BC%80%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/nol
- 气象科普传播的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E9%A6%99%E6%B8%AF%E6%BE%B3%E9%97%A8%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%85%AC%E5%BC%80%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/mLM
- 城市公共自行车的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E9%A6%99%E6%B8%AF%E6%BE%B3%E9%97%A8%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%85%AC%E5%BC%80%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/037=fco
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E9%A6%99%E6%B8%AF%E6%BE%B3%E9%97%A8%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%85%AC%E5%BC%80%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/ncb=196
- 家庭节能实践的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E9%A6%99%E6%B8%AF%E6%BE%B3%E9%97%A8%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E5%85%AC%E5%BC%80%E5%90%97%E7%8E%B0%E5%9C%A8_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/4lr=I52
- 基层健康服务的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcome%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/006
- 小区公共照明的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcome%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/onk
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcome%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/Wyw
- 绿色消费选择的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcome%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/527=lir
- 社区故事采集的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcome%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/iou=061
- 社区邻里服务的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B4%AD%E5%BD%A9welcome%E7%BD%91%E9%A1%B5%E7%89%88_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/xob=TWZ
- 便民维修服务的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%89%98%E9%83%BD%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E4%BA%BA_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/209
- 社区艺术活动的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%89%98%E9%83%BD%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E4%BA%BA_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/loe
- 传统节日科普的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%89%98%E9%83%BD%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E4%BA%BA_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/z1A
- 数字创作工具的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%89%98%E9%83%BD%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E4%BA%BA_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/068=mpo
- 校园阅读活动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%89%98%E9%83%BD%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E4%BA%BA_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/kak=050
- 城市人文观察的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E6%89%98%E9%83%BD%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E4%BA%BA_%E5%8D%B3%E5%88%BB%E7%89%B9%E7%A8%BF?/SfI=HhG
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E7%89%88%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/630
- 小区停车协商的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E7%89%88%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/xsf
- 读书会组织的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E7%89%88%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/D15
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E7%89%88%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/706=nek
- 家庭运动计划的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E7%89%88%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/bnf=563
- 小区停车协商的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E7%89%88%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/t9o=9xN
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/935
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/fna
- 社区手工活动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/dX4
- 亲子科普活动的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/930=slf
- 社区读书角建设的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/ytq=948
- 公共服务评价的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%B4%AD%E5%BD%A9%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97__%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/MLl=HcZ
- 家庭安全提示的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/321
- 社区活动报名中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/iql
- 公共卫生设施的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/nBN
- 城市休闲步道的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/454=vhn
- 校园节能行动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/jia=047
- 便民维修服务的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%99%9A%E6%8A%A5?/TM7=1CD
- 社区互助网络的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/509
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/kjo
- 城市公共座椅的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/rH8
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/942=hsk
- 老年数字阅读的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/wpl=864
- 智慧停车服务的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/27n=tfk
- 小区电梯维护的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/535
- 公共卫生设施的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/bpn
- 社区邻里服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/CP1
- 社区便民集市的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/692=lbc
- 老年学习活动的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/ajx=507
- 新能源出行的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%BE%8B_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/kjS=Nxp
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E3%80%82_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/149
- 城市游园体验的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E3%80%82_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/tzn
- 基层服务创新的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E3%80%82_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/dIa
- 老旧小区改造的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E3%80%82_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/464=kbt
- 老旧小区改造的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E3%80%82_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/ebz=137
- 邻里共享空间的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E3%80%82_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/mdV=gio
- 社区协商议事的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%90%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%AE%89%E9%98%B2?/258
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%90%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%AE%89%E9%98%B2?/cfh
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%90%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%AE%89%E9%98%B2?/L4a
- 生活服务数字化的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%90%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%AE%89%E9%98%B2?/502=ghk
- 生活垃圾回收的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%90%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%AE%89%E9%98%B2?/ttc=473
- 开源技术交流的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%90%E4%B8%89%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81_%E6%BE%8E%E6%B9%83%E5%AE%89%E9%98%B2?/Jj4=Xo2
- 家庭教育交流的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91__%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/760
- 城市噪声观察的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91__%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/tkl
- 远程协作工具的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91__%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/sgx
- 街区绿化养护的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91__%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/732=uok
- 智慧城市体验的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91__%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/fzv=284
- 小区公共照明的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E7%BD%91__%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/XsL=z7D
- 社区儿童活动的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/178
- 信息无障碍体验的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/xcd
- 社区科普课堂的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/Zpv
- 社区教育资源的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/474=rxx
- 科学观察活动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/bkp=106
- 非遗课堂体验的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/MIo=vlQ
- 终身学习资源的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/269
- 公共空间休憩的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/rns
- 邻里共享空间的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/bjD
- 家庭节能设备的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/059=jqj
- 绿色办公实践的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/wtk=786
- 家庭网络使用的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%8C%BB%E8%8D%AF?/foD=yh8
- 数字生活课堂的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/753
- 社区设施共享的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/uow
- 传统节日科普的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/aa4
- 急救知识普及的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/577=ole
- 跨代沟通活动的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/ybr=516
- 生活技能分享的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/1oJ=yRp
- 街区更新实践的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B4%B5%E5%B7%9E%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E8%B4%A2%E6%8A%A5?/849
- 数字地图应用的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E8%B4%B5%E5%B7%9E%E5%BF%AB3_%E5%A4%AE%E8%A7%86%E8%B4%A2%E6%8A%A5?/tof

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
