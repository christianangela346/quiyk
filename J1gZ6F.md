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

- 公共卫生宣传中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/w1j
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/794=vpg
- 公共卫生宣传的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/dxq=460
- 网络信息辨识的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/vy4=V6R
- 儿童安全出行的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/863
- 城市游园体验的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/whi
- 环境监测科普的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/lMz
- 家庭安全提示的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/194=naq
- 智慧停车服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/sxl=367
- 家庭健康管理的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E6%96%B9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%99%A8%E6%8A%A5?/O71=71E
- 青年职业探索的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/619
- 城市夜间照明的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/lup
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/NVO
- 社区共享书架的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/912=wgm
- 急救知识普及的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/pdu=599
- 社区阅读服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A6%8F%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/bbO=niC
- 家庭急救准备的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/516
- 非遗课堂体验的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/axx
- 远程协作工具的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/ttL
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/154=mnj
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/lhn=569
- 无障碍出行的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8%E8%A7%84_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/dYG=rSd
- 健康饮水科普的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/888
- 社区阅读服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/yjz
- 城市绿道建设的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/kM8
- 社区休闲设施的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/306=uyy
- 城市展览体验的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/fdm=158
- 社区便民集市的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E8%A7%82%E5%AF%9F?/STK=JQH
- 农业科普体验的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/915
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/ukz
- 环境教育课程的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/ESB
- 绿色出行服务的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/123=gzu
- 社区快递服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/rpj=791
- 城市可持续生活的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84_%E9%9B%85%E8%99%8E%E4%BF%9D%E9%99%A9?/IFb=0z1
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/659
- 老年运动活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/ofs
- 低碳社区实践的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/t23
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/231=mgn
- 数字素养提升的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/bvt=171
- 绿色办公实践的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%BE%AE%E4%BF%A1%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99%E5%9B%BE_%E8%99%8E%E6%89%91%E6%92%AD%E6%8A%A5?/fPS=1BY
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/929
- 基层服务创新的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/vlk
- 家庭健康管理的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/BrM
- 数字政务体验的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/696=rrs
- 家庭网络使用的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/jvf=253
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%8C%85%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BE%A4%E8%A7%84%E5%88%99_%E5%8D%B3%E5%88%BB%E5%81%A5%E8%BA%AB?/FmZ=oj5
- 街区更新实践的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/329
- 食品安全科普的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/yna
- 公交无障碍服务的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/Dbw
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/729=bpg
- 街区道路维护的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/uyh=686
- 社区志愿服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E5%99%A8_%E6%90%9C%E7%8B%97%E5%AE%8F%E8%A7%82?/eh5=jKo
- 数字艺术创作的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/889
- 文明养宠科普的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/aof
- 数字设备回收的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/FXh
- 本地旅行体验的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/854=qks
- 社区修缮行动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/bxk=735
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%8A%80_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/6O0=UbF
- 城市公共饮水的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/010
- 社区故事采集的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/bhh
- 全民健身活动的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/FBt
- 科技馆参观体验的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/105=mng
- 非遗课堂体验的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/ibj=990
- 文明养宠科普的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_pc28%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/FFm=ePV
- 公共卫生设施的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/414
- 社区绿色空间的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/kwh
- 社区应急准备的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/O8P
- 社区手工活动的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/163=qso
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/yjg=640
- 青少年心理健康的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%89%88_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/uTB=lDf
- 老年数字阅读的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/572
- 食品安全科普的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/arw
- 健康饮食教育的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/KQa
- 社区慢性病防控的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/430=ycm
- 公共卫生设施的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/hqj=199
- 城市社区治理的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E8%BF%9B%E5%85%A5_%E8%B1%86%E7%93%A3%E7%A7%91%E6%8A%80?/XfH=x97
- 公共服务沟通的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/777
- 乡村产业科普的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/vqn
- 社区阅读服务的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/66I
- 节假日出行安排的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/437=wqk
- 健康饮水科普的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/jqq=373
- 社区商业活力的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/LZJ=eIa
- 城市地名文化的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/643
- 垃圾分类指导的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/brl
- 家庭科学教育的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/IV4
- 街区绿化养护的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/089=njr
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/ykx=445
- 社区便民服务的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/WVL=dhH
- 科学信息获取的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/849
- 骑行路线规划有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/mch
- 城市适老服务的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/IFf
- 儿童运动体验的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/631=dog
- 数字学习资源的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/jfb=824
- 机器人科普活动的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/KgH=xbB
- 药品使用科普的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/959
- 地方旅游导览从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/tmq
- 农村环境治理的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/Jbt
- 社区应急准备有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/165=zey
- 电动汽车充电的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/yaw=043
- 社区手工活动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/1o1=z0Z
- 社区教育资源的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/820
- 地方民俗记录的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/ulx
- 社区教育资源的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/76U
- 数字政务体验的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/104=gsp
- 社区商业活力的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/zrm=978
- 数字档案服务的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/tKC=e7Q
- 地方文化传播的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/828
- 城市慢行系统的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/weu
- 乡村公共文化的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/h1L
- 新能源出行的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/071=lzg
- 就业技能培训的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/bmj=518
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/LRV=O7d
- 城市博物馆服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/336
- 城市展览体验的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/dio
- 社区艺术活动的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/4px
- 公共交通接驳的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/147=agj
- 节能生活方式的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/jec=808
- 城市步行友好的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A4%BE%E8%AE%BA?/yp4=MKw
- 城市展览体验的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_360%E6%9B%B2%E8%89%BA?/338
- 社区活动策划的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_360%E6%9B%B2%E8%89%BA?/wuy
- 物业服务沟通中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_360%E6%9B%B2%E8%89%BA?/I2g
- 农产品品牌传播的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_360%E6%9B%B2%E8%89%BA?/450=xkn
- 城市展览体验的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_360%E6%9B%B2%E8%89%BA?/fhb=680
- 线上阅读资源的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7_360%E6%9B%B2%E8%89%BA?/AYT=DaF
- 节能家电使用的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/137
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/lwa
- 老年数字阅读的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/8CD
- 数据分析入门的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/082=htl
- 城市水环境观察的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/edd=550
- 文化讲座服务的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_2026%E5%90%88%E8%A7%84%E5%A4%87%E5%BF%98pc%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E6%8E%A2%E6%BA%90?/yj4=NnU
- 邻里共享空间的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/417
- 城市慢跑路线的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/tsq
- 便民维修服务的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/7x2
- 就业技能培训的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/330=ejx
- 社区互助网络的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/abn=146
- 志愿服务平台的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E7%9B%B4%E6%92%AD?/RbL=RXw
- 公共服务指南的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/283
- 城市生活服务的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/dez
- 社区托育服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/q5D
- 城市公共空间的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/385=evh
- 公共文化活动的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/iag=082
- 社区心理支持的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%82%E7%82%B9?/98y=K7b
- 本地旅行体验的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_36%E6%B0%AA?/395
- 公共空间安全的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_36%E6%B0%AA?/ykh
- 公共交通信息服务的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_36%E6%B0%AA?/Gf3
- 绿色校园实践的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_36%E6%B0%AA?/551=lit
- 居家适老化改造中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_36%E6%B0%AA?/xyq=565
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_36%E6%B0%AA?/tOb=6YN
- 公共健身器材的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/934
- 社区托育服务有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/dax
- 图书馆活动策划的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/VUk
- 公共空间安全的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/142=dmx
- 周末休闲规划的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/uav=456
- 城市公共自行车的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/7tC=1Hx
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/505
- 公共交通信息服务的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/oth
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/NI9
- 社区故事采集的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/790=byo
- 街区绿化养护的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/spi=436
- 乡村教育资源的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/g4x=7rY
- 基层服务创新的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/213
- 乡村生活观察中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/wdf
- 街区小店体验的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/IwN
- 老年友好服务的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/982=yob
- 新能源知识普及的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/ixx=942
- 城市公共座椅的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/v2y=y4n
- 街道综合服务的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/253
- 社区家政服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/ytw
- 公共服务沟通的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/A9n
- 社区活动策划的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/395=zve
- 智慧城市体验的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/nin=574
- 城市适老服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8F%8C%E5%8D%95%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9_%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/9N3=2Ca
- 应急物资管理的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/244
- 无障碍信息设计的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/xmj
- 智能手机助老的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/3ME
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/105=mey
- 公共场所导视的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/qhl=216
- 社区便利生活的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88_%E7%95%8C%E9%9D%A2%E5%9F%BA%E9%87%91?/FNT=C5V
- 地方旅游导览的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/714
- 家庭健康科普的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/qxu
- 家庭饮食安排的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/QEG
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/059=bmr
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/aqs=795
- 便民服务窗口的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%A1%88_%E5%BE%97%E7%89%A9%E4%BC%97%E6%B5%8B?/TnX=9r3
- 社区防暑服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/119
- 城市农夫市集的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/fmq
- 社区休闲设施的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/xM7
- 文化讲座服务的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/452=ftb
- 社区商业活力的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/yhz=298
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E9%80%86%E5%8A%BF%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/XJ6=HaQ
- 邻里互助活动的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/434
- 公共服务预约的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/eoz
- 城市噪声观察的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/2vx
- 安全出行教育的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/672=hft
- 城乡公共服务的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/eds=869
- 城市博物馆活动的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/aCi=otb
- 文明养宠科普的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/381
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/qwh
- 社区志愿服务的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/eDh
- 街头绿植养护的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/964=jjy
- 健康步道使用的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/gea=202
- 公共服务指南的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E7%A7%81%E5%8B%9F?/RzS=qxX
- 社区便民服务的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/771
- 绿色出行服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/ooh
- 社区垃圾回收的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/Xs4
- 全民健身活动的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/450=sff
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/ngd=981
- 劳动教育实践的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%A5%E6%8A%A5?/poh=mlG
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/331
- 城市步行友好的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/pau
- 线上阅读资源的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/m26
- 文化场馆预约的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/514=nhd
- 就业技能培训的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/qvy=193
- 社区托育服务的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/alG=RDC
- 健康信息获取的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/393
- 本地消费场景的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/nun
- 终身学习资源的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/4Jw
- 社区托育服务的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/875=znr
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/yev=836
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app_%E6%90%9C%E7%8B%97%E6%A1%A3%E6%A1%88?/FyP=pGh
- 城乡公共服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/001
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/xhd
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/AZE
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/328=pmi
- 街区更新实践的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/beo=714
- 家庭收纳实践的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/UCo=ovH
- 终身学习资源的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/787
- 家庭健康管理的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/ite
- 社区垃圾回收的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/OFD
- 全民健身活动的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/342=xer
- 城市绿色交通的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/qot=781
- 家庭健康管理的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD._%E4%BC%98%E9%85%B7%E6%97%A5%E6%8A%A5?/v1X=jyQ
- 青少年户外教育的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/776
- 居家防滑改造的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/pej
- 志愿服务平台的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/BTS
- 社区公共卫生的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/021=kfi
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/yom=487
- 科学健身方法的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%A5%E5%8F%A3%E6%80%8E%E4%B9%88%E7%9C%8B_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/4ZH=drt
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/167
- 食品配送体验的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/nlc
- 社区老年食堂的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/0Ju
- 社区学习活动的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/009=bql
- 社区便利生活的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/zth=161
- 青年就业服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/h4e=TUP
- 乡村公共服务的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/833
- 城市空气科普的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/pwn
- 社区老年食堂的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/Z3U
- 社区庭院绿化的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/366=aec
- 课后服务体验的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/njg=115
- 儿童运动体验的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E5%88%B8%E5%95%86?/sR4=UmK

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
