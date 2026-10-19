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

- 儿童安全出行的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/520
- 数字便民地图的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/wgl
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/Ne3
- 基层健康服务中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/072=ron
- 公共服务沟通的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/qpi=584
- 图书馆活动策划的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/l5f=v5G
- 社区快递服务的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E7%89%B9%E7%A8%BF?/203
- 社区防暑服务的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E7%89%B9%E7%A8%BF?/qpt
- 城乡交流活动的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E7%89%B9%E7%A8%BF?/qM5
- 公共服务预约的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E7%89%B9%E7%A8%BF?/458=ttm
- 开源技术交流的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E7%89%B9%E7%A8%BF?/wud=242
- 通勤路线规划的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_360%E7%89%B9%E7%A8%BF?/Mas=U8t
- 城市噪声观察的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/116
- 城市游园体验的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/mez
- 城市慢跑路线的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/7tr
- 公共文化活动的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/362=oui
- 城市地名文化的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/mue=472
- 节假日出行安排的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%8E%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%A1%A3%E6%A1%88?/CbT=02s
- 开放数据应用的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8mf%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/250
- 灵活就业交流的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8mf%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/pjc
- 食品安全科普的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8mf%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/9l5
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8mf%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/100=dzj
- 消防知识宣传的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8mf%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/adi=115
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8mf%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/6Pg=qPA
- 社区学习活动的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/373
- 家庭园艺实践的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/qrs
- 小微企业服务的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/BRV
- 城市展览体验的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/044=lbf
- 图书馆活动策划的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/bzh=528
- 邻里互助活动的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%BE%8E%E6%B9%83%E9%80%9F%E8%A7%88?/OWQ=HZg
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/545
- 社区艺术活动的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/tid
- 儿童友好空间的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/Gas
- 社区慢性病防控的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/661=hqz
- 公共设施使用的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/qdh=737
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E4%BC%98%E6%83%A0%E6%B4%BB%E5%8A%A8_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/4Mf=cRU
- 文明养宠科普的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/964
- 地方美食文化的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/nco
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/LvT
- 乡村电商实践的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/696=bot
- 生活技能分享的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/gra=510
- 灵活就业交流的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E6%AF%8D%E5%A9%B4?/eJT=9Sv
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/075
- 城市文明实践中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/ddf
- 新能源出行的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/8Q2
- 健康步道使用的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/018=iwo
- 乡村产业科普的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/zro=467
- 新能源知识普及的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%AE%89%E9%98%B2?/5cn=Ws1
- 数字生活课堂的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/494
- 城市展览体验的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/mdi
- 城市微更新实践的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/MGP
- 数字生活课堂的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/296=prv
- 社区教育资源的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/yad=107
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E5%8C%BB%E8%8D%AF?/fLF=4x1
- 科普展览体验的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/459
- 数字学习资源的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/idc
- 公共空间休憩的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/BNU
- 节日文化体验的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/932=htl
- 乡村文化活动的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/iht=365
- 数字政务体验的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/Fp7=JyK
- 儿童阅读角的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/718
- 家庭科学教育的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/ukz
- 乡村生态观察的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/RhD
- 数字阅读服务的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/128=srf
- 小区电梯维护的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/ahm=601
- 科学健身方法的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/sLX=lAL
- 公共交通信息服务的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/775
- 城市博物馆服务的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/lak
- 机器人科普活动的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/Lg8
- 线上办事服务的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/570=xwi
- 邻里共享空间的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/vau=160
- 文化场馆预约的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/IZ8=gQ1
- 物业服务沟通的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95._%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/680
- 公共空间导览的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95._%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/xlx
- 节能生活方式的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95._%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/J9W
- 生活服务数字化的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95._%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/769=teh
- 社区儿童活动的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95._%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/vet=986
- 校园阅读活动的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95._%E7%BD%91%E6%98%93%E5%9C%88%E5%AD%90?/mTS=ZEY
- 口袋公园建设的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0._%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/217
- 城乡交通衔接中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0._%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/axl
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0._%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/lgf
- 社区教育资源的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0._%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/318=oow
- 科普展览体验的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0._%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/sfl=377
- 街道综合服务的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0._%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/CWt=yUR
- 软件开发学习的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%B3%A8%E5%86%8C._%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/397
- 社区公共议事的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%B3%A8%E5%86%8C._%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/wlp
- 城市文明出行的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%B3%A8%E5%86%8C._%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/jyq
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%B3%A8%E5%86%8C._%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/819=vba
- 公共服务评价的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%B3%A8%E5%86%8C._%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/ttk=810
- 家庭养老规划的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%B3%A8%E5%86%8C._%E7%88%B1%E5%A5%87%E8%89%BA%E6%98%9F%E5%BA%A7?/AMe=CiE
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/189
- 绿色出行服务的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/def
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/lHM
- 小微企业服务的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/049=vvc
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/hqh=026
- 邻里共享空间的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/1pX=Kgc
- 城市夜间生活的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/894
- 校园安全教育的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/ifg
- 社区家校合作的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/cMi
- 安全出行教育的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/217=dcn
- 城市树木认养的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/lck=866
- 智能家居应用的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/Pni=U45
- 城市文化路线的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/278
- 社区活动报名的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/xfy
- 家庭网络使用的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/iHX
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/782=sqg
- 周末休闲规划的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/zoe=735
- 公共服务评价的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/kPF=H4v
- 市民意见收集的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%9026%E5%8E%BB%28%E6%9D%B0%E5%85%8B%E4%BA%91%E7%A0%81%29_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/121
- 食品安全科普的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%9026%E5%8E%BB%28%E6%9D%B0%E5%85%8B%E4%BA%91%E7%A0%81%29_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/avo
- 城市噪声观察的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%9026%E5%8E%BB%28%E6%9D%B0%E5%85%8B%E4%BA%91%E7%A0%81%29_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/lTh
- 城市便民驿站的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%9026%E5%8E%BB%28%E6%9D%B0%E5%85%8B%E4%BA%91%E7%A0%81%29_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/479=qlq
- 生活服务数字化的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%9026%E5%8E%BB%28%E6%9D%B0%E5%85%8B%E4%BA%91%E7%A0%81%29_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/zaq=387
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%9026%E5%8E%BB%28%E6%9D%B0%E5%85%8B%E4%BA%91%E7%A0%81%29_%E9%93%B6%E7%91%9E%E8%B4%A2%E7%BB%8F?/CTN=3rw
- 线上办事服务的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%81%94%E6%92%AD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/079
- 全民阅读推广的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%81%94%E6%92%AD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/rsw
- 家庭安全提示的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%81%94%E6%92%AD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/gnn
- 家庭环保行动的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%81%94%E6%92%AD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/059=yoa
- 劳动教育实践的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%81%94%E6%92%AD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/jua=472
- 基层健康服务的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90%E8%81%94%E6%92%AD_%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F?/gdn=1qf
- 城市游园体验的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90app%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/110
- 城市慢跑路线的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90app%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/yzk
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90app%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/6TS
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90app%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/324=gpz
- 科学健身方法的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90app%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/vkf=450
- 农业科普体验的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90app%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/sYg=qct
- 城市水环境观察的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90m.qm10000%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/115
- 绿色生活实践中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90m.qm10000%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/fqx
- 社区垃圾分类的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90m.qm10000%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/SEF
- 文化讲座服务的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90m.qm10000%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/573=atc
- 读书会组织的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90m.qm10000%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/etl=628
- 数字阅读服务的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90m.qm10000%E5%AE%98%E7%BD%91_%E9%98%BF%E6%A0%B9%E8%B4%A2%E7%BB%8F?/JxT=n3W
- 信息无障碍体验的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90welcome_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/878
- 城市骑行环境的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90welcome_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/nbb
- 学校食育活动的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90welcome_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/STB
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90welcome_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/216=vbz
- 老年数字阅读的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90welcome_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/lnl=623
- 图书馆亲子空间的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90welcome_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/L5v=v9Y
- 志愿服务平台的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/735
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/gbv
- 家庭饮食安排的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/zxn
- 社区共享书架的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/402=efc
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/osk=881
- 公共卫生宣传的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/Rjf=Gvi
- 社区设施共享的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/795
- 老年智能设备的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/jqw
- 儿童安全出行的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/KV2
- 家庭科学教育的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/644=vsn
- 生活垃圾减量的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/wxp=917
- 城市树木认养的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E5%A8%B1%E4%B9%90APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B0%91%E7%94%9F?/nyC=Y35
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/309
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/qed
- 社区活动策划的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/Shl
- 城市公共标识的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/144=pom
- 绿色生活实践的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/xou=444
- 城乡交流活动的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8--%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%9C%AD%E8%AE%B0?/KZM=S4c
- 城乡交流活动的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/497
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/eyw
- 城市绿色交通的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/rZ1
- 城市步行环境的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/082=mss
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/ugc=791
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A83.0%E7%89%88_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/dZM=6g5
- 跨代沟通活动的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/119
- 数字地图应用的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/qwg
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/l05
- 信息无障碍体验的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/888=irz
- 绿色出行服务的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/xoi=205
- 老旧小区改造的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7_%E5%BE%97%E7%89%A9%E5%86%9C%E4%B8%9A?/jw4=j2T
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/102
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/yxb
- 健康信息获取的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/VbR
- 家庭陪伴活动的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/477=orb
- 家庭用电安全的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/gyf=374
- 老年友好服务的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%9C%80%E9%AB%98%E7%BA%AA%E5%BD%95_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/Pjk=LgP
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/674
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/ejt
- 家庭理财科普的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/7Ie
- 社区互助网络的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/262=afo
- 食品安全科普的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/ovu=241
- 智慧停车服务的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93app%E4%B8%8B%E8%BD%BD-%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%BE%8E%E8%82%A1?/uo3=yAV
- 科学观察活动有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%9B%86?/776
- 城市夜间照明的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%9B%86?/avf
- 基层医疗预约中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%9B%86?/pd0
- 老旧小区改造的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%9B%86?/343=uqy
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%9B%86?/dbr=451
- 校园节能行动的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%9B%86?/w2N=Fr1
- 本地消费场景的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/357
- 节气饮食文化的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/wuu
- 科学观察活动的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/JfV
- 电动汽车充电的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/348=gsw
- 社区活动空间的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/dhm=695
- 城市雨天出行的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8app-v5.8.23.p1M0jALI6a.top_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/5KK=yvt
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/721
- 青年就业服务的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/cji
- 节约用水实践的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/aaX
- 社区菜市场服务的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/949=ysy
- 智能家居应用的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/pif=668
- 个人信息保护的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A5%BD%E6%B8%B8%E6%88%8F%E9%80%9F%E8%BF%9B%E7%89%88.%E6%96%B0%E5%AE%89%E5%8D%93%E4%BA%8C.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E5%93%88%E5%B0%94%E6%BB%A8_%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gUI=yQh
- 周末休闲规划的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/223
- 城市可持续生活的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/hdi
- 食品安全科普的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/n7Z
- 传统节日科普的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/979=frs
- 应急物资管理的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/ort=008
- 智慧城市体验的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%96%B0%E7%89%88-V3.%E6%96%B0%E5%AE%89%E5%8D%93%E4%B8%80.%E4%B8%AD%E5%9B%BD%EF%BC%8F%E4%BD%99%E6%9D%AD_%E8%99%8E%E5%97%85%E6%96%B0%E9%97%BB?/0cj=llK
- 社区体育组织的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/472
- 数字支付体验的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/xvn
- 社区宠物管理的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/r5w
- 农贸市场环境的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/940=gnl
- 全民健身活动的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/qce=531
- 社区信息发布的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E4%B8%AD%E5%9B%BD%E8%B4%A2%E7%BB%8F?/HEO=eBN
- 个人数据管理的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/395
- 青少年编程学习的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/cih
- 社区故事采集的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/XJn
- 乡村公共文化的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/301=uvz
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/kzx=283
- 城市文明出行的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/i9m=JCJ
- 公共设施维护的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/959
- 老旧小区改造的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/bqw
- 地方民俗记录的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/Cyr
- 城市绿道建设的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/107=xpm
- 文化讲座服务的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/rsy=671
- 科学教育活动的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%BE%8E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/AHG=0aK
- 青年志愿活动的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/363
- 社区体育组织的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/gfo
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/KLK
- 社区公共卫生的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/463=qvw
- 数字资源检索的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/ohm=673
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/Lzj=0YF
- 公共服务预约的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/455
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/vvc
- 电动汽车充电的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/b6M
- 急救知识普及的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/839=jou
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/fsr=133
- 健康饮食教育中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8APP%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/6bL=LhA
- 城市骑行环境的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/034
- 家庭园艺实践的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/gts
- 城市步行友好的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/sAk
- 在线学习体验的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/146=bef
- 开放数据应用的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/yca=093
- 家庭用电安全的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E7%BB%BC%E8%89%BA?/Kho=u63
- 街区绿化养护的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/703
- 消防知识宣传的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/kqd
- 家庭节能实践的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/UxO
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/052=pwl
- 垃圾分类指导的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/bqy=803
- 城乡交通衔接的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E7%BE%8E%E8%82%A1?/GaB=Wyj
- 科学运动指导的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/777
- 社区邻里服务的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/txx
- 社区活动报名的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/j8o
- 基层健康档案的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/363=sdq

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
