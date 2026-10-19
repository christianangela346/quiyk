# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 学校食育活动的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/Z3q
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/601=iah
- 城市游园体验的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/wii=954
- 家庭节能实践的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%87%A4%E5%87%B0%E6%B1%BD%E8%BD%A6?/KY0=0KD
- 运动安全知识的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%BA%81pp%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/344
- 街头绿植养护的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%BA%81pp%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/goo
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%BA%81pp%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/UNy
- 城市适老服务中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%BA%81pp%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/147=hng
- 社区托育服务的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%BA%81pp%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/hiw=427
- 个人时间管理的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%A4%A7%E5%BA%81pp%E5%AE%98%E6%96%B9%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%97%B6%E8%AE%AF?/EjN=ySs
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/124
- 社区托育服务中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/zhf
- 公共空间安全的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/L6N
- 邻里共享空间的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/450=cra
- 城市绿道建设的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/mhz=379
- 街区更新实践的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BE%B7%E5%BD%A9%E7%BD%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/zHB=JkX
- 乡村电商实践的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/314
- 社区应急准备的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/nbj
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/k43
- 城市文化路线的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/317=ory
- 社区垃圾回收的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/iaf=379
- 城乡交流活动的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BE%B7%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/iRF=1uY
- 科普展览体验的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/651
- 数字学习资源的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/mdv
- 数字创意课程的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/Jlj
- 社区互助网络的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/446=eom
- 数据分析入门的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/hjg=318
- 城市共享单车的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/Dyv=wXg
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/622
- 本地历史资料的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/tva
- 本地消费场景的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/TRO
- 城市社区治理从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/050=hoe
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/uev=536
- 地方文化传播的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BE%B7%E5%BD%A9%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%88%BF%E4%BA%A7?/RxT=PTA
- 本地消费场景的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/051
- 智能家居应用的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/cau
- 街头绿植养护的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/BY4
- 数字创意课程中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/830=vac
- 城市步行友好中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/jim=919
- 全民阅读推广的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_52888%E5%BE%B7%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/3rL=djb
- 校园阅读活动的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/533
- 社区教育资源的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/lfq
- 街区更新实践的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/Hk9
- 健康饮水科普的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/041=afl
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/ija=292
- 社区故事采集的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/MHG=t1A
- 社区信息发布的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%9A%E5%BB%BA?/585
- 社区便民服务的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%9A%E5%BB%BA?/wwu
- 家庭科学教育的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%9A%E5%BB%BA?/gka
- 社区修缮行动的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%9A%E5%BB%BA?/539=wyc
- 个人数据管理的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%9A%E5%BB%BA?/ltu=503
- 数字创意课程的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%85%9A%E5%BB%BA?/mGW=4xM
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/140
- 街道综合服务的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/dcb
- 儿童运动体验的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/gSY
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/591=xtv
- 小区电梯维护的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/phg=490
- 数字阅读服务的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%99%9A%E6%8A%A5?/p8g=CFH
- 社区绿色空间的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/230
- 社区庭院绿化的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/bsu
- 数字设备回收的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/AUl
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/153=wjo
- 公共空间导览的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/sra=178
- 城市噪声观察的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%88%9B%E6%8A%95?/6Hf=zCg
- 城市骑行环境中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/879
- 城市农夫市集的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/umq
- 社区科普课堂的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/f8s
- 数字创意课程的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/519=vla
- 数字档案服务的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/xjp=148
- 租房信息服务中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_welcometo%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%9E%81%E9%80%9F%E7%89%88_%E8%B1%86%E7%93%A3%E5%86%9B%E4%BA%8B?/xKZ=MJ4
- 居民健康教育的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/037
- 口袋公园建设的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/swe
- 社区学习活动的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/Xhj
- 劳动教育实践的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/691=oia
- 低碳社区实践中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/htz=679
- 城市展览体验的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E9%94%90%E8%AF%84?/i2E=uPf
- 社区绿色空间的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/207
- 社区防暑服务的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/fju
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/e5V
- 城市博物馆活动的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/802=dih
- 城市适老服务的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/tec=723
- 社区志愿服务的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%9C%9F%E8%B4%A7?/yTH=6k0
- 城市噪声观察的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/151
- 青少年科技社团的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/azn
- 文明养宠科普的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/JVJ
- 老年友好服务的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/781=kcu
- 个人数据管理的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/rrt=956
- 乡村生活观察的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E4%B8%9C%E6%96%B9%E4%BA%91%E5%BD%A9%E7%A5%A8welcome%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/hDZ=4IS
- 社区公共卫生的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/109
- 数字地图应用的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/deu
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/QiC
- 家庭教育交流的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/449=opf
- 社区宠物管理有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/ivl=989
- 社区养老服务的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-welcome%E7%99%BB%E5%BD%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%BA%E9%87%91?/BwG=mo6
- 公共图书馆服务的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/375
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/oej
- 邻里共享空间的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/2cC
- 乡村公共服务的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/615=yku
- 城市应急广播的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/aat=980
- 家庭教育交流的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%A5%BD%E5%BD%A9welcome%E7%99%BB%E9%99%86_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/Mt6=uZ6
- 社区互助网络的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/781
- 老年智能设备的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/cio
- 街区道路维护的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/mug
- 家庭饮食安排的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/740=sse
- 科学观察活动的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/zzs=604
- 地方民俗记录的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/SMl=GJD
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/036
- 社区便民集市的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/jds
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/Wkc
- 地方民俗记录的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/540=hny
- 城市绿色交通的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/fwz=500
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%86%9B%E4%BA%8B?/blz=fiB
- 家庭节能设备的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/380
- 科学观察活动的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/blk
- 城市地名文化的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/9Fi
- 家庭志愿活动的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/425=vkr
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/ewv=324
- 城市地名文化的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%AF%8C%E4%B9%90%E6%B1%87%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/f6p=SBE
- 周末休闲规划的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/148
- 线上阅读资源的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/shl
- 新能源出行从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/jxV
- 公共卫生宣传的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/210=wko
- 无障碍信息设计的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/bor=066
- 青年志愿活动的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_9123%E5%A5%BD%E5%BD%A9%E8%8B%B9%E6%9E%9C%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/xy9=MNf
- 乡村教育资源的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/792
- 公园无障碍服务的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/rxc
- 开放数据应用的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/7AD
- 网络安全教育的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/892=xty
- 科学教育活动的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/gkt=339
- 老年数字阅读的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E5%A5%BD%E5%BD%A99123%E5%A4%A7%E5%8F%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%95%B0%E8%AF%BB?/s7t=pXQ
- 公共交通接驳的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/082
- 光伏知识科普的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/lqz
- 智能手机助老的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/MQY
- 家庭收纳实践的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/431=goi
- 数字地图应用的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/iwx=056
- 社区停车服务的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%90%89%E5%BD%A9%E7%BD%91%E7%AB%99_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/t0T=xYj
- 职业技能学习的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/750
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/zdl
- 数字阅读服务的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/Tfy
- 乡村电商实践的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/791=kow
- 社区知识分享的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/dgd=108
- 社区便民集市的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%AE%9E%E5%BD%95?/aip=En5
- 青少年科技社团的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/376
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/rhx
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/jDe
- 邻里共享空间的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/631=phk
- 全民阅读推广中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/hbj=596
- 数字创意课程的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E9%87%91%E6%B1%87%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/DBY=JSC
- 图书借阅体验的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/274
- 光伏知识科普的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/lvh
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/reA
- 文明养宠科普的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/011=xtf
- 数字创意课程的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/bws=149
- 公共服务评价的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E6%B1%87%E5%BD%A9_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/X8S=JA8
- 无障碍出行的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/787
- 城市公共标识的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/wvh
- 气象科普传播的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/r0k
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/987=blg
- 家庭网络使用中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/uvw=478
- 科学信息获取的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E9%87%91%E6%B1%87%E5%BD%A9%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%BB%8F%E6%B5%8E?/h62=nQI
- 机器学习入门的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/752
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/tze
- 软件开发学习的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/cup
- 青少年心理健康的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/861=tfl
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/crf=464
- 城市步行友好的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E6%B1%87%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%8A%95%E7%A8%BF?/GjK=W7X
- 急救知识普及的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/125
- 休闲运动入门的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/yyo
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/a56
- 急救知识普及的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/698=izr
- 社区便民集市的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/hzj=411
- 亲子科普活动的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E9%87%91%E6%B1%87%E5%BD%A9APP%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/YGU=GgZ
- 城市文明实践的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/799
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/uzh
- 电子商务服务的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/YFH
- 城市慢跑路线的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/407=kwr
- 数字创作工具的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/etc=100
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/iUu=vHh
- 家庭消费规划的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_360%E6%99%9A%E6%8A%A5?/418
- 青少年户外教育的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_360%E6%99%9A%E6%8A%A5?/hxb
- 物业服务沟通的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_360%E6%99%9A%E6%8A%A5?/KHn
- 生成式工具使用的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_360%E6%99%9A%E6%8A%A5?/638=fcj
- 数字地图应用的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_360%E6%99%9A%E6%8A%A5?/ait=108
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%93%8D%E4%BD%9C%E6%95%99%E7%A8%8B_360%E6%99%9A%E6%8A%A5?/Pvk=kui
- 乡村生态观察的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/899
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/tfi
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/4Ca
- 农业科普体验的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/618=rtm
- 城市住房服务的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/pvg=483
- 智慧停车服务的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3?/Dod=cry
- 节日文化体验的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/848
- 亲子阅读活动的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/fxl
- 社区信息发布的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/5mc
- 儿童友好街区的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/795=pwp
- 城市应急科普的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/lvl=261
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%88%B7%E7%AB%AF_%E5%BE%97%E7%89%A9%E5%AE%89%E9%98%B2?/UJh=pDR
- 数字公共文化的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/876
- 小微企业服务的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/edm
- 在线学习体验的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/uhb
- 居民健康教育的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/370=ydk
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/wxp=009
- 城市公共艺术的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/liR=7qM
- 社区停车服务的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/476
- 社区手工活动的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/quz
- 家庭饮食安排的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/ZKG
- 儿童友好空间的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/137=mgs
- 社区安全巡查的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/had=364
- 城市绿色交通的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8-app-%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%96%B0%E6%B5%AA%E8%BD%AC%E8%BD%BD?/lSq=241
- 基层健康档案的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/706
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/kgx
- 公共文化活动的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/MRD
- 社区故事采集的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/601=lpf
- 社区休闲设施的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/gfv=238
- 社区庭院绿化的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8_%E7%84%A6%E7%82%B9%E8%B4%A2%E7%BB%8F?/gT9=0FJ
- 个人数据管理的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/798
- 文明养宠科普的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/mpd
- 学校食育活动的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/oED
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/383=jcu
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/dup=415
- 城市适老服务的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF?/OB3=qVA
- 开源技术交流的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/475
- 应急物资管理的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/lix
- 城市夜间照明中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/SvB
- 城市微更新实践的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/837=ibi
- 青少年编程学习的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/ebv=612
- 社区应急准备的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E4%B9%85%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E5%A6%86?/wAv=0gI
- 青年志愿活动的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/899
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/qha
- 绿色校园实践的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/Exc
- 老年人出行服务的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/205=wpn
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/loc=173
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%AF%BB%E5%9B%BE?/d9U=56A
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/161
- 城市公共厕所的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/eld
- 公交无障碍服务的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/o9d
- 物业服务沟通的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/187=mjp
- 绿色校园实践的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/knt=820
- 家庭节能设备的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%81%A5%E8%BA%AB?/55N=Gvv
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/095
- 公共文化活动的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/qqy
- 非遗体验活动的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/Ep9
- 街区绿化养护的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/027=ljt
- 小微企业服务的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/jrv=601
- 数字课堂应用的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BC%80%E5%BF%83%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%8A%A8%E6%BC%AB?/Cec=xEL
- 智慧城市体验的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%96%87%E5%8C%96?/173
- 家庭消费规划的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%96%87%E5%8C%96?/gcw
- 居民健康教育的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%96%87%E5%8C%96?/QyO
- 地方旅游导览的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%96%87%E5%8C%96?/787=nas
- 科学运动指导的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%96%87%E5%8C%96?/usb=849
- 家庭食品保存的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%BC%80%E5%BF%83100%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E6%96%87%E5%8C%96?/FYs=mPa

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
