# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/673
- 社区科普课堂的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/arv
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/dau
- 生活垃圾回收的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/481=ucn
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/nlq=989
- 骑行路线规划的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E4%B8%80%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E9%A2%84%E6%B5%8B%E6%B1%87%E6%80%BB_%E8%8A%92%E6%9E%9C%E6%8A%95%E7%A5%A8?/r99=u8L
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/170
- 社区心理支持的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/plp
- 新能源知识普及的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/WgN
- 城市农夫市集的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/543=mlc
- 家庭运动计划的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/ewf=544
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9A28%E9%A2%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E6%95%B0%E8%AF%BB?/nxn=cgg
- 社区交通安全的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E7%89%9B%E5%BD%A9%E7%BD%91_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/546
- 智能手机助老的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E7%89%9B%E5%BD%A9%E7%BD%91_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/wzt
- 城市生活记录的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E7%89%9B%E5%BD%A9%E7%BD%91_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/Ogq
- 青少年心理健康的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E7%89%9B%E5%BD%A9%E7%BD%91_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/694=kgc
- 开放数据应用的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E7%89%9B%E5%BD%A9%E7%BD%91_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/dvn=592
- 社区花园共建的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_pc28%E9%A2%84%E6%B5%8B%E7%89%9B%E5%BD%A9%E7%BD%91_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/X12=BCs
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_pc28%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/359
- 老年人出行服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_pc28%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/zbo
- 社区故事采集的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_pc28%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/LPY
- 科普展览体验的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_pc28%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/468=fhf
- 家庭网络使用的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_pc28%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/igl=823
- 公共服务预约的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_pc28%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%92%AD%E6%8A%A5?/qBa=2rF
- 城市人文观察的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/085
- 儿童友好街区的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/inh
- 街道综合服务的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/lky
- 乡村产业科普的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/963=wik
- 邻里互助活动的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/dum=173
- 乡村生态旅游的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%9028%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/dik=MR0
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/760
- 文化场馆预约的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/hql
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/7Hy
- 老年运动活动的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/282=omd
- 家庭健康管理的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/bfy=767
- 城市共享单车的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/zOF=Djl
- 小区公共照明的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_28%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/182
- 药品使用科普的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_28%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/acy
- 线上阅读资源的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_28%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/cAZ
- 健康饮水科普的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_28%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/702=faw
- 家庭科学教育的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_28%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/tms=826
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_28%E4%B8%8B%E8%BD%BDapp%E5%BD%A9%E7%A5%A8_%E4%BA%AC%E4%B8%9C%E5%AE%9E%E5%BD%95?/HSc=V10
- 老年智能设备的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_28%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/730
- 社区安全巡查的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_28%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/oga
- 社区托育服务的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_28%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/mdj
- 本地旅行体验的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_28%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/250=nlq
- 绿色办公实践的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_28%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/dix=331
- 乡村阅读空间的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_28%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%88%B7%E5%A4%96?/WEj=QjN
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_28%E5%9C%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/347
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_28%E5%9C%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/pnn
- 环境监测科普的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_28%E5%9C%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/0mh
- 本地消费场景的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_28%E5%9C%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/749=vhb
- 乡村文化空间的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_28%E5%9C%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/day=888
- 城市微更新实践的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_28%E5%9C%88%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/r1S=sJx
- 消防知识宣传的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%AF%BF%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A72.8_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/412
- 医院导诊服务的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%AF%BF%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A72.8_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/wju
- 公共文化活动的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%AF%BF%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A72.8_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/7PC
- 公共交通接驳的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%AF%BF%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A72.8_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/902=anp
- 邻里互助活动的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%AF%BF%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A72.8_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/pdp=800
- 公共空间照明的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%B0%8F%E5%AF%BF%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A72.8_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/bw7=Htl
- 线上办事服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8F%8C%E7%BB%8428%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/124
- 城市步行友好的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8F%8C%E7%BB%8428%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/kab
- 科学运动指导的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8F%8C%E7%BB%8428%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/QBY
- 城乡交通衔接的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8F%8C%E7%BB%8428%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/837=zoa
- 数字创作工具有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8F%8C%E7%BB%8428%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/opt=532
- 就业技能培训的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8F%8C%E7%BB%8428%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E9%A2%84%E6%B5%8B_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/qek=QXx
- 社区公共餐饮的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/296
- 青年职业探索的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/etg
- 儿童安全出行的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/m9l
- 绿色校园实践的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/436=jhs
- 小区公共照明的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/ufz=559
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E8%AE%A1%E5%88%92%E4%B9%8B%E5%AE%B6%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/reX=sLY
- 街区道路维护的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/167
- 社区消防演练的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/hbk
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/YUe
- 机器学习入门的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/229=sbu
- 街道综合服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/ldi=373
- 节假日出行安排的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%92%AA%E7%89%8C%E6%9C%80%E6%96%B0%E7%BB%93%E6%9E%9C_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/dcG=YEM
- 公共健身器材的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%88%90%E5%8A%9F%E6%A1%88%E4%BE%8B70%E6%9C%9F_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/686
- 城市微更新实践中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%88%90%E5%8A%9F%E6%A1%88%E4%BE%8B70%E6%9C%9F_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/yxf
- 乡村公共服务的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%88%90%E5%8A%9F%E6%A1%88%E4%BE%8B70%E6%9C%9F_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/N5K
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%88%90%E5%8A%9F%E6%A1%88%E4%BE%8B70%E6%9C%9F_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/146=ohx
- 社区信息发布的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%88%90%E5%8A%9F%E6%A1%88%E4%BE%8B70%E6%9C%9F_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/dpn=359
- 社区公共卫生的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%88%90%E5%8A%9F%E6%A1%88%E4%BE%8B70%E6%9C%9F_%E5%A4%AE%E8%A7%86%E9%97%AE%E7%AD%94?/SyH=inx
- 全民健身活动的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95%E8%B5%84%E6%96%99_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/020
- 户外活动组织的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95%E8%B5%84%E6%96%99_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/ltm
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95%E8%B5%84%E6%96%99_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/vDe
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95%E8%B5%84%E6%96%99_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/475=aef
- 城市公共厕所的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95%E8%B5%84%E6%96%99_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/iju=672
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95%E8%B5%84%E6%96%99_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/zX1=llz
- 节日文化体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95%28%E4%B8%80%29_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/067
- 绿色出行服务的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95%28%E4%B8%80%29_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/jrs
- 数字地图应用的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95%28%E4%B8%80%29_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/oRm
- 家庭收纳实践的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95%28%E4%B8%80%29_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/982=vwu
- 家庭节能实践的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95%28%E4%B8%80%29_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/veh=107
- 城市步行友好的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95%28%E4%B8%80%29_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/sZG=M7A
- 公共设施维护的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/206
- 地方文化传播的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/zjo
- 社区活动报名的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/JNw
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/288=doq
- 生成式工具使用的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/buq=175
- 青少年科技社团的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E4%B8%93%E5%AE%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E8%B1%86%E7%93%A3%E7%88%86%E6%96%99?/kwJ=yqu
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BE%A4%2C%E7%85%A7%E8%B5%84%E6%96%99%E6%89%93%E7%A5%A8%2C%E4%B8%8D%E4%B8%AD%E8%BF%98%E5%8F%AF%E6%8A%A5%E9%94%80_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/858
- 城市文明出行的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BE%A4%2C%E7%85%A7%E8%B5%84%E6%96%99%E6%89%93%E7%A5%A8%2C%E4%B8%8D%E4%B8%AD%E8%BF%98%E5%8F%AF%E6%8A%A5%E9%94%80_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/cit
- 节假日出行安排的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BE%A4%2C%E7%85%A7%E8%B5%84%E6%96%99%E6%89%93%E7%A5%A8%2C%E4%B8%8D%E4%B8%AD%E8%BF%98%E5%8F%AF%E6%8A%A5%E9%94%80_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/kPB
- 健康步道使用的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BE%A4%2C%E7%85%A7%E8%B5%84%E6%96%99%E6%89%93%E7%A5%A8%2C%E4%B8%8D%E4%B8%AD%E8%BF%98%E5%8F%AF%E6%8A%A5%E9%94%80_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/672=giw
- 城市文化路线的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BE%A4%2C%E7%85%A7%E8%B5%84%E6%96%99%E6%89%93%E7%A5%A8%2C%E4%B8%8D%E4%B8%AD%E8%BF%98%E5%8F%AF%E6%8A%A5%E9%94%80_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/jee=686
- 社区读书角建设的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BE%A4%2C%E7%85%A7%E8%B5%84%E6%96%99%E6%89%93%E7%A5%A8%2C%E4%B8%8D%E4%B8%AD%E8%BF%98%E5%8F%AF%E6%8A%A5%E9%94%80_%E8%B4%A2%E7%BB%8F%E6%89%8B%E8%AE%B0?/3DF=eMA
- 骑行路线规划的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/475
- 小微企业服务的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/ywr
- 老年人日常照护的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/iOY
- 公共服务指南的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/613=ayx
- 本地旅行体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/wgb=976
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%BD%91%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/Pil=f8m
- 城市运动公园的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/289
- 租房信息服务的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/ukw
- 城市游园体验的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/Ks2
- 家庭消费规划的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/457=rbz
- 乡村公共文化的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/uik=555
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/12h=AZd
- 公共场馆服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%8B%A5%E6%97%A0%E9%94%99%28%E6%89%93%E4%B8%80%E4%B8%AA%E7%94%9F%E8%82%96%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/589
- 公共交通接驳的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%8B%A5%E6%97%A0%E9%94%99%28%E6%89%93%E4%B8%80%E4%B8%AA%E7%94%9F%E8%82%96%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/uyp
- 社区儿童活动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%8B%A5%E6%97%A0%E9%94%99%28%E6%89%93%E4%B8%80%E4%B8%AA%E7%94%9F%E8%82%96%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/B3p
- 乡村公共文化的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%8B%A5%E6%97%A0%E9%94%99%28%E6%89%93%E4%B8%80%E4%B8%AA%E7%94%9F%E8%82%96%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/281=byw
- 儿童友好空间的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%8B%A5%E6%97%A0%E9%94%99%28%E6%89%93%E4%B8%80%E4%B8%AA%E7%94%9F%E8%82%96%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/jjx=077
- 远程协作工具的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E8%8B%A5%E6%97%A0%E9%94%99%28%E6%89%93%E4%B8%80%E4%B8%AA%E7%94%9F%E8%82%96%29_%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/tdI=tn9
- 老旧小区改造的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/761
- 社区阅读服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/kuk
- 全民健身活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/Gbd
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/671=olu
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/fpc=515
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E5%8D%81%E5%A4%A7%E6%8E%92%E5%90%8D_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/pwx=xNo
- 科学信息获取的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8app%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/778
- 城市基础设施的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8app%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/wpg
- 社区快递服务的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8app%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/mT1
- 居民健康教育的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8app%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/175=ffz
- 线上阅读资源的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8app%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/apw=996
- 本地消费场景的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8app%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/X85=vMi
- 智能手机助老的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_28%E5%9C%88%E8%B5%B0%E5%8A%BF%E5%9B%BE%E9%A2%84%E6%B5%8B_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/685
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_28%E5%9C%88%E8%B5%B0%E5%8A%BF%E5%9B%BE%E9%A2%84%E6%B5%8B_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/xyh
- 社区垃圾分类的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_28%E5%9C%88%E8%B5%B0%E5%8A%BF%E5%9B%BE%E9%A2%84%E6%B5%8B_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/t6T
- 日常摄影记录的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_28%E5%9C%88%E8%B5%B0%E5%8A%BF%E5%9B%BE%E9%A2%84%E6%B5%8B_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/433=woq
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_28%E5%9C%88%E8%B5%B0%E5%8A%BF%E5%9B%BE%E9%A2%84%E6%B5%8B_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/tvt=875
- 基层服务创新的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_28%E5%9C%88%E8%B5%B0%E5%8A%BF%E5%9B%BE%E9%A2%84%E6%B5%8B_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/LTt=Qya
- 农村环境治理的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/308
- 数字学习资源的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/btt
- 城市生活记录的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/Mr3
- 城市公共空间的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/639=ebc
- 社区共享书架的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/jke=641
- 农产品消费体验的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9F%BA%E9%87%91?/CzI=CbI
- 乡村阅读活动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/091
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/vzd
- 周末休闲规划的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/UQC
- 线上办事服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/823=czq
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/fqs=175
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%9028%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/ZO4=HN6
- 科学观察活动的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/590
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/afi
- 小微企业服务中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/sb4
- 本地旅行体验的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/253=xyg
- 基层医疗预约的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/ukd=048
- 学校体育活动的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_pc2.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/yyQ=PIB
- 城市应急广播的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/810
- 小区电梯维护的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/iuh
- 城市社区治理的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/x4E
- 街区绿化养护的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/625=trl
- 社区儿童活动中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/kcj=193
- 青年就业服务中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_pc28%E5%8F%8C%E5%8D%95%E4%B8%80%E6%B3%A8%E9%A2%84%E6%B5%8B_%E9%A1%BA%E4%B8%B0%E6%B8%B8%E6%88%8F?/mvz=dbJ
- 老年友好服务的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/668
- 城乡公共服务的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/jng
- 小区公共照明的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/xL8
- 基层医疗预约的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/860=kwb
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/wfr=581
- 家庭消费规划的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8pc28%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/2Ve=yFw
- 城市文明出行的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/666
- 城市建设科普的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/rvb
- 公共图书馆服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/BOf
- 运动安全知识的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/014=qiu
- 社区消防演练的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/oyh=732
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_28c%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E4%B8%8D_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/LFe=AtP
- 社区活动空间的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/886
- 社区信息发布的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/ion
- 社区读书角建设的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/Ibj
- 文化遗产保护科普的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/724=wmh
- 社区宠物管理的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/lvg=089
- 公共空间照明的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_28c%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%92%8C%E6%B3%95%E5%90%97_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/Rg5=uws
- 城市公共自行车的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/783
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/etz
- 城市文化路线的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/S46
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/017=jgr
- 小区电梯维护的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/gbu=933
- 城市博物馆活动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_cp288%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/qmw=6ua
- 开放数据应用的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_cp288%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/375
- 食品配送体验的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_cp288%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/vvv
- 非遗体验活动的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_cp288%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/z5N
- 城市应急广播中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_cp288%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/569=fzj
- 旧物循环利用的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_cp288%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/yzr=344
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_cp288%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E5%9B%BE%E9%89%B4?/RqD=XJu
- 个人信息保护中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/317
- 社区庭院绿化的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/ngq
- 儿童户外活动中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/QA7
- 数字档案服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/145=cad
- 环境监测科普的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/ryv=215
- 节能家电使用的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/dQO=jv4
- 跨代沟通活动的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/905
- 社区故事采集的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/gex
- 个人时间管理的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/YwJ
- 家庭科学教育的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/784=ido
- 社区志愿服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/dly=995
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/Rpe=VAv
- 文化讲座服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/131
- 老年人日常照护的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/uuh
- 公交站点体验的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/XF1
- 生成式工具使用的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/480=avz
- 家庭安全提示的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/irw=744
- 公共服务沟通的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%8A%A8%E6%BC%AB?/dGs=z3V
- 老年智能设备的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/992
- 公共交通接驳的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/dfc
- 城市公共标识的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/Ejg
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/608=lnt
- 公共服务数字化的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/ldn=168
- 老年运动活动的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/XU1=7Gz
- 个人时间管理的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/874
- 地方民俗记录的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/iux
- 运动安全知识的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/oUF
- 农村环境治理的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/028=ssn
- 数字艺术创作的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/cuh=361
- 学校食育活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/REw=BAc
- 社区家校合作的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/188
- 租房信息服务的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/lee
- 城市应急广播的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/Urv
- 城市应急科普的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/779=lhm
- 灵活就业交流的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/bcb=951
- 乡村阅读空间的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%A7%91%E6%8A%80?/nYz=Xrx
- 公共设施使用的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A6%99%E6%B8%AFpc28_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/010
- 城市建设科普的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A6%99%E6%B8%AFpc28_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/ppp
- 图书借阅体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A6%99%E6%B8%AFpc28_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/jsv
- 本地历史资料中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A6%99%E6%B8%AFpc28_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/559=bwg
- 社区快递服务的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A6%99%E6%B8%AFpc28_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/uzz=490
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%A6%99%E6%B8%AFpc28_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E6%8A%A5?/Qgm=I3v
- 小区停车协商的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/078
- 城市运动公园的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/hij
- 乡村生态观察中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/eu0
- 日常摄影记录的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/014=rmo
- 城市噪声观察的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/ukp=798
- 城市展览体验的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/T6Y=gdW
- 课后服务体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/405
- 社区法律科普的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/koe
- 家庭节能实践的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/RmC
- 街区绿化养护的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E5%9B%BD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/334=nbe

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
