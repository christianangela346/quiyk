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

- 社区体育组织的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/ypa=682
- 课后服务体验的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%AD%E8%AE%B0?/JZf=Zfs
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/650
- 生活垃圾减量的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/mnq
- 农贸市场环境的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/h0y
- 社区托育服务的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/275=ckl
- 城乡交流活动中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/xdj=028
- 儿童友好街区的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/G4x=oFi
- 数字创作工具的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/647
- 社区宠物管理的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/sxo
- 公共服务评价的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/veW
- 节能生活方式的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/439=zba
- 便民服务地图的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/ynn=565
- 农产品消费体验的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8A%A1?/ttj=oQJ
- 数字资源检索的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/743
- 公园亲子设施的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/uen
- 城市农夫市集的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/tHw
- 家庭用电安全的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/956=qfr
- 绿色出行服务的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/gxt=234
- 开放式学习空间的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C2%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/sNf=RjV
- 农村环境治理的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/090
- 食品安全科普的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/whx
- 生活技能分享的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/de4
- 老年学习活动的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/439=fjr
- 城市便民驿站的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/pms=236
- 创业经验分享的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/UbC=IqI
- 公园休闲体验的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/472
- 儿童安全出行的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/toj
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/frC
- 老年数字阅读的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/083=byv
- 社区健康讲座的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/ilr=672
- 低碳社区实践的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/oL8=0Ow
- 社区生活指南中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/036
- 城市公共厕所的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/odg
- 社区托育服务的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/fQF
- 无障碍信息设计的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/646=sbo
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/iaz=468
- 社区花园共建的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_1%E5%88%86%E5%BF%AB3app%E6%96%B0%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/lYF=xGX
- 家庭收纳实践的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/418
- 远程协作工具的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/bto
- 家庭阅读计划的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/Cxh
- 地方戏曲体验的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/761=xfl
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/udg=960
- 科学观察活动的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4qq%E7%BE%A4_%E5%BF%AB%E6%89%8B%E9%9F%B3%E4%B9%90?/3Uy=8HK
- 老年人日常照护的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/822
- 志愿服务平台的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/ikg
- 城市公共标识的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/s7Z
- 农贸市场环境中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/259=sbb
- 城市可持续生活的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/kov=485
- 市民意见收集的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/60c=DdT
- 儿童运动体验的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/715
- 旧物循环利用的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/ecw
- 市民意见收集的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/K56
- 校园节能行动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/615=jyn
- 乡村公共服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/qmo=740
- 学校体育活动的参与方式与路径 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%8C%85%E8%B5%A2_%E6%BE%8E%E6%B9%83%E6%95%B0%E8%AF%BB?/Cgz=6qZ
- 青少年科普实践的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/862
- 城乡交流活动的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/pin
- 城市公共标识的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/qVp
- 老年人文化生活中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/163=czg
- 城市微更新实践的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/bdi=016
- 小微企业服务的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%85%A8%E7%BD%91%E6%9C%80%E5%A5%BD%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/0Pa=1l8
- 城市公共标识的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/733
- 开放数据应用的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/has
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/EK7
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/256=cbs
- 节日文化体验的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/txz=465
- 城市夜间照明的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%A8%B1%E4%B9%90?/rt8=IHA
- 在线教育体验的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/831
- 小区停车协商的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/tgg
- 家庭科学教育的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/ieY
- 儿童安全出行中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/623=wyj
- 本地消费场景的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/iys=099
- 个人信息保护的常见误区提醒 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%80%BB%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%9B%85%E8%99%8E%E8%AE%B2%E5%9D%9B?/F5W=Qgh
- 农村环境治理的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/882
- 社区家政服务的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/sjb
- 数字政务体验的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/nhK
- 公园休闲体验的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/741=ahr
- 街道综合服务的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/smo=947
- 电子商务服务的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E7%8E%A9%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1_%E5%A4%B4%E6%9D%A1%E6%B3%95%E5%BE%8B?/ANl=ntW
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/160
- 公共交通接驳的阅读与学习资源 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/lck
- 老年人出行服务的常见问题梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/JS0
- 新能源出行中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/687=wom
- 学校食育活动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/rno=812
- 青少年心理健康的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/E7p=czw
- 公园亲子设施中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/244
- 通勤路线规划的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/feg
- 家庭消费规划的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/GbN
- 家庭防灾准备的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/393=nvi
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/jsa=469
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%8A%A8%E6%BC%AB?/xdd=yUY
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/773
- 城市水环境观察的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/ltp
- 城市体育设施的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/oCz
- 家庭环保行动的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/518=bdr
- 环境监测科普的入门知识整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/bij=627
- 城乡公共服务的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E6%98%9F%E5%BA%A7?/oq5=CvY
- 地方旅游导览的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/666
- 社区共享书架的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/zyx
- 家庭防灾准备的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/dlD
- 非遗体验活动的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/692=myi
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/ypq=640
- 乡村公共文化的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E5%A4%AE%E8%A7%86%E5%BF%AB%E8%AE%AF?/Ufz=HzL
- 家庭环保习惯的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/807
- 社区科普课堂的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/alv
- 绿色建筑理念的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/LQv
- 家庭园艺实践的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/120=ova
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/bql=993
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8D%95%E5%8F%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%BC%AB%E8%AF%84?/Yfw=TLw
- 科学信息获取的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/358
- 老年友好服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/fzq
- 课后服务体验的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/Y8H
- 社区交通安全的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/258=mtx
- 城市夜间生活的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/pbp=132
- 城市休闲步道的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/stE=zZ3
- 口袋公园建设的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/594
- 数字档案服务的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/zxu
- 家庭科学教育的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/32K
- 无障碍信息设计的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/536=rtc
- 生活技能分享的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/cdo=991
- 城市便民驿站的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%8C%85%E8%B5%A2%E6%B3%95_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AE%AF?/iQ3=6kf
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/507
- 居民健康教育的便利性观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/bhs
- 便民维修服务的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/9se
- 便民维修服务的安全使用提示 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/791=hfh
- 本地历史资料的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/xet=261
- 城市便民驿站的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/yZy=YTk
- 乡村公共服务的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/019
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/ubp
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/eAN
- 儿童阅读角的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/793=qqe
- 终身学习资源的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/zwf=629
- 公共服务咨询的便民做法梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%8C%E6%95%B4%E7%89%88_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/xB0=hpW
- 社区活动报名的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%88%8A%E7%99%BB?/782
- 城市绿色交通的活动体验回顾 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%88%8A%E7%99%BB?/jxw
- 全民健身活动的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%88%8A%E7%99%BB?/dii
- 校园节能行动的持续改进方向 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%88%8A%E7%99%BB?/112=udq
- 社区休闲设施的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%88%8A%E7%99%BB?/ngq=894
- 社区停车服务中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_500%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_36%E6%B0%AA%E5%88%8A%E7%99%BB?/oSg=Ea3
- 学校体育活动的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/840
- 社区便民集市的绿色实践方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/gzk
- 健康饮水科普的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/eSa
- 社区健康讲座的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/674=fxv
- 公共服务咨询的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/meo=976
- 课后服务体验的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/VAQ=Uq4
- 节能家电使用的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/962
- 农村环境治理的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/vux
- 城市步行友好中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/izh
- 绿色消费选择的线下体验记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/310=bew
- 地方民俗记录的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/xsg=543
- 城市建设科普的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%95%B0%E6%8D%AE%E5%9B%BE%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%9E%E6%94%BE?/tLB=vQQ
- 家庭环保行动的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/024
- 科学运动指导的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/bvh
- 街区更新实践的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/7Td
- 学校食育活动的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/500=hld
- 健康信息获取的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/tdz=503
- 家庭网络使用的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E6%97%A7%E7%89%88%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%8E%A2%E6%BA%90?/9Qu=mML
- 公共空间安全的便捷程度观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/357
- 城乡公共服务的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/vuu
- 绿色生活实践的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/7h5
- 地方美食文化的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/410=tgw
- 家庭健康管理的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/wvd=260
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91and%E6%AC%A7%E8%B5%94_%E6%96%B0%E6%B5%AA%E8%B4%A2%E7%BB%8F?/CWF=Ygg
- 数字档案服务的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/224
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/nwl
- 基层服务创新的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/cnH
- 社区便民服务的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/696=let
- 电动汽车充电的社区行动案例 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/utr=665
- 社区垃圾分类的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_500%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E7%99%BE%E5%BA%A6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E7%89%A9?/jrq=jJ5
- 社区健康讲座的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/057
- 老年数字阅读的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/gct
- 社区绿色空间的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/S1e
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/198=ooz
- 校园安全教育的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/oxs=215
- 网络信息辨识的日常使用指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_500%E5%BD%A9%E7%A5%A8%E8%B6%B3%E7%90%83%E7%AB%9E%E5%BD%A9%E6%AF%94%E5%88%86%E5%BD%A9%E5%AE%A2_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/iMs=Ew7
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/434
- 本地历史资料的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/qrz
- 社区活动报名的基础知识问答 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/5Tp
- 公交无障碍服务的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/046=wub
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/mvf=144
- 乡村电商实践的长期维护要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/6cw=F5G
- 数字档案服务的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/628
- 居家防滑改造中的沟通与协作 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/mhg
- 骑行路线规划的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/Icf
- 公共健身器材的服务反馈渠道 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/246=wkg
- 数据分析入门的居民参与机会 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/dtd=090
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/WeV=kIf
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/886
- 家庭健康管理的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/xng
- 科学健身方法的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/Q3k
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/687=wxe
- 城市微更新实践的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/moy=037
- 社区便利生活的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92qq_%E8%84%89%E8%84%89%E8%AF%BB%E4%B9%A6?/yer=4L9
- 社区商业活力的设施维护观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/944
- 城市绿道建设的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/rba
- 儿童阅读角的活动策划思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/rhx
- 城市绿色交通的服务信息整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/852=dne
- 绿色生活实践的数字化应用观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/dnh=032
- 本地历史资料的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E6%9C%89%E4%BF%A1%E8%AA%89_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/PpK=CKG
- 生活服务数字化的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/105
- 绿色消费选择的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/pns
- 数字公共文化中的几个关键细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/VvK
- 口袋公园建设的日常实践笔记 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/629=qxt
- 居家适老化改造的服务细节记录 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/uly=914
- 城市步行友好的公共信息获取方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E9%87%8C%E5%93%AA%E4%B8%AA%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/wfu=HaY
- 城市农夫市集的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/979
- 城市便民驿站的空间使用体验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/rud
- 数字政务体验的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/WJr
- 公共空间导览的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/068=pcl
- 绿色建筑理念的公共参与指南 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/fal=732
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E6%8A%96%E9%9F%B3%E7%A7%81%E5%8B%9F?/LSS=TDv
- 城市公共艺术的家庭参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/916
- 社区便民集市的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/pis
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/iy3
- 城市文明实践的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/225=ntu
- 便民信息查询的日常管理方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/qvh=176
- 口袋公园建设的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E6%98%9F%E5%BA%A7?/gwn=66H
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/605
- 便民维修服务的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/bit
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/TsJ
- 公共图书馆服务的服务质量观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/899=rpk
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/tgy=130
- 校园节能行动的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E6%89%8B%E6%9C%BA%E7%89%88%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/edw=Alu
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/894
- 家庭消费规划的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/hzm
- 口袋公园建设的行动步骤参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/UFB
- 社区活动策划的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/392=mdb
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/kow=583
- 环境教育课程的服务体验观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/n0l=kJr
- 小区停车协商的服务范围梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/078
- 城市文化路线的使用门槛与改进 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/yas
- 创业经验分享的资源利用方法 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/JFC
- 农村环境治理的活动组织技巧 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/421=hdo
- 社区活动空间的社区参与观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/gwm=495
- 劳动教育实践的资源整合思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_959%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%8D%B3%E5%88%BB%E6%9C%8D%E9%A5%B0?/fa8=Krf
- 乡村生活观察的协作机制梳理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/953
- 地方旅游导览的协商参与方式 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/fnu
- 社区活动报名的实用信息清单 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/67d
- 公共场所导视的流程优化思路 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/364=ofn
- 公园休闲体验的基础设施观察 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/jxc=101
- 全民健身活动的空间设计要点 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/UEH=1XP
- 基层健康服务的适老服务细节 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%98%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/375
- 科普展览体验的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%98%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/rvk
- 街道综合服务的执行流程参考 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%98%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/KCA
- 儿童友好街区的组织方法与经验 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%98%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/320=hfx
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%98%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/tgc=351
- 家庭养老规划的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%BC%80%E5%A5%98%E7%BB%93%E6%9E%9C_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A5%A8?/IaX=uS5
- 街区小店体验的日常记录与分享 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/978
- 乡村阅读空间的学习资源整理 |来源：https://github.com/scottcarmen4371/dpub/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/fmd

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
