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

- 家庭节能实践的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7-%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/780
- 科学教育活动的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7-%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/ghx
- 儿童阅读角中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7-%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/Cvw
- 街区绿化养护的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7-%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/479=rmw
- 城市绿道建设的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7-%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/swr=833
- 智能家居应用的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7-%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/D5W=v5P
- 健康信息获取的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90-%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/566
- 无障碍出行的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90-%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/hdd
- 社区生活指南的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90-%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/AxP
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90-%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/826=ywi
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90-%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/xoj=470
- 城市公共艺术的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90-%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/rxq=MJV
- 城市地名文化的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/541
- 数据分析入门的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/zxp
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/Nyq
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/536=rvt
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/urk=441
- 公共空间导览的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A%E7%A7%98%E7%B1%8D-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/SnZ=aYo
- 社区故事采集的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/802
- 本地旅行体验的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/grj
- 市民意见收集的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/0A4
- 智能家居应用的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/421=nbq
- 城市空气科普的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/xyf=975
- 老年人文化生活的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E4%B8%8E%E6%80%BB%E7%BB%93-%E8%99%8E%E5%97%85%E8%B4%A2%E6%8A%A5?/KLW=RcW
- 公交无障碍服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/243
- 网络安全教育的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/cre
- 乡村文化活动的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/1o5
- 图书馆活动策划的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/672=tnt
- 城市步行环境的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/wrk=120
- 城市基础设施的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC-%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/Gb1=Sm2
- 城市慢行系统的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%9D%E9%99%A9?/384
- 城市骑行环境的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%9D%E9%99%A9?/bhv
- 城市生活记录的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%9D%E9%99%A9?/xsf
- 社区应急准备的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%9D%E9%99%A9?/561=ole
- 城市便民驿站的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%9D%E9%99%A9?/pdd=531
- 社区志愿服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BF%AB3%E6%8A%80%E5%B7%A7qq%E7%BE%A4-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%9D%E9%99%A9?/Ldw=q39
- 新能源知识普及的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/567
- 青年就业服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/oeo
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/vAM
- 街道综合服务的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/241=rcd
- 社区便民服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/wfd=260
- 居家防滑改造的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%92%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B-%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/3Si=EbL
- 家庭节能实践的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF?/670
- 社区共享书架的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF?/spo
- 开放数据应用的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF?/Qgt
- 绿色消费选择的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF?/057=xqz
- 数字艺术创作的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF?/jje=033
- 城市共享单车的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E4%B8%8A%E5%B2%B8%E6%8A%80%E5%B7%A7-%E8%85%BE%E8%AE%AF?/QwD=k4u
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89-%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/999
- 社区心理支持的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89-%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/uwl
- 公共空间照明的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89-%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/z7v
- 社区便民集市的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89-%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/414=mzh
- 社区故事采集的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89-%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/cqc=442
- 社区教育资源的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B8%89%E5%BF%85%E8%83%9C%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80%EF%BC%88KK%EF%BC%89-%E8%B7%A8%E6%B4%8B%E8%B4%A2%E7%BB%8F?/sDe=1af
- 社区体育组织的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF-%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/154
- 城市公共艺术中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF-%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/uyj
- 小区电梯维护的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF-%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/9vo
- 城市绿色交通的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF-%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/898=zdb
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF-%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/qqo=937
- 创业经验分享的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF-%E8%99%8E%E5%97%85%E5%85%AC%E5%BC%80%E8%AF%BE?/PjZ=HMu
- 城市基础设施的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/478
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/stv
- 社区便利生活的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/xg7
- 乡村公共文化的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/554=lpo
- 社区家校合作的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/aye=622
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E9%B8%BF%E5%8F%91%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%93%94%E5%93%A9%E7%9E%AD%E6%9C%9B?/Bef=OsU
- 城市夜间照明的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/910
- 绿色建筑理念的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/avg
- 地方美食文化的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/Cgn
- 家庭教育交流的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/635=nkq
- 社区休闲设施的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/sho=327
- 城市文明实践的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.8.15%2C%E5%BF%AB%E4%B8%89%E7%A8%B3%E8%B5%9A%E7%A7%98%E8%AF%80-%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/E1h=9Zb
- 医院导诊服务中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/244
- 社区公共卫生的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/exo
- 农村环境治理的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/uhB
- 城市公共座椅的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/671=ovx
- 家庭照护支持中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/rjg=031
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_3d%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/049=WNR
- 社区停车服务的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/271
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/vlx
- 数字生活课堂的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/oRz
- 非遗体验活动的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/471=sqd
- 旧物循环利用中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/gry=813
- 社区学习活动的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%9C%80%E6%96%B0%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E7%82%B9?/cmh=dRE
- 公共空间安全的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%96%B0%E6%B5%AA%E4%BC%97%E6%B5%8B?/584
- 城市步行环境的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%96%B0%E6%B5%AA%E4%BC%97%E6%B5%8B?/xtc
- 公园休闲体验的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%96%B0%E6%B5%AA%E4%BC%97%E6%B5%8B?/jQt
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%96%B0%E6%B5%AA%E4%BC%97%E6%B5%8B?/376=dui
- 公共服务评价的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%96%B0%E6%B5%AA%E4%BC%97%E6%B5%8B?/tan=069
- 城市步行友好的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E6%96%B0%E6%B5%AA%E4%BC%97%E6%B5%8B?/f5h=5GE
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/136
- 乡村教育资源的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/rqs
- 传统手工艺体验的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/zA1
- 学校食育活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/205=wmi
- 本地消费场景的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/liu=714
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E4%B8%83%E7%A0%81%E5%B1%82%E8%BF%9B%E5%BC%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/MkM=lC2
- 街头绿植养护的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/802
- 基层健康服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/dzh
- 街区更新实践的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/P8J
- 城市建设科普的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/096=ytf
- 健康步道使用的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/ljt=823
- 社区公共议事的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%BA%95%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/H41=RNC
- 科学信息获取中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/258
- 社区体育组织的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/mmd
- 光伏知识科普的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/ruf
- 青少年科技社团的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/307=pgm
- 运动安全知识的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/nos=211
- 线上阅读资源的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E4%BC%98%E9%85%B7%E4%BF%A1%E8%B4%B7?/3kj=hff
- 乡村公共阅读的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/235
- 公共文化活动的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/izg
- 公共场所导视的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/xMl
- 城市公共空间的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/214=etl
- 儿童户外活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/xww=412
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/GSc=0Hc
- 物业服务沟通的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36-%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/375
- 远程协作工具的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36-%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/fqz
- 儿童户外活动的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36-%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/H1j
- 城市慢行系统的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36-%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/259=xeh
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36-%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/rdc=582
- 城乡交流活动的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71.3.9_18_36-%E8%B4%A2%E7%BB%8F%E7%BB%8F%E6%B5%8E?/bhr=68I
- 家庭健康管理的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/437
- 城市噪声观察的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/yan
- 城市文明出行的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/XTB
- 社区科普课堂的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/184=myx
- 旧物循环利用的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/pjs=534
- 社区信息发布的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E6%AD%A3%E7%A1%AE%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/YM0=l4Y
- 城市微更新实践的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95-%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/472
- 急救知识普及的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95-%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/dbv
- 新能源知识普及的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95-%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/KFx
- 城市文明实践的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95-%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/167=aei
- 小区停车协商的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95-%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/dra=093
- 电子商务服务的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%95%E7%9A%84%E5%85%AD%E7%A7%8D%E6%96%B9%E6%B3%95-%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/0Zf=Wop
- 生成式工具使用的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/178
- 便民维修服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/ihk
- 社区快递服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/Khm
- 创业经验分享中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/437=rys
- 社区知识分享的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/zuk=254
- 城市公共艺术的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8C%E7%BE%8E%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/xiA=7F7
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/703
- 公益活动组织的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/lje
- 数字设备回收的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/Xxc
- 数字素养提升的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/575=yab
- 数字设备回收的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/myr=607
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E6%9C%80%E8%81%AA%E6%98%8E%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95-%E5%BF%AB%E6%89%8B%E7%BB%BC%E8%89%BA?/ijg=Lxi
- 校园阅读活动的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/806
- 城市应急广播的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/axz
- 社区休闲设施的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/IzQ
- 社区慢性病防控的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/484=tof
- 公共空间照明的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/qug=705
- 绿色建筑理念的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92-%E8%99%8E%E6%89%91%E5%8D%83%E5%B8%86?/siX=m23
- 便民维修服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/824
- 全民阅读推广的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/wwl
- 节能生活方式的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/6He
- 青少年心理健康的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/339=mra
- 机器人科普活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/sdj=852
- 城市公共座椅的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%9C%80%E7%A8%B3%E9%AB%98%E6%89%8B%E5%9B%9E%E6%9C%AC%E6%89%93%E6%B3%95-%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/3IC=ur3
- 小区电梯维护的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/809
- 日常摄影记录的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/tuo
- 数字政务体验的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/K7z
- 基层医疗预约的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/446=jde
- 数字阅读服务的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/yer=909
- 城市文化路线的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9AQQ-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/wGq=lmk
- 开放数据应用的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/099
- 小区电梯维护的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/lsf
- 运动安全知识的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/xfX
- 社区文化节活动的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/121=cjw
- 非遗体验活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/xqs=542
- 居家适老化改造的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8D%95%E5%B8%A6%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%94%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/DF7=ihw
- 地方民俗记录的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8-360%E8%B4%A2%E7%BB%8F?/498
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8-360%E8%B4%A2%E7%BB%8F?/dvq
- 文化讲座服务的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8-360%E8%B4%A2%E7%BB%8F?/gPw
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8-360%E8%B4%A2%E7%BB%8F?/386=xbm
- 智慧城市体验的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8-360%E8%B4%A2%E7%BB%8F?/fxv=933
- 绿色办公实践的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%8A%E5%B2%B8-360%E8%B4%A2%E7%BB%8F?/dNy=T1t
- 就业技能培训的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/425
- 青年志愿活动的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/gti
- 社区应急准备的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/b6m
- 学校食育活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/163=oap
- 乡村生态观察的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/hoy=389
- 社区停车服务的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/OWm=CHj
- 城市地名文化的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/387
- 信息无障碍体验的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/ney
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/h4N
- 乡村生态观察的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/878=ldn
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/msp=864
- 智慧停车服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92-%E8%8A%92%E6%9E%9C%E5%BD%A9%E7%A5%A8?/LcV=ful
- 节能生活方式的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/503
- 儿童友好街区的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/zwq
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/hfy
- 周末休闲规划中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/377=rsr
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/wna=262
- 公交无障碍服务的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%80%81%E5%B8%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B8%AF%E8%82%A1?/bYC=6cz
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/302
- 物业服务沟通的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/fty
- 公共空间照明的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/tPu
- 公园亲子设施的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/250=kao
- 数字创意课程的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/ugl=493
- 城市公共座椅的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%8D%95%E5%B8%A6%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/DWd=fEh
- 机器学习入门的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7-%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/952
- 城市公共饮水的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7-%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/hcq
- 城市公共自行车的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7-%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/NvL
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7-%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/799=kbw
- 光伏知识科普的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7-%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/eer=853
- 儿童阅读角的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80QQ%E5%8F%B7-%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/UyG=njM
- 小区电梯维护的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app-%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/902
- 绿色校园实践的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app-%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/xlr
- 青年就业服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app-%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/xJa
- 网络安全教育的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app-%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/274=bla
- 数据分析入门的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app-%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/qfm=489
- 青年志愿活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94app-%E8%B0%B7%E6%AD%8C%E8%AF%BB%E6%8A%A5?/THl=mci
- 公园休闲体验的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/011
- 社区文化节活动的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/wkg
- 青年志愿活动的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/om6
- 便民服务地图的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/276=cby
- 公共文化活动的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/kah=869
- 城市公共标识的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E6%80%8E%E4%B9%88%E8%B7%9F%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E7%89%B9%E7%A8%BF?/ZxN=uYr
- 社区运动空间的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq-%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/220
- 城乡公共服务的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq-%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/uly
- 城市游园体验的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq-%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/wNt
- 街区小店体验的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq-%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/169=sua
- 创业经验分享的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq-%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/cby=214
- 绿色出行服务的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4%E8%81%8Aqq-%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/FrD=17q
- 社区协商议事的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6-%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/408
- 乡村生态观察的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6-%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/scf
- 公共交通接驳的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6-%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/PfJ
- 公共交通信息服务的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6-%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/230=ecq
- 公共服务咨询的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6-%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/uzq=964
- 老年智能设备的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6-%E9%A1%BA%E4%B8%B0%E7%BB%8F%E6%B5%8E?/HLe=L2N
- 城市雨天出行的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1-%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/892
- 青少年心理健康的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1-%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/wob
- 社区活动策划的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1-%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/J83
- 家庭网络使用的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1-%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/055=puo
- 家庭健康科普的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1-%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/dbl=867
- 城市水环境观察的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1-%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/SoH=sJk
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/757
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/ger
- 社区便利生活的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/iVS
- 家庭运动计划的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/768=hwt
- 社区法律科普的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/ktp=993
- 公共健身器材的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E5%87%A4%E5%87%B0%E7%83%AD%E6%A6%9C?/i7w=GZr
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9?/852
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9?/xxc
- 急救知识普及的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9?/2yD
- 课后服务体验的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9?/587=ijt
- 生活垃圾减量的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9?/mxk=224
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80-%E8%99%8E%E6%89%91%E5%9C%B0%E6%96%B9?/pdB=dSj
- 社区养老服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/016
- 健康步道使用的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/hqr
- 老年学习活动的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/xpU
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/427=jim

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
