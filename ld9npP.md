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

- 家庭阅读计划的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/402
- 科普展览体验的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/euq
- 非遗体验活动的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/AsC
- 健康饮水科普的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/515=mbl
- 城市公共艺术的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/csw=418
- 社区心理支持的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/UHA=5L7
- 社区教育资源的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/565
- 公共场所导视的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/rtk
- 无障碍信息设计的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/yAG
- 全民阅读推广的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/427=sap
- 软件开发学习的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/ndf=382
- 文明养宠科普的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/vAt=Vae
- 青少年职业启蒙的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/616
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/yfx
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/Wsc
- 乡村阅读活动的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/758=cau
- 社区交通安全的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/fym=323
- 校园安全教育的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_36%E6%B0%AA%E8%B4%A2%E6%8A%A5?/VUf=Lns
- 家庭志愿活动的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/277
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/vrm
- 居家适老化改造的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/2Ww
- 公交无障碍服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/106=xsj
- 新能源知识普及的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/hwj=280
- 校园阅读活动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/631=6s8
- 城市慢跑路线的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/847
- 个人时间管理的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/opj
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/FRU
- 社区家政服务的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/184=bik
- 社区快递服务的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/ftd=960
- 地方民俗记录的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/2Bl=yP4
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/630
- 社区教育资源的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/ghr
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/UCL
- 市民热线服务的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/866=ovp
- 小区电梯维护的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/emg=078
- 休闲运动入门的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E5%BF%85%E5%BA%94%E8%A7%86%E9%A2%91?/fjQ=BDW
- 城市农夫市集的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/402
- 医院导诊服务的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/mql
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/wqw
- 社区心理支持的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/622=ldz
- 创业经验分享的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/enq=835
- 公共服务沟通的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E8%B1%86%E7%93%A3%E8%AE%BF%E8%B0%88?/xHi=MGB
- 城市生活服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/690
- 新能源知识普及的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/xlz
- 节气饮食文化的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/cgT
- 城市文明出行的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/094=iht
- 健康步道使用的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/rpm=034
- 创业经验分享的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E7%99%BE%E5%BA%A6%E5%AE%8F%E8%A7%82?/sD1=M5L
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/867
- 公共卫生宣传的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/wud
- 本地消费场景的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/LVz
- 节日文化体验的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/893=ixn
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/mqt=333
- 科学健身方法的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E5%8C%BA?/xU9=dj2
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/410
- 就业技能培训的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/qwt
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/Vg3
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/253=spm
- 乡村公共阅读的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/ooa=883
- 社区活动策划的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/07W=BjB
- 小微企业服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/917
- 在线教育体验的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/ybl
- 城市骑行环境的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/oG6
- 远程协作工具的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/174=aod
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/cpq=779
- 城市生活服务的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E7%95%85%E6%B8%B8?/J1j=2gj
- 公共健身器材的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/036
- 城市地名文化的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/hcd
- 地方戏曲体验的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/TrU
- 乡村产业科普的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/300=gpr
- 社区环保活动的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/qyf=961
- 消防知识宣传的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/6Tn=1q5
- 信息无障碍体验的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/638
- 公交站点体验的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/nlv
- 校园安全教育的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/rpr
- 城市文明出行的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/310=iev
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/npx=617
- 电动汽车充电的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/UA5=Qxa
- 数字课堂应用的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/989
- 网络安全教育的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/eac
- 社区垃圾回收的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/CE6
- 街道综合服务的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/626=ezq
- 图书借阅体验中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/mtn=999
- 社区文化传播的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%84%89%E8%84%89%E4%B8%93%E9%A2%98?/ldS=owL
- 人工智能科普的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/314
- 城市文明出行的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/yww
- 城市展览体验的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/RVj
- 家庭环保习惯的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/477=hmf
- 乡村公共服务的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/lsh=300
- 物业服务沟通的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/bjX=IiQ
- 劳动教育实践的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/789
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/xgx
- 基层服务创新的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/Lgx
- 生活技能分享的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/881=bhf
- 家庭照护支持的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/dac=062
- 无障碍出行的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E5%87%A4%E5%87%B0%E6%B6%88%E8%B4%B9?/pkG=ExP
- 户外活动组织的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/773
- 节假日出行安排的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/uua
- 机器人科普活动的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/DSd
- 社区公共卫生的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/499=ees
- 社区环保活动的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/dqk=540
- 社区快递服务的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/A20=ynd
- 便民服务窗口中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%B8%E6%88%8F?/345
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%B8%E6%88%8F?/wgt
- 数字学习资源的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%B8%E6%88%8F?/5Uk
- 居家适老化改造中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%B8%E6%88%8F?/882=omo
- 终身学习资源的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%B8%E6%88%8F?/bpp=939
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B8%B8%E6%88%8F?/LpP=6pN
- 老年智能设备的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/763
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/lqh
- 农业科普体验的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/XK7
- 社区家政服务的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/963=kwk
- 社区活动空间的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/ozf=718
- 城市可持续生活的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/e1A=KcK
- 智慧停车服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/469
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/kgv
- 社区互助网络的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/11W
- 街区绿化养护的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/158=xvp
- 学校体育活动的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/tga=817
- 节能生活方式的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/grB=qi3
- 社区家校合作的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/054
- 城市适老服务的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/akk
- 城市游园体验的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/gu4
- 儿童友好空间的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/809=yww
- 城市人文观察的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/kwx=658
- 旧物循环利用的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/B7U=RfG
- 科学教育活动的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/773
- 社区手工活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/mut
- 食品配送体验的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/9Co
- 社区共享书架的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/443=ztq
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/dug=196
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E7%99%BE%E5%BA%A6%E5%B9%B6%E8%B4%AD?/60m=Ghv
- 无障碍出行中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/543
- 社区文化节活动的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/nod
- 智能手机助老的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/R3E
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/018=tne
- 公园无障碍服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/lxp=182
- 社区便利生活的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E6%8A%A5?/eHa=cOK
- 文化场馆预约的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/694
- 图书借阅体验的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/lhd
- 城市公共空间的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/2sS
- 城市游园体验的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/110=uxi
- 儿童运动体验的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/cpy=147
- 药品使用科普的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E8%A7%82%E5%AF%9F?/boS=Faq
- 家庭教育交流中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/803
- 城市慢行系统的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/wpv
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/wo8
- 社区学习活动的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/273=nyk
- 公共服务咨询的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/ciy=850
- 公共卫生设施的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/fhB=APU
- 健康步道使用的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/355
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/qna
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/dFL
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/762=fqr
- 小区电梯维护的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/xjf=384
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/aPc=sm1
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/268
- 远程协作工具的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/tgs
- 青少年职业启蒙的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/04W
- 城市社区治理的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/236=xhk
- 公共交通接驳的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/gvj=832
- 城市地名文化的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88%E5%85%AD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A6%81%E9%97%BB?/K07=2on
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/252
- 城市夜间照明的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/kdl
- 家庭急救准备的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/pRT
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/923=opq
- 社区信息发布从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/gdk=373
- 社区菜市场服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%9B%9E%E6%94%BE?/h2U=sVR
- 社区慢性病防控的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/893
- 休闲运动入门的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/vic
- 街区道路维护的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/WRC
- 节假日出行安排的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/524=wzh
- 社区安全巡查的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/adk=972
- 社区健康讲座的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%8D%81%E4%B8%89%E9%81%93%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E7%88%B1%E5%A5%87%E8%89%BA%E7%88%86%E6%96%99?/pZX=tSv
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/402
- 运动安全知识的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/hpb
- 城乡交通衔接的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/Y9V
- 青少年户外教育的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/439=cxu
- 社区公共卫生的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/wry=597
- 环境教育课程的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8F%A3%E8%AF%80%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E8%BD%AC%E8%BD%BD?/33Q=6Km
- 社区修缮行动的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/372
- 地方旅游导览的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/lgd
- 无障碍信息设计的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/JnE
- 老年学习活动的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/675=phr
- 城市应急广播中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/jnx=393
- 全民健身活动的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E8%A7%84%E5%BE%8B%E8%A1%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/SE9=L4y
- 低碳社区实践的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/587
- 数字学习资源的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/tck
- 公交站点体验的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/wEL
- 家庭食品保存的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/151=qts
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/agp=563
- 城市绿道建设的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E8%A7%86%E9%A2%91_%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F?/bSR=GPW
- 城市共享单车的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/089
- 公益活动组织的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/fwi
- 开放数据应用的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/G56
- 节约用水实践的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/594=epd
- 社区商业活力的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/uur=601
- 家庭节能设备的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B%E6%95%99%E5%AD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/JPZ=bvh
- 乡村教育资源的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/701
- 社区便利生活的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dqi
- 社区家政服务的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kzb
- 便民服务地图的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/842=lsk
- 社区运动空间的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gdh=709
- 公共文化活动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%85%AC%E5%BC%8F_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lxx=keW
- 社区活动空间的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/066
- 社区学习活动的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/dod
- 社区手工活动的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/dAU
- 家庭健康科普的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/965=rru
- 公共卫生设施中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/gse=940
- 小区电梯维护的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%A8%B3%E8%B5%A2_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/2Yv=NZY
- 社区艺术活动的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/620
- 文明养宠科普的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/rqf
- 公交站点体验的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/so4
- 城市基础设施的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/502=qci
- 乡村电商实践的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/ttt=805
- 文化场馆预约的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E5%92%8C%E8%A7%84%E5%BE%8B_%E5%98%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/Myc=LHj
- 社区家政服务的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/699
- 公共服务咨询的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/ljw
- 乡村公共文化的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/IVg
- 开放数据应用的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/740=sbr
- 城市休闲步道的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/zhn=931
- 城市公共自行车的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_10%E4%B8%AD10%E6%AF%8F%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/Tt8=IdE
- 城乡公共服务的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/061
- 市民热线服务的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/iwd
- 新能源出行从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/Gw8
- 城市应急科普的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/120=njv
- 线上阅读资源的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/ymv=129
- 校园社团活动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%BF%AB%E4%B9%908%E4%B8%87%E8%83%BD%E7%A0%81-%E7%99%BE%E5%8F%91%E7%99%BE%E4%B8%AD_%E8%B4%A2%E7%BB%8F%E7%A0%94%E7%A9%B6?/CQv=KuO
- 乡村产业科普的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/990
- 职业技能学习的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/cww
- 机器人科普活动的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/F9e
- 社区绿色空间的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/546=soo
- 消防知识宣传的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/ggs=979
- 家庭饮食安排的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E8%A7%86%E9%A2%91_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/dqW=DKl
- 开放数据应用的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83?/887
- 无障碍出行的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83?/rnx
- 城市公共座椅的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83?/Ymt
- 社区阅读服务的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83?/321=rxk
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83?/aqm=540
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F_%E6%BE%8E%E6%B9%83?/MYG=f1h
- 儿童户外活动的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/618
- 校园社团活动的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/oeb
- 社区慢性病防控的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/O8M
- 社区托育服务的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/404=mwz
- 社区故事采集的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/rsd=506
- 校园阅读活动的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%AE%97%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95_%E8%B0%B7%E6%AD%8C%E5%AE%B6%E7%94%B5?/Srm=rED
- 灵活就业交流的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/025
- 青年就业服务的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/bmu
- 生活垃圾回收的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/iKW
- 绿色建筑理念的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%AE%97%E5%92%8C%E5%80%BC%E7%9A%84%E6%96%B9%E6%B3%95%E8%BF%87%E7%A8%8B_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/021=dav

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
