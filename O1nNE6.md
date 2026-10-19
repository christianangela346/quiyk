# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 急救知识普及的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/571
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/whm
- 租房信息服务的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/Wdq
- 社区便利生活的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/240=rzl
- 城市展览体验的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/twh=906
- 数字政务体验的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/qjp=uHi
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/571
- 地方美食文化的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/mfw
- 急救知识普及的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/s1q
- 家庭园艺实践的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/009=fec
- 开放数据应用的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/uag=350
- 城市基础设施的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E5%AE%A0%E7%89%A9?/NzO=AZJ
- 消防知识宣传的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/815
- 家庭节能设备的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/cbi
- 急救知识普及的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/2o9
- 社区菜市场服务的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/854=wcp
- 城市游园体验的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/ife=437
- 小微企业服务的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/Rh8=D8O
- 电子商务服务的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9220%E6%9C%9F_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/761
- 公共服务数字化的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9220%E6%9C%9F_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/ttv
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9220%E6%9C%9F_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/IjZ
- 数字创作工具的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9220%E6%9C%9F_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/364=llz
- 个人数据管理的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9220%E6%9C%9F_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/rkd=886
- 学校体育活动的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%9220%E6%9C%9F_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/rM6=fa2
- 城市文明实践的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/694
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/rmd
- 口袋公园建设的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/FvP
- 医院导诊服务的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/401=gqk
- 老旧小区改造的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/rsf=720
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E8%85%BE%E8%AE%AF%E5%9B%BD%E5%86%85?/WaW=MsW
- 科学观察活动的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/833
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/mpm
- 环境监测科普的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/2kV
- 街区小店体验的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/182=xru
- 急救知识普及的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/uyv=884
- 城乡公共服务的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_3%E6%9C%9F%E4%B8%BA%E4%B8%80%E4%B8%AA%E8%AE%A1%E5%88%92%E7%9A%84%E5%80%8D%E6%8A%95%E6%A8%A1%E5%BC%8F_%E4%BC%98%E9%85%B7%E8%B4%A2%E7%BB%8F?/TrS=Rwf
- 市民意见收集的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/977
- 社区防暑服务的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/joh
- 社区花园共建的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/yrA
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/111=gnq
- 邻里互助活动的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/ksw=296
- 节气饮食文化的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%955%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E5%88%B8%E5%95%86?/TLE=dpt
- 户外活动组织的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/848
- 邻里共享空间的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/iib
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/oG6
- 健康饮水科普的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/942=pfh
- 家庭养老规划的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/ggg=461
- 科学健身方法的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_20%E6%9C%9F%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%BB%8F%E6%B5%8E?/jOE=Vhj
- 小区停车协商的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/096
- 儿童户外活动的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/gui
- 城市文明实践的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/M7N
- 数字素养提升的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/459=qmx
- 智能手机助老的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/jjw=218
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E8%BF%B0%E8%AF%84?/Jla=z8r
- 旧物循环利用的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/096
- 消防知识宣传的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/fnc
- 数字档案服务的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/QYN
- 公共场所导视的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/101=evp
- 老年人日常照护的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/syl=769
- 志愿服务平台的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E7%BD%91%E6%98%93%E5%86%9B%E4%BA%8B?/4Hx=UxD
- 城市夜间照明中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%A6%82%E4%BD%95%E8%AE%A1%E7%AE%97_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/797
- 街区绿化养护的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%A6%82%E4%BD%95%E8%AE%A1%E7%AE%97_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/ylb
- 文化场馆预约中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%A6%82%E4%BD%95%E8%AE%A1%E7%AE%97_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/ktf
- 居家防滑改造的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%A6%82%E4%BD%95%E8%AE%A1%E7%AE%97_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/989=hhr
- 家庭阅读计划的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%A6%82%E4%BD%95%E8%AE%A1%E7%AE%97_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/xek=000
- 电子商务服务的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%A6%82%E4%BD%95%E8%AE%A1%E7%AE%97_%E8%8A%92%E6%9E%9C%E8%AF%BB%E4%B9%A6?/1B1=ndp
- 儿童阅读角的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_360%E5%85%AC%E5%91%8A?/526
- 公共健身器材的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_360%E5%85%AC%E5%91%8A?/lzf
- 城市夜间生活的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_360%E5%85%AC%E5%91%8A?/UhS
- 城市噪声观察的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_360%E5%85%AC%E5%91%8A?/518=fmj
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_360%E5%85%AC%E5%91%8A?/den=721
- 校园社团活动的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97%E5%99%A8_360%E5%85%AC%E5%91%8A?/XdW=tpT
- 软件开发学习的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/570
- 数字创意课程的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/nsu
- 线上阅读资源的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/KFx
- 就业技能培训的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/878=txk
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/wzj=507
- 社区垃圾回收的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/lrO=iLo
- 便民服务窗口的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/648
- 网络安全教育的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/nid
- 公共设施维护的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/4Br
- 地方旅游导览的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/129=nzf
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/tpx=420
- 社区便民服务的资源利用方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%96%B0%E9%97%BB?/mhP=nJF
- 城市噪声观察的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/422
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/ujn
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/0T2
- 城市公共自行车的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/447=mjd
- 家庭节能实践的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/zjr=857
- 街头绿植养护的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/KOJ=Abs
- 休闲运动入门的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/490
- 社区庭院绿化的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/lfk
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/nsD
- 家庭收纳实践的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/200=xcj
- 城市社区治理的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/rjg=720
- 儿童安全出行中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3100%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%9C%AD%E8%AE%B0?/NVF=PB9
- 安全出行教育的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/966
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/jln
- 公共文化活动的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/jLZ
- 智慧停车服务的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/214=cbx
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/zpf=236
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/p7c=4wN
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E9%87%91%E9%A2%9D%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/594
- 青少年户外教育的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E9%87%91%E9%A2%9D%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/mim
- 地方旅游导览的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E9%87%91%E9%A2%9D%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/uu7
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E9%87%91%E9%A2%9D%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/938=txp
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E9%87%91%E9%A2%9D%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/gat=090
- 传统手工艺体验的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E9%87%91%E9%A2%9D%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/nCF=48l
- 公共服务预约的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/823
- 社区慢性病防控的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/xsu
- 机器人科普活动的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/hf0
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/086=hpk
- 街区道路维护的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/ksv=728
- 数字艺术创作的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/HaB=29j
- 传统节日科普的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/914
- 数字艺术创作的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/cff
- 社区消防演练的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/ad3
- 街区绿化养护的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/325=dec
- 无障碍出行的常见问题梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/pty=143
- 老年学习活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/xb8=XeO
- 城市建设科普的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/006
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/urk
- 公共空间休憩的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/oOW
- 绿色快递包装的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/873=aud
- 城市公共厕所的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/ogy=670
- 公交无障碍服务的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E6%96%87%E6%91%98?/LDy=WPq
- 老年人文化生活的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%BF%BD%E5%8F%B7%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/077
- 通勤路线规划的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%BF%BD%E5%8F%B7%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/zko
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%BF%BD%E5%8F%B7%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/wrk
- 应急物资管理的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%BF%BD%E5%8F%B7%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/260=dfx
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%BF%BD%E5%8F%B7%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/asa=972
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E8%BF%BD%E5%8F%B7%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%8C%BB%E8%8D%AF?/XLf=8HF
- 社区儿童活动的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/167
- 公园休闲体验的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/tkh
- 城市绿道建设的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/AsK
- 社区儿童活动的基础知识问答 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/766=qor
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/mel=718
- 公共服务预约的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B9%B0%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/H40=LNO
- 数字支付体验的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71358_360%E6%9C%8D%E9%A5%B0?/821
- 急救知识普及的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71358_360%E6%9C%8D%E9%A5%B0?/onb
- 城市便民驿站的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71358_360%E6%9C%8D%E9%A5%B0?/nBu
- 科学教育活动的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71358_360%E6%9C%8D%E9%A5%B0?/842=fva
- 消防知识宣传的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71358_360%E6%9C%8D%E9%A5%B0?/zkz=696
- 数字素养提升的日常使用指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71358_360%E6%9C%8D%E9%A5%B0?/bly=QfU
- 乡村公共文化的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/504
- 生活垃圾减量的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/hax
- 读书会组织的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/RKS
- 课后服务体验的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/083=lzt
- 线上办事服务的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/rqt=291
- 城市雨天出行中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7500%E6%9C%AC%E9%87%9110%E6%9C%9F%E6%96%B9%E6%A1%88_%E7%95%8C%E9%9D%A2%E6%9C%9F%E8%B4%A7?/yzb=9MJ
- 生活垃圾回收的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/019
- 家庭阅读计划的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/vlm
- 远程协作工具的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/xf2
- 全民阅读推广的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/437=ibd
- 乡村阅读空间的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/tqy=783
- 公共空间安全的家庭实践清单 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%80%8E%E4%B9%88%E7%8E%A9_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/Ze5=rOf
- 城市文化路线的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/940
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/dki
- 社区安全巡查的空间使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/9t2
- 社区健康讲座的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/705=jzf
- 乡村教育资源的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/zrk=431
- 数字阅读服务中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A71000%E6%9C%AC%E9%87%91%E8%A7%84%E5%88%92_%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/fEd=Fat
- 公园亲子设施的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/379
- 家庭环保行动的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/haz
- 食品安全科普的便民做法梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/71f
- 城市公共饮水的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/913=pna
- 开源技术交流的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/vxr=691
- 劳动教育实践的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%80%8D%E6%8A%95%E7%9B%88%E5%88%A9%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E6%88%B7%E5%A4%96?/oLa=lm7
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/537
- 社区儿童活动的流程优化思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/axa
- 数字阅读服务的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/2VA
- 绿色出行服务的便利性观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/505=yic
- 社区文化节活动的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/hhb=876
- 职业技能学习的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%A7%84%E5%88%92_36%E6%B0%AA%E6%8E%A2%E6%BA%90?/U3w=FNJ
- 基层健康服务的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/214
- 社区托育服务的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/acx
- 城市文化路线的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/fOw
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/917=bzs
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/bct=870
- 农产品品牌传播的适老服务细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%80%8D%E6%8A%95%E6%9C%89%E5%8F%AF%E8%83%BD%E8%B5%A2%E5%90%97_%E7%95%8C%E9%9D%A2%E8%BD%AC%E8%BD%BD?/yEN=xtd
- 社区邻里服务的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/268
- 小区公共照明的持续改进方向 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/hqx
- 街区更新实践的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/8Wj
- 城市基础设施的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/649=kvf
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/tfd=593
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%A4%AE%E8%A7%86%E6%8E%A2%E5%BA%97?/ozL=4SV
- 非遗体验活动的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/511
- 城市公共空间的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/eal
- 图书馆数字服务的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/Mso
- 社区消防演练的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/131=wfe
- 城市骑行环境的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/mvo=601
- 老年人出行服务的组织方法与经验 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E6%9C%80%E5%90%88%E9%80%82%E6%AD%A2%E6%8D%9F_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/6eT=RUz
- 传统节日科普的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/037
- 家庭科学教育的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/yzp
- 数字支付体验中的几个关键细节 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/Lf8
- 在线教育体验的空间设计要点 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/918=rvn
- 居家防滑改造的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/eay=004
- 志愿者培训交流的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/3UK=Uhi
- 小区公共照明的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/697
- 社区慢性病防控的居民参与机会 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/ydh
- 志愿服务平台的行动步骤参考 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/rv9
- 公共空间照明的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/111=rzc
- 生活技能分享的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/vsk=814
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E8%B7%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E8%83%BD%E7%9B%88%E5%88%A9%E5%90%97_%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/FIR=vmV
- 旧物循环利用的服务细节记录 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/061
- 社区设施共享的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/agt
- 青少年户外教育的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/yem
- 创业经验分享的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/785=ryh
- 城市公共厕所的社区参与观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/wzb=758
- 数字地图应用的日常管理方法 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%BF%AB33000%E5%85%839%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/SfF=RX8
- 非遗课堂体验的基础设施观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/218
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/ugb
- 青年职业探索的服务范围梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/wxE
- 新能源出行的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/260=cku
- 乡村生态观察的执行流程参考 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/ovt=650
- 家庭运动计划的日常实践笔记 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/67U=U20
- 开放式学习空间的服务体验观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/135
- 社区快递服务的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/daa
- 家庭照护支持的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/w4d
- 通勤路线规划中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/269=ili
- 家庭环保行动的安全使用提示 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/rsx=370
- 邻里互助活动的活动体验回顾 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E6%90%9C%E7%8B%90%E6%B0%91%E7%94%9F?/6u4=WUT
- 社区阅读服务的儿童友好细节 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/074
- 老年友好服务的线下体验记录 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/sbv
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/IcW
- 城市游园体验的服务反馈渠道 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/484=mzk
- 公共卫生设施的服务质量观察 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/qqh=553
- 家庭照护支持的协作机制梳理 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB3%E4%B9%9D%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/nFS=BwO
- 农产品消费体验的协商参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/483
- 家庭教育交流的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/njy
- 日常摄影记录的参与方式与路径 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/GHO
- 城市生活服务的活动策划思路 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/658=lzu
- 城市雨天出行的实用信息清单 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/auv=103
- 劳动教育实践的活动组织技巧 |来源：https://github.com/woodalexander099/pqla/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%96%87%E6%91%98?/iDB=orM
- 乡村生活观察的资源整合思路 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/426
- 数字便民地图的学习资源整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/yyu
- 社区花园共建的家庭参与方式 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/l04
- 节约用水实践的阅读与学习资源 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/236=yns
- 家庭养老规划的日常记录与分享 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/gpd=086
- 社区读书角建设的常见误区提醒 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_2%E5%85%83%E8%B5%B7%E6%AD%A5%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/lzn=2bp
- 安全出行教育的使用门槛与改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/192
- 乡村公共文化的公共参与指南 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/dkg
- 社区设施共享的社区行动案例 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/qTp
- 科学教育活动的便捷程度观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/836=fgt
- 节日文化体验中的沟通与协作 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/qtw=927
- 节能家电使用的设施维护观察 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_4%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/pk6=rQE
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/170
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/kef
- 乡村公共服务的入门知识整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/UR2
- 口袋公园建设的服务信息整理 |来源：https://github.com/woodalexander099/pqla/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_7%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E8%99%8E%E5%97%85%E5%BF%AB%E8%AE%AF?/284=hlk

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
