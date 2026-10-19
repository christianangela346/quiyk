# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 家庭运动计划的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BD%91%E5%9D%80-%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/woz=554
- 便民服务地图的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E7%BD%91%E5%9D%80-%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/aTK=fYq
- 社区协商议事的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90?/999
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90?/isx
- 街区小店体验的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90?/9n2
- 无障碍信息设计的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90?/746=ypc
- 老年友好服务的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90?/iob=568
- 城市夜间照明的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%93%E5%AE%B6%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90?/y17=Hdu
- 全民健身活动的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/036
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/dmh
- 全民健身活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/LJZ
- 社区信息发布的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/376=tqz
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/nxm=569
- 社区阅读服务的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/lbZ=eHj
- 乡村生态观察中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/356
- 校园社团活动的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/pcx
- 生成式工具使用的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/GSJ
- 在线学习体验的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/212=zxt
- 节能生活方式的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/oma=321
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F-%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/S3x=xyi
- 传统节日科普的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/075
- 城市便民驿站的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/sdy
- 校园安全教育的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/BYC
- 老年智能设备中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/624=eqj
- 文化讲座服务的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/teq=626
- 节约用水实践的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E5%A4%A7%E7%BE%A4-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/O9X=KGY
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/106
- 社区菜市场服务的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/ovt
- 家庭理财科普的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/W8z
- 数字资源检索的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/743=xsl
- 本地历史资料的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/ahh=414
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/UsT=WWW
- 城市空气科普的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B-%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/904
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B-%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/hvq
- 社区安全巡查的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B-%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/ZgA
- 公共设施使用的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B-%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/706=ylm
- 社区文化节活动的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B-%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/woa=482
- 电动汽车充电的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%A7%84%E5%BE%8B-%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/S2z=Cra
- 社区绿色空间的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E8%AE%B2%E5%9D%9B?/691
- 线上办事服务的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E8%AE%B2%E5%9D%9B?/jnd
- 亲子科普活动的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E8%AE%B2%E5%9D%9B?/Pdi
- 街道综合服务的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E8%AE%B2%E5%9D%9B?/167=ufx
- 校园社团活动的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E8%AE%B2%E5%9D%9B?/hcw=875
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7-36%E6%B0%AA%E8%AE%B2%E5%9D%9B?/KBt=HSy
- 儿童阅读角的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95-%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/150
- 青少年科普实践的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95-%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/ddk
- 家庭环保行动的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95-%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/DFC
- 健康饮食教育的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95-%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/450=egl
- 城市应急广播的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95-%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/yak=546
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86pk10%E7%BB%9D%E5%AF%86%E7%8E%A9%E6%B3%95-%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/vPw=ZY1
- 家庭急救准备的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95-%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/890
- 城市公共座椅的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95-%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/sit
- 急救知识普及的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95-%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/KVe
- 家庭节能实践的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95-%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/858=spb
- 城市慢行系统的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95-%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/opv=162
- 绿色生活实践的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E4%B9%B0%E6%B3%95-%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/PDk=gfR
- 食品配送体验中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/499
- 智能手机助老的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/ecp
- 开放数据应用的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/9aA
- 数字创作工具的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/742=xwj
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/mve=848
- 城市骑行环境的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E4%B9%B0-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/2B5=ziC
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/169
- 城市公共空间的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/upi
- 老年友好服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/P5u
- 公共空间安全的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/810=qxn
- 社区停车服务的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/zrm=472
- 绿色建筑理念的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86pk10%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95-%E5%87%A4%E5%87%B0%E5%88%9B%E6%8A%95?/g5D=Aqf
- 城市社区治理的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/822
- 乡村生活观察的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/ebv
- 智慧城市体验的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/1pn
- 在线学习体验的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/258=wjy
- 公共空间安全的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/rue=488
- 远程协作工具的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92-%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/Rum=8pj
- 社区手工活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A-%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/307
- 公共设施维护的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A-%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/ftt
- 本地历史资料的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A-%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/3jS
- 劳动教育实践的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A-%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/180=xkb
- 城市慢跑路线的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A-%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/bmu=414
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%B5%A2%E5%BE%97%E5%A4%9A-%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/8z8=mHa
- 家庭收纳实践的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD-360%E7%A7%81%E5%8B%9F?/391
- 小区公共照明的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD-360%E7%A7%81%E5%8B%9F?/svt
- 城乡公共服务的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD-360%E7%A7%81%E5%8B%9F?/Qwe
- 家庭节能实践的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD-360%E7%A7%81%E5%8B%9F?/279=ewp
- 社区信息发布的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD-360%E7%A7%81%E5%8B%9F?/zxj=960
- 读书会组织的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86pk107%E6%9C%9F%E5%BF%85%E4%B8%AD-360%E7%A7%81%E5%8B%9F?/JfS=Zjq
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/662
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/ozs
- 生活垃圾减量的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/xHO
- 老年友好服务的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/782=obf
- 社区设施共享的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/kry=698
- 公园休闲体验的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_pk10%E6%80%8E%E6%A0%B7%E6%9D%80%E5%86%A0%E5%86%9B%E5%8F%B7-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/9uV=pP0
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/989
- 读书会组织的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/niq
- 健康饮水科普的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/NLs
- 全民健身活动的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/102=gae
- 文明养宠科普的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/nix=177
- 社区故事采集的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95-%E7%9F%A5%E4%B9%8E%E6%95%B0%E8%AF%BB?/qvE=MO4
- 生活垃圾减量的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/870
- 老年智能设备的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/ncb
- 社区托育服务的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/JXd
- 公益活动组织的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/338=kpk
- 邻里互助活动的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/qij=886
- 数字生活课堂的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E4%B8%80%E5%88%86-%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/Vih=0k3
- 公共服务咨询的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/007
- 乡村电商实践的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/adg
- 社区家校合作的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/rfd
- 社区便民集市的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/598=wkz
- 图书借阅体验的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/pmd=536
- 周末休闲规划的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91pk10%E7%BD%91%E5%9D%80-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/HZd=jIP
- 社区便利生活的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/220
- 城市骑行环境的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/mtb
- 物业服务沟通的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/SOQ
- 乡村公共文化的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/985=fus
- 社区活动空间的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/fli=710
- 邻里共享空间的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91pk10%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85-%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/UzZ=KfN
- 老年数字阅读的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88-%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/970
- 绿色校园实践的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88-%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/wdx
- 消防知识宣传的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88-%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/MJo
- 社区活动策划的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88-%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/446=zwv
- 城市雨天出行的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88-%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/cwm=411
- 家庭运动计划的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88-%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/8Ki=8Ah
- 开放式学习空间的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/629
- 城市公共饮水的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/bsx
- 骑行路线规划的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/rYF
- 科学教育活动的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/046=lsn
- 社区科普课堂的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/ryt=916
- 社区交通安全的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%89%8D%E8%83%BD%E8%B5%A2-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BF%A1%E8%AE%BF?/nPd=JD2
- 社区家政服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/921
- 城市公共空间的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/fff
- 基层医疗预约的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/JyF
- 学校体育活动的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/442=pvz
- 全民健身活动的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/wrc=422
- 科学观察活动的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86pk10%E9%AB%98%E6%89%8B%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/jOQ=2JT
- 基层医疗预约的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/190
- 市民热线服务的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/kfd
- 城市地名文化的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/7ZT
- 生成式工具使用的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/643=efy
- 城市慢行系统的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/djj=193
- 社区便民服务的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E5%88%86%E5%88%86pk%E6%8B%BE%E8%AE%A1%E5%88%92%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92-%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/r44=G8c
- 数字资源检索中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/844
- 社区信息发布的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/qgp
- 城市公共厕所的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/hOk
- 城市步行友好中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/434=mof
- 无障碍信息设计的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/kbh=976
- 亲子科普活动的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81-%E7%A7%98%E9%B2%81%E8%B4%A2%E7%BB%8F?/xOR=Gyx
- 光伏知识科普的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86PK%E6%8B%BE-36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/888
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86PK%E6%8B%BE-36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/fsf
- 社区设施共享的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86PK%E6%8B%BE-36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/ftu
- 科学健身方法的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86PK%E6%8B%BE-36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/380=esg
- 家庭养老规划的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86PK%E6%8B%BE-36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/rgj=252
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86PK%E6%8B%BE-36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/sEL=Yob
- 光伏知识科普的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91-%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/131
- 公共服务指南的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91-%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/dvb
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91-%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/6kc
- 农产品品牌传播的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91-%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/004=jsn
- 食品安全科普的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91-%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/dmv=628
- 家庭运动计划的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E7%BD%91-%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/8O8=urR
- 小区停车协商的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/265
- 日常摄影记录的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/zid
- 社区应急准备的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/1Ln
- 城市基础设施的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/281=sth
- 社区设施共享的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/evq=141
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89-%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/V9i=tws
- 社区文化传播的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/497
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/zun
- 城市可持续生活的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/Dgf
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/712=lqz
- 户外活动组织的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/rha=094
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86PK%E6%8B%BE%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95-%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/Wxm=QB9
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/077
- 老年人出行服务的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/dnr
- 数字档案服务的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/b4F
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/305=irm
- 科学信息获取的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/cpq=749
- 急救知识普及的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86PK%E5%8D%81%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E4%BA%BA%E5%B7%A5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E7%9F%A5%E4%B9%8E%E6%B0%91%E7%94%9F?/8AD=XJb
- 电子商务服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A-%E7%99%BE%E5%BA%A6%E6%96%87%E6%91%98?/298
- 社区防暑服务的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A-%E7%99%BE%E5%BA%A6%E6%96%87%E6%91%98?/rdt
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A-%E7%99%BE%E5%BA%A6%E6%96%87%E6%91%98?/05f
- 环境教育课程的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A-%E7%99%BE%E5%BA%A6%E6%96%87%E6%91%98?/450=krc
- 地方文化传播的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A-%E7%99%BE%E5%BA%A6%E6%96%87%E6%91%98?/zqp=638
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E6%80%8E%E4%B9%88%E7%8E%A9%E8%83%BD%E8%B5%9A-%E7%99%BE%E5%BA%A6%E6%96%87%E6%91%98?/BvB=Qvt
- 社区快递服务的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/673
- 社区家政服务的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/rrg
- 街区绿化养护的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/KOs
- 青年志愿活动的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/542=fbv
- 公共服务数字化中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/kjc=858
- 乡村文化空间的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%95%E4%B8%83%E7%A0%81%E6%80%8E%E4%B9%88%E7%8E%A9-%E5%BF%AB%E6%89%8B%E5%AE%9E%E5%BD%95?/JUv=8vN
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E9%A2%84%E6%B5%8B-360%E8%B4%A2%E6%8A%A5?/638
- 智能家居应用的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E9%A2%84%E6%B5%8B-360%E8%B4%A2%E6%8A%A5?/bgm
- 城市噪声观察的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E9%A2%84%E6%B5%8B-360%E8%B4%A2%E6%8A%A5?/HIL
- 学校食育活动的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E9%A2%84%E6%B5%8B-360%E8%B4%A2%E6%8A%A5?/626=men
- 乡村文化活动的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E9%A2%84%E6%B5%8B-360%E8%B4%A2%E6%8A%A5?/soc=320
- 社区活动报名的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%88%86%E5%88%86pk10%E9%A2%84%E6%B5%8B-360%E8%B4%A2%E6%8A%A5?/ewB=Niq
- 儿童友好街区的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%958%E7%A0%81-%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/993
- 健康信息获取的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%958%E7%A0%81-%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/upb
- 线上办事服务的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%958%E7%A0%81-%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/vfB
- 数字生活课堂的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%958%E7%A0%81-%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/675=xld
- 小区停车协商的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%958%E7%A0%81-%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/aue=825
- 健康饮水科普的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10%E7%A8%B3%E8%B5%9A%E6%96%B9%E6%B3%958%E7%A0%81-%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/83J=i7Q
- 公共卫生宣传的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86pk10%E9%AA%97%E5%B1%80-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/257
- 街区道路维护中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86pk10%E9%AA%97%E5%B1%80-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/lwz
- 城市基础设施的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86pk10%E9%AA%97%E5%B1%80-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/E9U
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86pk10%E9%AA%97%E5%B1%80-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/070=mte
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86pk10%E9%AA%97%E5%B1%80-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/gfd=528
- 消防知识宣传的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86pk10%E9%AA%97%E5%B1%80-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F?/9ZH=PVq
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app-%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/094
- 乡村公共阅读的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app-%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/jgk
- 数字档案服务的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app-%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/ZKW
- 街区绿化养护中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app-%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/722=jcl
- 家庭节能设备的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app-%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/zbq=287
- 物业服务沟通的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pk10app-%E5%BE%97%E7%89%A9%E5%9B%BD%E9%99%85?/Ufo=vXu
- 社区活动空间的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84-%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/687
- 青少年户外教育中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84-%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/yaq
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84-%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/Gvj
- 社区共享书架的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84-%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/098=oim
- 邻里互助活动的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84-%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/tjd=130
- 绿色校园实践的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84-%E4%BC%98%E9%85%B7%E8%A7%82%E5%AF%9F?/k3H=bVd
- 农村环境治理的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/959
- 社区互助网络的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/azr
- 地方美食文化的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/i19
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/710=oir
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/ata=047
- 节假日出行安排的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10%E6%98%AF%E4%BB%80%E4%B9%88-%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/a7S=RvC
- 社区读书角建设的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86pk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/139
- 城市应急广播的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86pk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/lgi
- 基层健康服务的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86pk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/vIu
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86pk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/093=hrb
- 个人数据管理的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86pk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/lcj=465
- 街区小店体验的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%88%86%E5%88%86pk10%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E8%B4%A2%E7%BB%8F%E7%9B%B4%E6%92%AD?/563=BnN
- 环境监测科普的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10-%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/294
- 社区健康讲座的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10-%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/bqv
- 儿童运动体验的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10-%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/TTX
- 户外活动组织的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10-%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/633=zrw
- 小区停车协商的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10-%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/alc=054
- 社区防暑服务的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pk10-%E8%B1%86%E7%93%A3%E7%BE%8E%E8%82%A1?/VcD=hMz
- 亲子科普活动中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A610%E5%8F%B7%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C-%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/961
- 城市绿道建设的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A610%E5%8F%B7%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C-%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/agf
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A610%E5%8F%B7%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C-%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/l7h
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A610%E5%8F%B7%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C-%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/812=dyb
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A610%E5%8F%B7%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C-%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/xui=201
- 校园安全教育的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A610%E5%8F%B7%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E7%BB%8F%E9%AA%8C-%E5%BE%97%E7%89%A9%E4%B8%93%E9%A2%98?/ce8=cAv
- 城市博物馆活动的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86pk10%E8%B7%A8%E5%BA%A6-%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/880
- 乡村公共服务中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86pk10%E8%B7%A8%E5%BA%A6-%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/igz
- 社区活动报名的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86pk10%E8%B7%A8%E5%BA%A6-%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/QoG
- 城市水环境观察的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86pk10%E8%B7%A8%E5%BA%A6-%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/348=tkf
- 终身学习资源的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86pk10%E8%B7%A8%E5%BA%A6-%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/zgu=940
- 城乡交流活动的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86pk10%E8%B7%A8%E5%BA%A6-%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/hGU=O91
- 公园无障碍服务的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86pk%E6%8B%BE%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92-%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/540
- 职业技能学习的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86pk%E6%8B%BE%E5%85%A8%E5%A4%A9%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92-%E6%96%B0%E6%B5%AA%E6%97%B6%E6%8A%A5?/rxq

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
