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

- 医院导诊服务的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/SWS
- 健康饮食教育的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/190=fpv
- 街区更新实践的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gdv=873
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/920=Phn
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/177
- 数据分析入门的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/cxo
- 数字资源检索的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/vEK
- 城市文明出行的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/483=lek
- 传统手工艺体验的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/yqx=503
- 社区活动策划的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E8%84%89%E8%84%89%E8%BF%B0%E8%AF%84?/lqY=JGv
- 社区便民服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/242
- 街区道路维护的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/lij
- 居家适老化改造的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/tDr
- 科普展览体验的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/363=uvi
- 社区环保活动的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/kyc=055
- 城市夜间生活有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%9E%E6%9C%9B?/z0o=Ty6
- 绿色出行服务的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/843
- 基层服务创新的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/ifl
- 文明养宠科普的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/i3i
- 城市微更新实践的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/652=ipj
- 社区文化节活动的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/mlq=830
- 城市水环境观察的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7-%E5%BE%97%E7%89%A9%E8%B4%A2%E6%8A%A5?/6oy=9by
- 社区故事采集的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/308
- 地方旅游导览的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/rle
- 传统手工艺体验的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/v1L
- 周末休闲规划的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/537=uko
- 城市夜间生活的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/avy=618
- 智慧停车服务的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%B8%E6%88%8F?/ETq=2Gb
- 儿童户外活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/399
- 城市应急科普的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/xnd
- 社区修缮行动的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/huM
- 远程协作工具的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/116=ato
- 本地历史资料的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/xay=926
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99-%E8%99%8E%E5%97%85%E5%BF%AB%E6%8A%A5?/PUM=Z3o
- 居民健康教育的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/062
- 社会体育指导的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/inx
- 社区快递服务的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/sAu
- 家庭食品保存中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/396=bxi
- 城市公共饮水的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ksd=171
- 城市游园体验的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88-%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/211=oRK
- 社区垃圾回收的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/104
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/gnu
- 急救知识普及的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/2D9
- 数字公共文化的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/157=twk
- 家庭健康科普的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/uhn=190
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E4%BA%AC%E4%B8%9C%E5%85%AC%E7%9B%8A?/4zn=NuA
- 城市社区治理的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A-%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/675
- 科学健身方法的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A-%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/dar
- 个人时间管理的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A-%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/9d1
- 数字支付体验的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A-%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/694=uah
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A-%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/omc=213
- 农产品消费体验的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A-%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/8WC=0O0
- 新能源出行的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/609
- 绿色校园实践的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/sys
- 公交站点体验的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/yh8
- 绿色办公实践的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/578=opg
- 低碳社区实践的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/tfg=075
- 公益活动组织的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/ItS=MXY
- 电子商务服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_PC28%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/221
- 科技馆参观体验的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_PC28%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/cpu
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_PC28%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/z8v
- 电动汽车充电的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_PC28%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/875=iio
- 社区养老服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_PC28%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/yeb=829
- 青年志愿活动的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_PC28%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E8%BE%9F%E8%B0%A3?/wYM=HfT
- 城市人文观察的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9FPK10-%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/520
- 城市休闲步道的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9FPK10-%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/xca
- 节日文化体验的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9FPK10-%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/mJc
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9FPK10-%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/070=klo
- 开放数据应用的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9FPK10-%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/ddu=451
- 口袋公园建设的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9FPK10-%E5%A4%B4%E6%9D%A1%E8%B4%A2%E7%BB%8F?/fzv=Jet
- 通勤路线规划的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6PK10%E4%BA%A4%E6%B5%81%E7%BE%A4-%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/592
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6PK10%E4%BA%A4%E6%B5%81%E7%BE%A4-%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/bic
- 社区运动空间的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6PK10%E4%BA%A4%E6%B5%81%E7%BE%A4-%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/d1m
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6PK10%E4%BA%A4%E6%B5%81%E7%BE%A4-%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/689=uco
- 本地历史资料的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6PK10%E4%BA%A4%E6%B5%81%E7%BE%A4-%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/hkh=068
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E8%B5%9B%E8%BD%A6PK10%E4%BA%A4%E6%B5%81%E7%BE%A4-%E8%85%BE%E8%AE%AF%E6%8E%A2%E5%BA%97?/b5g=8IV
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/955
- 社区绿色空间的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/fwr
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/NZi
- 个人信息保护的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/855=vif
- 老年数字阅读的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/fsh=915
- 电动汽车充电的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E8%B5%9B%E8%BD%A6%E4%BF%A1%E8%AA%89%E7%BE%A4-%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/7Nk=zGC
- 老年人日常照护的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B5%9B%E8%BD%A6PK10%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/092
- 低碳社区实践的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B5%9B%E8%BD%A6PK10%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xjq
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B5%9B%E8%BD%A6PK10%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dGB
- 公共服务指南的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B5%9B%E8%BD%A6PK10%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/173=tdj
- 城市噪声观察的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B5%9B%E8%BD%A6PK10%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/tpo=733
- 社区活动报名的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E8%B5%9B%E8%BD%A6PK10%E5%BE%AE%E4%BF%A1%E7%BE%A4-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/2tD=Z1M
- 城市农夫市集的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC-%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/240
- 社区家政服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC-%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/ihv
- 在线教育体验的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC-%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/o5b
- 公共空间安全的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC-%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/720=zti
- 环境教育课程的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC-%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/qlc=271
- 老年人日常照护的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC-%E4%BC%98%E9%85%B7%E5%AE%B6%E5%B1%85?/L2v=Sc4
- 健康饮水科普的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A93D-%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/694
- 城市步行友好的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A93D-%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/sja
- 城市生活服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A93D-%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/4MB
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A93D-%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/885=rid
- 健康饮食教育的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A93D-%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/imi=311
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A93D-%E5%87%A4%E5%87%B0%E6%BC%AB%E8%AF%84?/aqU=LkX
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_3D%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/154
- 基层医疗预约的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_3D%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/haf
- 传统节日科普的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_3D%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/ZyW
- 城市基础设施的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_3D%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/188=ssb
- 城市体育设施的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_3D%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/ziz=437
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_3D%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/uGM=SZP
- 课后服务体验的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3D%E8%B5%B0%E5%8A%BF-%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/343
- 城市适老服务的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3D%E8%B5%B0%E5%8A%BF-%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/zea
- 农贸市场环境的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3D%E8%B5%B0%E5%8A%BF-%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/CFt
- 社区读书角建设的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3D%E8%B5%B0%E5%8A%BF-%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/150=juy
- 网络安全教育的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3D%E8%B5%B0%E5%8A%BF-%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/vrv=802
- 急救知识普及的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3D%E8%B5%B0%E5%8A%BF-%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/9rw=Ihy
- 在线教育体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92-360%E6%B8%B8%E6%88%8F?/167
- 城市便民驿站的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92-360%E6%B8%B8%E6%88%8F?/pxu
- 乡村公共文化的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92-360%E6%B8%B8%E6%88%8F?/apF
- 节能家电使用的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92-360%E6%B8%B8%E6%88%8F?/830=xxo
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92-360%E6%B8%B8%E6%88%8F?/pcg=684
- 农村环境治理的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92-360%E6%B8%B8%E6%88%8F?/igq=EWl
- 公共图书馆服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/706
- 数字生活课堂的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/hmy
- 公交站点体验的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/n4g
- 健康信息获取的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/732=hhg
- 城市社区治理的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/esx=291
- 周末休闲规划的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6-%E8%85%BE%E8%AE%AF%E6%97%A5%E6%8A%A5?/5cO=OKW
- 家庭消费规划的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/516
- 公共设施维护的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/kba
- 家庭消费规划的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/tP4
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/595=mbj
- 邻里共享空间的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/gma=863
- 城市展览体验中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BF%B0%E8%AF%84?/kzx=AUJ
- 公共空间安全的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/342
- 城市绿色交通的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/nsr
- 家庭教育交流的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/1aT
- 乡村阅读活动的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/977=cbs
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/upa=149
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/yZK=Zgt
- 学校食育活动的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/431
- 乡村公共文化的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/ser
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/Cd3
- 地方文化传播的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/873=thv
- 智慧停车服务的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/erx=387
- 社区志愿服务的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app-%E6%8E%8C%E4%B8%8A%E8%B4%A2%E7%BB%8F?/ckd=Q5O
- 社区公共餐饮的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/898
- 社区协商议事的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/fvg
- 社区故事采集的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/Ia3
- 开源技术交流的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/316=suk
- 科技馆参观体验的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/cpk=149
- 本地历史资料的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/cc9=DPX
- 节气饮食文化的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/227
- 社区协商议事的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/xao
- 城市地名文化的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/t3a
- 社区儿童活动的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/471=wgb
- 数据分析入门的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/ycw=890
- 绿色建筑理念的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E7%BD%91%E7%AB%99-%E6%8A%96%E9%9F%B3%E7%BE%8E%E8%82%A1?/Fay=YKB
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/317
- 社区应急准备的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/owx
- 地方戏曲体验的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/NoS
- 低碳社区实践的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/377=nne
- 城市体育设施的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/vfb=609
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E7%AB%99-%E5%A4%B4%E6%9D%A1%E4%BF%9D%E9%99%A9?/IlW=XGO
- 基层服务创新的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99-%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/060
- 农业科普体验的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99-%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/tvw
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99-%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/U1V
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99-%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/074=zoe
- 公交无障碍服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99-%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/pwf=379
- 软件开发学习的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99-%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/kOx=bYH
- 家庭消费规划的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%98%E7%BD%91%E5%BF%AB3-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/313
- 校园社团活动的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%98%E7%BD%91%E5%BF%AB3-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/rho
- 青年就业服务的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%98%E7%BD%91%E5%BF%AB3-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/oys
- 儿童阅读角的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%98%E7%BD%91%E5%BF%AB3-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/263=zvf
- 公共交通信息服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%98%E7%BD%91%E5%BF%AB3-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/tyr=072
- 城市应急广播的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%98%E7%BD%91%E5%BF%AB3-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F?/0nK=IHH
- 公共卫生设施的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/606
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/orp
- 家庭环保习惯的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/ahl
- 社区便利生活的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/155=rpp
- 数字地图应用的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/jws=160
- 城市可持续生活的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0-%E8%85%BE%E8%AE%AF%E8%83%BD%E6%BA%90?/OaJ=Bok
- 城市共享单车的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/495
- 乡村教育资源的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/seq
- 网络安全教育的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/TbL
- 小区公共照明的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/557=rlk
- 社区邻里服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/aqi=266
- 灵活就业交流的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E8%99%8E%E5%97%85%E5%85%AC%E5%91%8A?/L19=zGo
- 农村环境治理中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/710
- 居家防滑改造的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/epn
- 生活垃圾回收的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/onZ
- 公共空间休憩的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/621=aye
- 乡村公共阅读的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/dju=376
- 社区文化传播的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/R8c=Lim
- 数字生活课堂的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/398
- 传统节日科普的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/thh
- 城市雨天出行的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/KC0
- 城市便民驿站的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/963=kmp
- 社区文化节活动的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/vzh=009
- 社区设施共享的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91-%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/5cP=mle
- 气象科普传播的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/857
- 家庭网络使用的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/rbz
- 绿色出行服务的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/Gc0
- 软件开发学习中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/818=xcr
- 城市步行友好的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/tff=233
- 社区养老服务的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99-%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/gxB=i6g
- 社区法律科普的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/201
- 家庭科学教育的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/bjd
- 公共服务评价的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/447
- 小区公共照明的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/582=nwh
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/ayf=496
- 儿童户外活动的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E4%BA%BA%E5%A4%A7?/6p5=Lgy
- 便民维修服务的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/799
- 老年友好服务的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/qsq
- 农村环境治理的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/aHs
- 图书借阅体验的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/137=qmw
- 在线学习体验的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/obu=495
- 城市农夫市集的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E5%9B%9E%E6%94%BE?/owk=zFN
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB3app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/420
- 公共场所导视的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB3app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/ral
- 居家适老化改造的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB3app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/VMe
- 绿色消费选择的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB3app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/587=kla
- 志愿服务平台的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB3app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/xag=006
- 社区环保活动的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BF%AB3app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD-%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/q7X=0xg
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/794
- 街头绿植养护的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/gzb
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/Gvt
- 骑行路线规划的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/022=wyb
- 科技馆参观体验的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/yzz=579
- 家庭急救准备的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91-%E9%9B%85%E8%99%8E%E9%80%9F%E8%A7%88?/ZlP=L9Z
- 节能生活方式的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/070
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/omp
- 电子商务服务的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/Qes
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/253=lvn
- 志愿服务平台的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/imk=537
- 数字学习资源的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4-%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/aCn=svt
- 节约用水实践的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/107
- 城市公共饮水的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/uqq
- 城市应急科普的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/FWi
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/074=xfp
- 家庭健康管理的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/bzz=135
- 社区活动策划的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92-%E5%A4%AE%E8%A7%86%E6%97%B6%E6%8A%A5?/9O0=kfz
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92-%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/024
- 数字设备回收的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92-%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/fnj
- 健康步道使用的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92-%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/xJA
- 无障碍出行的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92-%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/930=xcb
- 城市应急广播的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92-%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/hgh=778
- 城市公共艺术的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E8%AE%A1%E5%88%92-%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/V0s=Hud
- 全民健身活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/989
- 城市生活服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/mlw
- 城市建设科普的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/Otf
- 垃圾分类指导的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/603=vpi
- 公园亲子设施的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/fiu=416
- 家庭健康科普的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/sBk=0mX

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
