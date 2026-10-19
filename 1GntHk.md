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

- 电动汽车充电的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/l8d
- 城市适老服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/703=wwt
- 社区设施共享的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/zbo=352
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/nCB=T9u
- 城市人文观察的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/063
- 基层健康档案的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/vlx
- 社区垃圾分类的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/IJ5
- 口袋公园建设的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/050=pvx
- 软件开发学习的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/svz=674
- 城市人文观察的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app_%E7%9F%A5%E4%B9%8E%E8%83%BD%E6%BA%90?/dOk=jq2
- 社区宣传栏更新的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/537
- 开放式学习空间的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/xnc
- 公共服务预约的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/kZm
- 农产品消费体验的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/779=ung
- 社区邻里服务的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/zlj=954
- 城市体育设施的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E4%B8%8D%E4%BA%86_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/T1r=wGG
- 户外活动组织的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/889
- 地方美食文化的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/bbx
- 社区公共卫生的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/Ii3
- 城乡交流活动的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/074=all
- 社区科普课堂的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/dqz=526
- 基层医疗预约的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E7%94%B5?/IUm=LGV
- 城市适老服务的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/491
- 社区读书角建设的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/tza
- 乡村电商实践的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/WjI
- 休闲运动入门的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/601=ndk
- 开放式学习空间的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/tqh=923
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E5%BE%AE%E4%BF%A1_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/Om8=TFZ
- 文化场馆预约的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/973
- 社区科普课堂的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/ebz
- 家庭环保习惯的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/y2o
- 校园节能行动的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/840=fuh
- 日常摄影记录的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/epl=189
- 乡村教育资源的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/zNY=TQj
- 城市文明实践的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/914
- 节约用水实践的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/ewt
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/37n
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/315=huv
- 健康饮食教育的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/rrh=937
- 城乡交流活动的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%95%8A_%E6%BE%8E%E6%B9%83%E6%85%A7%E7%9C%BC?/T1y=8LK
- 通勤路线规划的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_360%E5%85%AC%E7%9B%8A?/421
- 校园社团活动的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_360%E5%85%AC%E7%9B%8A?/kpx
- 家庭理财科普的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_360%E5%85%AC%E7%9B%8A?/Udd
- 家庭网络使用的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_360%E5%85%AC%E7%9B%8A?/856=sln
- 老年运动活动的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_360%E5%85%AC%E7%9B%8A?/gza=916
- 家庭科学教育的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_360%E5%85%AC%E7%9B%8A?/Hc3=eDe
- 生活服务数字化的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_360%E6%98%9F%E5%BA%A7?/708
- 儿童友好空间的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_360%E6%98%9F%E5%BA%A7?/agz
- 劳动教育实践的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_360%E6%98%9F%E5%BA%A7?/CIU
- 社区邻里服务的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_360%E6%98%9F%E5%BA%A7?/562=gog
- 食品安全科普的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_360%E6%98%9F%E5%BA%A7?/isf=522
- 社区快递服务的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%A2_360%E6%98%9F%E5%BA%A7?/2XI=G0n
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/099
- 社区修缮行动的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/ett
- 青少年心理健康的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/Yby
- 社区体育组织的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/437=hcq
- 科学观察活动的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/qmp=794
- 社区商业活力的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%8B%B9%E6%9E%9C%E5%A4%A7%E5%8F%91app%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD%E4%B8%8D%E4%BA%86%E4%BA%86%E5%91%80_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/wL3=J6K
- 社区艺术活动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/338
- 基层服务创新的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/auy
- 日常摄影记录的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/4hv
- 应急物资管理的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/815=qpz
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/yij=977
- 居家适老化改造的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/spL=QN9
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/297
- 社区便民集市的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/adv
- 网络安全教育的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/T1w
- 社区停车服务的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/149=wob
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/riv=336
- 就业技能培训的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%BE%97%E7%89%A9%E6%B8%B8%E6%88%8F?/oZB=90X
- 家庭园艺实践的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/380
- 城市住房服务的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/ika
- 图书借阅体验的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/uxH
- 社区停车服务的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/576=iaq
- 社区体育组织的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/xfy=843
- 公交站点体验的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA_%E5%8D%B3%E5%88%BB%E9%94%90%E8%AF%84?/fzB=ymK
- 城市地名文化的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/528
- 便民服务地图的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/cnx
- 青年志愿活动的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/qY7
- 城市噪声观察的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/591=flb
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/ddp=173
- 公园休闲体验的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E5%BF%85%E5%BA%94%E8%A1%8C%E6%83%85?/vhc=lAX
- 节约用水实践的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/125
- 城市绿道建设的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/pqi
- 居民健康教育的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/g7V
- 公共服务预约的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/963=nle
- 城市共享单车的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/qhd=610
- 通勤路线规划的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/O5U=rGf
- 家庭科学教育的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/616
- 校园阅读活动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/asr
- 老年学习活动的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/MUJ
- 社区邻里服务的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/809=qbh
- 街道综合服务的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/vlx=231
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E6%88%BF%E4%BA%A7?/1hj=dXL
- 城市适老服务的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/525
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/dhn
- 城市绿色交通的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/Dwh
- 城市骑行环境的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/104=zpw
- 劳动教育实践的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/zog=025
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E5%9C%A8%E5%93%AA%E6%89%BE%E5%88%B0_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/9nB=TgY
- 城市公共自行车的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/744
- 社区科普课堂从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/moq
- 儿童安全出行的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/nvb
- 公共设施维护的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/217=yly
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/oxz=844
- 城市生活服务的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E9%80%9F%E5%8F%91_%E6%90%9C%E7%8B%97%E6%88%BF%E4%BA%A7?/Qdh=2FP
- 城市公共饮水的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/494
- 乡村阅读活动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/kfh
- 社区阅读服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/GKk
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/511=bin
- 城市公共艺术的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/crd=244
- 社区信息发布的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/lXA=IOK
- 校园节能行动的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_360%E9%A3%9F%E5%93%81?/987
- 农产品消费体验的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_360%E9%A3%9F%E5%93%81?/bhn
- 社区防暑服务的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_360%E9%A3%9F%E5%93%81?/0Uy
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_360%E9%A3%9F%E5%93%81?/906=viq
- 社区交通安全的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_360%E9%A3%9F%E5%93%81?/wic=628
- 社区公共议事中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_2024%E5%B9%B4%E5%A4%A7%E5%8F%91%E6%96%B0%E7%89%88APP%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_360%E9%A3%9F%E5%93%81?/oQk=Ysz
- 家庭教育交流的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/595
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/vrk
- 绿色消费选择的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/J8n
- 家庭照护支持的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/632=bgu
- 青年职业探索的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/svh=627
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91dafabet%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91%E7%BD%91%E9%A1%B5%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%8D%83%E5%B8%86?/0qu=6Sk
- 城市体育设施中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/039
- 读书会组织的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/opm
- 公共卫生宣传的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/uLA
- 本地消费场景的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/119=kuw
- 口袋公园建设的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/qys=344
- 绿色校园实践的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91dafa888%E9%BB%84%E9%87%91%E7%89%88%E5%94%AF%E4%B8%80%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/T36=OeL
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/866
- 城市基础设施的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/dpk
- 城市社区治理的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/2yQ
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/522=oyo
- 个人时间管理的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/ilf=384
- 基层健康服务的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E6%8E%92%E5%88%973%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/VjN=iLL
- 老年数字阅读的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/068
- 校园社团活动的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/bev
- 农产品消费体验的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/NLk
- 城市微更新实践的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/823=ojp
- 骑行路线规划的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/sno=865
- 青少年心理健康的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%8E%92%E5%88%97%E4%B8%89%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/qky=fqH
- 青少年科普实践的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/565
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/rpr
- 周末休闲规划的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/fsR
- 就业技能培训有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/628=zrn
- 地方美食文化的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/znu=874
- 社区公共餐饮的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%973_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/80g=47C
- 农产品消费体验的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/442
- 家庭安全提示的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/oct
- 机器学习入门的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/HlR
- 公交站点体验的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/109=omq
- 节日文化体验的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/gbx=032
- 社区防暑服务的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%975_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/4L7=YSc
- 电子商务服务中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/377
- 低碳社区实践的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/rju
- 城市绿道建设的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/RXf
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/256=zie
- 数字便民地图的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/ooi=488
- 社区公共卫生的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E4%B8%8B%E8%BD%BD%E6%8E%92%E5%88%97%E4%B8%89_%E4%BA%AC%E4%B8%9C%E6%88%B7%E5%A4%96?/Ehx=TJ2
- 邻里共享空间的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/505
- 数字素养提升的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/adb
- 急救知识普及的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/a74
- 社区公共餐饮的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/184=avl
- 健康饮食教育的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/jyn=122
- 家庭志愿活动的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_11%E9%80%895%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/uOL=Bsh
- 儿童运动体验的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/044
- 社区协商议事中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/jiy
- 租房信息服务的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/CX5
- 公共空间照明的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/624=bfl
- 社区便利生活的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/rum=493
- 节假日出行安排的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_1%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E7%BA%BD%E7%BA%A6%E8%B4%A2%E7%BB%8F?/hEQ=1qA
- 安全出行教育的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/631
- 市民意见收集的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/wey
- 社区互助网络的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/3Hv
- 城市公共厕所的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/788=gen
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/qtm=275
- 地方民俗记录的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_3D%E7%A6%8F%E5%BD%A9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%94%B6%E8%97%8F?/o6l=bmy
- 休闲运动入门的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/682
- 户外活动组织的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/dbe
- 儿童安全出行的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/Bkb
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/456=wqm
- 日常摄影记录的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/tee=136
- 生活垃圾减量的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_6%E5%88%86%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%99%9A%E6%8A%A5?/uY2=cxk
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/615
- 社区停车服务的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/tys
- 社区活动策划的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/ttt
- 农村环境治理的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/338=xif
- 社区体育组织的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/wic=956
- 青少年户外教育的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_6%E7%A7%92%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E4%B8%93%E9%A2%98?/2cn=j3Z
- 光伏知识科普的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/210
- 城市应急科普的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/zvt
- 科学观察活动的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/a0L
- 就业技能培训的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/871=anl
- 垃圾分类指导的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/iew=608
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%AE%89%E5%BE%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/IB8=5V9
- 家庭环保习惯的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/519
- 社区体育组织中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/knx
- 食品安全科普的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/d41
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/511=rvr
- 数字资源检索的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/vpk=713
- 生活垃圾减量的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A81%E7%A7%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E9%80%9F%E8%A7%88?/k4G=Szt
- 社区活动空间的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/994
- 地方美食文化的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/vmy
- 青少年户外教育的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/as1
- 城市文化路线的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/146=osr
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/srw=842
- 农产品消费体验的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%A6%8F%E5%BD%A93d%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/rdG=ttX
- 农贸市场环境的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/785
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/tur
- 数字地图应用的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/MI6
- 儿童安全出行的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/551=evj
- 科学教育活动的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/sqe=538
- 校园安全教育的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E8%B4%B5%E5%B7%9E%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/ViD=J02
- 社区知识分享的协商参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/395
- 开放式学习空间中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/mmq
- 城市公共厕所中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/6WE
- 职业技能学习中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/808=sdz
- 城乡交流活动的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/tft=792
- 数字生活课堂的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E6%AC%A2%E4%B9%90%E7%94%9F%E8%82%96%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/kXb=Kst
- 社区法律科普的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/152
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/lhe
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/SNB
- 社区体育组织的参与方式与路径 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/284=atz
- 校园社团活动的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/jxk=253
- 青年职业探索的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%90%E5%8D%81%E5%88%86%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A1%8C%E6%83%85?/dpl=E5M
- 便民维修服务的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/653
- 社区文化节活动的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/nnt
- 数字艺术创作的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/P48
- 全民健身活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/965=vpu
- 数字设备回收的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/jan=403
- 生成式工具使用的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%89%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/Q2F=9nI
- 数字课堂应用中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/447
- 家庭教育交流中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/qhg
- 健康步道使用的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/iGx
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/954=oew
- 基层健康档案的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/htp=886
- 医院导诊服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%8A%E6%B5%B7%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%BC%AB?/6qd=Fne
- 全民健身活动的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/002
- 社区手工活动的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/nuq
- 农贸市场环境的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/RnM
- 老年人日常照护的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/755=opx
- 公共服务评价的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/wjj=059
- 城市步行友好的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%8B%E8%BD%BD__%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/Kzr=yKC
- 智能家居应用的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/529
- 家庭环保行动的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/eil
- 本地旅行体验的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/kBA
- 公园休闲体验的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/368=xdw
- 城市运动公园的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/bkm=162
- 家庭环保行动的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/zqo=usK

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
