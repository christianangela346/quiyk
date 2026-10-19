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

- 骑行路线规划的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_2024%E5%B9%B4%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/lpt=644
- 图书借阅体验的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_2024%E5%B9%B4%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_36%E6%B0%AA%E6%97%A5%E6%8A%A5?/xqi=jlX
- 乡村教育资源的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_360%E8%AE%BA%E5%9D%9B?/026
- 健康步道使用的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_360%E8%AE%BA%E5%9D%9B?/jwh
- 数字学习资源的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_360%E8%AE%BA%E5%9D%9B?/Vnq
- 地方戏曲体验的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_360%E8%AE%BA%E5%9D%9B?/955=kwv
- 城市应急广播的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_360%E8%AE%BA%E5%9D%9B?/nvl=661
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB35%E5%88%86%E9%92%9F%E4%B8%80%E6%9C%9F%E8%AE%A1%E5%88%92_360%E8%AE%BA%E5%9D%9B?/U5i=9w0
- 劳动教育实践的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/562
- 社区便利生活的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/qsr
- 绿色消费选择的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/T1Q
- 青少年编程学习中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/823=hgg
- 读书会组织的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/uhb=382
- 数字课堂应用的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E8%99%8E%E5%97%85%E6%95%B0%E8%AF%BB?/2CG=UCG
- 城市应急科普的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/483
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/sax
- 城市公共厕所的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/yg4
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/827=jxc
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/cfi=831
- 环境教育课程的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A3%E7%89%88%E5%85%8D%E8%B4%B9_%E9%9B%85%E8%99%8E%E4%BA%BA%E5%A4%A7?/qNv=5GV
- 城市社区治理的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/467
- 社区公共议事的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/xhr
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/0su
- 非遗课堂体验的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/486=txc
- 社区公共卫生的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/ctf=501
- 家庭运动计划的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%9C%80%E5%87%86_%E9%A1%BA%E4%B8%B0%E5%8D%9A%E5%AE%A2?/3qw=R5S
- 社区绿色空间的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/425
- 社区生活指南的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/fcb
- 社区活动策划的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/VzL
- 绿色消费选择的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/786=did
- 机器学习入门的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/nma=317
- 社区活动空间的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/qvc=JXl
- 街头绿植养护的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/771
- 城市文化路线的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/znm
- 青少年科普实践的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/YWz
- 青少年心理健康的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/771=wff
- 课后服务体验中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/ruu=347
- 城市博物馆活动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%BD%A9%E5%8D%9A%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/fU5=2kz
- 社区安全巡查的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/842
- 职业技能学习中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gvm
- 应急物资管理的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/LcQ
- 校园安全教育的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/643=vss
- 食品安全科普的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/oie=134
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%97%A0%E9%99%90%E9%92%BB%E7%9F%B3%E7%89%88%E6%9C%80%E6%96%B0%E7%AB%A0%E8%8A%82%E5%88%97%E8%A1%A8_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/bUR=Vo1
- 城市公共空间的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/984
- 社区便民集市的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/khi
- 文明养宠科普的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/OIn
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/099=iku
- 社区交通安全的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/czk=782
- 城市博物馆服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E6%9C%BA%E7%89%88%E5%86%85%E7%BD%AE%E8%8F%9C%E5%8D%95%E7%89%88_%E7%95%8C%E9%9D%A2%E7%90%86%E8%B4%A2?/tdQ=xfx
- 社区家校合作的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/366
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/wfl
- 健康饮食教育的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/737
- 旧物循环利用的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/795=mow
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/yko=675
- 公共健身器材的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/v8Z=ySk
- 社区读书角建设的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/892
- 公共服务评价的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/chq
- 公共交通接驳中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/Cib
- 图书馆数字服务的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/015=fzw
- 城市公共自行车的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/ubj=750
- 绿色消费选择的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_666%E6%9C%80%E6%96%B0%E7%89%88%E5%BD%A9%E7%A5%A8app_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/dda=P50
- 开源技术交流的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/468
- 生活服务数字化的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/orw
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/ned
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/644=gql
- 社区生活指南的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/iic=977
- 城市公共厕所的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_767%E5%A8%B1%E4%B9%909767%E5%BD%A9%E7%A5%A83.0.0%E7%89%88%E6%9C%AC%E8%AF%84%E6%B5%8B_%E5%8D%B3%E5%88%BB%E4%BD%93%E8%82%B2?/ZvP=U2K
- 公共服务沟通的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_369cc%E5%BD%A9%E7%A5%A8app_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/719
- 绿色生活实践的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_369cc%E5%BD%A9%E7%A5%A8app_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/pkc
- 科普展览体验的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_369cc%E5%BD%A9%E7%A5%A8app_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/4KT
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_369cc%E5%BD%A9%E7%A5%A8app_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/857=ekj
- 老年学习活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_369cc%E5%BD%A9%E7%A5%A8app_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/bth=063
- 生活垃圾减量的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_369cc%E5%BD%A9%E7%A5%A8app_%E5%BE%97%E7%89%A9%E5%91%A8%E6%8A%A5?/4Ra=CVZ
- 社区家校合作中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/168
- 小微企业服务的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/ebu
- 公共服务预约的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/SfD
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/979=xez
- 公共交通接驳的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/rai=063
- 文化场馆预约的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8%C2%B7cn_%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/cZ3=r2j
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/464
- 公共交通接驳的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/vwm
- 老年人文化生活的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/0wx
- 食品安全科普的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/223=vry
- 健康信息获取的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/lcb=186
- 社区安全巡查的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_959cc%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BD%AC%E8%BD%BD?/8z8=Ei8
- 生活技能分享的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/752
- 生成式工具使用中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/jim
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/wNO
- 社会体育指导的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/406=wdb
- 城市空气科普的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/wry=073
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E6%B3%A8%E5%86%8C%E9%80%8118%E5%BD%A9%E9%87%91%E7%BD%91_%E6%99%A8%E9%97%B4%E8%B4%A2%E7%BB%8F?/zKx=lfd
- 社区交通安全的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/768
- 智慧停车服务的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/qnp
- 城市步行环境的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/WQ3
- 城乡公共服务的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/536=bma
- 地方美食文化中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/jir=639
- 绿色办公实践的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%8118%E5%85%83%E5%BD%A9%E9%87%91_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/t3g=3jQ
- 通勤路线规划中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/525
- 公共服务咨询的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/ttc
- 城市水环境观察的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/eD7
- 社区防暑服务的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/395=emm
- 地方文化传播的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/djd=883
- 城市文化路线的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8app%E9%80%81%E5%BD%A9%E9%87%9138%E5%85%83%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%84%E8%AE%BA?/dZQ=Lew
- 生活垃圾回收的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/170
- 农产品消费体验从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/mio
- 文化讲座服务的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/P10
- 居民健康教育的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/951=gpw
- 基层医疗预约的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/hvw=656
- 数字课堂应用的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99app_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/HAa=njj
- 农产品品牌传播中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/511
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jmz
- 街道综合服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/1Ki
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/261=xvk
- 社区养老服务的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/yny=334
- 公共服务预约的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E8%B6%B3%E7%90%83_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/bHh=v7Y
- 家庭食品保存的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/355
- 社区活动报名的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/zee
- 家庭防灾准备的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/yC8
- 在线教育体验的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/780=lvk
- 社区手工活动的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/pby=551
- 户外活动组织的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E6%AD%A3%E7%89%88%E5%BD%A9%E8%99%B9%E5%A4%9A%E5%A4%9A_%E7%95%8C%E9%9D%A2%E5%AE%A0%E7%89%A9?/WpK=UMa
- 休闲运动入门的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/150
- 农贸市场环境中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/edi
- 数字政务体验的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/Swm
- 运动安全知识的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/877=pec
- 社区家政服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/tss=561
- 城市骑行环境的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_Dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%80%BA%E5%B8%82?/eXb=N4I
- 基层服务创新的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_360%E5%AE%89%E9%98%B2?/750
- 社区科普课堂的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_360%E5%AE%89%E9%98%B2?/dzw
- 社区信息发布的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_360%E5%AE%89%E9%98%B2?/x1c
- 城市绿道建设的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_360%E5%AE%89%E9%98%B2?/448=tjv
- 家庭节能实践的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_360%E5%AE%89%E9%98%B2?/scq=054
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%A4%A7%E5%85%A8app_360%E5%AE%89%E9%98%B2?/Fbx=d7b
- 乡村产业科普的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/261
- 光伏知识科普的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/dbs
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/9kd
- 城市树木认养的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/789=his
- 城市生活服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/hsc=754
- 社区阅读服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%94%AF%E4%B8%80%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E5%8D%9A%E5%AE%A2?/FJ7=Wvr
- 城市文化路线的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/373
- 社区防暑服务的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/alt
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/Yqn
- 社区庭院绿化的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/930=ssh
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/sgs=063
- 社区设施共享的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_797%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/JgD=nqB
- 本地历史资料的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/712
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/gzk
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/sN7
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/286=lie
- 绿色建筑理念的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/qcm=141
- 小区公共照明的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%8158%E5%85%83%E5%BD%A9%E9%87%91%E7%BD%91%E7%AB%99_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/MIC=huN
- 数字支付体验的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/805
- 社区文化节活动的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/nqh
- 健康饮水科普的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/y7X
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/517=xef
- 城市休闲步道的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/lyz=492
- 城乡交流活动的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_785%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/Cyd=jnF
- 街区小店体验的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/534
- 地方旅游导览的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/dps
- 城市噪声观察的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/IwI
- 生活技能分享的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/376=wsr
- 公共卫生宣传的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/uek=734
- 数字地图应用的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6ios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%B4%E6%92%AD?/8HM=LBQ
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/096
- 低碳社区实践的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/ucg
- 在线学习体验的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/QOd
- 新能源知识普及中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/934=egk
- 节气饮食文化的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/jhn=643
- 街区绿化养护的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%8B%B9%E6%9E%9C%E6%AD%A3%E8%A7%84%E5%AE%98%E6%96%B9%E7%BD%91%E5%BD%A9%E7%A5%A8app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%A5%E6%8A%A5?/qt4=B9a
- 居民健康教育的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/853
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/lhl
- 文明养宠科普的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/zsL
- 机器学习入门的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/565=wdg
- 亲子阅读活动的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/hou=640
- 公共图书馆服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_365%E4%BA%9A%E6%B4%B2%E5%94%AF%E4%B8%80%E5%AE%98%E7%BD%91%E5%BD%A9%E7%A5%A8_%E7%90%86%E8%B4%A2%E8%B4%A2%E7%BB%8F?/eFg=cjQ
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB?/004
- 公益活动组织的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB?/hum
- 城市生活服务的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB?/5yw
- 城市水环境观察的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB?/711=nxh
- 社区庭院绿化的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB?/dlh=781
- 城市微更新实践的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8app%E8%8B%B9%E6%9E%9C%E7%89%88%E5%9C%A8%E7%BA%BF%E5%AE%89%E8%A3%85_%E5%8D%B3%E5%88%BB?/e8G=tuF
- 食品安全科普的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/230
- 家庭用电安全的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/pjg
- 家庭饮食安排的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/lIl
- 社区垃圾分类的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/915=rhn
- 社区艺术活动的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/ack=848
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E8%8B%B9%E6%9E%9C%E7%89%88app%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E4%B9%A6%E7%94%BB?/vxy=nGf
- 城市游园体验的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/225
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/rqg
- 骑行路线规划的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/8wW
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/409=zwr
- 公园亲子设施的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/dli=274
- 家庭网络使用的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E4%B8%8A%E8%AE%A2%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/A3L=kFh
- 数字阅读服务的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/434
- 公共文化活动的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/uld
- 数字学习资源的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/kq4
- 农村环境治理的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/035=dst
- 社区绿色空间的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/ycg=653
- 社区垃圾回收的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_288cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/lGn=lWq
- 城市住房服务的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8c9com%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/423
- 气象科普传播的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8c9com%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/jkx
- 城市公共空间的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8c9com%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/5H0
- 全民健身活动的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8c9com%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/804=ogl
- 个人时间管理的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8c9com%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/kcj=553
- 科学健身方法的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8c9com%E8%8B%B9%E6%9E%9C_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/R63=uoi
- 城市运动公园的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%881.0.0_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/847
- 本地历史资料的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%881.0.0_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/ync
- 青少年科普实践的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%881.0.0_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/KIh
- 科学运动指导的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%881.0.0_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/538=ljx
- 儿童阅读角的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%881.0.0_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/iyt=494
- 无障碍信息设计的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%881.0.0_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/Dqj=IAn
- 社区活动策划的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88-%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E7%AD%96?/797
- 绿色生活实践的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88-%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E7%AD%96?/kpt
- 社区互助网络的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88-%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E7%AD%96?/rks
- 智慧停车服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88-%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E7%AD%96?/349=paw
- 社区知识分享的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88-%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E7%AD%96?/uzj=569
- 家庭防灾准备的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88-%E8%BD%AF%E4%BB%B6_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%BF%E7%AD%96?/A4f=cH8
- 家庭节能实践的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%89%E5%8D%93%E7%89%88app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/480
- 智能家居应用的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%89%E5%8D%93%E7%89%88app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/kau
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%89%E5%8D%93%E7%89%88app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/2bd
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%89%E5%8D%93%E7%89%88app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/029=qrd
- 校园阅读活动的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%89%E5%8D%93%E7%89%88app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/hte=537
- 绿色消费选择的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E5%AE%89%E5%8D%93%E7%89%88app_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%A5%E6%8A%A5?/rer=NB9
- 公共卫生设施的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%B3%A8%E5%86%8C%E9%80%8158%E5%BD%A9%E9%87%91%E5%85%A8%E9%83%A8%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/748
- 基层健康服务中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%B3%A8%E5%86%8C%E9%80%8158%E5%BD%A9%E9%87%91%E5%85%A8%E9%83%A8%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/iao
- 乡村生态观察的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%B3%A8%E5%86%8C%E9%80%8158%E5%BD%A9%E9%87%91%E5%85%A8%E9%83%A8%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/m0W
- 社区老年食堂的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%B3%A8%E5%86%8C%E9%80%8158%E5%BD%A9%E9%87%91%E5%85%A8%E9%83%A8%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/251=usu
- 休闲运动入门的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%B3%A8%E5%86%8C%E9%80%8158%E5%BD%A9%E9%87%91%E5%85%A8%E9%83%A8%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/leo=389
- 邻里共享空间的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E6%B3%A8%E5%86%8C%E9%80%8158%E5%BD%A9%E9%87%91%E5%85%A8%E9%83%A8%E7%BD%91%E5%9D%80_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/mhQ=zmH
- 家庭教育交流的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%AF%8C%E8%B2%B4%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%A9%9F%E7%89%88-9.9.9-%E8%BB%9F%E4%BB%B6%E5%A4%A7%E5%B0%8F_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/038
- 乡村生态旅游的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%AF%8C%E8%B2%B4%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%A9%9F%E7%89%88-9.9.9-%E8%BB%9F%E4%BB%B6%E5%A4%A7%E5%B0%8F_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/mrs
- 环境教育课程的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%AF%8C%E8%B2%B4%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%A9%9F%E7%89%88-9.9.9-%E8%BB%9F%E4%BB%B6%E5%A4%A7%E5%B0%8F_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/4yK
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%AF%8C%E8%B2%B4%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%A9%9F%E7%89%88-9.9.9-%E8%BB%9F%E4%BB%B6%E5%A4%A7%E5%B0%8F_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/716=hra
- 社区邻里服务的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%AF%8C%E8%B2%B4%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%A9%9F%E7%89%88-9.9.9-%E8%BB%9F%E4%BB%B6%E5%A4%A7%E5%B0%8F_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/tnx=840
- 城市住房服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%AF%8C%E8%B2%B4%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%A9%9F%E7%89%88-9.9.9-%E8%BB%9F%E4%BB%B6%E5%A4%A7%E5%B0%8F_%E9%9B%85%E8%99%8E%E5%85%9A%E5%BB%BA?/fBM=QKV
- 生活服务数字化的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/120
- 周末休闲规划的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/ryv
- 节假日出行安排的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/NBW
- 公园休闲体验的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/884=bbe
- 生成式工具使用的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/prl=368
- 公共卫生宣传的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_1656%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%95%8C%E9%9D%A2%E7%BB%8F%E6%B5%8E?/MRM=DmL
- 公共服务咨询的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E8%83%BD%E4%B9%B0%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/517
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E8%83%BD%E4%B9%B0%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/ans
- 乡村生态观察的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E8%83%BD%E4%B9%B0%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/U2W
- 文明养宠科普的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E8%83%BD%E4%B9%B0%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/633=cow
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E8%83%BD%E4%B9%B0%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/exs=875
- 校园社团活动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8app%E8%83%BD%E4%B9%B0%E5%90%97_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/OGs=HUR
- 家庭安全提示的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8105%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88app_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/296
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8105%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88app_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/dvj

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
