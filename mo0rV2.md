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

- 健康信息获取的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%83%BD%E5%81%9A%E5%81%87%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/Y0j
- 儿童安全出行的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%83%BD%E5%81%9A%E5%81%87%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/608=ucj
- 居家适老化改造的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%83%BD%E5%81%9A%E5%81%87%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/ncu=064
- 公共服务预约的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%83%BD%E5%81%9A%E5%81%87%E5%90%97_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/7xf=OwM
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E4%BA%86%E5%A5%BD%E5%87%A0%E4%B8%AA%E8%B4%A6%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/033
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E4%BA%86%E5%A5%BD%E5%87%A0%E4%B8%AA%E8%B4%A6%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/cyg
- 租房信息服务的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E4%BA%86%E5%A5%BD%E5%87%A0%E4%B8%AA%E8%B4%A6%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/h1P
- 便民信息查询的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E4%BA%86%E5%A5%BD%E5%87%A0%E4%B8%AA%E8%B4%A6%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/898=rnk
- 食品安全科普的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E4%BA%86%E5%A5%BD%E5%87%A0%E4%B8%AA%E8%B4%A6%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/jkg=193
- 电子商务服务的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E4%BA%86%E5%A5%BD%E5%87%A0%E4%B8%AA%E8%B4%A6%E5%8F%B7_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/FZq=y2Z
- 社区志愿服务的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%80%E4%B8%8B%E5%A4%A7%E6%B3%A8%E5%B0%B1%E4%B8%8D%E4%B8%AD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/386
- 家庭安全提示的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%80%E4%B8%8B%E5%A4%A7%E6%B3%A8%E5%B0%B1%E4%B8%8D%E4%B8%AD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/nbg
- 社区老年食堂的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%80%E4%B8%8B%E5%A4%A7%E6%B3%A8%E5%B0%B1%E4%B8%8D%E4%B8%AD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/oH8
- 校园阅读活动的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%80%E4%B8%8B%E5%A4%A7%E6%B3%A8%E5%B0%B1%E4%B8%8D%E4%B8%AD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/720=thf
- 城市绿道建设的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%80%E4%B8%8B%E5%A4%A7%E6%B3%A8%E5%B0%B1%E4%B8%8D%E4%B8%AD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dmw=062
- 青年职业探索的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%80%E4%B8%8B%E5%A4%A7%E6%B3%A8%E5%B0%B1%E4%B8%8D%E4%B8%AD_%E8%A1%8C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/yaY=mxw
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E8%BF%91%E4%B8%A4%E7%99%BE%E4%B8%87%E5%91%8A%E7%A0%B4_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/937
- 家庭健康管理的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E8%BF%91%E4%B8%A4%E7%99%BE%E4%B8%87%E5%91%8A%E7%A0%B4_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/cqj
- 公共交通接驳的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E8%BF%91%E4%B8%A4%E7%99%BE%E4%B8%87%E5%91%8A%E7%A0%B4_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/Kdq
- 社区活动报名的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E8%BF%91%E4%B8%A4%E7%99%BE%E4%B8%87%E5%91%8A%E7%A0%B4_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/118=bfw
- 城市应急科普的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E8%BF%91%E4%B8%A4%E7%99%BE%E4%B8%87%E5%91%8A%E7%A0%B4_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/upk=794
- 药品使用科普的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E8%BF%91%E4%B8%A4%E7%99%BE%E4%B8%87%E5%91%8A%E7%A0%B4_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/94R=R2B
- 城市夜间生活的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/692
- 城市公共空间的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/kka
- 数字创作工具的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/MTZ
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/744=znw
- 城市公共自行车的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/duu=426
- 课后服务体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%81%E5%A4%A7%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/Y6J=GyN
- 数字便民地图的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%B3%A8%E5%86%8C%E6%88%90%E5%8A%9F%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/002
- 社区公共议事的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%B3%A8%E5%86%8C%E6%88%90%E5%8A%9F%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/mam
- 便民维修服务的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%B3%A8%E5%86%8C%E6%88%90%E5%8A%9F%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/Oi9
- 城市公共自行车的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%B3%A8%E5%86%8C%E6%88%90%E5%8A%9F%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/049=xyr
- 社区活动空间的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%B3%A8%E5%86%8C%E6%88%90%E5%8A%9F%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/slg=868
- 消防知识宣传的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E6%B3%A8%E5%86%8C%E6%88%90%E5%8A%9F%E9%80%8138%E5%85%83%E5%BD%A9%E9%87%91_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/MZm=b0M
- 邻里互助活动的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_pg%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/340
- 数字支付体验的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_pg%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/pzr
- 骑行路线规划的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_pg%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/dIS
- 儿童友好空间的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_pg%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/195=act
- 街头绿植养护的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_pg%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/ofv=504
- 青少年户外教育的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_pg%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/Z73=zzp
- 社区读书角建设的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/004
- 休闲运动入门的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/ady
- 开源技术交流的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/ylk
- 社区信息发布的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/389=wsm
- 垃圾分类指导的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/pjl=725
- 安全出行教育的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/yv1=S2C
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1_360%E8%BF%B0%E8%AF%84?/034
- 城市水环境观察的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1_360%E8%BF%B0%E8%AF%84?/vyr
- 节能家电使用的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1_360%E8%BF%B0%E8%AF%84?/KjS
- 儿童友好空间的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1_360%E8%BF%B0%E8%AF%84?/700=xrp
- 绿色办公实践的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1_360%E8%BF%B0%E8%AF%84?/lch=410
- 文化场馆预约的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%88%B0%E5%BE%AE%E4%BF%A1_360%E8%BF%B0%E8%AF%84?/lzk=M5U
- 校园阅读活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%9B%B4%E6%8E%A5%E6%8F%90%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/396
- 公园休闲体验的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%9B%B4%E6%8E%A5%E6%8F%90%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/qlo
- 社区活动策划的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%9B%B4%E6%8E%A5%E6%8F%90%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/qp2
- 社区儿童活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%9B%B4%E6%8E%A5%E6%8F%90%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/157=uku
- 终身学习资源的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%9B%B4%E6%8E%A5%E6%8F%90%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/bzv=122
- 乡村生态旅游的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%9B%B4%E6%8E%A5%E6%8F%90%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/mWh=sHW
- 城市可持续生活的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/594
- 公共卫生设施的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/rlh
- 个人数据管理的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/guO
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/989=mor
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/oxi=346
- 社区体育组织的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%A0%B4%E8%A7%A3%E7%89%88_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/03O=v4O
- 老年学习活动的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%B3%A8%E9%94%80%E8%B4%A6%E5%8F%B7_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/455
- 旧物循环利用的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%B3%A8%E9%94%80%E8%B4%A6%E5%8F%B7_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/ocq
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%B3%A8%E9%94%80%E8%B4%A6%E5%8F%B7_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/Ii6
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%B3%A8%E9%94%80%E8%B4%A6%E5%8F%B7_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/815=ovs
- 社区设施共享的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%B3%A8%E9%94%80%E8%B4%A6%E5%8F%B7_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/wnt=853
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E6%80%8E%E4%B9%88%E6%B3%A8%E9%94%80%E8%B4%A6%E5%8F%B7_%E6%90%9C%E7%8B%90%E8%AF%BB%E6%8A%A5?/JYO=7it
- 非遗体验活动的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%BB%91%E5%AE%9A%E6%89%8B%E6%9C%BA%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/479
- 农业科普体验的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%BB%91%E5%AE%9A%E6%89%8B%E6%9C%BA%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/lrm
- 青少年科普实践的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%BB%91%E5%AE%9A%E6%89%8B%E6%9C%BA%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/suP
- 科学教育活动的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%BB%91%E5%AE%9A%E6%89%8B%E6%9C%BA%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/056=ojz
- 公共交通接驳的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%BB%91%E5%AE%9A%E6%89%8B%E6%9C%BA%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/yao=652
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E7%BB%91%E5%AE%9A%E6%89%8B%E6%9C%BA%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%AC%E4%B8%9C%E7%90%86%E8%B4%A2?/30n=bjX
- 租房信息服务的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E8%A6%81%E6%88%91%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E5%B9%B2%E4%BB%80%E4%B9%88_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%91%8A?/361
- 光伏知识科普的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E8%A6%81%E6%88%91%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E5%B9%B2%E4%BB%80%E4%B9%88_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%91%8A?/mvk
- 公共健身器材的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E8%A6%81%E6%88%91%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E5%B9%B2%E4%BB%80%E4%B9%88_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%91%8A?/Lr5
- 消防知识宣传的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E8%A6%81%E6%88%91%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E5%B9%B2%E4%BB%80%E4%B9%88_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%91%8A?/596=fiu
- 公共服务数字化的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E8%A6%81%E6%88%91%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E5%B9%B2%E4%BB%80%E4%B9%88_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%91%8A?/qgf=750
- 数字学习资源的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E8%A6%81%E6%88%91%E6%89%8B%E6%8C%81%E8%BA%AB%E4%BB%BD%E8%AF%81%E5%B9%B2%E4%BB%80%E4%B9%88_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%91%8A?/3pu=kTv
- 数字阅读服务的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%90%9E%E9%92%B1%E7%9A%84%E8%B7%AF%E5%AD%90%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/107
- 老年人文化生活的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%90%9E%E9%92%B1%E7%9A%84%E8%B7%AF%E5%AD%90%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/svy
- 智能手机助老的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%90%9E%E9%92%B1%E7%9A%84%E8%B7%AF%E5%AD%90%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/CLh
- 公共场所导视的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%90%9E%E9%92%B1%E7%9A%84%E8%B7%AF%E5%AD%90%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/878=vna
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%90%9E%E9%92%B1%E7%9A%84%E8%B7%AF%E5%AD%90%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/sqi=615
- 社区公共议事的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E6%90%9E%E9%92%B1%E7%9A%84%E8%B7%AF%E5%AD%90%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E5%A4%B4%E6%9D%A1?/2uB=2sL
- 青年志愿活动的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/558
- 城市公共座椅的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/rsx
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/UxF
- 绿色快递包装的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/945=fbx
- 健康饮水科普的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/scv=734
- 地方美食文化的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/WPv=k5q
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%8F%8D%E6%B0%B4%E6%97%A5%E8%B5%9A3000_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/971
- 数字创作工具的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%8F%8D%E6%B0%B4%E6%97%A5%E8%B5%9A3000_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/pnr
- 城乡公共服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%8F%8D%E6%B0%B4%E6%97%A5%E8%B5%9A3000_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/xZa
- 食品配送体验的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%8F%8D%E6%B0%B4%E6%97%A5%E8%B5%9A3000_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/290=mgs
- 个人时间管理的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%8F%8D%E6%B0%B4%E6%97%A5%E8%B5%9A3000_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/jlx=241
- 公共服务预约从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%8F%8D%E6%B0%B4%E6%97%A5%E8%B5%9A3000_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/Y90=fbc
- 街区小店体验的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BF%9D%E6%8C%81%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9%E5%91%A2_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/044
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BF%9D%E6%8C%81%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9%E5%91%A2_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/lkd
- 公交无障碍服务的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BF%9D%E6%8C%81%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9%E5%91%A2_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/bGy
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BF%9D%E6%8C%81%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9%E5%91%A2_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/667=vqo
- 物业服务沟通的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BF%9D%E6%8C%81%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9%E5%91%A2_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/xzt=145
- 公共服务评价中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BF%9D%E6%8C%81%E6%AF%8F%E5%A4%A9%E7%9B%88%E5%88%A9%E5%91%A2_%E4%BC%98%E9%85%B7%E8%B5%84%E8%AE%AF?/kDa=W04
- 运动安全知识的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BD%9C%E5%BC%8A%E7%9A%84_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/404
- 校园节能行动的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BD%9C%E5%BC%8A%E7%9A%84_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/gup
- 乡村公共服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BD%9C%E5%BC%8A%E7%9A%84_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/pcT
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BD%9C%E5%BC%8A%E7%9A%84_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/602=enp
- 数字支付体验的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BD%9C%E5%BC%8A%E7%9A%84_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/poi=039
- 社区教育资源的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%80%8E%E4%B9%88%E4%BD%9C%E5%BC%8A%E7%9A%84_%E9%9B%85%E8%99%8E%E7%A7%81%E5%8B%9F?/VO5=WYE
- 社区协商议事的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F%E5%90%97_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/590
- 公共空间休憩的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F%E5%90%97_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/wzs
- 校园节能行动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F%E5%90%97_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/4Z6
- 城市公共饮水的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F%E5%90%97_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/986=cbr
- 便民服务窗口的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F%E5%90%97_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/rar=406
- 线上办事服务的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%BF%AB%E4%B8%89%E6%98%AF%E6%9D%80%E5%A4%A7%E8%B5%94%E5%B0%8F%E5%90%97_%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/qlB=nh4
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E7%BD%AA%E9%87%8F%E5%88%91%E6%A0%87%E5%87%862024%E6%9C%80%E6%96%B0_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/595
- 周末休闲规划的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E7%BD%AA%E9%87%8F%E5%88%91%E6%A0%87%E5%87%862024%E6%9C%80%E6%96%B0_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/sev
- 亲子科普活动的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E7%BD%AA%E9%87%8F%E5%88%91%E6%A0%87%E5%87%862024%E6%9C%80%E6%96%B0_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/hbt
- 社区读书角建设的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E7%BD%AA%E9%87%8F%E5%88%91%E6%A0%87%E5%87%862024%E6%9C%80%E6%96%B0_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/814=umj
- 社区交通安全的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E7%BD%AA%E9%87%8F%E5%88%91%E6%A0%87%E5%87%862024%E6%9C%80%E6%96%B0_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/yel=902
- 网络安全教育的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E8%B5%8C%E5%8D%9A%E7%BD%AA%E9%87%8F%E5%88%91%E6%A0%87%E5%87%862024%E6%9C%80%E6%96%B0_%E5%BE%97%E7%89%A9%E5%8E%86%E5%8F%B2?/NYC=90E
- 科学信息获取的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/556
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/ccj
- 城市公共厕所的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/8zU
- 城市公共标识的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/834=nhz
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/hlc=817
- 家庭教育交流的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/KHa=r9L
- 校园社团活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%B8%80%E8%88%AC%E6%98%AF%E5%A4%9A%E5%B0%91%E5%A4%A9_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/535
- 儿童友好街区的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%B8%80%E8%88%AC%E6%98%AF%E5%A4%9A%E5%B0%91%E5%A4%A9_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/zmr
- 口袋公园建设的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%B8%80%E8%88%AC%E6%98%AF%E5%A4%9A%E5%B0%91%E5%A4%A9_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/2H9
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%B8%80%E8%88%AC%E6%98%AF%E5%A4%9A%E5%B0%91%E5%A4%A9_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/282=sln
- 社区心理支持的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%B8%80%E8%88%AC%E6%98%AF%E5%A4%9A%E5%B0%91%E5%A4%A9_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/cby=404
- 课后服务体验的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%B8%80%E8%88%AC%E6%98%AF%E5%A4%9A%E5%B0%91%E5%A4%A9_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/aD1=6jL
- 城乡公共服务的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B5%8C%E5%8D%9A%E5%A4%9A%E5%B0%91%E9%92%B1%E8%AE%A4%E5%AE%9A%E4%B8%BA%E8%BF%9D%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/614
- 便民服务地图的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B5%8C%E5%8D%9A%E5%A4%9A%E5%B0%91%E9%92%B1%E8%AE%A4%E5%AE%9A%E4%B8%BA%E8%BF%9D%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/zqf
- 环境教育课程的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B5%8C%E5%8D%9A%E5%A4%9A%E5%B0%91%E9%92%B1%E8%AE%A4%E5%AE%9A%E4%B8%BA%E8%BF%9D%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/Fsh
- 读书会组织的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B5%8C%E5%8D%9A%E5%A4%9A%E5%B0%91%E9%92%B1%E8%AE%A4%E5%AE%9A%E4%B8%BA%E8%BF%9D%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/540=bmy
- 邻里共享空间的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B5%8C%E5%8D%9A%E5%A4%9A%E5%B0%91%E9%92%B1%E8%AE%A4%E5%AE%9A%E4%B8%BA%E8%BF%9D%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/anw=217
- 小区公共照明的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E8%B5%8C%E5%8D%9A%E5%A4%9A%E5%B0%91%E9%92%B1%E8%AE%A4%E5%AE%9A%E4%B8%BA%E8%BF%9D%E6%B3%95_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/ycB=M0n
- 低碳社区实践的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%BC%9A%E6%9C%89%E6%A1%88%E5%BA%95%E5%90%97%E5%AF%B9%E5%AD%90%E5%A5%B3%E6%9C%89%E5%BD%B1%E5%93%8D%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/802
- 城市体育设施的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%BC%9A%E6%9C%89%E6%A1%88%E5%BA%95%E5%90%97%E5%AF%B9%E5%AD%90%E5%A5%B3%E6%9C%89%E5%BD%B1%E5%93%8D%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/uxs
- 社区故事采集的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%BC%9A%E6%9C%89%E6%A1%88%E5%BA%95%E5%90%97%E5%AF%B9%E5%AD%90%E5%A5%B3%E6%9C%89%E5%BD%B1%E5%93%8D%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/RUV
- 老年运动活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%BC%9A%E6%9C%89%E6%A1%88%E5%BA%95%E5%90%97%E5%AF%B9%E5%AD%90%E5%A5%B3%E6%9C%89%E5%BD%B1%E5%93%8D%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/495=bwi
- 老年友好服务的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%BC%9A%E6%9C%89%E6%A1%88%E5%BA%95%E5%90%97%E5%AF%B9%E5%AD%90%E5%A5%B3%E6%9C%89%E5%BD%B1%E5%93%8D%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/dhm=030
- 科学教育活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B5%8C%E5%8D%9A%E6%8B%98%E7%95%99%E4%BC%9A%E6%9C%89%E6%A1%88%E5%BA%95%E5%90%97%E5%AF%B9%E5%AD%90%E5%A5%B3%E6%9C%89%E5%BD%B1%E5%93%8D%E5%90%97_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/sbw=9eg
- 便民服务窗口的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%8D%E8%B4%B9%E8%B5%8C%E5%8D%9Aapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/884
- 家庭节能设备的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%8D%E8%B4%B9%E8%B5%8C%E5%8D%9Aapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/gvg
- 文化场馆预约的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%8D%E8%B4%B9%E8%B5%8C%E5%8D%9Aapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/7Ah
- 社区知识分享的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%8D%E8%B4%B9%E8%B5%8C%E5%8D%9Aapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/599=jjh
- 地方美食文化的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%8D%E8%B4%B9%E8%B5%8C%E5%8D%9Aapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/tvb=695
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%85%8D%E8%B4%B9%E8%B5%8C%E5%8D%9Aapp%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%96%87%E5%BA%93?/mRb=JzO
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8Capp_%E8%84%89%E8%84%89%E6%94%B6%E8%97%8F?/135
- 城市基础设施的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8Capp_%E8%84%89%E8%84%89%E6%94%B6%E8%97%8F?/dcm
- 全民阅读推广的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8Capp_%E8%84%89%E8%84%89%E6%94%B6%E8%97%8F?/klO
- 公共服务预约的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8Capp_%E8%84%89%E8%84%89%E6%94%B6%E8%97%8F?/573=rta
- 本地消费场景的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8Capp_%E8%84%89%E8%84%89%E6%94%B6%E8%97%8F?/wkb=472
- 城市骑行环境的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E7%BD%91%E8%B5%8Capp_%E8%84%89%E8%84%89%E6%94%B6%E8%97%8F?/6K4=IM1
- 志愿者培训交流的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BD%91%E8%B5%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/498
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BD%91%E8%B5%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/ent
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BD%91%E8%B5%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/nkb
- 个人信息保护的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BD%91%E8%B5%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/002=jqy
- 社区消防演练的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BD%91%E8%B5%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/bvh=894
- 社区设施共享的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E4%BF%A1%E8%AA%89%E7%BD%91%E8%B5%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/oeD=Lob
- 公共场所导视的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E8%B5%8C%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8app_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/328
- 健康信息获取的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E8%B5%8C%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8app_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/rwv
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E8%B5%8C%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8app_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/BOa
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E8%B5%8C%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8app_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/615=vbk
- 城市建设科普的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E8%B5%8C%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8app_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/ozk=628
- 城市噪声观察的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E7%BD%91%E8%B5%8C%E5%AE%98%E7%BD%91%E5%A4%A7%E5%85%A8app_%E8%85%BE%E8%AE%AF%E6%9C%8D%E9%A5%B0?/SHN=UUm
- 城市博物馆活动的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_pg%E8%B5%8C%E5%8D%9A%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/179
- 数字资源检索的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_pg%E8%B5%8C%E5%8D%9A%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/nmn
- 便民维修服务的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_pg%E8%B5%8C%E5%8D%9A%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/VLN
- 公共服务评价的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_pg%E8%B5%8C%E5%8D%9A%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/258=oes
- 乡村公共服务的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_pg%E8%B5%8C%E5%8D%9A%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/sln=549
- 地方戏曲体验的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_pg%E8%B5%8C%E5%8D%9A%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp_%E6%8A%96%E9%9F%B3%E5%AE%89%E9%98%B2?/mIo=LWh
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%BA%9A%E6%B4%B2%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E7%AC%AC%E4%B8%80_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/669
- 志愿服务平台的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%BA%9A%E6%B4%B2%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E7%AC%AC%E4%B8%80_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/oqx
- 环境监测科普的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%BA%9A%E6%B4%B2%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E7%AC%AC%E4%B8%80_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/WY4
- 信息无障碍体验的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%BA%9A%E6%B4%B2%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E7%AC%AC%E4%B8%80_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/598=rox
- 社区应急准备的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%BA%9A%E6%B4%B2%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E7%AC%AC%E4%B8%80_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/qpc=598
- 食品安全科普的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E4%BA%9A%E6%B4%B2%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E4%BF%A1%E8%AA%89%E6%8E%92%E5%90%8D%E7%AC%AC%E4%B8%80_%E8%B4%A2%E7%BB%8F%E6%94%BF%E7%AD%96?/dbg=fWF
- 地方民俗记录的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E8%B5%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/715
- 在线教育体验的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E8%B5%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/wrq
- 儿童户外活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E8%B5%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/seG
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E8%B5%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/768=yts
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E8%B5%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/dfp=935
- 公共空间休憩中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%80%81%E5%93%81%E7%89%8C%E7%BD%91%E8%B5%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%BB%E6%8A%A5?/HfP=NuE
- 社区庭院绿化的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%8D%9Apg%E7%94%B5%E5%AD%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/361
- 图书馆数字服务的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%8D%9Apg%E7%94%B5%E5%AD%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/yzy
- 城市文化路线的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%8D%9Apg%E7%94%B5%E5%AD%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/fQw
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%8D%9Apg%E7%94%B5%E5%AD%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/834=dmj
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%8D%9Apg%E7%94%B5%E5%AD%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/wtv=477
- 社区文化传播的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E8%B5%8C%E5%8D%9Apg%E7%94%B5%E5%AD%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E7%BA%AA%E5%AE%9E?/XXt=yZm
- 城市骑行环境的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_pg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BC%97%E6%B5%8B?/904
- 城市文明出行的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_pg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BC%97%E6%B5%8B?/res
- 乡村公共阅读的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_pg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BC%97%E6%B5%8B?/Tm2
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_pg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BC%97%E6%B5%8B?/112=jun
- 课后服务体验的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_pg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BC%97%E6%B5%8B?/cly=431
- 数字学习资源的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_pg%E8%B5%8F%E9%87%91%E5%A5%B3%E7%8E%8B%E7%BD%91%E8%B5%8C%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_360%E4%BC%97%E6%B5%8B?/nDP=ney
- 社区交通安全的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E5%8D%9Aapp%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/587
- 公交站点体验的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E5%8D%9Aapp%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/agw
- 家庭健康管理的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E5%8D%9Aapp%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/kvd
- 药品使用科普的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E5%8D%9Aapp%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/582=qkp
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E5%8D%9Aapp%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/ers=755
- 城市应急科普的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E8%B5%8C%E5%8D%9Aapp%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/Feo=mXf
- 环境教育课程的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/911
- 城市水环境观察的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/jtj
- 校园安全教育的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/1Yd
- 社区体育组织的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/678=tep
- 社区共享书架的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/mjw=263
- 青少年科普实践的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E8%B5%8C%E5%8D%9Aapp%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/HFl=rIF
- 乡村阅读空间的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%B5%8C%E5%8D%9Aapp%E5%89%8D%E5%8D%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/586
- 老年人出行服务的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%B5%8C%E5%8D%9Aapp%E5%89%8D%E5%8D%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/xgr
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%B5%8C%E5%8D%9Aapp%E5%89%8D%E5%8D%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/iRK
- 创业经验分享的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%B5%8C%E5%8D%9Aapp%E5%89%8D%E5%8D%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/512=swn
- 基层健康档案的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%B5%8C%E5%8D%9Aapp%E5%89%8D%E5%8D%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/etq=042
- 节气饮食文化的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%B5%8C%E5%8D%9Aapp%E5%89%8D%E5%8D%81_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/F1T=57E
- 社区活动空间的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%87%BA%E5%90%8D%E7%9A%84%E8%B5%8C%E5%8D%9Aapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/075
- 城市共享单车的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%87%BA%E5%90%8D%E7%9A%84%E8%B5%8C%E5%8D%9Aapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/fdw
- 社区读书角建设的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%87%BA%E5%90%8D%E7%9A%84%E8%B5%8C%E5%8D%9Aapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/9TL
- 家庭教育交流的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%87%BA%E5%90%8D%E7%9A%84%E8%B5%8C%E5%8D%9Aapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/429=hfh
- 绿色快递包装的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%87%BA%E5%90%8D%E7%9A%84%E8%B5%8C%E5%8D%9Aapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/qab=529
- 社区便利生活的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%87%BA%E5%90%8D%E7%9A%84%E8%B5%8C%E5%8D%9Aapp_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%94%90%E8%AF%84?/rAI=IH6
- 图书借阅体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%8B_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/209
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%8B_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/bqo
- 垃圾分类指导的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%8B_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/eJ5
- 应急物资管理的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%8B_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/516=qpx
- 生活垃圾回收的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%8B_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/hts=623
- 数字课堂应用的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E6%8E%A8%E8%8D%90%E4%B8%80%E4%B8%8B_%E6%96%B0%E6%B5%AA%E5%BD%A9%E7%A5%A8?/iA1=wVc
- 运动安全知识的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/631
- 青年志愿活动的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/ivx
- 数字学习资源的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/cyX
- 儿童运动体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/451=dhx
- 科普展览体验的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/qrx=773
- 社区法律科普的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C_%E5%A4%B4%E6%9D%A1%E5%88%8A%E7%99%BB?/hFX=Nru
- 城市便民驿站的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%8A%BC%E6%B3%A8%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/024
- 城市水环境观察的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%8A%BC%E6%B3%A8%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/zdi
- 老年学习活动的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%8A%BC%E6%B3%A8%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/Xno
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%8A%BC%E6%B3%A8%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/359=gmd
- 数字创意课程的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%8A%BC%E6%B3%A8%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/vyh=998
- 社区慢性病防控的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%8A%BC%E6%B3%A8%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%97%A5%E6%8A%A5?/mvb=Tbh
- 城市应急科普的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%85%A8%E7%90%83%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/188
- 青年就业服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%85%A8%E7%90%83%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/cys
- 青少年科技社团的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%85%A8%E7%90%83%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/nOM
- 老年智能设备的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%85%A8%E7%90%83%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/174=lho
- 城乡交流活动的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%85%A8%E7%90%83%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/zdi=794
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%85%A8%E7%90%83%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/TqY=Dxe

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
