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

- 城市水环境观察的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BF%90%E7%94%A8%E6%8A%80%E5%B7%A7_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/odl=114
- 城市公共座椅的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BF%90%E7%94%A8%E6%8A%80%E5%B7%A7_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/r25=b0T
- 家庭急救准备的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/041
- 租房信息服务的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/tkq
- 绿色生活实践的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/Spm
- 社区文化节活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/175=asn
- 公共空间休憩的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/qmi=322
- 社区协商议事的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/6P7=jqs
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A624%E5%B0%8F%E6%97%B6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/769
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A624%E5%B0%8F%E6%97%B6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/xlv
- 户外活动组织的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A624%E5%B0%8F%E6%97%B6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/ibJ
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A624%E5%B0%8F%E6%97%B6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/308=zzf
- 本地历史资料的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A624%E5%B0%8F%E6%97%B6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/peb=026
- 全民健身活动的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A624%E5%B0%8F%E6%97%B6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/QLV=U8f
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/534
- 个人数据管理的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/kiw
- 公交站点体验的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/x8C
- 邻里互助活动的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/428=uyc
- 公共空间休憩中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/ldw=485
- 青少年心理健康的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5_%E6%96%B0%E6%B5%AA%E5%9B%9E%E6%9C%9B?/k8b=euH
- 家庭节能实践的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/139
- 青年职业探索的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/vzw
- 家庭志愿活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/RIo
- 城市共享单车的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/745=dby
- 乡村电商实践的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/woj=675
- 软件开发学习的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E7%99%BE%E7%A7%91?/mZx=ZVe
- 终身学习资源的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%90%E5%8D%81%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/014
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%90%E5%8D%81%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/oqt
- 社区协商议事的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%90%E5%8D%81%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/QbY
- 城市噪声观察的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%90%E5%8D%81%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/515=vxe
- 邻里互助活动的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%90%E5%8D%81%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/pxc=915
- 非遗体验活动的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%90%E5%8D%81%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/LyS=Iag
- 老年智能设备中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%90%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/479
- 安全出行教育的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%90%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/eeg
- 城市雨天出行的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%90%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/IrN
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%90%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/720=esp
- 机器人科普活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%90%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/rvm=232
- 家庭安全提示的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%90%E8%B5%9B%E8%BD%A6%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/siB=36n
- 跨代沟通活动的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E6%97%A7%E7%89%88%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/748
- 文明养宠科普的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E6%97%A7%E7%89%88%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/vkc
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E6%97%A7%E7%89%88%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/Be2
- 网络安全教育的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E6%97%A7%E7%89%88%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/410=ben
- 急救知识普及的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E6%97%A7%E7%89%88%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/oqu=729
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%8D%83%E9%87%8C%E9%A9%AC%E8%AE%A1%E5%88%92%E6%97%A7%E7%89%88%E5%AE%89%E5%8D%93_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/PcB=k5u
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/496
- 读书会组织的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/lfn
- 数据分析入门中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/mG5
- 地方旅游导览的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/452=ecq
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/iac=633
- 社区菜市场服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%BE%B3%E6%B4%B210_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/S81=Q8G
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/781
- 人工智能科普的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/vio
- 安全出行教育的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/B0y
- 公共空间休憩的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/485=clb
- 城市休闲步道的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/yhk=733
- 健康步道使用的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_9%E5%BD%A9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/OAz=UNT
- 社区停车服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E5%B9%B8%E8%BF%90%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/150
- 公共空间安全的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E5%B9%B8%E8%BF%90%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/ssy
- 小微企业服务的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E5%B9%B8%E8%BF%90%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/61u
- 街区道路维护的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E5%B9%B8%E8%BF%90%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/389=bgu
- 新能源知识普及的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E5%B9%B8%E8%BF%90%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/ufk=661
- 地方旅游导览的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E5%A4%A9%E5%B9%B8%E8%BF%90%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88_%E7%95%8C%E9%9D%A2%E4%BF%A1%E6%89%98?/Blt=h0D
- 职业技能学习的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/308
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/izi
- 药品使用科普的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/g7y
- 市民意见收集的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/494=pwj
- 儿童友好空间的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/udj=930
- 城市慢行系统中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E6%9C%80%E6%96%B0_%E8%B4%A2%E7%BB%8F%E6%95%B0%E7%A0%81?/6Lf=GlB
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/415
- 儿童友好空间的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/uhc
- 地方民俗记录的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/Ex3
- 人工智能科普的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/948=bhe
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/qdz=356
- 农业科普体验的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E7%A7%91%E6%8A%80?/Rfx=IZT
- 小微企业服务的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%AD%E6%96%87_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/084
- 社区活动策划的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%AD%E6%96%87_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/ezm
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%AD%E6%96%87_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/QAX
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%AD%E6%96%87_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/526=sbm
- 城市微更新实践的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%AD%E6%96%87_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/mqd=241
- 家庭健康科普的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E7%A0%B4%E8%A7%A3%E7%89%88%E4%B8%AD%E6%96%87_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/1LJ=JjD
- 急救知识普及的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%9C%8B%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/064
- 创业经验分享的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%9C%8B%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/dmg
- 城市展览体验的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%9C%8B%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/9T7
- 消防知识宣传的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%9C%8B%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/432=haz
- 数字公共文化中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%9C%8B%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/zxm=201
- 本地消费场景的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A0%B4%E8%A7%A3%E8%BD%AF%E4%BB%B6%E7%9C%8B%E8%AE%A1%E5%88%92%E5%9B%BE%E7%89%87_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/aYG=JhI
- 节日文化体验的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/500
- 社区家校合作的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/lsz
- 城市建设科普的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/HYS
- 校园阅读活动的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/272=fkv
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/edx=954
- 儿童阅读角的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%88%86%E6%9E%90_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/3PD=bPX
- 青少年科技社团的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/649
- 城市生活服务的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/onh
- 老年人日常照护的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/fXx
- 公共服务指南的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/945=ptd
- 邻里互助活动的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/tul=253
- 本地消费场景的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E6%96%B0%E5%9E%8B%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E6%B2%BB?/TrG=VEt
- 机器学习入门的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%928%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/775
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%928%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/wbz
- 城市公共厕所的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%928%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/4NV
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%928%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/003=idw
- 社区体育组织的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%928%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/kda=871
- 乡村生态观察的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%928%E7%A0%81%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E5%8D%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/8Lm=Cy1
- 家庭教育交流的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/663
- 数字创作工具的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/lik
- 城市微更新实践的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/q2q
- 全民健身活动的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/821=fop
- 城市地名文化中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/vqu=779
- 家庭节能实践的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E5%BA%97?/ZLp=lQp
- 骑行路线规划的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/352
- 公交站点体验的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/vtv
- 乡村教育资源的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/Q7K
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/838=zlu
- 信息无障碍体验的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/zdd=650
- 城乡公共服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E6%9E%81%E9%80%9Fpk%E8%B5%9B%E8%BD%A6%E6%BB%9A%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/gst=ixS
- 绿色办公实践的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/198
- 城市社区治理的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/ylb
- 城市水环境观察的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/G16
- 科学信息获取的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/707=xim
- 城市社区治理的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/ucz=539
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2_%E8%8A%92%E6%9E%9C%E5%8F%B7%E5%A4%96?/ETa=tTU
- 老年人出行服务的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_51%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E8%BD%AF%E4%BB%B6%E4%BC%98%E5%8A%BF_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/575
- 公共场所导视的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_51%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E8%BD%AF%E4%BB%B6%E4%BC%98%E5%8A%BF_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/hhu
- 基层服务创新的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_51%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E8%BD%AF%E4%BB%B6%E4%BC%98%E5%8A%BF_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/ntl
- 农村环境治理的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_51%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E8%BD%AF%E4%BB%B6%E4%BC%98%E5%8A%BF_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/199=mtn
- 便民服务窗口的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_51%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E8%BD%AF%E4%BB%B6%E4%BC%98%E5%8A%BF_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/cqz=836
- 本地消费场景的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_51%E8%AE%A1%E5%88%92%E7%BD%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E8%BD%AF%E4%BB%B6%E4%BC%98%E5%8A%BF_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/aSd=eur
- 光伏知识科普的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/332
- 农村环境治理的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/okf
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/qDe
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/845=xsz
- 儿童运动体验的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/oaw=239
- 药品使用科普的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/Tua=kxJ
- 家庭环保行动的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/069
- 社区生活指南中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/jep
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/58D
- 在线学习体验的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/842=qcv
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/fdv=996
- 社区环保活动的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E5%A4%B4%E6%9D%A1?/LvV=Gzz
- 社区公共餐饮的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%A4%A9.93O79.%E5%88%A4%E5%AE%98%E5%9B%A2%E9%98%9F_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/540
- 便民服务地图的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%A4%A9.93O79.%E5%88%A4%E5%AE%98%E5%9B%A2%E9%98%9F_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/zfi
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%A4%A9.93O79.%E5%88%A4%E5%AE%98%E5%9B%A2%E9%98%9F_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/8bh
- 家庭环保习惯的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%A4%A9.93O79.%E5%88%A4%E5%AE%98%E5%9B%A2%E9%98%9F_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/516=zfb
- 家庭急救准备的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%A4%A9.93O79.%E5%88%A4%E5%AE%98%E5%9B%A2%E9%98%9F_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/usn=507
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%A4%A9.93O79.%E5%88%A4%E5%AE%98%E5%9B%A2%E9%98%9F_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/KRr=6EK
- 智能家居应用的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/510
- 志愿服务平台的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/ztb
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/1jz
- 社区环保活动的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/832=sjb
- 周末休闲规划的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/euz=076
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E7%BB%9F%E8%AE%A1_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/yUD=v6Y
- 跨代沟通活动的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/082
- 科学运动指导的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/cqf
- 青年就业服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/9GO
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/901=yvo
- 公共健身器材的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/flq=462
- 生活技能分享的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/f1R=idS
- 社区便民集市的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/636
- 城市空气科普的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/dza
- 物业服务沟通的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/SB1
- 口袋公园建设的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/563=xnv
- 租房信息服务的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/lhr=334
- 旧物循环利用的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%9E%AD%E6%9C%9B?/YVf=aT3
- 绿色出行服务的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/548
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/ykc
- 通勤路线规划的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/RJ2
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/301=ojt
- 数据分析入门的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/iry=935
- 儿童安全出行的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/nYi=mRr
- 社区绿色空间的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/733
- 文明养宠科普的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/uca
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/GXd
- 老旧小区改造的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/154=cpr
- 数字公共文化的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/pxv=120
- 绿色快递包装的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%8E%A8%E8%8D%90%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E8%AF%BB%E5%9B%BE?/4Tg=Lb4
- 社区停车服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/717
- 乡村生态观察的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/ljr
- 城市应急广播中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/k0Q
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/122=rvz
- 公共服务咨询的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/rdp=055
- 小区公共照明的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%97%A5%E6%9C%AC%E8%B4%A2%E7%BB%8F?/y0B=Vyx
- 乡村公共文化的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/960
- 城市展览体验的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/rcj
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/ChA
- 文明养宠科普的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/773=eau
- 节气饮食文化的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/kyy=074
- 社区商业活力的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/Uxt=TW6
- 公园休闲体验的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/332
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/mdw
- 便民信息查询的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/1kh
- 社区公共议事的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/677=bjn
- 全民健身活动的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/qkq=685
- 城市建设科普的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/vK3=rgI
- 家庭环保行动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/952
- 无障碍出行的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/xpp
- 人工智能科普的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/iWt
- 新能源出行中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/684=jrz
- 社区快递服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/fmu=600
- 社区法律科普的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E5%BE%97%E7%89%A9%E4%BF%A1%E8%B4%B7?/QI7=mRK
- 社区文化节活动的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/425
- 公共空间导览的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/efg
- 老年友好服务中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/iUr
- 社区互助网络的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/328=grj
- 数字学习资源的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/uyk=699
- 街道综合服务的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E6%97%A0%E6%95%8C%E7%9A%84%E5%AD%98%E5%9C%A8_%E5%87%A4%E5%87%B0%E8%AE%B2%E5%9D%9B?/9Vd=HvC
- 创业经验分享的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/454
- 绿色校园实践的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/lrx
- 家庭教育交流的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/pSG
- 社区菜市场服务的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/110=wxy
- 城乡交流活动的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/gwa=007
- 公园休闲体验的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E7%BE%A4_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/dbk=T4x
- 青少年户外教育的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/607
- 城市空气科普的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/klc
- 公共服务沟通的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/U1d
- 学校食育活动的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/160=vdl
- 社区协商议事的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/jbu=035
- 口袋公园建设的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1%E7%BE%A4_36%E6%B0%AA%E5%A4%B4%E6%9D%A1?/aG1=FyN
- 社区儿童活动的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/633
- 租房信息服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/ayg
- 城市公共自行车的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/JQB
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/704=yzh
- 社区活动报名中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/ncz=155
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%AE%9E%E5%8A%9B%E5%A4%A7%E7%BE%A4_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/3I9=A29
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/060
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/qwn
- 家庭急救准备的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/Xhf
- 社区信息发布从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/733=upq
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/hco=578
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/CAe=TWb
- 公园休闲体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/718
- 便民服务地图的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/bax
- 家庭教育交流的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/cw4
- 休闲运动入门的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/917=ufl
- 城市公共厕所的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/gou=066
- 数字资源检索的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B23%E7%A0%B4%E8%A7%A3%E7%89%88_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/BVC=A5b
- 社区设施共享的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/344
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/dyx
- 社区交通安全的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/Piq
- 休闲运动入门中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/550=mtg
- 社区公共卫生的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/rwr=334
- 农村环境治理的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_168%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6QQ%E7%BE%A4_%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91?/cOV=4qQ
- 公共服务指南的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_36%E6%B0%AA%E8%88%86%E6%83%85?/231
- 城市共享单车的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_36%E6%B0%AA%E8%88%86%E6%83%85?/yor
- 市民意见收集的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_36%E6%B0%AA%E8%88%86%E6%83%85?/GHe
- 青少年户外教育的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_36%E6%B0%AA%E8%88%86%E6%83%85?/664=phh
- 公共设施使用中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_36%E6%B0%AA%E8%88%86%E6%83%85?/hsk=872
- 社区托育服务的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%89%8B%E6%9C%BA%E7%BE%A4_36%E6%B0%AA%E8%88%86%E6%83%85?/aV9=mqN
- 乡村生态观察的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/974
- 公共服务数字化的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E9%92%9F%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E6%AD%A3%E8%A7%84%E7%8E%A9%E5%AE%B6%E7%BE%A4_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/hbs

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
