# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 生活垃圾回收的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9Fpk10%E6%80%8E%E4%B9%88%E7%8E%A9-%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/uww=817
- 乡村生态观察的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%9E%81%E9%80%9Fpk10%E6%80%8E%E4%B9%88%E7%8E%A9-%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/qZB=0Lb
- 职业技能学习的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9FPK10%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/270
- 社区生活指南的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9FPK10%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/hkm
- 老年数字阅读的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9FPK10%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/2Qz
- 社区便利生活的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9FPK10%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/758=aqg
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9FPK10%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/ier=735
- 城市绿道建设的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%9E%81%E9%80%9FPK10%E7%99%BB%E5%BD%95-%E5%8D%B3%E5%88%BB%E8%AE%BA%E5%9D%9B?/S3j=lzq
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9Fpk10app-%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/588
- 社区学习活动的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9Fpk10app-%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/uvu
- 公共交通接驳的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9Fpk10app-%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/H4k
- 老年人出行服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9Fpk10app-%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/635=ogk
- 街区绿化养护的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9Fpk10app-%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/ymd=114
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9Fpk10app-%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/FAQ=tnf
- 城市公共标识的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97%E6%9E%81%E9%80%9Fpk10%E4%BA%94%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9-360%E5%9B%BE%E9%89%B4?/238
- 志愿者培训交流的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97%E6%9E%81%E9%80%9Fpk10%E4%BA%94%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9-360%E5%9B%BE%E9%89%B4?/nyd
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97%E6%9E%81%E9%80%9Fpk10%E4%BA%94%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9-360%E5%9B%BE%E9%89%B4?/SEh
- 城市骑行环境的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97%E6%9E%81%E9%80%9Fpk10%E4%BA%94%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9-360%E5%9B%BE%E9%89%B4?/868=rwi
- 社区商业活力的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97%E6%9E%81%E9%80%9Fpk10%E4%BA%94%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9-360%E5%9B%BE%E9%89%B4?/ezy=808
- 远程协作工具的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97%E6%9E%81%E9%80%9Fpk10%E4%BA%94%E5%88%86%E9%92%9F%E5%AE%98%E6%96%B9-360%E5%9B%BE%E9%89%B4?/FzP=pDP
- 环境监测科普的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%87%8C%E9%9D%A2%E9%92%B1%E5%8F%AF%E4%BB%A5%E5%8F%96%E5%87%BA%E6%9D%A5%E5%90%97-%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/092
- 街区道路维护的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%87%8C%E9%9D%A2%E9%92%B1%E5%8F%AF%E4%BB%A5%E5%8F%96%E5%87%BA%E6%9D%A5%E5%90%97-%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/nag
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%87%8C%E9%9D%A2%E9%92%B1%E5%8F%AF%E4%BB%A5%E5%8F%96%E5%87%BA%E6%9D%A5%E5%90%97-%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/iqM
- 新能源知识普及的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%87%8C%E9%9D%A2%E9%92%B1%E5%8F%AF%E4%BB%A5%E5%8F%96%E5%87%BA%E6%9D%A5%E5%90%97-%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/170=hee
- 社区便利生活的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%87%8C%E9%9D%A2%E9%92%B1%E5%8F%AF%E4%BB%A5%E5%8F%96%E5%87%BA%E6%9D%A5%E5%90%97-%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/lim=405
- 亲子科普活动的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9Fpk10%E9%87%8C%E9%9D%A2%E9%92%B1%E5%8F%AF%E4%BB%A5%E5%8F%96%E5%87%BA%E6%9D%A5%E5%90%97-%E6%90%9C%E7%8B%90%E7%A4%BE%E5%8C%BA?/KW1=5Pf
- 非遗课堂体验的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/773
- 校园安全教育的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/pih
- 社区教育资源的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/2cs
- 青年职业探索的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/704=zgk
- 应急物资管理的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/tux=934
- 文化讲座服务的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9Fpk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/uGf=Rfl
- 绿色生活实践的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6app-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/872
- 家庭节能设备的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6app-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/ike
- 数据分析入门的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6app-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/mUN
- 公益活动组织的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6app-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/106=les
- 公共场所导视的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6app-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/osb=206
- 数字素养提升中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E8%B5%9B%E8%BD%A6app-%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/VDI=eKQ
- 邻里互助活动的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E4%B8%80%E5%88%86%E9%92%9F%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2-360%E5%81%A5%E5%BA%B7?/959
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E4%B8%80%E5%88%86%E9%92%9F%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2-360%E5%81%A5%E5%BA%B7?/btp
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E4%B8%80%E5%88%86%E9%92%9F%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2-360%E5%81%A5%E5%BA%B7?/6cf
- 绿色生活实践的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E4%B8%80%E5%88%86%E9%92%9F%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2-360%E5%81%A5%E5%BA%B7?/744=jww
- 城市人文观察的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E4%B8%80%E5%88%86%E9%92%9F%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2-360%E5%81%A5%E5%BA%B7?/wrn=996
- 邻里共享空间的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_168%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E4%B8%80%E5%88%86%E9%92%9F%E6%95%B0%E6%8D%AE%E6%9F%A5%E8%AF%A2-360%E5%81%A5%E5%BA%B7?/9AG=UD1
- 环境教育课程的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/566
- 城市游园体验的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/rdv
- 社区垃圾回收的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/2S7
- 市民意见收集的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/368=vau
- 数据分析入门的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/xth=160
- 绿色校园实践的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_168%E8%B5%9B%E8%BD%A6%E4%BD%93%E5%BD%A9%E4%B8%80%E5%88%86%E9%92%9F%E6%9C%80%E6%96%B0%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E8%BF%B0%E8%AF%84?/pyN=OUG
- 全民健身活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%89%8B%E8%BE%93788%E7%A2%98tw-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/662
- 社区体育组织的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%89%8B%E8%BE%93788%E7%A2%98tw-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/cyh
- 网络安全教育的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%89%8B%E8%BE%93788%E7%A2%98tw-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/jKT
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%89%8B%E8%BE%93788%E7%A2%98tw-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/713=ude
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%89%8B%E8%BE%93788%E7%A2%98tw-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/cgr=077
- 基层健康服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_168%E8%B5%9B%E8%BD%A6%E5%AE%98%E7%BD%91%E6%89%8B%E8%BE%93788%E7%A2%98tw-%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8D%8F?/o5Q=z7y
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_168%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/190
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_168%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/gus
- 乡村文化空间的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_168%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/otb
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_168%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/688=njh
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_168%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/djy=629
- 健康信息获取的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_168%E8%B5%9B%E8%BD%A6%E8%BD%AF%E4%BB%B6-%E6%96%B0%E6%B5%AA%E5%9C%B0%E6%96%B9?/GIR=8ms
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91-%E5%8E%86%E5%8F%B2-%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/125
- 城市夜间照明的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91-%E5%8E%86%E5%8F%B2-%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/aup
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91-%E5%8E%86%E5%8F%B2-%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/9dw
- 城市公共标识的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91-%E5%8E%86%E5%8F%B2-%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/316=izw
- 周末休闲规划的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91-%E5%8E%86%E5%8F%B2-%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/hvd=395
- 城市慢行系统的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%AE%98%E7%BD%91%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91-%E5%8E%86%E5%8F%B2-%E8%85%BE%E8%AE%AF%E6%9C%AD%E8%AE%B0?/gn9=Tuy
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/536
- 远程协作工具的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/fcr
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/p4b
- 乡村阅读空间的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/430=uzz
- 课后服务体验的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/xwp=746
- 线上阅读资源的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6-%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/hOd=W4K
- 家庭园艺实践的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%9C%9F%E5%AE%9E%E8%B5%9B%E8%BD%A63%E7%A0%B4%E8%A7%A3%E7%89%88-%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/761
- 软件开发学习的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%9C%9F%E5%AE%9E%E8%B5%9B%E8%BD%A63%E7%A0%B4%E8%A7%A3%E7%89%88-%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/chm
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%9C%9F%E5%AE%9E%E8%B5%9B%E8%BD%A63%E7%A0%B4%E8%A7%A3%E7%89%88-%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/zpk
- 图书馆活动策划的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%9C%9F%E5%AE%9E%E8%B5%9B%E8%BD%A63%E7%A0%B4%E8%A7%A3%E7%89%88-%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/538=hbj
- 社区活动策划中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%9C%9F%E5%AE%9E%E8%B5%9B%E8%BD%A63%E7%A0%B4%E8%A7%A3%E7%89%88-%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/lku=950
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%9C%9F%E5%AE%9E%E8%B5%9B%E8%BD%A63%E7%A0%B4%E8%A7%A3%E7%89%88-%E9%95%BF%E8%99%B9%E8%B4%A2%E7%BB%8F?/Hib=EGZ
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87app-%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/728
- 智能手机助老的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87app-%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/zyk
- 城市步行环境的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87app-%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/PiO
- 运动安全知识的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87app-%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/815=toh
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87app-%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/usx=111
- 城市公共标识的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_168%E9%A3%9E%E8%89%87app-%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/6dn=DzW
- 全民阅读推广的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/205
- 软件开发学习的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/vsf
- 儿童运动体验的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/k0j
- 儿童阅读角的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/959=tkx
- 校园安全教育的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/mel=583
- 居家适老化改造的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_168%E9%A3%9E%E8%89%87app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E9%9B%85%E8%99%8E%E7%BE%8E%E5%A6%86?/3uN=nRy
- 社区花园共建中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%97%B6%E5%B0%9A?/937
- 公共服务评价的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%97%B6%E5%B0%9A?/liy
- 食品安全科普的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%97%B6%E5%B0%9A?/Dev
- 城市噪声观察的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%97%B6%E5%B0%9A?/719=tsm
- 科学健身方法的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%97%B6%E5%B0%9A?/zrv=181
- 城市农夫市集的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-36%E6%B0%AA%E6%97%B6%E5%B0%9A?/UqH=Ixl
- 儿童阅读角的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%87%E7%95%AA%E6%91%8A%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD%E8%AE%B0%E5%BD%95-%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/465
- 绿色校园实践的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%87%E7%95%AA%E6%91%8A%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD%E8%AE%B0%E5%BD%95-%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/osa
- 社区环保活动的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%87%E7%95%AA%E6%91%8A%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD%E8%AE%B0%E5%BD%95-%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/9lC
- 小区停车协商的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%87%E7%95%AA%E6%91%8A%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD%E8%AE%B0%E5%BD%95-%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/852=rio
- 城市公共标识的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%87%E7%95%AA%E6%91%8A%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD%E8%AE%B0%E5%BD%95-%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/bru=556
- 基层健康服务的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_168%E9%A3%9E%E8%89%87%E7%95%AA%E6%91%8A%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E7%9B%B4%E6%92%AD%E8%AE%B0%E5%BD%95-%E7%BD%91%E6%98%93%E6%88%B7%E5%A4%96?/UNm=a12
- 城市适老服务的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/265
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/kea
- 社区文化节活动的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/cfU
- 青年就业服务的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/347=bzg
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/xpx=995
- 无障碍出行的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96-%E6%90%9C%E7%8B%97%E6%96%87%E5%8C%96?/yTp=ve3
- 食品配送体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/869
- 光伏知识科普的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/uuw
- 生活服务数字化的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/0zF
- 社区互助网络的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/333=kxk
- 数字阅读服务的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/zht=846
- 便民信息查询的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8168%E9%A3%9E%E8%89%87app%E4%B8%8B%E8%BD%BD-%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/xUb=S0u
- 社区学习活动的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E7%9A%84%E4%BA%BA%E5%A4%9A-%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/064
- 终身学习资源的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E7%9A%84%E4%BA%BA%E5%A4%9A-%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/frq
- 线上办事服务的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E7%9A%84%E4%BA%BA%E5%A4%9A-%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/g2V
- 个人时间管理的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E7%9A%84%E4%BA%BA%E5%A4%9A-%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/682=lwg
- 家庭养老规划的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E7%9A%84%E4%BA%BA%E5%A4%9A-%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/ukv=757
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%A3%9E%E8%89%87%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E7%9A%84%E4%BA%BA%E5%A4%9A-%E6%BE%8E%E6%B9%83%E7%9B%98%E7%82%B9?/tRr=AAf
- 文化场馆预约的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87168%E6%98%AF%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84-%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/995
- 社区休闲设施的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87168%E6%98%AF%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84-%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/cdo
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87168%E6%98%AF%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84-%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/asj
- 低碳社区实践的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87168%E6%98%AF%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84-%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/191=ezr
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87168%E6%98%AF%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84-%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/inh=109
- 城市休闲步道的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%A3%9E%E8%89%87168%E6%98%AF%E5%B1%9E%E4%BA%8E%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84-%E7%99%BE%E5%BA%A6%E6%91%84%E5%BD%B1?/mmE=1Zm
- 数字学习资源的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/659
- 城市水环境观察的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/knm
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/LfQ
- 节日文化体验的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/625=eey
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/rpw=589
- 生活技能分享的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_168%E8%B5%9B%E8%BD%A6%E9%A3%9E%E8%89%87%E7%BE%A4-%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/rCL=VRu
- 城市公共厕所中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/228
- 科普展览体验的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/waj
- 便民信息查询的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/3UJ
- 环境监测科普的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/416=zzb
- 乡村公共阅读的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/lgs=829
- 健康饮食教育中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90168-%E5%93%94%E5%93%A9%E5%91%A8%E6%8A%A5?/kg8=Ieg
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_168%E9%A3%9E%E8%89%87%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/671
- 社区活动报名的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_168%E9%A3%9E%E8%89%87%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/uex
- 城市共享单车的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_168%E9%A3%9E%E8%89%87%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/Ylg
- 公共卫生设施的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_168%E9%A3%9E%E8%89%87%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/057=swe
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_168%E9%A3%9E%E8%89%87%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/wbd=414
- 家庭节能实践的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_168%E9%A3%9E%E8%89%87%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/nxO=HiD
- 药品使用科普的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%BC%80%E5%A5%96app-%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/236
- 城乡公共服务的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%BC%80%E5%A5%96app-%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/soy
- 老年学习活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%BC%80%E5%A5%96app-%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/Re8
- 老年人日常照护的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%BC%80%E5%A5%96app-%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/560=sdu
- 本地历史资料的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%BC%80%E5%A5%96app-%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/lsr=125
- 家庭环保行动的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_168%E5%B9%B8%E8%BF%90%E9%A3%9E%E5%BC%80%E8%89%87%E5%BC%80%E5%A5%96app-%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/qoc=r7i
- 绿色校园实践的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/580
- 乡村阅读空间的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/xmf
- 食品安全科普的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/1qh
- 城市适老服务中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/289=otv
- 城市慢行系统的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/ofk=498
- 家庭运动计划的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E5%A4%B4%E6%9D%A1%E6%A5%BC%E5%B8%82?/lx5=MPI
- 数字支付体验的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/255
- 公共场馆服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/vmz
- 数字生活课堂的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/8kk
- 公共设施使用的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/727=jmx
- 在线学习体验的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/jat=687
- 全民健身活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%A3%9E%E5%A4%A9%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/qPR=jsh
- 社区宠物管理的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A5%87%E5%BC%82%E6%9E%9C%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/185
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A5%87%E5%BC%82%E6%9E%9C%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/udu
- 智能手机助老的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A5%87%E5%BC%82%E6%9E%9C%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/3F6
- 数字创作工具的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A5%87%E5%BC%82%E6%9E%9C%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/113=qov
- 城市宠物友好空间中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A5%87%E5%BC%82%E6%9E%9C%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/eic=019
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%A5%87%E5%BC%82%E6%9E%9C%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6app-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F?/1w1=uMH
- 便民维修服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6MOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95-%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/491
- 小微企业服务的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6MOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95-%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/tix
- 骑行路线规划的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6MOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95-%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/1T4
- 儿童户外活动的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6MOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95-%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/350=nfe
- 城市休闲步道的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6MOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95-%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/ucb=641
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6MOD%E4%BD%9C%E5%BC%8A%E8%8F%9C%E5%8D%95-%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/izP=n5T
- 日常摄影记录的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/833
- 城市社区治理的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/bte
- 社区应急准备的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/CyU
- 社区商业活力的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/209=uuk
- 社区公共卫生的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/dto=766
- 口袋公园建设的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6168%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/li4=5dU
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B5%A2%E4%BA%868%E5%B9%B4%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/070
- 乡村公共阅读的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B5%A2%E4%BA%868%E5%B9%B4%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/uef
- 小区电梯维护的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B5%A2%E4%BA%868%E5%B9%B4%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/tBt
- 文化讲座服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B5%A2%E4%BA%868%E5%B9%B4%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/080=loi
- 公交站点体验的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B5%A2%E4%BA%868%E5%B9%B4%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/bzj=065
- 课后服务体验的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E8%B5%A2%E4%BA%868%E5%B9%B4%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/VKN=FIG
- 公共设施使用的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61-10%E5%90%8D%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/122
- 公共空间照明的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61-10%E5%90%8D%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/qxg
- 老旧小区改造的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61-10%E5%90%8D%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/zmh
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61-10%E5%90%8D%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/940=frh
- 绿色消费选择中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61-10%E5%90%8D%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/qop=189
- 农业科普体验的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61-10%E5%90%8D%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E8%99%8E%E5%97%85%E6%99%A8%E6%8A%A5?/0zt=ukA
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BB%BF%E9%92%A5%E5%8C%99%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/143
- 在线教育体验的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BB%BF%E9%92%A5%E5%8C%99%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/skw
- 信息无障碍体验的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BB%BF%E9%92%A5%E5%8C%99%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/XmW
- 读书会组织从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BB%BF%E9%92%A5%E5%8C%99%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/770=rlp
- 社区阅读服务的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BB%BF%E9%92%A5%E5%8C%99%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/hjc=313
- 健康步道使用的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%90%91%E5%89%8D%E5%86%B2%E7%BB%BF%E9%92%A5%E5%8C%99%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD-%E7%95%8C%E9%9D%A2%E5%85%AC%E7%9B%8A?/1nt=WmR
- 绿色快递包装的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A69%E7%A0%81%E5%AF%B9%E5%88%B7%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/553
- 周末休闲规划的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A69%E7%A0%81%E5%AF%B9%E5%88%B7%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/fem
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A69%E7%A0%81%E5%AF%B9%E5%88%B7%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/84k
- 医院导诊服务的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A69%E7%A0%81%E5%AF%B9%E5%88%B7%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/578=eep
- 亲子阅读活动的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A69%E7%A0%81%E5%AF%B9%E5%88%B7%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/cws=067
- 基层健康服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E8%B5%9B%E8%BD%A69%E7%A0%81%E5%AF%B9%E5%88%B7%E6%96%B9%E6%B3%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BB%BC%E8%89%BA?/lLJ=GVy
- 农业科普体验的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/713
- 公共服务数字化的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/nrs
- 健康饮水科普的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/Ldt
- 智能手机助老的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/495=jxb
- 课后服务体验的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/ynd=388
- 社区休闲设施的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E4%B8%8B%E8%BD%BD%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6-%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/hWf=sQ6
- 家庭健康管理的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/642
- 公共文化活动的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/bco
- 城市文明实践的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/81G
- 公共服务数字化的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/081=dae
- 公共设施维护的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/zru=891
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/dQ2=qpn
- 开源技术交流的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/791
- 社区商业活力的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/uce
- 城市住房服务的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/u3N
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/400=gms
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/oru=374
- 公共图书馆服务的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E8%AE%A1%E5%88%92-%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/zGW=udI
- 社区互助网络的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/477
- 公共交通接驳的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/dyv
- 网络信息辨识的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/5Hf
- 基层健康档案的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/273=ckh
- 生成式工具使用的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/wys=321
- 读书会组织的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/pJ4=K03
- 老年智能设备的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/282
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/bao
- 在线学习体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/VM3
- 本地历史资料的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/743=meq
- 公园休闲体验中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/ahr=887
- 乡村文化活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E8%8A%92%E6%9E%9C%E5%91%A8%E6%8A%A5?/ydy=WJX
- 公共设施维护的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%877%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F-%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/659
- 邻里共享空间的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%877%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F-%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/qsy
- 节约用水实践的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%877%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F-%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/svn
- 公共卫生设施的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%877%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F-%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/629=arl
- 灵活就业交流的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%877%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F-%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/wdd=768
- 城市骑行环境的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%877%E7%A0%81%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F-%E6%8A%96%E9%9F%B3%E6%BC%AB%E8%AF%84?/zbV=0Eo
- 运动安全知识的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%925%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/731
- 乡村生活观察的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%925%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/obi
- 数字支付体验的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%925%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/5fL
- 文化场馆预约的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%925%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/438=vlh
- 数字艺术创作的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%925%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/mta=248
- 乡村文化活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%925%E7%A0%81%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F?/rrO=yS9
- 生成式工具使用的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E4%BD%93%E5%BD%A9%E9%A3%9E%E8%89%87168%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/426
- 本地历史资料的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E4%BD%93%E5%BD%A9%E9%A3%9E%E8%89%87168%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2%E7%BD%91-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/tag

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
