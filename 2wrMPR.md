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

- 社区体育组织的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/427
- 医院导诊服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/bjh
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/h9w
- 新能源知识普及的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/295=jjm
- 口袋公园建设的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/ewh=939
- 校园安全教育的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4_%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/FbJ=Qe6
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/019
- 学校食育活动的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/zgp
- 家庭园艺实践的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/buf
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/164=hsc
- 地方戏曲体验的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/mzi=955
- 社区协商议事的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%9124%E5%B0%8F%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E4%B8%93%E6%A0%8F?/usx=eVo
- 城乡公共服务的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%BE%A4%E6%9C%80%E5%8E%89%E5%AE%B3_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/407
- 健康步道使用的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%BE%A4%E6%9C%80%E5%8E%89%E5%AE%B3_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/gte
- 电子商务服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%BE%A4%E6%9C%80%E5%8E%89%E5%AE%B3_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/Uo1
- 公园休闲体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%BE%A4%E6%9C%80%E5%8E%89%E5%AE%B3_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/798=bgo
- 绿色校园实践的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%BE%A4%E6%9C%80%E5%8E%89%E5%AE%B3_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/uqv=563
- 社区环保活动的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%BE%A4%E6%9C%80%E5%8E%89%E5%AE%B3_%E9%A1%BA%E4%B8%B0%E5%88%9B%E6%8A%95?/MVn=WZ4
- 在线学习体验的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/349
- 开放式学习空间的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/xfj
- 社区法律科普的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/Hi9
- 社区读书角建设的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/384=stt
- 社区文化传播的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/tto=796
- 基层服务创新的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%8A%95%E7%A8%BF?/Kkk=3AX
- 社区环保活动的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/489
- 社区养老服务的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/yfv
- 城市空气科普的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/za2
- 乡村生活观察的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/010=fvg
- 社区艺术活动的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/ody=706
- 数字便民地图的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%B5%9A%E9%92%B1_%E5%A4%AE%E8%A7%86%E6%88%B7%E5%A4%96?/JVw=FAe
- 社区老年食堂的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/220
- 绿色出行服务的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/gao
- 社区花园共建的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/Tve
- 社区设施共享的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/592=jjj
- 科学观察活动的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/hnr=029
- 街区更新实践的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%A7%93%E8%B4%A2%E7%BB%8F?/0IL=Ede
- 社区环保活动的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/187
- 城市地名文化的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/dxm
- 街区小店体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/Jn3
- 家庭运动计划的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/201=jyo
- 老年人日常照护的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/gjp=092
- 城市农夫市集的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/SjG=q20
- 智慧城市体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E8%B7%9F%E5%A4%B410%E6%9C%9F_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/608
- 社区活动策划的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E8%B7%9F%E5%A4%B410%E6%9C%9F_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/ken
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E8%B7%9F%E5%A4%B410%E6%9C%9F_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/9Xk
- 街区小店体验的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E8%B7%9F%E5%A4%B410%E6%9C%9F_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/704=qnr
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E8%B7%9F%E5%A4%B410%E6%9C%9F_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/tmj=834
- 个人时间管理的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E8%AE%A1%E5%88%92%E8%B7%9F%E5%A4%B410%E6%9C%9F_%E7%BD%91%E6%98%93%E8%88%86%E6%83%85?/GUC=Inn
- 社区邻里服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B7%9F%E5%8F%8D%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/785
- 家庭照护支持的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B7%9F%E5%8F%8D%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/rdv
- 家庭用电安全的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B7%9F%E5%8F%8D%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/EaC
- 科学运动指导的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B7%9F%E5%8F%8D%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/206=jot
- 数字便民地图的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B7%9F%E5%8F%8D%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/erj=889
- 环境教育课程的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B7%9F%E5%8F%8D%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/vQl=6UM
- 绿色消费选择的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/290
- 便民服务地图的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/pvw
- 传统节日科普的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/7C6
- 城市步行友好的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/256=opo
- 家庭防灾准备的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/mdc=629
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/MqZ=KRH
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/605
- 生成式工具使用的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/art
- 社区活动策划的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/oZb
- 城市休闲步道的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/261=flh
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/epp=310
- 儿童安全出行的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/HQV=3c7
- 社区邻里服务的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E6%9C%AF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/513
- 青年就业服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E6%9C%AF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/gtz
- 城市绿色交通的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E6%9C%AF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/NDH
- 城市应急科普的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E6%9C%AF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/088=dbc
- 青少年编程学习的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E6%9C%AF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/xjt=680
- 社区停车服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E6%9C%AF%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E6%B1%87%E5%B8%82?/2Ko=mL7
- 城市骑行环境的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/940
- 小微企业服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/deo
- 儿童安全出行的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/pn5
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/916=zfi
- 城市微更新实践的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/zss=435
- 青少年科普实践中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/WX4=XKD
- 智能手机助老的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%80%8D%E6%8A%95%E6%9C%89%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/970
- 绿色出行服务的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%80%8D%E6%8A%95%E6%9C%89%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/arv
- 社区快递服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%80%8D%E6%8A%95%E6%9C%89%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/cYe
- 社区协商议事的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%80%8D%E6%8A%95%E6%9C%89%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/430=rpq
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%80%8D%E6%8A%95%E6%9C%89%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/dqx=159
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%80%8D%E6%8A%95%E6%9C%89%E5%87%A0%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/gLm=kIj
- 城市噪声观察的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99%E6%9C%89%E7%94%A8%E5%90%97_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/207
- 公益活动组织的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99%E6%9C%89%E7%94%A8%E5%90%97_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/fzg
- 城市便民驿站的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99%E6%9C%89%E7%94%A8%E5%90%97_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/6R8
- 老年友好服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99%E6%9C%89%E7%94%A8%E5%90%97_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/833=rrb
- 农产品品牌传播的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99%E6%9C%89%E7%94%A8%E5%90%97_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/zhu=091
- 读书会组织的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99%E6%9C%89%E7%94%A8%E5%90%97_%E9%9F%A9%E5%9B%BD%E8%B4%A2%E7%BB%8F?/uFe=WdJ
- 乡村公共服务的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/345
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/gwn
- 节约用水实践的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/lDO
- 校园节能行动从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/998=qyf
- 城市骑行环境的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/bau=769
- 创业经验分享的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/b0k=1qp
- 青少年户外教育中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/753
- 社区休闲设施的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/jev
- 家庭安全提示的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/6HS
- 健康饮食教育的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/305=lro
- 社区故事采集的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/kxb=748
- 低碳社区实践的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E6%B3%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/n0C=wiP
- 家庭收纳实践的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7360_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/384
- 数字支付体验中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7360_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/rug
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7360_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/grk
- 家庭饮食安排的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7360_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/975=yak
- 城市文明出行的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7360_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/tob=676
- 数字艺术创作的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7360_%E7%9F%A5%E4%B9%8E%E5%88%8A%E7%99%BB?/1aA=xlZ
- 社区体育组织的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E7%8E%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/949
- 口袋公园建设的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E7%8E%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/jtv
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E7%8E%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/s81
- 图书馆数字服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E7%8E%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/353=snd
- 社区故事采集的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E7%8E%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/xeo=599
- 基层健康服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E7%8E%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/oEo=ijB
- 城市适老服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%80%8D%E6%8A%95%E5%93%A5%E6%9C%80%E6%96%B0%E6%99%92%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/745
- 环境教育课程的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%80%8D%E6%8A%95%E5%93%A5%E6%9C%80%E6%96%B0%E6%99%92%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/xej
- 城市休闲步道的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%80%8D%E6%8A%95%E5%93%A5%E6%9C%80%E6%96%B0%E6%99%92%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/kBG
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%80%8D%E6%8A%95%E5%93%A5%E6%9C%80%E6%96%B0%E6%99%92%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/894=rug
- 绿色出行服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%80%8D%E6%8A%95%E5%93%A5%E6%9C%80%E6%96%B0%E6%99%92%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/zwf=974
- 数字支付体验的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%80%8D%E6%8A%95%E5%93%A5%E6%9C%80%E6%96%B0%E6%99%92%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/X3C=MAl
- 人工智能科普的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/961
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/aey
- 绿色快递包装的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/IF6
- 社区手工活动的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/140=its
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/dxw=013
- 公园休闲体验的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%80%8D%E6%8A%95_%E7%99%BE%E5%BA%A6%E5%AE%A0%E7%89%A9?/l4b=FEb
- 社区艺术活动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/336
- 邻里共享空间的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/yta
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/HMg
- 社区休闲设施的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/230=ddx
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/ngz=437
- 科学教育活动的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/G4P=lNV
- 生活垃圾减量的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_1234%E5%80%8D%E6%8A%95%E6%9C%80%E8%81%AA%E6%98%8E%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/001
- 智能家居应用的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_1234%E5%80%8D%E6%8A%95%E6%9C%80%E8%81%AA%E6%98%8E%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/cdi
- 公共卫生设施的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_1234%E5%80%8D%E6%8A%95%E6%9C%80%E8%81%AA%E6%98%8E%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/FmU
- 地方美食文化的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_1234%E5%80%8D%E6%8A%95%E6%9C%80%E8%81%AA%E6%98%8E%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/376=bte
- 骑行路线规划的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_1234%E5%80%8D%E6%8A%95%E6%9C%80%E8%81%AA%E6%98%8E%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/srn=976
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_1234%E5%80%8D%E6%8A%95%E6%9C%80%E8%81%AA%E6%98%8E%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/xTr=4X6
- 老年运动活动的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/391
- 公共交通信息服务的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/kut
- 小区电梯维护的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/iIE
- 城市水环境观察的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/725=yem
- 城市社区治理的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/jxa=312
- 数字档案服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E8%AF%A6%E7%BB%86%E8%AE%B2%E8%A7%A3_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/EK1=kv7
- 劳动教育实践的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/266
- 城市展览体验的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/cnc
- 乡村生活观察中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/0nJ
- 周末休闲规划的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/510=nkw
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/qlk=246
- 家庭运动计划的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%8410%E6%9C%9F%E5%80%8D%E6%8A%95_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/Uc6=4gw
- 社区教育资源的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%AF%94%E5%80%8D%E6%8A%95%E6%9B%B4%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/639
- 社区绿色空间的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%AF%94%E5%80%8D%E6%8A%95%E6%9B%B4%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/pkh
- 社区交通安全的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%AF%94%E5%80%8D%E6%8A%95%E6%9B%B4%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/M0m
- 社区志愿服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%AF%94%E5%80%8D%E6%8A%95%E6%9B%B4%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/597=daz
- 城市人文观察的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%AF%94%E5%80%8D%E6%8A%95%E6%9B%B4%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/jfd=180
- 青年就业服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E6%AF%94%E5%80%8D%E6%8A%95%E6%9B%B4%E5%A5%BD%E7%9A%84%E6%96%B9%E6%B3%95_%E7%BD%91%E6%98%93%E6%98%9F%E5%BA%A7?/r1y=woE
- 城市文明实践的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%8A%8A%E5%80%8D%E6%8A%95%E5%8F%8D%E8%BF%87%E6%9D%A5%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/924
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%8A%8A%E5%80%8D%E6%8A%95%E5%8F%8D%E8%BF%87%E6%9D%A5%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/utp
- 城市基础设施中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%8A%8A%E5%80%8D%E6%8A%95%E5%8F%8D%E8%BF%87%E6%9D%A5%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/63L
- 消防知识宣传的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%8A%8A%E5%80%8D%E6%8A%95%E5%8F%8D%E8%BF%87%E6%9D%A5%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/530=ayb
- 数字艺术创作的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%8A%8A%E5%80%8D%E6%8A%95%E5%8F%8D%E8%BF%87%E6%9D%A5%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/ejm=766
- 城市游园体验的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E6%8A%8A%E5%80%8D%E6%8A%95%E5%8F%8D%E8%BF%87%E6%9D%A5%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/tbo=nqu
- 智能家居应用中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%A2%E5%90%97_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/344
- 公共服务数字化的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%A2%E5%90%97_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/sbr
- 数字资源检索的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%A2%E5%90%97_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/Q7p
- 科普展览体验的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%A2%E5%90%97_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/428=hjm
- 全民阅读推广的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%A2%E5%90%97_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/vfy=885
- 生成式工具使用的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%B3%95%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%A2%E5%90%97_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8A%A1?/F3B=zJO
- 电子商务服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E4%BB%8E%E4%B8%80%E5%BC%80%E5%A7%8B_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/145
- 城市空气科普的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E4%BB%8E%E4%B8%80%E5%BC%80%E5%A7%8B_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/awk
- 数字设备回收的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E4%BB%8E%E4%B8%80%E5%BC%80%E5%A7%8B_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/Gch
- 运动安全知识的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E4%BB%8E%E4%B8%80%E5%BC%80%E5%A7%8B_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/967=dym
- 城市基础设施的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E4%BB%8E%E4%B8%80%E5%BC%80%E5%A7%8B_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/zaq=809
- 电子商务服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%80%8D%E6%8A%95%E4%BB%8E%E4%B8%80%E5%BC%80%E5%A7%8B_%E6%90%9C%E7%8B%90%E8%AF%BB%E4%B9%A6?/k42=F6F
- 旧物循环利用的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/405
- 家庭照护支持的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/onf
- 家庭饮食安排的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/GjS
- 城市步行友好的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/532=giq
- 家庭科学教育的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/eec=661
- 社区志愿服务的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/D81=h95
- 老年运动活动的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/350
- 城市公共自行车的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/tij
- 公交无障碍服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/uA2
- 节日文化体验的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/272=cuj
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/cvr=645
- 家庭环保习惯的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%AD%96%E7%95%A5_%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F?/WMa=zXN
- 线上办事服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E6%AD%A2%E6%8D%9F%E6%9C%80%E7%A7%91%E5%AD%A6_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/324
- 生成式工具使用的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E6%AD%A2%E6%8D%9F%E6%9C%80%E7%A7%91%E5%AD%A6_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/vud
- 医院导诊服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E6%AD%A2%E6%8D%9F%E6%9C%80%E7%A7%91%E5%AD%A6_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/a3I
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E6%AD%A2%E6%8D%9F%E6%9C%80%E7%A7%91%E5%AD%A6_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/233=rli
- 城乡公共服务的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E6%AD%A2%E6%8D%9F%E6%9C%80%E7%A7%91%E5%AD%A6_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/zrl=416
- 非遗体验活动的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E6%AD%A2%E6%8D%9F%E6%9C%80%E7%A7%91%E5%AD%A6_%E5%93%94%E5%93%A9%E6%88%B7%E5%A4%96?/L3c=xS5
- 在线学习体验的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E9%80%82_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/328
- 科学运动指导的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E9%80%82_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/gss
- 便民信息查询的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E9%80%82_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/8h4
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E9%80%82_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/537=wef
- 数字设备回收的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E9%80%82_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/bxh=218
- 社区养老服务的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%87%A0%E6%9C%9F%E6%9C%80%E5%90%88%E9%80%82_%E8%99%8E%E6%89%91%E6%8A%95%E7%A8%BF?/347=7tz
- 街区更新实践的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/093
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/hxy
- 数字素养提升从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/b0r
- 社区修缮行动的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/342=srh
- 社区活动空间的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/gwu=628
- 家庭理财科普的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%95%B0%E8%AF%BB?/ZW6=qDG
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/241
- 租房信息服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/bqp
- 生成式工具使用的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/ZdB
- 在线学习体验的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/355=gzj
- 消防知识宣传的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/jka=331
- 节能家电使用的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E7%88%B1%E5%A5%87%E8%89%BA%E9%A3%9F%E5%93%81?/1Ve=08B
- 社区安全巡查的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E6%9C%89%E5%87%A0%E7%A7%8D_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/295
- 社区共享书架的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E6%9C%89%E5%87%A0%E7%A7%8D_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/yex
- 社区设施共享的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E6%9C%89%E5%87%A0%E7%A7%8D_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/XSW
- 社区宠物管理的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E6%9C%89%E5%87%A0%E7%A7%8D_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/561=pwh
- 环境监测科普的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E6%9C%89%E5%87%A0%E7%A7%8D_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/pzd=465
- 社区活动报名的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E6%9C%89%E5%87%A0%E7%A7%8D_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/HlP=yQx
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/183
- 本地历史资料的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/opd
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/4lN
- 志愿服务平台的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/749=htf
- 科学信息获取的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/evq=704
- 公共设施使用的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_3d%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%83%E5%B8%86?/pke=cEv
- 生成式工具使用的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_15%E6%9C%9F%E5%80%8D%E6%8A%95%E5%AE%9E%E6%88%98%E6%A1%88%E4%BE%8B%E5%88%86%E4%BA%AB_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/919
- 街区小店体验的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_15%E6%9C%9F%E5%80%8D%E6%8A%95%E5%AE%9E%E6%88%98%E6%A1%88%E4%BE%8B%E5%88%86%E4%BA%AB_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/bee
- 老旧小区改造的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_15%E6%9C%9F%E5%80%8D%E6%8A%95%E5%AE%9E%E6%88%98%E6%A1%88%E4%BE%8B%E5%88%86%E4%BA%AB_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/2av
- 户外活动组织的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_15%E6%9C%9F%E5%80%8D%E6%8A%95%E5%AE%9E%E6%88%98%E6%A1%88%E4%BE%8B%E5%88%86%E4%BA%AB_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/192=etc
- 医院导诊服务的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_15%E6%9C%9F%E5%80%8D%E6%8A%95%E5%AE%9E%E6%88%98%E6%A1%88%E4%BE%8B%E5%88%86%E4%BA%AB_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/tkg=750
- 低碳社区实践的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_15%E6%9C%9F%E5%80%8D%E6%8A%95%E5%AE%9E%E6%88%98%E6%A1%88%E4%BE%8B%E5%88%86%E4%BA%AB_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/tEL=JZx
- 城市游园体验的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E7%9A%84%E8%A7%84%E5%88%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/956
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E7%9A%84%E8%A7%84%E5%88%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/dbh
- 户外活动组织的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E7%9A%84%E8%A7%84%E5%88%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/1M4
- 城市运动公园的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E7%9A%84%E8%A7%84%E5%88%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/578=uiw
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E7%9A%84%E8%A7%84%E5%88%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/kyz=374
- 社区商业活力的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%80%8D%E6%8A%95%E7%9A%84%E8%A7%84%E5%88%99%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/Xuk=m4H
- 社区信息发布的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%951.3.9.27%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%95%B0%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/889
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%951.3.9.27%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%95%B0%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/oqq
- 农业科普体验的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%951.3.9.27%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%95%B0%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/vhP
- 垃圾分类指导的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%951.3.9.27%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%95%B0%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/820=aqf
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%951.3.9.27%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%95%B0%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/ccn=656
- 线上办事服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%951.3.9.27%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%95%B0%E6%98%AF%E5%A4%9A%E5%B0%91_%E5%BF%85%E5%BA%94%E4%B8%93%E6%A0%8F?/w4s=KKh
- 城市便民驿站的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/892
- 个人时间管理的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/hji
- 无障碍出行的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/w8j
- 绿色消费选择的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/008=yim
- 公共服务预约的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/slk=747
- 乡村产业科普的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8%E5%B7%A5%E5%85%B7%E5%9C%A8%E7%BA%BF_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A4%BE%E8%AE%BA?/cg2=Jah
- 公共空间导览的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3D%E5%AE%88%E5%8F%B7%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/148
- 数字档案服务的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3D%E5%AE%88%E5%8F%B7%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/kkw
- 数字资源检索的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3D%E5%AE%88%E5%8F%B7%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/HJS
- 社区运动空间的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_3D%E5%AE%88%E5%8F%B7%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%88%86%E6%96%99?/174=sqa

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
