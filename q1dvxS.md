# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 读书会组织的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/785
- 个人数据管理的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/min
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/E4V
- 老年人日常照护的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/915=slx
- 市民热线服务的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/jlg=532
- 图书馆亲子空间的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E4%BD%93%E8%82%B2?/w0d=5kx
- 灵活就业交流的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AB%E4%BB%80%E4%B9%88-%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/900
- 社区慢性病防控的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AB%E4%BB%80%E4%B9%88-%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/wig
- 社区防暑服务的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AB%E4%BB%80%E4%B9%88-%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/mK9
- 社区活动策划的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AB%E4%BB%80%E4%B9%88-%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/737=kxd
- 乡村休闲旅游的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AB%E4%BB%80%E4%B9%88-%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/uro=080
- 本地历史资料中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6%E5%8F%AB%E4%BB%80%E4%B9%88-%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/qJK=paj
- 市民热线服务的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92-%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/296
- 休闲运动入门的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92-%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/sof
- 社区公共议事的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92-%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/ZYu
- 社区知识分享的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92-%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/838=dmh
- 就业技能培训的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92-%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/tgu=368
- 家庭科学教育的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E6%80%8E%E4%B9%88%E5%81%9A%E8%AE%A1%E5%88%92-%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/ssx=VpW
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E7%9A%84%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/836
- 老年运动活动的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E7%9A%84%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/vty
- 开源技术交流的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E7%9A%84%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/xOc
- 科学健身方法的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E7%9A%84%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/078=zcz
- 亲子科普活动的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E7%9A%84%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/izl=097
- 社区学习活动的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E7%9A%84%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF%E8%AE%BF%E8%B0%88?/sLj=vbU
- 街区更新实践的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99-%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/890
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99-%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/dnn
- 家庭志愿活动的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99-%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/nSQ
- 社区读书角建设的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99-%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/055=vtz
- 公共服务数字化的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99-%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/tuw=279
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%A6%81%E9%A1%BA%E9%BE%99-%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8A%A1?/pG0=Siw
- 公共设施维护的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A26%E7%A7%8D%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/885
- 社区协商议事的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A26%E7%A7%8D%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/alw
- 儿童户外活动的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A26%E7%A7%8D%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/MN9
- 社区快递服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A26%E7%A7%8D%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/661=gta
- 社区垃圾分类的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A26%E7%A7%8D%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/ffc=700
- 节假日出行安排的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A26%E7%A7%8D%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/CdT=IOt
- 科学信息获取的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/988
- 公共图书馆服务的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/kyo
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/rfw
- 社区故事采集的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/469=nfc
- 终身学习资源的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/tiv=537
- 城市步行友好的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E5%87%86%E7%A1%AE%E7%9A%84%E7%AE%97%E6%B3%95-%E8%99%8E%E5%97%85%E5%8C%BB%E8%8D%AF?/gKa=GYC
- 城市微更新实践的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/103
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/ypr
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/4Ci
- 家庭节能设备的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/161=zrv
- 乡村电商实践的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/jdx=006
- 开放数据应用的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/Jn8=8SQ
- 新能源出行的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/131
- 居家防滑改造的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/pfz
- 绿色校园实践的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/T8k
- 城市生活服务的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/437=nso
- 安全出行教育的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/lum=076
- 青少年科普实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/6GB=iLk
- 老年人日常照护的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BA%84%E9%97%B2%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/236
- 骑行路线规划的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BA%84%E9%97%B2%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/xkv
- 老年人出行服务的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BA%84%E9%97%B2%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/RY7
- 家庭用电安全的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BA%84%E9%97%B2%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/324=leg
- 个人数据管理的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BA%84%E9%97%B2%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/zrq=744
- 智能手机助老的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BA%84%E9%97%B2%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F-%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/tNy=gAm
- 亲子阅读活动的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/604
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/meo
- 小区停车协商的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/t2c
- 公共服务评价的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/988=xee
- 农村环境治理的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/lyd=173
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8-%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/gcy=er9
- 城乡交通衔接的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%95%BF%E9%BE%99%E4%B8%80%E8%88%AC%E6%9C%80%E5%A4%9A%E5%A4%9A%E5%B0%91%E6%9C%9F%E6%89%8D%E4%BC%9A%E6%96%AD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/342
- 全民健身活动的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%95%BF%E9%BE%99%E4%B8%80%E8%88%AC%E6%9C%80%E5%A4%9A%E5%A4%9A%E5%B0%91%E6%9C%9F%E6%89%8D%E4%BC%9A%E6%96%AD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/qlk
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%95%BF%E9%BE%99%E4%B8%80%E8%88%AC%E6%9C%80%E5%A4%9A%E5%A4%9A%E5%B0%91%E6%9C%9F%E6%89%8D%E4%BC%9A%E6%96%AD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/8b3
- 周末休闲规划的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%95%BF%E9%BE%99%E4%B8%80%E8%88%AC%E6%9C%80%E5%A4%9A%E5%A4%9A%E5%B0%91%E6%9C%9F%E6%89%8D%E4%BC%9A%E6%96%AD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/667=nji
- 青少年科技社团的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%95%BF%E9%BE%99%E4%B8%80%E8%88%AC%E6%9C%80%E5%A4%9A%E5%A4%9A%E5%B0%91%E6%9C%9F%E6%89%8D%E4%BC%9A%E6%96%AD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/xdw=732
- 生活垃圾回收的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E9%95%BF%E9%BE%99%E4%B8%80%E8%88%AC%E6%9C%80%E5%A4%9A%E5%A4%9A%E5%B0%91%E6%9C%9F%E6%89%8D%E4%BC%9A%E6%96%AD-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8C%BB%E8%8D%AF?/oQy=DPr
- 城市地名文化的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%A1%BA%E9%BE%99%E7%9A%84%E6%AD%A3%E7%A1%AE%E6%89%93%E6%B3%95-%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/292
- 社区设施共享的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%A1%BA%E9%BE%99%E7%9A%84%E6%AD%A3%E7%A1%AE%E6%89%93%E6%B3%95-%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/yca
- 城市社区治理的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%A1%BA%E9%BE%99%E7%9A%84%E6%AD%A3%E7%A1%AE%E6%89%93%E6%B3%95-%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/L6V
- 数字学习资源的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%A1%BA%E9%BE%99%E7%9A%84%E6%AD%A3%E7%A1%AE%E6%89%93%E6%B3%95-%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/645=vyw
- 家庭阅读计划的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%A1%BA%E9%BE%99%E7%9A%84%E6%AD%A3%E7%A1%AE%E6%89%93%E6%B3%95-%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/nmr=104
- 城市公共艺术的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E9%A1%BA%E9%BE%99%E7%9A%84%E6%AD%A3%E7%A1%AE%E6%89%93%E6%B3%95-%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/iLM=xiO
- 在线教育体验的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/192
- 社区心理支持的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/shf
- 全民健身活动的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/FgQ
- 学校体育活动的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/025=xnz
- 校园节能行动的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/gup=593
- 社区科普课堂的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99-%E8%99%8E%E6%89%91%E6%91%84%E5%BD%B1?/4wd=DIl
- 开源技术交流的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/373
- 便民维修服务的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/imf
- 社区环保活动的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/ghq
- 城市文明实践的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/363=fjt
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/yri=923
- 新能源出行从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA-%E8%85%BE%E8%AE%AF%E5%AE%89%E9%98%B2?/tMP=JBn
- 城市噪声观察的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/407
- 农业科普体验的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/kpn
- 数字地图应用的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/5ra
- 公共健身器材的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/147=kwn
- 街区更新实践的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/lnm=951
- 城市文明出行的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E4%BC%98%E9%85%B7%E5%88%9B%E6%8A%95?/TMv=QoA
- 社区便民集市的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F-%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/745
- 基层健康服务的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F-%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/zay
- 数字档案服务的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F-%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/LQ2
- 老年人日常照护的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F-%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/628=ajd
- 气象科普传播的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F-%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/ote=976
- 社区故事采集的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F-%E6%96%B0%E6%B5%AA%E6%95%B0%E8%AF%BB?/PMy=nip
- 社区休闲设施的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E8%B5%A2%E5%BE%97%E5%A4%9A%E5%90%97-%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/348
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E8%B5%A2%E5%BE%97%E5%A4%9A%E5%90%97-%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/ubc
- 软件开发学习的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E8%B5%A2%E5%BE%97%E5%A4%9A%E5%90%97-%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/3f2
- 城市公共座椅的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E8%B5%A2%E5%BE%97%E5%A4%9A%E5%90%97-%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/206=mfe
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E8%B5%A2%E5%BE%97%E5%A4%9A%E5%90%97-%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/lzb=922
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E8%B5%A2%E5%BE%97%E5%A4%9A%E5%90%97-%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/xnh=rqX
- 地方旅游导览的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/203
- 社区共享书架的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/dcf
- 街头绿植养护的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/58N
- 老年运动活动的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/281=pwm
- 家庭食品保存的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/xem=404
- 健康饮水科普的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E6%96%B9%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/xTZ=BMu
- 城市公共饮水的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%AF%BB%E4%B9%A6?/821
- 儿童户外活动的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%AF%BB%E4%B9%A6?/ccp
- 通勤路线规划的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%AF%BB%E4%B9%A6?/LUS
- 家庭饮食安排的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%AF%BB%E4%B9%A6?/421=imb
- 城市微更新实践的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%AF%BB%E4%B9%A6?/qcl=696
- 社区绿色空间的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%AF%BB%E4%B9%A6?/xYO=q1F
- 社区互助网络的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/498
- 城市生活服务的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/ics
- 课后服务体验的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/iPO
- 公共服务预约的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/996=fmf
- 本地消费场景的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/cbd=651
- 生活服务数字化的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/5oL=6uq
- 口袋公园建设的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/402
- 青少年户外教育的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/coh
- 小区停车协商的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/PcW
- 急救知识普及的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/635=rzy
- 便民服务地图的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/eos=284
- 医院导诊服务的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A0%8D%E9%BE%99%E9%A1%BA%E9%BE%99%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7-%E9%A1%BA%E4%B8%B0%E7%BE%8E%E9%A3%9F?/kLk=Imx
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/212
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/dvg
- 城市可持续生活的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/Xgp
- 城市公共座椅的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/837=mhf
- 社区读书角建设中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/gxd=748
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%BF%98%E6%98%AF%E9%A1%BA%E9%BE%99%E5%A5%BD-%E8%99%8E%E6%89%91%E6%97%B6%E5%B0%9A?/HLe=BxQ
- 青少年心理健康的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99-%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/105
- 绿色办公实践的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99-%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/ish
- 城市基础设施的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99-%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/fOh
- 城市展览体验的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99-%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/626=kvb
- 无障碍信息设计的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99-%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/zwv=010
- 公园亲子设施的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99-%E6%90%9C%E7%8B%90%E4%BA%BA%E7%89%A9?/k8z=f0h
- 节能生活方式的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2-%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/608
- 数字便民地图的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2-%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/wya
- 居家防滑改造的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2-%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/ZUu
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2-%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/664=ehe
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2-%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/cpg=631
- 数字课堂应用的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E7%8E%A9%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E4%B9%88%E6%89%8D%E4%BC%9A%E8%B5%A2-%E5%8D%B3%E5%88%BB%E8%B4%A2%E7%BB%8F?/nzH=VPI
- 个人时间管理的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/965
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/ikr
- 城市运动公园的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/nJ6
- 城市文化路线的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/272=ruc
- 儿童户外活动的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/tzq=101
- 健康饮水科普的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E6%96%87%E5%BA%93?/Fpi=rtR
- 社区文化节活动的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/375
- 农村环境治理的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/she
- 城市公共自行车的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/nVZ
- 职业技能学习的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/379=flq
- 乡村阅读活动的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/xwa=235
- 数字素养提升的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/zOR=wf2
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/335
- 城市共享单车的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/hga
- 老年人文化生活的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/3g8
- 社区健康讲座的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/606=ksv
- 开放式学习空间的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/yxg=853
- 公共设施维护的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E7%A0%8D%E9%BE%99%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/Epm=0gV
- 社区交通安全的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/515
- 城市文明实践的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/iiw
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/Pfq
- 老年友好服务中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/280=jmc
- 社区信息发布的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/bvi=864
- 数据分析入门的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%9C%80%E9%95%BF%E5%A4%9A%E5%B0%91%E6%9C%9F-%E7%9F%A5%E4%B9%8E%E8%B4%A2%E6%8A%A5?/ska=Mrj
- 公园休闲体验的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99-36%E6%B0%AA%E6%B3%95%E5%BE%8B?/041
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99-36%E6%B0%AA%E6%B3%95%E5%BE%8B?/lxz
- 青年职业探索的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99-36%E6%B0%AA%E6%B3%95%E5%BE%8B?/flV
- 社区公共餐饮的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99-36%E6%B0%AA%E6%B3%95%E5%BE%8B?/882=rce
- 家庭安全提示的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99-36%E6%B0%AA%E6%B3%95%E5%BE%8B?/gdd=913
- 社区儿童活动的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%95%BF%E9%BE%99-36%E6%B0%AA%E6%B3%95%E5%BE%8B?/8sU=Oaj
- 数字设备回收的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99-%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/990
- 城市步行环境的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99-%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/aqi
- 公园亲子设施的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99-%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/SR3
- 无障碍信息设计的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99-%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/695=xsy
- 社区设施共享的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99-%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/agp=367
- 社区垃圾回收的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E6%80%8E%E4%B9%88%E9%A1%BA%E9%BE%99-%E8%85%BE%E8%AE%AF%E9%80%9A%E4%BF%A1?/5Ov=Ago
- 农贸市场环境的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F-%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/318
- 骑行路线规划的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F-%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/cow
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F-%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/N2V
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F-%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/226=jdg
- 社区花园共建的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F-%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/doi=656
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E6%80%8E%E6%A0%B7%E6%89%8D%E4%B8%8D%E4%BC%9A%E4%BA%8F-%E5%A4%B4%E6%9D%A1%E5%8C%BB%E8%8D%AF?/naf=vl6
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/886
- 农贸市场环境的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/wrl
- 家庭收纳实践的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/Fd2
- 青少年户外教育的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/522=lsq
- 个人信息保护的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/fvx=250
- 城市文明出行的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E8%83%BD%E4%B8%AD%E5%BD%A9%E7%A5%A8%E7%9A%84%E4%BA%BA%E6%98%AF%E5%91%BD%E4%B8%AD%E6%B3%A8%E5%AE%9A%E5%90%97-%E9%A1%BA%E4%B8%B0%E8%BE%9F%E8%B0%A3?/1WV=81o
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81-%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/620
- 基层健康档案的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81-%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/rtv
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81-%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/OS4
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81-%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/312=jvq
- 消防知识宣传中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81-%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/lgy=382
- 公共空间照明的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E7%8E%A9%E9%BE%99%E5%92%8C%E9%A1%BA%E9%BE%99%E7%9A%84%E5%AF%93%E6%84%8F%E5%92%8C%E8%B1%A1%E5%BE%81-%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/yqq=Q6g
- 农产品消费体验的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/654
- 基层服务创新从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/mcp
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/RtI
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/718=qzs
- 城市环境志愿行动的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/pdj=002
- 社区艺术活动的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%BF%BD%E9%95%BF%E9%BE%99%E7%9A%84%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/nV1=AQ4
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/685
- 数字资源检索的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/rju
- 在线学习体验的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/AYE
- 社区活动报名的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/048=mbw
- 青年职业探索的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/rjr=254
- 数字阅读服务的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E7%8E%A9%E6%89%8D%E4%B8%8D%E8%BE%93%E9%92%B1-%E9%9B%85%E8%99%8E%E5%86%9B%E4%BA%8B?/zhK=OgF
- 公共空间照明的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2-%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/718
- 个人信息保护的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2-%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/gmo
- 老年学习活动的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2-%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/NDr
- 生活服务数字化的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2-%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/272=hhg
- 校园节能行动的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2-%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/tlq=611
- 公共空间休憩的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%A6%82%E4%BD%95%E4%B9%B0%E6%89%8D%E6%9C%89%E6%9C%BA%E4%BC%9A%E8%B5%A2-%E7%9F%A5%E4%B9%8E%E5%86%9C%E4%B8%9A?/Uud=FE6
- 图书借阅体验的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/878
- 地方民俗记录的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/hts
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/et9
- 社区信息发布中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/938=bjy
- 基层医疗预约的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/gqn=803
- 数字生活课堂的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BD%91%E8%B5%8C%E6%9C%80%E5%A5%BD%E9%A1%BA%E9%95%BF%E9%BE%99-%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/1TE=U3m
- 老年人日常照护的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/155
- 校园阅读活动的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/mrn
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/w0h
- 就业技能培训的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/855=icm
- 绿色办公实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/nrp=438
- 线上阅读资源的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_66%E9%A1%BA88%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/WmX=dPU
- 电动汽车充电的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/028
- 城市共享单车的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/zfh
- 老年人出行服务的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/stJ
- 社区体育组织的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/969=ydf
- 老年学习活动的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/yrv=385
- 农村环境治理的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%A1%BA%E9%BE%99%E5%92%8C%E7%A0%8D%E9%BE%99%E7%9A%84%E6%8A%80%E5%B7%A7-%E5%A4%B4%E6%9D%A1%E4%B8%93%E6%A0%8F?/fM0=IR0
- 数字创意课程的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/049
- 乡村公共服务的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/jns
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/p7n
- 地方戏曲体验的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/003=kqg
- 市民意见收集的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/bju=955
- 健康步道使用的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_pk10%E5%9B%9B%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/07M=Kzw
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B-%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/486
- 安全出行教育的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B-%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/nxg
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B-%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/I8G
- 社区安全巡查的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E8%B5%8C%E5%9C%BA%E7%A0%8D%E9%BE%99%E6%98%AF%E5%A5%BD%E4%BA%8B%E8%BF%98%E6%98%AF%E5%9D%8F%E4%BA%8B-%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/506=tsx

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
