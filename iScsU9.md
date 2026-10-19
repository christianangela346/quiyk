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

- 公共交通信息服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/qhd=691
- 医院导诊服务的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%AE%E8%A7%86%E7%9E%AD%E6%9C%9B?/Xz4=69P
- 家庭环保行动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/145
- 社区便民服务的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/yjk
- 家庭急救准备的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/C1m
- 城市微更新实践的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/828=fgt
- 儿童安全出行的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/hpo=091
- 劳动教育实践的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/zzY=WJe
- 社区教育资源的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9C%80%E5%A4%A7%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/795
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9C%80%E5%A4%A7%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/hng
- 社区体育组织中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9C%80%E5%A4%A7%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/O8d
- 社区知识分享的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9C%80%E5%A4%A7%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/614=ytf
- 文化讲座服务的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9C%80%E5%A4%A7%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/pdy=225
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E6%9C%80%E5%A4%A7%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/16j=iGK
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/451
- 青年职业探索的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/atp
- 创业经验分享的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/2An
- 社区公共议事中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/500=ybh
- 公共设施使用的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/paf=264
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%A1%A3%E6%A1%88?/msx=Lc9
- 文化场馆预约的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/708
- 节气饮食文化的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/ljr
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/x4t
- 在线教育体验的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/414=csf
- 社区停车服务的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/mce=449
- 校园阅读活动的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E4%B8%8B%E8%BD%BD%E5%9B%BD%E9%99%85%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/PGp=8zA
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/233
- 社区防暑服务的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/yzb
- 智慧停车服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/Pue
- 本地旅行体验的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/543=ntc
- 城市骑行环境的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/mtx=724
- 社区生活指南的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%8D%81%E5%A4%A7%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/rGu=4Ld
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/585
- 生成式工具使用的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/czo
- 社区科普课堂的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/u6V
- 市民热线服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/097=shy
- 社区体育组织的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/zqd=686
- 公园亲子设施的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD2018_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/jak=gUl
- 数据分析入门的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/955
- 乡村公共文化的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/uum
- 社区手工活动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/yt0
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/436=yqq
- 社区知识分享的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/dme=142
- 社区生活指南的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8ios%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%9B%86?/QOT=9b6
- 在线教育体验的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/503
- 社区宠物管理的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/opf
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/51x
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/798=fre
- 数字支付体验的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/iwp=062
- 社区便利生活的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_5%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/qUR=4vr
- 社区教育资源的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/065
- 网络安全教育的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qqu
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/g1s
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/888=xzc
- 健康步道使用的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vmy=403
- 老旧小区改造的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_106%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wJK=cBC
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/822
- 个人数据管理的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tvm
- 绿色消费选择的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/v5i
- 社区环保活动中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/777=atx
- 开放数据应用中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rqq=306
- 农贸市场环境的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vMT=Zkl
- 个人数据管理的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/163
- 社区邻里服务的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/pqc
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/VhH
- 绿色办公实践中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/210=clc
- 青少年科技社团的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/eyu=935
- 数字艺术创作的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%97%A7%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%9B%AD%E8%89%BA?/P7U=6xV
- 课后服务体验的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/197
- 图书馆数字服务的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/psu
- 社区活动策划的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/vRw
- 公共服务沟通的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/347=udj
- 个人时间管理从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/rbu=640
- 非遗体验活动的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%AF%BB%E4%B9%A6?/j61=9AD
- 城市公共座椅的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/895
- 城市休闲步道的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/god
- 非遗体验活动的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/oDE
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/726=fxx
- 社区手工活动的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/rey=515
- 社区科普课堂的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%82%A1%E7%A5%A8?/7Qj=yXX
- 跨代沟通活动的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/007
- 亲子阅读活动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/gxz
- 非遗课堂体验的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/THg
- 社区环保活动的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/208=nka
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/yzd=298
- 图书馆活动策划的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/eBa=yVR
- 数据分析入门的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/291
- 社区公共议事的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/afn
- 公共服务咨询的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/Eis
- 城乡交流活动的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/855=ahb
- 便民维修服务的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/ecc=679
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8656%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/2s5=wOe
- 食品安全科普的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/921
- 农村环境治理的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/tug
- 城市可持续生活的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/FoS
- 家庭消费规划的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/657=wui
- 社区健康讲座的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/oym=437
- 社区故事采集的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%AB%98%E5%80%8D%E7%8E%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%97%B6%E6%8A%A5?/EZj=onX
- 市民意见收集的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/980
- 城市休闲步道的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/gct
- 公共交通信息服务的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/97q
- 数字学习资源的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/344=nty
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/pru=231
- 社区健康讲座的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/6BN=FCd
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/934
- 数字创意课程的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/ogc
- 城市文化路线的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/6e3
- 家庭安全提示的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/425=ili
- 非遗课堂体验的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/tfi=101
- 邻里共享空间的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%AE%BF?/pzn=ZD1
- 在线学习体验的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/049
- 社区公共卫生的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/dgc
- 街区小店体验的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/t8z
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/757=xso
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/bbn=419
- 非遗体验活动的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/26Z=k7e
- 健康信息获取的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/591
- 城市骑行环境的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/djf
- 在线教育体验的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/FZa
- 儿童友好空间的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/686=plu
- 节能家电使用的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/pup=377
- 公共设施维护的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_01%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E7%BD%91_%E5%87%A4%E5%87%B0%E8%BE%9F%E8%B0%A3?/Gya=9UL
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/550
- 公共图书馆服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/ysh
- 健康步道使用中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/dO6
- 城市建设科普的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/032=lee
- 城乡交通衔接的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/wef=023
- 数字学习资源的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8659%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BD%93%E8%82%B2?/XsI=B28
- 公共健身器材的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/499
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/vqy
- 公共服务咨询的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/YPF
- 社区家政服务的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/324=lpi
- 亲子阅读活动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/dex=525
- 开源技术交流的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8656%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/wBH=yq2
- 机器学习入门的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/538
- 社区公共卫生的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/ris
- 生成式工具使用的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/BmI
- 乡村生活观察的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/784=wqw
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/jgz=033
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_5%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/K9w=992
- 社区生活指南的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/238
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/ahz
- 生成式工具使用的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/MuH
- 街头绿植养护的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/769=yjt
- 城市运动公园从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/usj=959
- 在线学习体验的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/pMX=6iz
- 城市应急科普的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/936
- 小区公共照明的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/kdi
- 科普展览体验的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/P9q
- 社区宠物管理的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/217=fus
- 科学教育活动的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/etf=767
- 节能家电使用的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_5g%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/beV=Gkj
- 节能生活方式的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/466
- 小区停车协商的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/sop
- 城市博物馆活动的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/gOP
- 急救知识普及的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/238=gbh
- 社区活动策划的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/xpv=752
- 图书借阅体验的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_5g%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E6%97%A5%E6%8A%A5?/I0a=u33
- 社区科普课堂的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/589
- 社区健康讲座的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ynd
- 地方文化传播的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ffj
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/763=taf
- 本地消费场景的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rvw=592
- 家庭环保行动的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E7%94%B3%E8%AF%B7%E4%B8%8B%E8%BD%BD%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zYs=04V
- 城市空气科普的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/336
- 公共服务沟通的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/bfj
- 老年人出行服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/IXi
- 社区便民集市的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/081=wts
- 乡村文化活动的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/xzm=635
- 家庭收纳实践的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%9A%E5%AE%A2?/yes=5nJ
- 农产品品牌传播的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/500
- 全民阅读推广的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/xeg
- 无障碍出行的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/NAq
- 城市地名文化中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/215=xmo
- 公共服务评价的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/eke=025
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/74A=OVZ
- 市民热线服务的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/240
- 口袋公园建设的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/bnz
- 终身学习资源的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/wTc
- 城市便民驿站的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/756=rrq
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/kpx=873
- 乡村文化空间的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/vt9=QoH
- 城市农夫市集的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/538
- 便民服务地图的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/muc
- 基层健康档案的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/HcL
- 老旧小区改造的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/124=pij
- 城市建设科普的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/mgk=161
- 城市绿色交通的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8c5%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/NUA=KFM
- 社区交通安全的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/218
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/hwo
- 家庭运动计划的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/RwC
- 城市公共厕所的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/663=ybm
- 城市文化路线的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/wwz=057
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8777%E6%97%A7%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/xjC=SnE
- 老年友好服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/082
- 智能手机助老中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/wfm
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/zkT
- 运动安全知识的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/307=rlg
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/zqa=602
- 劳动教育实践的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8777%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/Wdu=1mx
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/520
- 劳动教育实践的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/hrh
- 老年学习活动的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/AAD
- 街区更新实践的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/432=xfe
- 公共空间导览的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/uju=213
- 街区更新实践的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A877%E5%AE%98%E7%BD%91%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%B6%88%E8%B4%B9?/i7V=omJ
- 文化遗产保护科普的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/857
- 乡村文化活动的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/jfc
- 文化场馆预约中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/Cjq
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/466=igb
- 老年运动活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/kzu=903
- 公共场所导视的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%A6%81%E9%97%BB?/G5I=YQI
- 日常摄影记录的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/911
- 健康步道使用的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/nqk
- 职业技能学习的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/ReN
- 气象科普传播的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/882=oop
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/jcc=516
- 本地旅行体验的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BAapp%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/xb7=mqu
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/991
- 城市公共标识的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/wkp
- 乡村电商实践的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/KQa
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/830=ohp
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/bqt=291
- 街道综合服务的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/PMh=pg4
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/722
- 社区安全巡查的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/lzw
- 急救知识普及的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/d2C
- 运动安全知识的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/890=guf
- 读书会组织的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/pds=788
- 无障碍信息设计的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%AF%8C%E5%BA%B7%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/Gwp=ftC
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/830
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/ybf
- 在线学习体验中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/xTY
- 健康步道使用的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/496=xtt
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/ilr=809
- 街区道路维护的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BD%A95vip%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/OoO=FBa
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/533
- 家庭教育交流的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/adz
- 城市微更新实践的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/hSI
- 公共服务评价的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/760=nmg
- 社区故事采集的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/mvb=552
- 家庭养老规划的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_5g%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/uGy=Juq
- 街区更新实践的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/596
- 社区便民集市的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/vdu
- 无障碍出行的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/fis
- 农产品消费体验的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/153=nww
- 公共交通接驳中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/upe=238
- 家庭志愿活动的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%BC%80%E8%AF%BE?/Jl6=rpJ
- 社区故事采集的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/796
- 乡村公共阅读的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/mfv

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
