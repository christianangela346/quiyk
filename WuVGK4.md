# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:18**

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

- 图书借阅体验的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_5003vip%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/2Vm
- 社区老年食堂的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_5003vip%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/594=krj
- 家庭健康科普的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_5003vip%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/vms=865
- 社区公共卫生的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_5003vip%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%A8%E6%8A%A5?/f9q=QUV
- 家庭消费规划的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A4%A7%E5%85%A8500_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/333
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A4%A7%E5%85%A8500_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/omu
- 家庭健康科普的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A4%A7%E5%85%A8500_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/jhh
- 城市运动公园的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A4%A7%E5%85%A8500_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/041=iyt
- 机器人科普活动的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A4%A7%E5%85%A8500_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/qqz=251
- 社区读书角建设的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%9F%BA%E6%9C%AC%E8%B5%B0%E5%8A%BF%E5%9B%BE%E5%A4%A7%E5%85%A8500_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/Z6q=aBl
- 文化讲座服务的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/054
- 城市公共厕所的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/poe
- 社区健康讲座的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/6l6
- 社区活动报名的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/811=fix
- 社区托育服务的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/ovx=580
- 数字地图应用的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%BB%84%E8%89%B2500%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/L2Y=LeL
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/514
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/emy
- 家庭健康科普的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/BC5
- 家庭消费规划的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/928=gkw
- 社区公共议事的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/lcg=333
- 节假日出行安排的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E8%BE%9F%E8%B0%A3?/9Fd=1tt
- 居家防滑改造的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/979
- 家庭环保习惯的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/oqg
- 街区道路维护的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/sgX
- 数字设备回收的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/519=ein
- 家庭养老规划的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/xwe=189
- 街道综合服务中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2_%E7%9F%A5%E4%B9%8E%E9%A3%9F%E5%93%81?/Mw3=Xwg
- 数字课堂应用的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/284
- 公共服务咨询的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/xfz
- 公共场所导视中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/DBp
- 数字阅读服务的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/427=dxr
- 社区绿色空间的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/uqm=860
- 公交站点体验的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%A5%E6%8A%A5?/DzG=rXz
- 学校食育活动中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/372
- 校园安全教育的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/ntt
- 读书会组织的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/nZq
- 乡村产业科普的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/446=wud
- 本地旅行体验的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/yct=056
- 青少年科技社团的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E5%A8%B1%E4%B9%90?/2eG=wiM
- 城市博物馆服务的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/546
- 城市运动公园的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/wjt
- 文化场馆预约的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/wLi
- 通勤路线规划的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/106=nhf
- 城市运动公园的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/cqn=596
- 社区家政服务的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E9%BB%84%E9%87%91%E7%89%88_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/dva=NsB
- 社区停车服务的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88_360%E6%A1%A3%E6%A1%88?/916
- 地方文化传播的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88_360%E6%A1%A3%E6%A1%88?/uer
- 校园节能行动的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88_360%E6%A1%A3%E6%A1%88?/ydk
- 老年人日常照护的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88_360%E6%A1%A3%E6%A1%88?/593=hln
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88_360%E6%A1%A3%E6%A1%88?/hak=977
- 城市步行环境的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%9B%88_360%E6%A1%A3%E6%A1%88?/ClK=elC
- 节日文化体验的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/655
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/esb
- 乡村阅读空间的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/83X
- 乡村生活观察的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/890=hjg
- 远程协作工具的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/cbe=465
- 社区知识分享的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BF%AB%E8%B5%A2_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/tW7=VNi
- 个人时间管理的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/594
- 城市空气科普的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/bfr
- 乡村生态旅游的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/6xP
- 在线学习体验从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/154=ooa
- 城市公共自行车的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/vpn=584
- 社区知识分享的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/oVQ=9b4
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/162
- 节假日出行安排的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/hnp
- 城乡交流活动的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/2y4
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/341=odj
- 家庭健康管理中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/nra=949
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/CMA=j5r
- 网络安全教育的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/643
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/ftv
- 开源技术交流的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/s0S
- 家庭运动计划的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/939=zmk
- 社区邻里服务的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/mfz=909
- 社区知识分享的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_75%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/GIq=DhK
- 消防知识宣传的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/787
- 生活垃圾减量的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/wtz
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/XxD
- 社区花园共建的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/003=xpf
- 家庭阅读计划的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/luf=719
- 地方文化传播的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_75%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%88%86%E6%83%85?/1vL=LAR
- 城市绿道建设的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/190
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/tcc
- 日常摄影记录的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/fTF
- 居家适老化改造中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/655=zke
- 开放式学习空间中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/gqp=304
- 公共空间安全的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/75I=YOz
- 公共交通接驳的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8106%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/188
- 口袋公园建设的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8106%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/veo
- 机器人科普活动的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8106%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/FtZ
- 社区故事采集的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8106%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/353=bzd
- 乡村教育资源的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8106%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/mkl=868
- 志愿服务平台的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8106%E8%80%81%E7%89%88_%E6%90%9C%E7%8B%90%E4%B9%A6%E7%94%BB?/uYq=ck4
- 公共服务指南的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_144%E7%89%9B%E5%BD%A9-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/931
- 开源技术交流的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_144%E7%89%9B%E5%BD%A9-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/ugc
- 社区公共卫生的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_144%E7%89%9B%E5%BD%A9-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/1zT
- 城市树木认养的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_144%E7%89%9B%E5%BD%A9-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/363=jbw
- 青少年心理健康的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_144%E7%89%9B%E5%BD%A9-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/pjl=266
- 光伏知识科普的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_144%E7%89%9B%E5%BD%A9-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E5%BD%B1%E8%A7%86?/WJg=nJO
- 文化讲座服务的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_144%E7%89%9B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/480
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_144%E7%89%9B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/aor
- 地方文化传播的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_144%E7%89%9B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/1KI
- 个人数据管理的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_144%E7%89%9B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/853=dbk
- 城市休闲步道的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_144%E7%89%9B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/ysw=971
- 健康步道使用的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_144%E7%89%9B%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/vlP=rUG
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_144%E7%89%9B%E5%BD%A9-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/981
- 社区邻里服务的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_144%E7%89%9B%E5%BD%A9-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/pgx
- 街区道路维护的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_144%E7%89%9B%E5%BD%A9-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/9js
- 街区更新实践的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_144%E7%89%9B%E5%BD%A9-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/192=esd
- 食品安全科普的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_144%E7%89%9B%E5%BD%A9-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/jcc=827
- 社区环保活动的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_144%E7%89%9B%E5%BD%A9-app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/vT7=ygG
- 社区志愿服务的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_144%E7%89%9B%E5%BD%A9-app_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/723
- 节日文化体验的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_144%E7%89%9B%E5%BD%A9-app_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/ome
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_144%E7%89%9B%E5%BD%A9-app_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/QGF
- 老旧小区改造的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_144%E7%89%9B%E5%BD%A9-app_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/493=inf
- 城市博物馆活动的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_144%E7%89%9B%E5%BD%A9-app_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/esk=445
- 消防知识宣传的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_144%E7%89%9B%E5%BD%A9-app_%E8%84%89%E8%84%89%E5%A8%B1%E4%B9%90?/n0g=Mu7
- 公共设施使用的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_144%E7%89%9B%E5%BD%A9-%E5%A4%A7%E5%8E%85_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/955
- 城市基础设施的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_144%E7%89%9B%E5%BD%A9-%E5%A4%A7%E5%8E%85_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/lfi
- 公共服务数字化的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_144%E7%89%9B%E5%BD%A9-%E5%A4%A7%E5%8E%85_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/zjw
- 小区停车协商的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_144%E7%89%9B%E5%BD%A9-%E5%A4%A7%E5%8E%85_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/076=tgy
- 全民健身活动的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_144%E7%89%9B%E5%BD%A9-%E5%A4%A7%E5%8E%85_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mbe=571
- 城市公共标识的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_144%E7%89%9B%E5%BD%A9-%E5%A4%A7%E5%8E%85_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/es6=uAM
- 志愿者培训交流的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/877
- 急救知识普及的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/ujj
- 城市慢行系统的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/t2v
- 城市基础设施的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/952=mva
- 气象科普传播的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/ydl=999
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/Q8M=TZs
- 老年人出行服务的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/232
- 社区志愿服务的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/fwu
- 健康信息获取的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/LRR
- 家庭节能实践的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/967=whs
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/gfu=994
- 小区电梯维护的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/tNb=SAe
- 职业技能学习的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/162
- 社区托育服务的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/pjj
- 线上办事服务的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/fON
- 开源技术交流的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/750=xnc
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/nnm=885
- 城市公共厕所的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_160%E5%BD%A9%E7%A5%A8-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%8A%92%E6%9E%9C%E4%BF%A1%E6%89%98?/Fuz=lbE
- 城市人文观察的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/304
- 科学信息获取的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/xiw
- 校园社团活动的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/h4J
- 社区协商议事的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/199=qhw
- 社区环保活动的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/ubu=642
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_160%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/oL1=LMg
- 城乡交流活动中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_160%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/054
- 旧物循环利用的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_160%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/gic
- 公共空间安全中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_160%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/6Sr
- 老年数字阅读的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_160%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/250=rws
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_160%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/lcb=941
- 课后服务体验的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_160%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%88%8A%E7%99%BB?/mtF=Iuz
- 城市体育设施的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/250
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/ifz
- 地方民俗记录的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/qGj
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/630=uxr
- 社区公共卫生的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/ulp=412
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_160%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%97%A5%E6%8A%A5?/Hww=a6z
- 口袋公园建设的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_18%E5%A8%B1%E4%B9%90-APP%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/024
- 乡村生态旅游的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_18%E5%A8%B1%E4%B9%90-APP%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/izi
- 本地消费场景的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_18%E5%A8%B1%E4%B9%90-APP%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/eJr
- 科学睡眠习惯的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_18%E5%A8%B1%E4%B9%90-APP%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/566=bbw
- 软件开发学习的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_18%E5%A8%B1%E4%B9%90-APP%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/wbi=726
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_18%E5%A8%B1%E4%B9%90-APP%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%95%99%E8%82%B2?/td9=JIg
- 光伏知识科普的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_271%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/603
- 乡村公共服务的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_271%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/xnn
- 数据分析入门的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_271%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/GX0
- 数字课堂应用的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_271%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/559=ggy
- 物业服务沟通的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_271%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/elo=655
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_271%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/rKM=sTI
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A833%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/756
- 节能家电使用的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A833%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/itq
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A833%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/GdO
- 亲子科普活动的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A833%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/486=jem
- 社区活动策划的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A833%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/wfm=367
- 应急物资管理的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A833%E6%9C%80%E6%96%B0%E7%89%88_%E8%84%89%E8%84%89%E5%8F%B7%E5%A4%96?/VaG=igK
- 城市公共座椅从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A833%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/904
- 健康步道使用的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A833%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/dtw
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A833%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/DJc
- 新能源出行的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A833%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/178=bnp
- 社区交通安全的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A833%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/ywl=570
- 传统手工艺体验的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A833%E6%B3%A8%E5%86%8C_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/QQq=rDh
- 社区志愿服务的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A833app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/105
- 社区共享书架的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A833app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/uoy
- 机器学习入门的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A833app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/b17
- 农村环境治理中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A833app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/387=bwq
- 开放式学习空间的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A833app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/grn=273
- 灵活就业交流的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A833app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/bM8=wub
- 社区公共卫生的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_33%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/989
- 数字档案服务的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_33%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/ntw
- 安全出行教育的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_33%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/Zv8
- 便民服务地图的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_33%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/344=rqq
- 地方美食文化的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_33%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/jni=299
- 城市建设科普的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_33%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%A7%81%E5%8B%9F?/2UK=8IS
- 青少年心理健康的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_33%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/429
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_33%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/hks
- 城市应急科普的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_33%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/C7H
- 街道综合服务的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_33%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/153=vzb
- 绿色出行服务的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_33%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/qxo=185
- 个人信息保护的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_33%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/jVd=Ryu
- 青少年心理健康的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/703
- 科学睡眠习惯的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/pad
- 社区养老服务的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/yx9
- 社区快递服务的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/378=jok
- 青少年科普实践的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/uok=039
- 社区文化节活动的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_33%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/Bgm=1ke
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/860
- 地方文化传播的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/fsc
- 气象科普传播的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/kLc
- 家庭养老规划的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/759=omr
- 社区防暑服务的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/kqd=517
- 本地消费场景的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_33%E5%BD%A9%E7%A5%A8-%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/vi1=bIj
- 公共空间休憩的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/227
- 数字课堂应用的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/itm
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/k9A
- 灵活就业交流的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/664=jfi
- 社区知识分享的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/hyf=898
- 城市慢行系统的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app_%E8%99%8E%E5%97%85%E8%AF%BB%E5%9B%BE?/JJc=fhb
- 便民服务窗口的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/671
- 公共服务预约的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/fgo
- 数字支付体验的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/A3x
- 社区环保活动的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/607=gyi
- 城市公共标识的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/lih=579
- 图书馆活动策划的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_33%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/aPc=ulm
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_61%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/783
- 城乡公共服务的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_61%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/azg
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_61%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/LdK
- 居家防滑改造的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_61%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/333=fgn
- 社区儿童活动的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_61%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/mcs=198
- 便民服务地图的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_61%E5%BD%A9%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%88%9B%E6%8A%95?/sPJ=Gos
- 远程协作工具的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_61%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/710
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_61%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/mid
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_61%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/QXo
- 食品配送体验的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_61%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/696=zxv
- 老年人文化生活的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_61%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/pgg=692
- 数字创作工具的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_61%E5%BD%A9%E9%9B%86%E5%9B%A2%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/OPa=TdP
- 社区宠物管理的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_62%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/854
- 社区手工活动的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_62%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/lyi
- 急救知识普及的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_62%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/uoV
- 城市公共标识的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_62%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/073=hbr
- 在线教育体验的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_62%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/zjc=977
- 城乡交流活动的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_62%E5%BD%A9%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%AE%B6%E5%B1%85?/YAv=53r
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E8%B4%A6%E6%88%B7%E6%9F%A5%E8%AF%A2_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/678
- 邻里互助活动的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E8%B4%A6%E6%88%B7%E6%9F%A5%E8%AF%A2_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/hhc
- 数字艺术创作的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E8%B4%A6%E6%88%B7%E6%9F%A5%E8%AF%A2_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/az4
- 租房信息服务的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E8%B4%A6%E6%88%B7%E6%9F%A5%E8%AF%A2_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/151=dvu
- 地方旅游导览的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E8%B4%A6%E6%88%B7%E6%9F%A5%E8%AF%A2_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/wle=979
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E4%B8%AA%E4%BA%BA%E8%B4%A6%E6%88%B7%E6%9F%A5%E8%AF%A2_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/8B3=WY8

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
