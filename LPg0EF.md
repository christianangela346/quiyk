# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 健康信息获取的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%8E%A9%E5%BF%AB3%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/871
- 城市微更新实践的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%8E%A9%E5%BF%AB3%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/rzk
- 数字课堂应用的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%8E%A9%E5%BF%AB3%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/b9u
- 光伏知识科普的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%8E%A9%E5%BF%AB3%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/609=ivx
- 地方旅游导览的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%8E%A9%E5%BF%AB3%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/vtj=301
- 家庭节能实践的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E7%8E%A9%E5%BF%AB3%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E5%9C%B0%E4%BA%A7?/IVh=RSP
- 居家防滑改造的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/252
- 社会体育指导的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/nhl
- 家庭运动计划的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/CLO
- 数字素养提升的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/791=vhp
- 农产品消费体验的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/yjh=702
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%9E%E5%BD%95?/l9i=MGw
- 城市社区治理的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%89%B9%E7%82%B9_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/945
- 无障碍出行的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%89%B9%E7%82%B9_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/gya
- 城市社区治理的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%89%B9%E7%82%B9_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/Lck
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%89%B9%E7%82%B9_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/903=psn
- 城市雨天出行的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%89%B9%E7%82%B9_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/bie=503
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%89%B9%E7%82%B9_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/7LJ=f4G
- 城市夜间照明的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%BC%98%E5%8A%BF_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/133
- 健康步道使用的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%BC%98%E5%8A%BF_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/qmb
- 青年就业服务的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%BC%98%E5%8A%BF_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/uZS
- 基层服务创新的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%BC%98%E5%8A%BF_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/538=pah
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%BC%98%E5%8A%BF_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/vsj=659
- 全民健身活动的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E4%B8%80%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E4%BC%98%E5%8A%BF_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/VRQ=LDv
- 公共设施使用的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%9B%BD%E5%AE%B6%E5%85%81%E8%AE%B8%E7%9A%84%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/045
- 本地历史资料的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%9B%BD%E5%AE%B6%E5%85%81%E8%AE%B8%E7%9A%84%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/igm
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%9B%BD%E5%AE%B6%E5%85%81%E8%AE%B8%E7%9A%84%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/Auc
- 社区商业活力的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%9B%BD%E5%AE%B6%E5%85%81%E8%AE%B8%E7%9A%84%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/969=aiv
- 城市公共空间的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%9B%BD%E5%AE%B6%E5%85%81%E8%AE%B8%E7%9A%84%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/htk=227
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%9B%BD%E5%AE%B6%E5%85%81%E8%AE%B8%E7%9A%84%E5%BD%A9%E7%A5%A8app%E6%9C%89%E5%93%AA%E4%BA%9B_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/L8v=XQ0
- 家庭网络使用的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/658
- 青少年心理健康的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/ljt
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/Jr0
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/060=uxj
- 城市文明实践的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/zwy=420
- 社区艺术活动的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BD%A9%E5%85%AC%E5%8F%B8%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/ped=kph
- 社区文化传播的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/057
- 城市步行友好的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/ihd
- 乡村生态观察的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/5kQ
- 食品安全科普的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/552=rmn
- 社区商业活力的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/aak=966
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/RmZ=q2m
- 科技馆参观体验的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/497
- 科技馆参观体验的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/zoc
- 老年友好服务的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/ImZ
- 全民健身活动的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/237=ozj
- 节气饮食文化的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/dic=775
- 远程协作工具的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/nCk=rIX
- 医院导诊服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/265
- 本地消费场景的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/ewt
- 社区便利生活的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/Zu4
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/054=fop
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/btl=999
- 就业技能培训的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%B4%BB%E5%8A%A8_%E9%9B%85%E8%99%8E%E5%9B%AD%E8%89%BA?/cGT=ar6
- 城市绿道建设的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/766
- 公共空间安全的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/cps
- 乡村生活观察的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/nau
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/238=onn
- 城市骑行环境的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/cta=997
- 小微企业服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/afo=XCy
- 社区快递服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85365%E9%80%9F%E5%8F%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/130
- 图书馆活动策划的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85365%E9%80%9F%E5%8F%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/ged
- 社区环保活动的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85365%E9%80%9F%E5%8F%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/mA6
- 家庭环保习惯的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85365%E9%80%9F%E5%8F%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/574=gdd
- 旧物循环利用的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85365%E9%80%9F%E5%8F%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/vln=191
- 乡村电商实践的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85365%E9%80%9F%E5%8F%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E5%86%85?/7D4=MXO
- 农贸市场环境的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/305
- 社区文化传播的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/hhn
- 青少年编程学习中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/DZv
- 健康饮食教育的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/868=ruf
- 公共服务预约的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/mua=777
- 科学健身方法的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E9%A2%84%E6%B5%8B%E6%9C%80%E6%96%B0_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/PRv=OBj
- 社区健康讲座的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_Welcome%E4%B9%90%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/601
- 网络信息辨识的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_Welcome%E4%B9%90%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/jkl
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_Welcome%E4%B9%90%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/fU6
- 社区活动策划的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_Welcome%E4%B9%90%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/353=rfn
- 绿色出行服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_Welcome%E4%B9%90%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/xph=091
- 便民信息查询的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_Welcome%E4%B9%90%E5%BD%A9%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E4%B8%93%E6%A0%8F?/xzN=uYg
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_Welcome%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/306
- 电动汽车充电的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_Welcome%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/dll
- 社区科普课堂的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_Welcome%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/NXF
- 乡村产业科普的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_Welcome%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/037=zoy
- 社区垃圾回收的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_Welcome%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/dka=082
- 公共空间安全的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_Welcome%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E7%BE%8E%E5%A6%86?/gEB=Iyd
- 全民阅读推广的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/605
- 社区老年食堂的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/xsj
- 本地消费场景的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/b9K
- 乡村电商实践的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/079=xfv
- 城市可持续生活的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/hkg=999
- 社区儿童活动的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/SGO=fku
- 节日文化体验的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E4%BB%BD%E5%BF%AB3%E7%A9%BA%E9%99%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/296
- 个人时间管理的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E4%BB%BD%E5%BF%AB3%E7%A9%BA%E9%99%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/wtq
- 家庭阅读计划的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E4%BB%BD%E5%BF%AB3%E7%A9%BA%E9%99%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/CbC
- 休闲运动入门的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E4%BB%BD%E5%BF%AB3%E7%A9%BA%E9%99%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/029=wsp
- 科技馆参观体验的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E4%BB%BD%E5%BF%AB3%E7%A9%BA%E9%99%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/hpu=140
- 绿色消费选择的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%80%E4%BB%BD%E5%BF%AB3%E7%A9%BA%E9%99%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%BD%A9%E7%A5%A8?/du5=YlS
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%98%A5%E9%9B%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/071
- 开源技术交流的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%98%A5%E9%9B%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/lgy
- 社区文化节活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%98%A5%E9%9B%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/x9p
- 公园休闲体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%98%A5%E9%9B%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/522=gxe
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%98%A5%E9%9B%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/fxj=933
- 儿童安全出行的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E6%98%A5%E9%9B%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/Of3=rDI
- 社区便利生活的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/204
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/ukw
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/EWw
- 公共场馆服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/865=wro
- 数字档案服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/bnk=972
- 家庭阅读计划的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E8%BD%AF%E4%BB%B6%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/JAg=IGD
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%88%90%E5%93%81%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E9%9A%90%E8%97%8F%E9%80%9A%E9%81%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/382
- 机器人科普活动的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%88%90%E5%93%81%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E9%9A%90%E8%97%8F%E9%80%9A%E9%81%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/xkz
- 地方文化传播的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%88%90%E5%93%81%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E9%9A%90%E8%97%8F%E9%80%9A%E9%81%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/DDu
- 电动汽车充电的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%88%90%E5%93%81%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E9%9A%90%E8%97%8F%E9%80%9A%E9%81%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/120=ovu
- 社区活动空间的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%88%90%E5%93%81%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E9%9A%90%E8%97%8F%E9%80%9A%E9%81%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/fox=217
- 邻里共享空间的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E6%88%90%E5%93%81%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3%E9%9A%90%E8%97%8F%E9%80%9A%E9%81%93_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/ChR=18O
- 城市地名文化的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E8%8D%B7%E8%8A%B11777.t%E2%85%B4_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/169
- 儿童户外活动的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E8%8D%B7%E8%8A%B11777.t%E2%85%B4_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/cvn
- 节日文化体验的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E8%8D%B7%E8%8A%B11777.t%E2%85%B4_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/H16
- 无障碍出行的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E8%8D%B7%E8%8A%B11777.t%E2%85%B4_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/774=yze
- 电子商务服务的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E8%8D%B7%E8%8A%B11777.t%E2%85%B4_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ouk=027
- 城市慢行系统的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E8%8D%B7%E8%8A%B11777.t%E2%85%B4_%E7%9B%9B%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ImJ=Qe8
- 城市游园体验中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/500
- 城市社区治理的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/qut
- 社区艺术活动的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/6AK
- 食品配送体验的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/204=yvw
- 社区互助网络的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/tmw=189
- 数字艺术创作的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_1%E5%88%86%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_%E8%99%8E%E5%97%85%E5%81%A5%E8%BA%AB?/99s=wSB
- 租房信息服务的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%B7%E6%B0%B4%E6%9E%AA%E7%A9%BA%E9%99%8D%E5%8F%AF%E7%BA%A6%E7%9C%8B%E5%A4%A7%E7%A7%80_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/999
- 家庭节能设备的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%B7%E6%B0%B4%E6%9E%AA%E7%A9%BA%E9%99%8D%E5%8F%AF%E7%BA%A6%E7%9C%8B%E5%A4%A7%E7%A7%80_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/ffu
- 本地历史资料的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%B7%E6%B0%B4%E6%9E%AA%E7%A9%BA%E9%99%8D%E5%8F%AF%E7%BA%A6%E7%9C%8B%E5%A4%A7%E7%A7%80_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/cLe
- 健康信息获取的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%B7%E6%B0%B4%E6%9E%AA%E7%A9%BA%E9%99%8D%E5%8F%AF%E7%BA%A6%E7%9C%8B%E5%A4%A7%E7%A7%80_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/902=uam
- 公共场馆服务的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%B7%E6%B0%B4%E6%9E%AA%E7%A9%BA%E9%99%8D%E5%8F%AF%E7%BA%A6%E7%9C%8B%E5%A4%A7%E7%A7%80_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/uul=748
- 环境监测科普的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%B7%E6%B0%B4%E6%9E%AA%E7%A9%BA%E9%99%8D%E5%8F%AF%E7%BA%A6%E7%9C%8B%E5%A4%A7%E7%A7%80_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/qZn=Mm4
- 社区花园共建中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/267
- 公交站点体验的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/vua
- 社区绿色空间中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/xm8
- 地方民俗记录的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/291=wnh
- 城市地名文化的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/ick=372
- 家庭科学教育的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/Qgk=Eln
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/570
- 公共卫生宣传的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/oxi
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/xTb
- 数字学习资源的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/726=fbk
- 社区便利生活的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/hth=452
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_1%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/wpu=xR9
- 家庭科学教育的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/797
- 社区宠物管理的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/alb
- 社区活动空间的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/QSb
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/536=rkf
- 老年数字阅读的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/nnr=420
- 社区菜市场服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%88%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E5%9B%9E%E6%94%BE?/WCX=9SS
- 青年就业服务的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/476
- 校园社团活动的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/eph
- 街区小店体验的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/gXj
- 城市适老服务的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/162=qnu
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/hjg=083
- 气象科普传播的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/yZz=5E6
- 社区儿童活动的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/429
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/fes
- 社区修缮行动的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/9iY
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/118=ypj
- 青年就业服务的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/hbl=026
- 城市可持续生活的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%9C%80%E5%87%86%E7%9A%84%E6%89%93%E6%B3%95%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E6%8A%96%E9%9F%B3%E7%BB%8F%E6%B5%8E?/Di0=Leq
- 城市公共标识的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%BA%E7%82%89_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/009
- 城市骑行环境的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%BA%E7%82%89_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/yva
- 小区停车协商的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%BA%E7%82%89_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/dFL
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%BA%E7%82%89_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/844=mtc
- 便民维修服务的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%BA%E7%82%89_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/jgy=791
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%9C%80%E5%A5%BD%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%87%BA%E7%82%89_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/JdN=y7K
- 社区互助网络的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/648
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/hag
- 街区道路维护中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/hrV
- 开放数据应用的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/450=xaj
- 社区手工活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/odn=047
- 家庭食品保存的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/IkX=dbE
- 家庭养老规划的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/168
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/ivz
- 光伏知识科普的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/99e
- 城市夜间生活的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/410=tho
- 在线学习体验的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/dkp=197
- 社区公共议事的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8%E7%BD%91%E7%AB%99_%E8%8A%92%E6%9E%9C%E8%A7%86%E9%A2%91?/FfT=I4v
- 远程协作工具的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/022
- 家庭食品保存的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/bwz
- 城市应急广播的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/gg6
- 口袋公园建设的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/684=mdw
- 公交无障碍服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/xlj=110
- 文明养宠科普的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%99%A8%E6%8A%A5?/uwo=DMJ
- 节日文化体验的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%A6w%D1%851%E7%82%B9vip_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/608
- 社区公共卫生的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%A6w%D1%851%E7%82%B9vip_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ess
- 乡村公共文化的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%A6w%D1%851%E7%82%B9vip_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/oYM
- 社区生活指南的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%A6w%D1%851%E7%82%B9vip_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/642=epv
- 节能生活方式的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%A6w%D1%851%E7%82%B9vip_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/lhr=624
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E5%92%A6w%D1%851%E7%82%B9vip_%E5%9B%BD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/qMK=XPS
- 数字便民地图的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%B0%E5%AD%90%E5%90%88%E9%9B%86_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/681
- 公共空间导览中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%B0%E5%AD%90%E5%90%88%E9%9B%86_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/gyc
- 乡村文化活动的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%B0%E5%AD%90%E5%90%88%E9%9B%86_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/s9g
- 家庭收纳实践的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%B0%E5%AD%90%E5%90%88%E9%9B%86_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/885=izy
- 城市噪声观察的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%B0%E5%AD%90%E5%90%88%E9%9B%86_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/orr=496
- 学校体育活动的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8F%B0%E5%AD%90%E5%90%88%E9%9B%86_%E5%93%94%E5%93%A9%E6%8E%A2%E5%BA%97?/QxZ=r6n
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/045
- 城市地名文化的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/mww
- 便民服务地图的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/JBa
- 家庭科学教育的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/714=iqt
- 街区绿化养护的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/hce=508
- 青年职业探索的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E4%B8%80%E5%88%86%E4%B8%89%E5%9D%97%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/CMT=pEE
- 公共空间照明的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%8A%A2%E5%BF%83%E5%BF%83%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/344
- 社区心理支持的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%8A%A2%E5%BF%83%E5%BF%83%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/vsy
- 家庭科学教育的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%8A%A2%E5%BF%83%E5%BF%83%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/xyA
- 科学信息获取的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%8A%A2%E5%BF%83%E5%BF%83%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/396=qwt
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%8A%A2%E5%BF%83%E5%BF%83%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/ikt=596
- 环境教育课程的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%8A%A2%E5%BF%83%E5%BF%83%E7%9A%84%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/zG3=JhI
- 街区道路维护的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB%E4%B9%90%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/572
- 绿色快递包装的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB%E4%B9%90%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/jdl
- 儿童户外活动的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB%E4%B9%90%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/SPS
- 社区便民集市的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB%E4%B9%90%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/477=yys
- 社区家校合作的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB%E4%B9%90%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/taj=319
- 家庭健康管理的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB%E4%B9%90%E6%98%AF%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/VVy=9pM
- 老年学习活动的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E5%BD%A9%E7%A5%A8%E8%B5%9A%E7%9A%84%E9%92%B1%E8%83%BD%E6%8F%90%E7%8E%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/596
- 公共场馆服务的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E5%BD%A9%E7%A5%A8%E8%B5%9A%E7%9A%84%E9%92%B1%E8%83%BD%E6%8F%90%E7%8E%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/dpj
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E5%BD%A9%E7%A5%A8%E8%B5%9A%E7%9A%84%E9%92%B1%E8%83%BD%E6%8F%90%E7%8E%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/kei
- 家庭养老规划的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E5%BD%A9%E7%A5%A8%E8%B5%9A%E7%9A%84%E9%92%B1%E8%83%BD%E6%8F%90%E7%8E%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/179=sgi
- 城市展览体验的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E5%BD%A9%E7%A5%A8%E8%B5%9A%E7%9A%84%E9%92%B1%E8%83%BD%E6%8F%90%E7%8E%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/gcd=311
- 劳动教育实践的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E8%90%9D%E5%8D%9C%E5%AF%86%E8%81%8A%E5%BD%A9%E7%A5%A8%E8%B5%9A%E7%9A%84%E9%92%B1%E8%83%BD%E6%8F%90%E7%8E%B0%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/Dgu=h5M
- 气象科普传播的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%AD%85%E5%BD%B1%E7%9B%B4%E6%92%AD5.3%E6%9C%80%E6%96%B0%E7%89%88%E7%89%B9%E8%89%B2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/644
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%AD%85%E5%BD%B1%E7%9B%B4%E6%92%AD5.3%E6%9C%80%E6%96%B0%E7%89%88%E7%89%B9%E8%89%B2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/ewn
- 网络安全教育的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%AD%85%E5%BD%B1%E7%9B%B4%E6%92%AD5.3%E6%9C%80%E6%96%B0%E7%89%88%E7%89%B9%E8%89%B2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/WJb
- 数字支付体验的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%AD%85%E5%BD%B1%E7%9B%B4%E6%92%AD5.3%E6%9C%80%E6%96%B0%E7%89%88%E7%89%B9%E8%89%B2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/890=xzm
- 开放数据应用的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%AD%85%E5%BD%B1%E7%9B%B4%E6%92%AD5.3%E6%9C%80%E6%96%B0%E7%89%88%E7%89%B9%E8%89%B2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/kib=775
- 社区活动策划的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E9%AD%85%E5%BD%B1%E7%9B%B4%E6%92%AD5.3%E6%9C%80%E6%96%B0%E7%89%88%E7%89%B9%E8%89%B2_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/OxR=IvS
- 智能家居应用的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/995
- 创业经验分享的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/hoq
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/TPR
- 家庭节能实践的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/313=kev
- 数字学习资源的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/amd=156
- 乡村生态观察的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86%E5%BF%AB3%E6%97%A7%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/M6h=n8S
- 开放数据应用的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/193
- 节能家电使用的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/url
- 儿童阅读角的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/QQw
- 社区信息发布的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/310=tev
- 公共卫生设施的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/uvz=614
- 家庭科学教育中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A0%8D%E9%BE%99%E5%BF%85%E8%B5%9A%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%8D%B3%E5%88%BB%E7%BA%AA%E5%AE%9E?/QD1=ZdC
- 绿色出行服务的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/607
- 邻里共享空间的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/zqm
- 城市绿色交通的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/gUX
- 儿童户外活动的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/963=wpc
- 公共服务咨询的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/lgb=413
- 文明养宠科普的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/vze=6OE
- 家庭健康管理的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/172
- 居民健康教育中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/arw
- 公园休闲体验的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/hLk
- 城乡公共服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%95%E6%B3%A8_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/622=wbw

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
