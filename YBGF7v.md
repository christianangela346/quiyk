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

- 社区艺术活动的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%8A%A9%E6%89%8B_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/ism=871
- 急救知识普及的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%8A%A9%E6%89%8B_%E5%8D%B3%E5%88%BB%E7%9E%AD%E6%9C%9B?/7rh=GKL
- 基层健康档案的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/424
- 小区电梯维护的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/wie
- 软件开发学习的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/mDq
- 乡村公共阅读的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/764=huo
- 青年志愿活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/vtg=631
- 城市展览体验的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E6%8A%A5?/l42=iUY
- 公园亲子设施的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/174
- 食品配送体验的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/tyd
- 儿童户外活动的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/we0
- 社区设施共享的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/047=emc
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/cle=677
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/0D9=FPm
- 社区儿童活动的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/613
- 社区公共卫生的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/cjf
- 青少年户外教育的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/xqL
- 家庭环保行动的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/206=gvj
- 居民健康教育的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/jsx=331
- 图书借阅体验的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/GLY=Q6k
- 亲子阅读活动的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B7%A5%E5%85%B7_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/296
- 读书会组织的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B7%A5%E5%85%B7_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/mfd
- 城市休闲步道的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B7%A5%E5%85%B7_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/XH5
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B7%A5%E5%85%B7_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/196=cfe
- 乡村阅读空间的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B7%A5%E5%85%B7_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/lef=420
- 公共卫生宣传的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%B7%A5%E5%85%B7_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/1Iz=vzl
- 就业技能培训的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E4%B8%80%E4%B8%AA%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AB%E8%BD%AC%E8%BD%AC_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/801
- 社区活动空间的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E4%B8%80%E4%B8%AA%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AB%E8%BD%AC%E8%BD%AC_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/vqn
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E4%B8%80%E4%B8%AA%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AB%E8%BD%AC%E8%BD%AC_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/Db9
- 城市公共艺术的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E4%B8%80%E4%B8%AA%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AB%E8%BD%AC%E8%BD%AC_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/269=paq
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E4%B8%80%E4%B8%AA%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AB%E8%BD%AC%E8%BD%AC_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/tbh=972
- 非遗课堂体验的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9C%89%E4%B8%80%E4%B8%AA%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AB%E8%BD%AC%E8%BD%AC_%E5%BF%AB%E6%89%8B%E9%80%9F%E8%A7%88?/mwH=swG
- 社区应急准备的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E7%AB%99_360%E6%95%99%E8%82%B2?/736
- 线上办事服务的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E7%AB%99_360%E6%95%99%E8%82%B2?/vhf
- 家庭用电安全的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E7%AB%99_360%E6%95%99%E8%82%B2?/Bck
- 科学观察活动的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E7%AB%99_360%E6%95%99%E8%82%B2?/764=rst
- 社区慢性病防控的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E7%AB%99_360%E6%95%99%E8%82%B2?/lzq=734
- 社区公共议事的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%BD%91%E7%AB%99_360%E6%95%99%E8%82%B2?/G6B=1yG
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/420
- 校园节能行动的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/jxk
- 社区庭院绿化的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/tFI
- 公共健身器材的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/113=fov
- 农业科普体验的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/xef=341
- 社区运动空间的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E7%8C%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/z4R=Jmt
- 就业技能培训的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%BC%97%E8%B5%A2%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/910
- 家庭志愿活动的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%BC%97%E8%B5%A2%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/byr
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%BC%97%E8%B5%A2%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/8Fa
- 家庭养老规划的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%BC%97%E8%B5%A2%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/829=jok
- 学校体育活动的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%BC%97%E8%B5%A2%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/mrq=104
- 邻里共享空间的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E4%BC%97%E8%B5%A2%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/O5y=9V3
- 公益活动组织的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/122
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/jku
- 社区消防演练的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/D7q
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/630=gel
- 环境监测科普的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/tpw=842
- 校园节能行动的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%8A%A9%E6%89%8B%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8E%A2%E6%BA%90?/HiG=ixj
- 社区活动空间的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/649
- 儿童友好空间的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/zje
- 口袋公园建设的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/VTd
- 个人信息保护的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/337=hxq
- 城市雨天出行的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/kkq=054
- 网络信息辨识的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E6%B8%B8%E6%88%8F?/Xbm=5Cj
- 文化讲座服务的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/735
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/vve
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/8D0
- 绿色消费选择的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/505=kuh
- 周末休闲规划的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/iju=311
- 校园节能行动的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%84%E6%96%99%E5%8A%A9%E6%89%8B_%E7%99%BE%E5%BA%A6%E4%BF%A1%E6%89%98?/tcU=Mi2
- 城市噪声观察的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/831
- 人工智能科普的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/xcc
- 乡村休闲旅游的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/Chi
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/464=bky
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/tts=148
- 城市展览体验的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%98%E7%BD%91%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/e5y=9hU
- 儿童阅读角的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/730
- 社区学习活动的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/xog
- 社区法律科普中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/vbf
- 公共服务预约的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/561=nod
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/uky=188
- 急救知识普及的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/p3i=UVZ
- 社区花园共建的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E5%8A%A8%E6%BC%AB?/926
- 智能手机助老的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E5%8A%A8%E6%BC%AB?/jqi
- 公园休闲体验的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E5%8A%A8%E6%BC%AB?/A7q
- 城市公共标识中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E5%8A%A8%E6%BC%AB?/390=fwd
- 家庭健康科普的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E5%8A%A8%E6%BC%AB?/boy=404
- 城市夜间照明的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%95%8C%E9%9D%A2%E5%8A%A8%E6%BC%AB?/epJ=1aS
- 全民健身活动的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/271
- 社区慢性病防控的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/ths
- 青年职业探索的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/7dj
- 社区读书角建设的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/613=jfr
- 城市生活记录的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/eip=907
- 城市夜间生活的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/jxd=cD7
- 数字阅读服务的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_ai%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/787
- 公共文化活动的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_ai%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/kgf
- 城市步行环境的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_ai%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/Dsx
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_ai%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/816=oiw
- 公共设施使用的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_ai%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/xpu=468
- 城市骑行环境的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_ai%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/DcG=piN
- 老年人日常照护的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E9%BB%91%E7%A7%91%E6%8A%80%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_360%E6%96%87%E6%91%98?/277
- 户外活动组织的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E9%BB%91%E7%A7%91%E6%8A%80%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_360%E6%96%87%E6%91%98?/hzu
- 绿色生活实践的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E9%BB%91%E7%A7%91%E6%8A%80%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_360%E6%96%87%E6%91%98?/Lpx
- 社区体育组织的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E9%BB%91%E7%A7%91%E6%8A%80%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_360%E6%96%87%E6%91%98?/474=gxm
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E9%BB%91%E7%A7%91%E6%8A%80%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_360%E6%96%87%E6%91%98?/yth=396
- 个人数据管理的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E9%BB%91%E7%A7%91%E6%8A%80%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_360%E6%96%87%E6%91%98?/62V=ffs
- 家庭网络使用中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%89%B9%E8%89%B2%E4%B8%8E%E4%BC%98%E5%8A%BF_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/704
- 消防知识宣传的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%89%B9%E8%89%B2%E4%B8%8E%E4%BC%98%E5%8A%BF_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/qrg
- 数字资源检索的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%89%B9%E8%89%B2%E4%B8%8E%E4%BC%98%E5%8A%BF_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/nVX
- 农村环境治理的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%89%B9%E8%89%B2%E4%B8%8E%E4%BC%98%E5%8A%BF_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/633=ueo
- 线上阅读资源的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%89%B9%E8%89%B2%E4%B8%8E%E4%BC%98%E5%8A%BF_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/yoe=162
- 社区教育资源的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E7%89%B9%E8%89%B2%E4%B8%8E%E4%BC%98%E5%8A%BF_36%E6%B0%AA%E5%AE%9E%E5%BD%95?/MPv=F4u
- 校园社团活动的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BE%AE%E4%B9%90%E5%BF%85%E8%B5%A2%E8%BE%85%E5%8A%A9%E5%99%A8%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/487
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BE%AE%E4%B9%90%E5%BF%85%E8%B5%A2%E8%BE%85%E5%8A%A9%E5%99%A8%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/wzn
- 社区防暑服务的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BE%AE%E4%B9%90%E5%BF%85%E8%B5%A2%E8%BE%85%E5%8A%A9%E5%99%A8%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/JC8
- 休闲运动入门的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BE%AE%E4%B9%90%E5%BF%85%E8%B5%A2%E8%BE%85%E5%8A%A9%E5%99%A8%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/530=ehw
- 食品配送体验的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BE%AE%E4%B9%90%E5%BF%85%E8%B5%A2%E8%BE%85%E5%8A%A9%E5%99%A8%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/fdz=701
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BE%AE%E4%B9%90%E5%BF%85%E8%B5%A2%E8%BE%85%E5%8A%A9%E5%99%A8%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/4PF=UlR
- 社区商业活力的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6?/956
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6?/ckb
- 社区老年食堂的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6?/pr7
- 青少年户外教育的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6?/079=mbc
- 城市便民驿站的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6?/zus=094
- 城市文明实践的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E7%99%BE%E5%BA%A6?/d0L=CEn
- 公益活动组织的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/731
- 市民热线服务的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/lfn
- 读书会组织的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/cEo
- 社区消防演练的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/743=tjp
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/hlo=967
- 家庭环保行动的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E8%99%8E%E6%89%91%E6%BC%AB%E8%AF%84?/mF3=VYf
- 电子商务服务中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/911
- 城市绿色交通的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/nog
- 城乡公共服务的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/tEK
- 社区便民服务的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/636=hok
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/atj=325
- 居家适老化改造中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%AE%B6%E7%94%B5?/zZq=Kpp
- 健康饮食教育的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/919
- 急救知识普及的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/fdc
- 邻里共享空间的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/ggn
- 家庭环保习惯的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/523=wby
- 传统手工艺体验的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/frc=114
- 读书会组织的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BA%AC%E4%B8%9C%E8%B4%A2%E7%BB%8F?/2yP=ddE
- 社区慢性病防控的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/857
- 社区健康讲座的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/poz
- 乡村文化活动的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/E7e
- 学校体育活动的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/049=yig
- 数字学习资源的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/yzt=164
- 校园节能行动的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/0Ol=s6m
- 城市文化路线的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/771
- 城市公共自行车的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/igb
- 社区文化传播的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/MKV
- 青少年心理健康的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/749=cui
- 节假日出行安排的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/gis=923
- 节能生活方式的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E6%88%BF%E4%BA%A7?/OqX=7rE
- 社区菜市场服务的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/879
- 机器人科普活动的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/eqx
- 电子商务服务的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/ozR
- 城市地名文化的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/006=yti
- 社区故事采集的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/nie=038
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/qWQ=WTR
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%95%99%E4%BD%A0%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/315
- 城市公共标识的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%95%99%E4%BD%A0%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/zhc
- 城市绿道建设的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%95%99%E4%BD%A0%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/pfP
- 智慧城市体验的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%95%99%E4%BD%A0%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/297=ioz
- 社区环保活动的实际需求与回应 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%95%99%E4%BD%A0%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/cxb=330
- 社区邻里服务的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%95%99%E4%BD%A0%E6%80%8E%E4%B9%88%E7%9C%8B%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%A7%86%E9%A2%91?/DOi=MEs
- 灵活就业交流的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_3d%E5%BF%AB3%E5%BF%85%E4%B8%8B%E4%B8%80%E8%83%86%E6%9C%80%E5%87%86%E5%8F%B7%E7%A0%81_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/416
- 乡村公共服务中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_3d%E5%BF%AB3%E5%BF%85%E4%B8%8B%E4%B8%80%E8%83%86%E6%9C%80%E5%87%86%E5%8F%B7%E7%A0%81_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kfz
- 社区休闲设施的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_3d%E5%BF%AB3%E5%BF%85%E4%B8%8B%E4%B8%80%E8%83%86%E6%9C%80%E5%87%86%E5%8F%B7%E7%A0%81_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/BWg
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_3d%E5%BF%AB3%E5%BF%85%E4%B8%8B%E4%B8%80%E8%83%86%E6%9C%80%E5%87%86%E5%8F%B7%E7%A0%81_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/707=xcp
- 家庭养老规划的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_3d%E5%BF%AB3%E5%BF%85%E4%B8%8B%E4%B8%80%E8%83%86%E6%9C%80%E5%87%86%E5%8F%B7%E7%A0%81_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rvk=945
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_3d%E5%BF%AB3%E5%BF%85%E4%B8%8B%E4%B8%80%E8%83%86%E6%9C%80%E5%87%86%E5%8F%B7%E7%A0%81_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/D5u=aVD
- 社区协商议事的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%92%8C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/898
- 城市微更新实践的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%92%8C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/wzc
- 绿色办公实践的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%92%8C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/YCS
- 社区知识分享的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%92%8C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/639=ewb
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%92%8C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/soi=343
- 老年智能设备的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F%E5%92%8C%E5%8F%A3%E8%AF%80_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/Oe5=fxV
- 科普展览体验的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/824
- 公共场所导视的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/nhh
- 街区更新实践的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/E3V
- 节能生活方式的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/330=tru
- 电子商务服务的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/tih=748
- 城市应急广播的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/IkO=6fl
- 老年学习活动的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%A5%87%E8%91%A9%E7%A5%9E%E6%8B%9B%E6%9B%9D%E5%85%89_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/536
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%A5%87%E8%91%A9%E7%A5%9E%E6%8B%9B%E6%9B%9D%E5%85%89_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/oce
- 急救知识普及的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%A5%87%E8%91%A9%E7%A5%9E%E6%8B%9B%E6%9B%9D%E5%85%89_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/8aY
- 数字生活课堂的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%A5%87%E8%91%A9%E7%A5%9E%E6%8B%9B%E6%9B%9D%E5%85%89_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/435=boi
- 家庭收纳实践的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%A5%87%E8%91%A9%E7%A5%9E%E6%8B%9B%E6%9B%9D%E5%85%89_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/nfg=877
- 街区小店体验的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%A5%87%E8%91%A9%E7%A5%9E%E6%8B%9B%E6%9B%9D%E5%85%89_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/mnt=8PK
- 城市公共厕所的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/157
- 生活垃圾减量的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/lhs
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/Wh4
- 开放数据应用的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/118=siz
- 居民健康教育的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/kfu=969
- 社区教育资源的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/mqR=qJJ
- 数字资源检索的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/797
- 社区活动策划的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/obf
- 城市雨天出行的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/s8S
- 家庭饮食安排的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/261=aeh
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/obt=827
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E6%96%B0%E6%B5%AA%E4%B9%A6%E7%94%BB?/7b0=VsJ
- 乡村阅读空间的长期维护要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/224
- 数字创作工具的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/bfp
- 城市生活服务的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/W09
- 公园亲子设施的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/207=ddl
- 网络安全教育的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/vhh=612
- 社区活动报名的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E8%B5%9A%E9%92%B1%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%99%BE%E7%A7%91?/C2Z=4Dq
- 社区绿色空间的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/106
- 城市夜间照明的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/vxu
- 社区托育服务的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/bDV
- 绿色生活实践的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/457=mgs
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/ont=660
- 市民热线服务的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/OJT=5Ww
- 图书馆活动策划的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/767
- 垃圾分类指导的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/gan
- 街区更新实践的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/4zt
- 垃圾分类指导的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/253=olx
- 社区手工活动的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/wtw=172
- 健康信息获取的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BE%A4%E9%83%BD%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/MT6=kt8
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/540
- 小区公共照明的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/flc
- 家庭急救准备的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/JCL
- 家庭科学教育的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/642=kff
- 数字政务体验的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/zkc=602
- 儿童安全出行的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/kyu=XdF
- 青少年科普实践的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6%E4%BA%A4%E6%B5%81_360%E6%B1%87%E5%B8%82?/343
- 乡村文化活动的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6%E4%BA%A4%E6%B5%81_360%E6%B1%87%E5%B8%82?/nsq
- 街区道路维护的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6%E4%BA%A4%E6%B5%81_360%E6%B1%87%E5%B8%82?/TI8
- 家庭安全提示的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6%E4%BA%A4%E6%B5%81_360%E6%B1%87%E5%B8%82?/733=eup
- 全民健身活动的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6%E4%BA%A4%E6%B5%81_360%E6%B1%87%E5%B8%82?/fhm=339
- 城市微更新实践的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A424%E5%B0%8F%E6%97%B6%E4%BA%A4%E6%B5%81_360%E6%B1%87%E5%B8%82?/7td=QE5
- 社区家政服务的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/723
- 新能源出行的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/tfu
- 校园安全教育的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/Op5
- 社区教育资源的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/075=uto
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/qbj=548
- 家庭消费规划的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/9GC=F2O
- 人工智能科普的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/471
- 数字艺术创作的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jpl
- 城市夜间照明的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/SBp
- 城市公共厕所的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/764=xrs
- 城市绿色交通的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ano=133
- 乡村阅读活动的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AF%BC%E5%B8%88_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/pUG=GKA
- 家庭收纳实践的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/145
- 小区电梯维护的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/eey
- 邻里互助活动的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/y9G
- 家庭急救准备的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/806=gbo
- 社区设施共享的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/dvt=430
- 家庭环保行动的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E6%B2%BB?/3rM=hnP
- 青少年科普实践的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B61.0.0%E5%85%8D%E8%B4%B9%E7%89%88_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/270
- 公共场所导视的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B61.0.0%E5%85%8D%E8%B4%B9%E7%89%88_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/rgc

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
