# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 音乐欣赏活动的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/ovf=412
- 城市公共标识的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%8D%81%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/wqh=EX9
- 社区修缮行动的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/823
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/vpj
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/S9Q
- 青年职业探索的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/321=vzi
- 社区志愿服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/xey=172
- 地方文化传播的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%9B%BE%E9%89%B4?/Tl7=mjl
- 地方文化传播的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/636
- 小微企业服务的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/xfa
- 绿色出行服务的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/TQq
- 社区生活指南的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/604=duf
- 科普展览体验的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/ctm=288
- 数字艺术创作的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/UdQ=FpR
- 城市公共座椅的常见问题梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/912
- 农业科普体验的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/uie
- 家庭养老规划的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/fB0
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/917=qyg
- 非遗课堂体验的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/edj=756
- 家庭环保习惯的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E5%91%A8%E6%8A%A5?/Bbx=X53
- 绿色建筑理念的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/816
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/nsu
- 城市游园体验的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/e87
- 街头绿植养护的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/953=lno
- 城市共享单车的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/nyl=199
- 城市微更新实践的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%94%B6%E8%97%8F?/eZY=11N
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/607
- 社区家政服务的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/gsm
- 数字政务体验的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/mWf
- 家庭运动计划的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/009=gny
- 线上阅读资源的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/rvv=416
- 城市公共艺术的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/E6M=Fd9
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/059
- 社区家政服务的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/oql
- 公共服务预约的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/9XR
- 城市农夫市集的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/997=xtz
- 无障碍出行从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/moz=701
- 数字支付体验的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E5%86%85?/SM6=uzz
- 社区设施共享的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/936
- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/bka
- 公共空间安全的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/cEU
- 节日文化体验的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/863=vmi
- 节约用水实践的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/ahi=609
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/n9d=cGx
- 城市步行友好的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/096
- 基层健康档案的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/dsk
- 农业科普体验的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/94x
- 社区科普课堂的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/621=xxq
- 社区养老服务的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/gfd=326
- 城市文明出行的实际需求与回应 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%B0%91%E7%94%9F?/T9h=zjg
- 社区学习活动的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/426
- 儿童友好街区的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/rwv
- 青年志愿活动的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/gjj
- 家庭志愿活动的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/981=jze
- 全民阅读推广的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/sew=501
- 食品安全科普的家庭参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E8%80%81%E7%89%88_%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/TEb=HlV
- 校园社团活动的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/413
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/ukd
- 科学信息获取的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/MSu
- 城市夜间生活的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/362=tyz
- 家庭急救准备的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/yjs=013
- 校园节能行动的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/GLj=WaZ
- 节假日出行安排的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/009
- 社区宠物管理的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/int
- 志愿者培训交流的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/qS3
- 城市夜间照明的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/540=fnu
- 开源技术交流的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/cvn=839
- 城市适老服务的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/vze=5a3
- 社区活动策划的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/058
- 租房信息服务的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/dqn
- 社区文化传播的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/NKZ
- 运动安全知识的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/948=irf
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/met=222
- 开源技术交流的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%8F%8C%E8%89%B2%E7%90%83%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/5mQ=Qu9
- 青年职业探索的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/079
- 社区活动策划的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/ifj
- 儿童安全出行的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/3r3
- 社区协商议事的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/687=dus
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/ylj=888
- 社区家政服务的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%8F%8C%E8%89%B2%E7%90%83%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%8A%95%E7%A5%A8?/zGr=ksf
- 全民阅读推广中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/603
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/yfw
- 家庭运动计划的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/AlH
- 读书会组织的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/747=qvh
- 在线学习体验的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/uhw=066
- 职业技能学习的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E8%85%BE%E8%AE%AF3%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/ff9=4jy
- 公园亲子设施的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_360%E6%88%BF%E4%BA%A7?/117
- 家庭健康管理的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_360%E6%88%BF%E4%BA%A7?/cdc
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_360%E6%88%BF%E4%BA%A7?/3xv
- 街区更新实践的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_360%E6%88%BF%E4%BA%A7?/855=llf
- 乡村产业科普的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_360%E6%88%BF%E4%BA%A7?/tzl=530
- 老年人日常照护的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF5%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_360%E6%88%BF%E4%BA%A7?/bjc=R5d
- 数字档案服务的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/582
- 家庭网络使用的参与方式与路径 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/gtk
- 农村环境治理的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/q1J
- 健康饮水科普的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/951=xtb
- 节气饮食文化的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/ief=914
- 健康饮食教育的空间使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%95%99%E8%82%B2?/W31=STR
- 健康信息获取的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/556
- 校园节能行动的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/ljg
- 数字公共文化的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/EjG
- 城市公共座椅的空间设计要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/348=fsp
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/gbp=949
- 乡村阅读空间的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E8%85%BE%E8%AE%AF%E4%B8%89%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%AF%81%E5%88%B8%E8%B4%A2%E7%BB%8F?/Pe7=UPb
- 气象科普传播的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/350
- 城市夜间照明的便民做法梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/smk
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/4nS
- 老年人日常照护的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/893=vyj
- 文明养宠科普的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/igs=672
- 家庭教育交流的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E8%85%BE%E8%AE%AF%E4%B8%80%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/sk8=gQQ
- 城市游园体验的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/887
- 公共服务数字化的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/ynx
- 社区法律科普的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/a0x
- 社区协商议事的组织方法与经验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/175=gqt
- 社区便民服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/unq=703
- 老年人出行服务的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/XVl=Kjp
- 家庭运动计划的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/036
- 气象科普传播的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/qnx
- 社区休闲设施的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/bkd
- 社区儿童活动的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/284=dvf
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/tsq=260
- 社区故事采集的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E4%BA%94%E5%88%86%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/iai=dtX
- 数字学习资源的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/167
- 公园休闲体验的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/vnz
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zj0
- 小微企业服务的学习资源整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/705=ljl
- 数字资源检索的社区参与观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/hpb=843
- 社区活动报名的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%94%E5%88%86%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/eKN=OUH
- 终身学习资源的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/144
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/rdk
- 街区道路维护的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/b2T
- 街道综合服务的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/899=zwa
- 儿童安全出行的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/zpn=498
- 乡村生态观察的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BD%A9%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/YzT=pxs
- 家庭网络使用的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/662
- 科学教育活动的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/ita
- 社区消防演练的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/p5q
- 智能家居应用的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/331=whk
- 城市文明实践的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/vik=191
- 社区手工活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E4%B8%8B%E8%BD%BD3d%E5%BD%A9%E7%A5%A8%E7%BD%91_%E7%BD%91%E6%98%93%E4%BF%A1%E8%B4%B7?/uQ5=Px0
- 科学健身方法的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/512
- 个人时间管理的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/myr
- 儿童安全出行的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/geq
- 青年志愿活动的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/841=rry
- 网络信息辨识的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/phk=571
- 公共文化活动的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8F%8C%E8%89%B2%E7%90%83_%E7%99%BE%E5%BA%A6%E4%B9%A6%E7%94%BB?/ZJU=v2D
- 科学运动指导的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/078
- 老年智能设备的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/iis
- 城市文化路线的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/gMQ
- 公共设施使用的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/284=elh
- 个人数据管理的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/bhd=603
- 生活垃圾回收的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E4%B8%AA%E7%A6%8F%E5%BD%A93d_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/QIM=Fss
- 社区设施共享的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/191
- 旧物循环利用中的沟通与协作 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/dqx
- 市民热线服务的线下体验记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/Rib
- 街区道路维护的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/033=xgr
- 食品安全科普的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/jtq=893
- 户外活动组织的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%97%A7%E7%89%88%E5%8F%8C%E8%89%B2%E7%90%83_%E7%BE%8E%E5%9B%BD%E8%B4%A2%E7%BB%8F?/mfn=tp0
- 青少年科普实践的儿童友好细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/708
- 家庭运动计划的数字化应用观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/onb
- 社区运动空间的服务质量观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/MtK
- 公共服务预约的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/321=gig
- 数字学习资源的便利性观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/iee=853
- 社区托育服务的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E4%B8%8B%E8%BD%BD%E8%80%81%E6%AC%BE%E5%8F%8C%E8%89%B2%E7%90%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%9B%98%E7%82%B9?/oEz=Or3
- 社区老年食堂的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/192
- 城市应急广播的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/plw
- 青少年科普实践的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/jnc
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/710=vwb
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/kru=782
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975%E5%A5%96%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/L9r=b65
- 开放数据应用的家庭实践清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/431
- 志愿者培训交流的流程优化思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/csr
- 环境教育课程的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/rKz
- 农贸市场环境的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/699=omu
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/ogp=873
- 城市公共空间的持续改进方向 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89%E9%A2%84%E6%B5%8B_%E8%8A%92%E6%9E%9C%E8%A7%82%E5%AF%9F?/4yk=LP4
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/399
- 社区停车服务的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/xev
- 社区体育组织的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/8aT
- 城市生活记录的协作机制梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/975=hod
- 社区活动报名的入门知识整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/dpb=597
- 基层健康服务的公共参与指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%BA%94%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E7%89%B9%E7%A8%BF?/lLh=Qfs
- 开源技术交流的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/482
- 社区生活指南的使用门槛与改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/nzp
- 地方美食文化的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/hPG
- 职业技能学习的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/524=bxx
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/sus=649
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%94%BF%E7%AD%96?/alt=rEs
- 骑行路线规划的服务范围梳理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/220
- 数字政务体验的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/zig
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/Cl8
- 生活服务数字化的适老服务细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/209=iks
- 城市人文观察的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/wwr=936
- 校园节能行动的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%8F%8C%E8%89%B2%E7%90%83%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%9A%E6%8A%A5?/D5g=BSM
- 城市绿色交通的线上线下服务衔接 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/313
- 社区慢性病防控的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/kcg
- 健康步道使用的执行流程参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/KzV
- 科学信息获取的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/487=hsx
- 就业技能培训的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/sdt=875
- 城市公共艺术的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/X3L=b2Q
- 公共空间休憩的日常记录与分享 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%973_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/255
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%973_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/roj
- 公共卫生宣传的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%973_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/PNN
- 公共服务指南的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%973_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/004=fmm
- 社区便民集市的数字工具使用体验 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%973_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/hoe=801
- 邻里共享空间的服务细节记录 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E4%BD%93%E5%BD%A9%E6%8E%92%E5%88%973_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/9lK=1Mt
- 社区商业活力的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/369
- 农业科普体验的基础设施观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/xaq
- 儿童户外活动的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/cx2
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/225=gsg
- 网络信息辨识的协商参与方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/fqq=147
- 小微企业服务的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%99%BE%E7%A7%91?/vPz=Fo0
- 社区老年食堂的资源整合思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%8D%81%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/005
- 社区商业活力的活动策划思路 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%8D%81%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/ght
- 软件开发学习的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%8D%81%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/PKW
- 社区停车服务的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%8D%81%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/020=hzk
- 家庭志愿活动的服务信息整理 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%8D%81%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/zci=290
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%8D%81%E5%88%86%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/kmn=b54
- 公共空间照明的常见误区提醒 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB%E4%B9%908_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/931
- 绿色办公实践的活动组织技巧 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB%E4%B9%908_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/bup
- 数字阅读服务的日常使用指南 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB%E4%B9%908_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/XOP
- 节气饮食文化的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB%E4%B9%908_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/487=bzx
- 社区公共卫生的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB%E4%B9%908_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/mti=054
- 社区文化传播的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%80%8E%E6%A0%B7%E4%B8%8B%E8%BD%BD%E5%BF%AB%E4%B9%908_%E8%8A%92%E6%9E%9C%E6%8E%A2%E5%BA%97?/jff=X5p
- 社区体育组织的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%895%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/584
- 家庭教育交流的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%895%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/qxf
- 节约用水实践的社区行动案例 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%895%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/uIq
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%895%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/634=mvj
- 数字素养提升的服务体验观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%895%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/pbt=001
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%895%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/r7l=WLF
- 家庭安全提示的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_11%E9%80%895%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/781
- 城市微更新实践有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_11%E9%80%895%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/tio
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_11%E9%80%895%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/c1l
- 城市文化路线的基础知识问答 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_11%E9%80%895%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/424=jsz
- 机器人科普活动的居民参与机会 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_11%E9%80%895%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/zjj=318
- 社区阅读服务的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_11%E9%80%895%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%97%B6%E5%B0%9A?/pzR=vxG
- 老年运动活动的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_11%E9%80%895%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/288
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_11%E9%80%895%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/qdq
- 老年智能设备的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_11%E9%80%895%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/Oln
- 药品使用科普的资源利用方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_11%E9%80%895%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/571=cyh
- 绿色办公实践的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_11%E9%80%895%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/nci=036
- 环境监测科普的长期维护要点 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_11%E9%80%895%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E8%AE%BA%E5%9D%9B?/tT1=5Xj
- 城市文明出行的实用信息清单 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/535
- 节能生活方式的行动步骤参考 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/zqr
- 电动汽车充电的日常实践笔记 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/Awt
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/957=ccg
- 节日文化体验的安全使用提示 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/wxt=157
- 社区公共卫生的设施维护观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_11%E9%80%89%E4%BA%94%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%83%E5%B8%86?/BNY=iD0
- 数字艺术创作的日常管理方法 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_1%E5%88%8611%E9%80%895%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/418
- 城市文明出行的便捷程度观察 |来源：https://github.com/marshalljustin434/ffvj/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_1%E5%88%8611%E9%80%895%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/bgf

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
