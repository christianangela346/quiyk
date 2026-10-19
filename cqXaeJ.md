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

- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/WGR
- 城市社区治理的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/812=cco
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/kop=468
- 日常摄影记录的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%9F%AD%E6%9C%9F%E5%85%BC_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/0ez=G9n
- 社区知识分享的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/749
- 家庭安全提示的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/xoh
- 信息无障碍体验的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/Lwq
- 数字档案服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/660=qkc
- 城乡交通衔接的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ftr=440
- 家庭节能设备的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E6%80%BB%E7%BB%93_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/QyA=AXi
- 节约用水实践的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/852
- 数字支付体验的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/tfk
- 城市文化路线的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/l6X
- 读书会组织的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/826=nxc
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/npf=003
- 公共服务数字化的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C100%25%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9?/33i=9RS
- 电子商务服务的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/397
- 智慧停车服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/yfh
- 家庭阅读计划的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/bOK
- 安全出行教育的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/121=ozw
- 城市公共艺术的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/vnb=490
- 生活垃圾回收的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3app_%E9%A1%BA%E4%B8%B0%E5%85%9A%E5%BB%BA?/uv1=Wiq
- 社区科普课堂的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/811
- 绿色生活实践中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/ejh
- 机器学习入门的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/qST
- 数字创意课程的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/447=pjp
- 城市夜间照明的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/wnz=745
- 邻里互助活动的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E6%AD%A3%E8%A7%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/Iy2=3WG
- 节假日出行安排的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/223
- 数字资源检索的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/pam
- 公园无障碍服务的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/4H3
- 城市慢行系统的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/860=dus
- 物业服务沟通的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/lcg=998
- 社区体育组织中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E4%B8%8D%E6%80%95%E9%95%BF%E9%BE%99_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/nr9=c81
- 就业技能培训的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/404
- 全民阅读推广的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/sbw
- 食品配送体验的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/xtG
- 地方旅游导览的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/578=dql
- 本地消费场景的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/ilg=928
- 公共服务评价的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/usb=22C
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/476
- 家庭急救准备的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/vgr
- 农产品消费体验的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/f2k
- 社区停车服务的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/795=gvl
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/bej=175
- 青少年科技社团的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%87%E8%83%BD%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/CFj=8nt
- 环境教育课程的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_360%E6%89%8B%E8%AE%B0?/928
- 社区学习活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_360%E6%89%8B%E8%AE%B0?/tkg
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_360%E6%89%8B%E8%AE%B0?/jSH
- 社区应急准备的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_360%E6%89%8B%E8%AE%B0?/462=uiv
- 家庭网络使用的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_360%E6%89%8B%E8%AE%B0?/hty=980
- 周末休闲规划的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E6%8A%80%E5%B7%A7_360%E6%89%8B%E8%AE%B0?/46j=igD
- 老年数字阅读的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/076
- 社区快递服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/wpc
- 公交站点体验的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/t4D
- 城市微更新实践的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/179=lfp
- 线上办事服务的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/zoe=546
- 街区道路维护的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%A2_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/LtY=c78
- 公园休闲体验的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/660
- 城市展览体验的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/hey
- 社区活动策划的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/Dup
- 远程协作工具的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/293=bkb
- 数字创意课程的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/lgp=921
- 节日文化体验的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E4%BC%98%E9%85%B7%E5%9C%88%E5%AD%90?/nGm=Hb7
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/772
- 家庭健康科普中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/zvc
- 应急物资管理的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/Ko5
- 机器学习入门的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/503=uvs
- 节约用水实践的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/tmn=529
- 社区庭院绿化的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/nhD=C2h
- 校园阅读活动的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/659
- 乡村文化活动的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/aip
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/3RI
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/639=elf
- 绿色办公实践从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/ect=401
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%8D%81%E5%88%86%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AF%84?/rwO=fYb
- 社区慢性病防控的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/772
- 电动汽车充电的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/zho
- 绿色快递包装的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/r3T
- 社区交通安全的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/358=wlg
- 社区读书角建设的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/iax=063
- 物业服务沟通的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%8D%81%E5%88%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A1%8C%E6%83%85?/FAM=AUR
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/090
- 城市夜间照明的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/epm
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/Imi
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/084=sir
- 乡村公共文化的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/zaw=787
- 社区快递服务的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E8%A7%A3%E5%AF%86?/FtL=0JR
- 城乡交流活动中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/110
- 城市噪声观察的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/lfs
- 城市博物馆活动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/uBs
- 数字学习资源的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/449=kcg
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/gnh=964
- 灵活就业交流的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E6%8A%BC%E5%A4%A7%E5%B0%8F%E5%BF%85%E8%B5%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/dFu=I29
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/263
- 全民健身活动的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/ina
- 个人数据管理的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/YIc
- 周末休闲规划的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/270=rjc
- 家庭消费规划的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/qyp=050
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E5%85%AD%E4%B8%AA%E6%8A%80%E5%B7%A7_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/2Xm=2BT
- 乡村生态旅游的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/758
- 城市公共饮水的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/vsi
- 家庭科学教育的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/4tk
- 科学信息获取的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/627=eff
- 智慧停车服务的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/gad=467
- 公共空间导览的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/xOm=nQ2
- 科学教育活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/505
- 家庭阅读计划的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/kql
- 城市骑行环境的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/2Av
- 社区科普课堂的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/870=xtu
- 智慧停车服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/qzh=225
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B%E6%80%8E%E4%B9%88%E7%9C%8B_%E5%BE%97%E7%89%A9%E8%AE%BA%E5%9D%9B?/FPH=2zw
- 环境教育课程的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/412
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/qoz
- 社区共享书架的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/i5R
- 农贸市场环境的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/692=myp
- 社区手工活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/tww=484
- 街区小店体验的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/VXU=Iqw
- 开放式学习空间的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/639
- 城市可持续生活的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/zdk
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/Qkl
- 新能源知识普及的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/314=ipv
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/qof=149
- 数字政务体验的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/6wc=ESg
- 机器学习入门的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/284
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/yox
- 乡村公共文化的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/pp3
- 租房信息服务的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/936=gnp
- 科普展览体验的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/kwd=707
- 城市应急科普的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%958%E5%B1%80%E5%BF%85%E5%BC%80_%E8%B0%B7%E6%AD%8C%E5%B9%B6%E8%B4%AD?/BQO=VJa
- 数字课堂应用的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/717
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/qqo
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/MPC
- 社区读书角建设的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/633=xus
- 职业技能学习的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/drq=657
- 社会体育指导的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/pUH=R7X
- 骑行路线规划的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/906
- 健康饮水科普的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/yop
- 公园休闲体验的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/Z0O
- 志愿者培训交流的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/612=him
- 休闲运动入门的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/hvq=599
- 老年数字阅读的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E5%BC%80%E8%AF%BE?/jMN=7At
- 智能家居应用的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/878
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/elt
- 街区绿化养护的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/Qum
- 公共服务指南的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/097=rew
- 城市展览体验的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/rqt=708
- 社区便利生活的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/PT7=VzA
- 智能家居应用的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/157
- 街区道路维护的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/ibn
- 城市建设科普的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/eiB
- 城市生活服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/197=bmg
- 校园安全教育的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/avc=732
- 数字课堂应用的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E6%A0%B7%E5%80%8D%E6%8A%95%E7%BB%9D%E5%AF%B9%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/efu=Ln9
- 城市文化路线的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/223
- 数字档案服务的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/tjy
- 社区休闲设施的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/lYx
- 家庭收纳实践的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/278=iaz
- 科学运动指导的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/glz=517
- 城市公共饮水中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%8D%E5%80%8D%E6%8A%95%E8%83%BD%E4%B8%8D%E8%83%BD%E8%B5%A2_36%E6%B0%AA%E4%BF%9D%E9%99%A9?/YaJ=NWg
- 公共服务指南的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%96%87%E5%8C%96?/455
- 乡村阅读活动的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%96%87%E5%8C%96?/bin
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%96%87%E5%8C%96?/FUm
- 城市建设科普的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%96%87%E5%8C%96?/713=haj
- 城市建设科普的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%96%87%E5%8C%96?/eop=557
- 光伏知识科普的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E6%96%87%E5%8C%96?/OHQ=mvi
- 课后服务体验的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/782
- 学校体育活动的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/nte
- 社区教育资源的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/DFY
- 城市噪声观察的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/237=kow
- 城市公共座椅的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/ywb=930
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_1358-1524%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F?/rjC=trw
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/583
- 公共文化活动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/ufh
- 城市夜间照明的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/1ny
- 儿童友好空间的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/929=cyz
- 健康饮水科普的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/xmc=394
- 青少年户外教育从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%87%A4%E5%87%B0%E6%88%B7%E5%A4%96?/AX2=z0K
- 家庭食品保存的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/742
- 老年智能设备的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/eis
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/FSM
- 气象科普传播的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/513=udt
- 开放数据应用的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/mkx=970
- 社区老年食堂的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_700%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/bA2=m24
- 公共文化活动的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/844
- 节假日出行安排的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/gmt
- 科学观察活动的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/4Pa
- 小微企业服务的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/870=gfy
- 社区故事采集从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/arv=961
- 家庭用电安全的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B3%E6%8A%95%E5%92%8C%E5%80%8D%E6%8A%95%E5%93%AA%E4%B8%AA%E6%96%B9%E6%A1%88%E6%AF%94%E8%BE%83%E5%A5%BD_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/upx=vYc
- 青年职业探索的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/062
- 小区公共照明的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/euc
- 社区停车服务的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/9fP
- 乡村公共服务有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/123=ixv
- 环境监测科普的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/ydl=464
- 家庭健康科普的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/8Lx=Vdh
- 乡村产业科普的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/950
- 乡村公共文化的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/yex
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/EhY
- 基层健康服务的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/295=sqm
- 公共交通信息服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/jem=763
- 数字学习资源的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%B6%88%E8%B4%B9?/7sV=3jp
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/750
- 开放式学习空间的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/vhr
- 城市可持续生活的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/9SS
- 社区商业活力的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/507=peb
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/hfn=871
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%B3%95%E5%88%99_%E5%BE%97%E7%89%A9%E5%BF%AB%E6%8A%A5?/wOl=DL3
- 科学运动指导的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/109
- 城市社区治理的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/iyt
- 社区学习活动的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/P1L
- 乡村电商实践的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/024=yjr
- 城市生活服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/ptq=247
- 城市噪声观察的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_3%E4%B8%B21%E5%92%8C3%E4%B8%B24%E5%93%AA%E4%B8%AA%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/RdI=gXu
- 公益活动组织的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/765
- 急救知识普及的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/ixe
- 青少年心理健康的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/DLy
- 公共服务预约的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/132=kyf
- 市民热线服务的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/kzl=793
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%9C%89%E8%B5%8C%E7%98%BE%E7%9A%84%E4%BA%BA%E8%83%BD%E6%88%92%E6%8E%89%E5%90%97_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/E4T=hLk
- 社区花园共建的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/408
- 老年友好服务中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/paw
- 网络安全教育的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/fbK
- 乡村生态观察的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/640=wds
- 图书借阅体验的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/wbt=073
- 城市公共自行车的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E6%8A%95%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E9%80%9A%E4%BF%A1?/I2C=se9
- 校园节能行动的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/381
- 社区交通安全的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/rlf
- 休闲运动入门的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/JCT
- 生活服务数字化的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/916=xsb
- 亲子科普活动的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/rzg=558
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/mdd=0Zz
- 城市建设科普的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/925
- 数字地图应用的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/wag
- 数字档案服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/SJa
- 社区安全巡查的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/473=ozz
- 数字支付体验的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/vgd=138
- 社会体育指导的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E9%91%AB%E7%A6%BE%E5%9B%BD%E9%99%85_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/Ek7=iAS
- 社区便民集市的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/899
- 软件开发学习的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/rrl
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/WgC
- 城市人文观察的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/980=zqc
- 街区道路维护的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/fzj=875
- 本地历史资料的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/aqG=aL4
- 儿童友好街区的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/931
- 本地旅行体验的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/fdp
- 城乡公共服务的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/Od0
- 非遗体验活动的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/966=mtf
- 公共文化活动的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/gjr=806
- 社区慢性病防控的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0app_%E5%BF%85%E5%BA%94%E8%AE%B2%E5%9D%9B?/XgF=r1D

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
