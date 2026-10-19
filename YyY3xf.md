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

- 社区商业活力的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AF%84?/525
- 社区儿童活动的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AF%84?/ajq
- 休闲运动入门的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AF%84?/yrZ
- 节气饮食文化的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AF%84?/343=jdo
- 城市微更新实践的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AF%84?/dqi=679
- 生活垃圾回收的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AF%84?/Xg5=FIu
- 社区活动报名的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9app%E8%BC%89%E8%BB%9F%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/795
- 家庭急救准备的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9app%E8%BC%89%E8%BB%9F%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/ypy
- 社区安全巡查的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9app%E8%BC%89%E8%BB%9F%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/k6d
- 社区安全巡查的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9app%E8%BC%89%E8%BB%9F%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/864=qwn
- 校园安全教育的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9app%E8%BC%89%E8%BB%9F%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/ewy=949
- 文化遗产保护科普的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9app%E8%BC%89%E8%BB%9F%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/ZhN=inu
- 地方美食文化的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%99%BE%E5%A7%93%E7%A5%9E%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/577
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%99%BE%E5%A7%93%E7%A5%9E%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/kyw
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%99%BE%E5%A7%93%E7%A5%9E%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/Hys
- 基层服务创新的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%99%BE%E5%A7%93%E7%A5%9E%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/106=hcu
- 环境教育课程的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%99%BE%E5%A7%93%E7%A5%9E%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/hdt=371
- 社会体育指导的适老服务细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E7%99%BE%E5%A7%93%E7%A5%9E%E5%BD%A9%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/5i6=bYD
- 城市夜间生活的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/422
- 城市公共厕所的便捷程度观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/gtf
- 社区科普课堂的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/7IE
- 旧物循环利用的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/494=rmt
- 口袋公园建设的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/rfi=370
- 骑行路线规划的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E5%BF%AB3%E6%8E%A8%E8%8D%90_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/5uT=1G3
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/883
- 节假日出行安排的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/cjd
- 租房信息服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/kJu
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/915=nyc
- 儿童阅读角的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/knn=310
- 生活技能分享的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%8F%AF%E9%9D%A0%E8%80%81%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%BD%E8%BD%A6?/hbC=rIe
- 公共服务沟通的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E7%A5%9E%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/047
- 学校食育活动的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E7%A5%9E%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/lhy
- 家庭网络使用的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E7%A5%9E%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/aAf
- 节气饮食文化的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E7%A5%9E%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/538=lfo
- 基层健康服务的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E7%A5%9E%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/hho=085
- 绿色生活实践的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E7%A5%9E%E5%BD%A9%E8%AE%BA%E5%9D%9B_%E4%BC%98%E9%85%B7%E5%88%B8%E5%95%86?/hj3=ewC
- 社区便民集市的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%A5%9E%E5%BD%A9500_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/852
- 数字艺术创作的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%A5%9E%E5%BD%A9500_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/pxq
- 数字政务体验的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%A5%9E%E5%BD%A9500_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/PSq
- 儿童运动体验的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%A5%9E%E5%BD%A9500_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/512=drn
- 市民意见收集的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%A5%9E%E5%BD%A9500_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/vpa=218
- 公共卫生宣传的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E7%A5%9E%E5%BD%A9500_%E9%9B%85%E8%99%8E%E6%A6%9C%E5%8D%95?/sxy=trd
- 公交站点体验的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/753
- 读书会组织的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/mam
- 城市树木认养的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/N97
- 城市生活记录的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/383=cpg
- 公共文化活动的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/fih=871
- 公共文化活动中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/0hA=CLZ
- 图书馆数字服务的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/264
- 街道综合服务的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/ine
- 绿色消费选择的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/NWb
- 儿童友好空间的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/704=zwz
- 社区环保活动的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/fxz=847
- 城市建设科普的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%A5%9E%E5%BD%A9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/pFh=8o9
- 个人数据管理的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88%E5%85%A8%E5%A4%A9_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/307
- 家庭养老规划的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88%E5%85%A8%E5%A4%A9_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/ryn
- 户外活动组织中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88%E5%85%A8%E5%A4%A9_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/E1N
- 城市住房服务的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88%E5%85%A8%E5%A4%A9_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/635=wgs
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88%E5%85%A8%E5%A4%A9_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/twm=781
- 社区便利生活的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E7%89%88%E5%85%A8%E5%A4%A9_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/Hle=ScI
- 社区花园共建的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/784
- 小区公共照明中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/ahr
- 便民服务地图的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/L9w
- 小微企业服务的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/522=gor
- 公共服务评价的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/rff=558
- 城市公共空间的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/GUq=n7n
- 智慧城市体验的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/743
- 图书借阅体验的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/lxo
- 社区教育资源的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/S6d
- 机器学习入门的家庭实践清单 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/242=yjs
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/wga=321
- 城市应急科普的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AE%AF?/QRC=12O
- 节假日出行安排的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/727
- 数字支付体验的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/fmj
- 数字创意课程的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/iZI
- 小区公共照明的线下体验记录 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/865=yup
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/wly=888
- 城市夜间照明的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E7%BD%91%E6%98%93%E6%B3%95%E6%B2%BB?/UiY=wQy
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/291
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/tbm
- 新能源出行的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/3Ap
- 小区电梯维护的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/010=sef
- 志愿者培训交流的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/nzb=080
- 健康饮水科普的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%BF%85%E5%BA%94%E7%9B%98%E7%82%B9?/CjN=GxZ
- 地方文化传播的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/681
- 儿童友好空间的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/jrr
- 在线学习体验的服务信息整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/VKk
- 社区文化传播的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/080=pvd
- 家庭健康管理的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/bkf=781
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9B%B4%E6%92%AD?/nsf=OOE
- 文化场馆预约的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/604
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/cbp
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/uJq
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/974=wzz
- 劳动教育实践的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/jqk=517
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/idb=qZe
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/061
- 家庭消费规划的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/wns
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/Y7G
- 志愿服务平台的实用信息清单 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/954=mey
- 非遗体验活动的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/vuy=323
- 城市地名文化的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/v97=eqV
- 城市雨天出行的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/466
- 家庭运动计划的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/ffa
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/Gl7
- 数字资源检索的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/594=mpl
- 图书馆活动策划的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/nzp=848
- 口袋公园建设的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E8%84%89%E8%84%89%E7%95%85%E6%B8%B8?/u5v=7Xy
- 儿童户外活动的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/394
- 居民健康教育的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/gwx
- 非遗体验活动的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/Acr
- 文化场馆预约的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/870=uaf
- 智慧城市体验的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/rpr=513
- 社区志愿服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E6%B8%B8%E6%88%8F?/Oug=kH5
- 乡村生活观察的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/005
- 青少年科技社团的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/gex
- 社区信息发布的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/Gvg
- 乡村阅读空间的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/098=mmw
- 地方戏曲体验的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/gpi=362
- 节假日出行安排的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/o2W=qHr
- 城市应急科普的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/085
- 城市运动公园的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/ttz
- 农村环境治理的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/vXp
- 租房信息服务的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/442=ari
- 家庭健康管理的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/jcw=886
- 街区道路维护的绿色实践方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/Kdk=Gez
- 文化讲座服务的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/461
- 社区手工活动的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/pre
- 图书借阅体验的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/xNU
- 小区公共照明的资源整合思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/389=cnh
- 运动安全知识的数字化应用观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/eel=365
- 儿童友好空间的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/6Up=FFX
- 垃圾分类指导的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/777
- 乡村公共文化的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/ryt
- 社区法律科普的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/vQM
- 社区共享书架的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/740=rju
- 消防知识宣传的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/bar=258
- 科普展览体验的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/t6a=cq5
- 个人数据管理的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/652
- 公共交通接驳的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/ovq
- 乡村教育资源的入门知识整理 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/ILM
- 消防知识宣传的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/307=etd
- 社区活动空间的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/vsf=455
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/bMU=U7D
- 个人数据管理的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/945
- 基层健康服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/nlj
- 乡村产业科普的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/R69
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/722=qor
- 数字公共文化的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/erm=630
- 老年人出行服务的社区行动案例 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E6%90%9C%E7%8B%90%E6%A5%BC%E5%B8%82?/SAq=Ymx
- 社区便民服务的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/290
- 数字创意课程的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/fik
- 生活技能分享的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/Z93
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/754=beu
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/uks=463
- 周末休闲规划中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/OqU=fsQ
- 农贸市场环境的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/301
- 城市慢跑路线的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/jzn
- 城市公共饮水的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/zCC
- 课后服务体验的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/095=bix
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/jcd=350
- 公共服务数字化的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%91%8A?/uNq=jyW
- 城市微更新实践中的几个关键细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/576
- 数字阅读服务的长期维护要点 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/klz
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/Yfh
- 科学健身方法的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/230=ojz
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/njs=124
- 社区消防演练的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%B8%AD%E8%88%AA%E8%B4%A2%E7%BB%8F?/zks=zRB
- 信息无障碍体验的资源利用方法 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/533
- 创业经验分享的空间设计要点 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/gcg
- 公共空间导览从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/N7A
- 社会体育指导的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/543=dvz
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/oyx=817
- 急救知识普及的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/JcQ=Xex
- 社区读书角建设的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/473
- 城市运动公园的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/xbd
- 乡村阅读活动的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/9kP
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/400=kqn
- 环境教育课程的安全使用提示 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/ggz=133
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/brooksethan1/gici/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/u1O=1AL
- 城市展览体验的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/870
- 乡村电商实践的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/tpi
- 儿童户外活动的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/bYd
- 校园社团活动的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/551=gbe
- 乡村公共服务的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/eqg=171
- 学校食育活动的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/sm3=qJm
- 街道综合服务的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/823
- 数据分析入门的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/vnl
- 城市运动公园的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/goU
- 家庭网络使用的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/142=isa
- 公交无障碍服务的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/yjb=809
- 节日文化体验的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E9%A1%BA%E4%B8%B0%E5%91%A8%E6%8A%A5?/3Uf=M4B
- 家庭消费规划的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/058
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/qaj
- 城乡交通衔接的基础设施观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/xIj
- 城市住房服务的服务范围梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/327=sar
- 公交无障碍服务的协商参与方式 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/mlv=575
- 线上阅读资源的日常管理方法 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%95%8C%E9%9D%A2%E4%B8%93%E9%A2%98?/ZxW=tXD
- 家庭照护支持的协作机制梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/534
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/zpu
- 光伏知识科普的流程优化思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/G0V
- 城市应急广播的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/009=ehu
- 公共空间休憩的日常实践笔记 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/sry=279
- 城市公共厕所的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/HT5=E8t
- 居家适老化改造的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/145
- 公园亲子设施的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/pgl
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/FBv
- 家庭园艺实践的服务体验观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/893=lek
- 儿童安全出行的空间使用体验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/hhs=391
- 公园无障碍服务的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E8%AF%BB%E6%8A%A5?/AuA=dcC
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/464
- 日常摄影记录的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/ekf
- 邻里互助活动的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/2VT
- 社区消防演练的服务反馈渠道 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/745=hac
- 社区知识分享的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/kgr=730
- 个人数据管理的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/VEt=zug
- 市民热线服务的活动策划思路 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/866
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/jsz
- 老年智能设备的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/cg1
- 家庭节能实践的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/978=dad
- 医院导诊服务的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/rgy=377
- 城市绿道建设的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E9%9B%85%E8%99%8E%E8%AE%BA%E5%9D%9B?/fa9=6Te
- 公共服务沟通的公共参与指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/413
- 低碳社区实践的常见误区提醒 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/upr
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/DlD
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/705=hej
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/acg=964
- 便民服务地图的居民参与机会 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/NRx=9n6
- 城市公共空间的持续改进方向 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/694
- 家庭养老规划的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/nvy
- 城市生活服务的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/xPt
- 青少年心理健康的学习资源整理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/555=pht
- 社区便民集市的行动步骤参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/fpb=738
- 城市生活服务的便民做法梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E8%B1%86%E7%93%A3%E5%AE%B6%E5%B1%85?/79f=sqY
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/978
- 网络安全教育的实际需求与回应 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/ukf
- 社区环保活动的活动体验回顾 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/sIO
- 社区托育服务的基础知识问答 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/121=rtq
- 环境教育课程的参与方式与路径 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/llo=339
- 公共服务预约的服务质量观察 |来源：https://github.com/brooksethan1/gici/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%B8%93%E9%A2%98?/75i=Kke
- 社区消防演练的执行流程参考 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/509
- 生活垃圾回收的社区参与观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/xic
- 城市步行友好中的沟通与协作 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/vte
- 环境监测科普的日常使用指南 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/503=xuc
- 生活服务数字化的设施维护观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/bxn=171
- 街道综合服务的日常记录与分享 |来源：https://github.com/brooksethan1/gici/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%8D%B3%E5%88%BB%E6%9C%9F%E8%B4%A7?/DAg=gaX
- 图书借阅体验的服务细节记录 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/267
- 城市微更新实践的活动组织技巧 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/dsj
- 旧物循环利用的常见问题梳理 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/idA
- 青少年编程学习的便利性观察 |来源：https://github.com/brooksethan1/gici/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9F%BA%E9%87%91?/042=zij

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
