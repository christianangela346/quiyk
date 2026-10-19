# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 社区庭院绿化的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%88%98%E7%8B%BC%E9%A2%84%E6%B5%8B%E7%BD%9128%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%9C%A8%E7%BA%BF-%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/yL1
- 公共卫生设施的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%88%98%E7%8B%BC%E9%A2%84%E6%B5%8B%E7%BD%9128%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%9C%A8%E7%BA%BF-%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/550=ndd
- 数字课堂应用的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%88%98%E7%8B%BC%E9%A2%84%E6%B5%8B%E7%BD%9128%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%9C%A8%E7%BA%BF-%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/vxb=594
- 社区志愿服务的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E6%88%98%E7%8B%BC%E9%A2%84%E6%B5%8B%E7%BD%9128%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%9C%A8%E7%BA%BF-%E7%9F%A5%E4%B9%8E%E7%BB%8F%E6%B5%8E?/p1l=Uvj
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E7%B2%BE%E5%87%86-%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/367
- 城市文明实践的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E7%B2%BE%E5%87%86-%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/kjt
- 在线教育体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E7%B2%BE%E5%87%86-%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/rDz
- 智慧停车服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E7%B2%BE%E5%87%86-%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/592=itv
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E7%B2%BE%E5%87%86-%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/qfj=989
- 乡村文化活动的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E7%BD%91%E7%B2%BE%E5%87%86-%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/sQy=aN1
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bapp-%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/042
- 城乡交通衔接的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bapp-%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/fqv
- 小区公共照明的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bapp-%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/UNt
- 基层医疗预约的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bapp-%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/499=cdz
- 社区便民集市的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bapp-%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/rpy=331
- 儿童户外活动的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%85%8D%E8%B4%B9%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8Bapp-%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/UPB=9H8
- 家庭急救准备的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%A5%9E28%E8%AE%BA%E5%9D%9B%E9%A2%84%E6%B5%8B-%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/295
- 儿童友好空间的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%A5%9E28%E8%AE%BA%E5%9D%9B%E9%A2%84%E6%B5%8B-%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/fce
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%A5%9E28%E8%AE%BA%E5%9D%9B%E9%A2%84%E6%B5%8B-%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/RIL
- 智慧城市体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%A5%9E28%E8%AE%BA%E5%9D%9B%E9%A2%84%E6%B5%8B-%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/468=gzv
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%A5%9E28%E8%AE%BA%E5%9D%9B%E9%A2%84%E6%B5%8B-%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/fsx=717
- 公共交通信息服务的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E7%A5%9E28%E8%AE%BA%E5%9D%9B%E9%A2%84%E6%B5%8B-%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/Xyt=RmF
- 城市建设科普的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B90%25%E5%AF%B9-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/960
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B90%25%E5%AF%B9-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/tyj
- 乡村公共文化的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B90%25%E5%AF%B9-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/CvB
- 地方民俗记录的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B90%25%E5%AF%B9-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/277=jvz
- 社区家校合作的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B90%25%E5%AF%B9-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/yvn=326
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B90%25%E5%AF%B9-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%A3%E5%AF%86?/abb=but
- 学校食育活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%A5%9E%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/908
- 社区垃圾分类的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%A5%9E%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/lxu
- 网络安全教育的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%A5%9E%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/tOD
- 智能家居应用的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%A5%9E%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/637=dbv
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%A5%9E%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/btt=553
- 地方文化传播的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc2.8%E9%A2%84%E6%B5%8B%E7%A5%9E%E9%A2%84%E6%B5%8B-%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/KC9=NN8
- 地方民俗记录的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/114
- 健康步道使用的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/qsj
- 家庭健康科普的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/U2Q
- 街区更新实践的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/760=zvz
- 环境教育课程的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/qhi=552
- 城市适老服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E8%B4%A2%E7%BB%8F%E5%9B%AD%E8%89%BA?/QEE=Dqv
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/386
- 健康饮食教育的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/wbq
- 地方文化传播的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/HhG
- 绿色消费选择的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/402=gfg
- 社区阅读服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/bxa=090
- 文明养宠科普的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%A1%BA%E4%B8%B0%E8%AE%BF%E8%B0%88?/DhK=QAw
- 智能家居应用的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/587
- 社区互助网络的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/qen
- 城市便民驿站的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/uS6
- 劳动教育实践的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/206=yva
- 本地旅行体验的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/wel=086
- 青年职业探索的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A3%9E%E9%A3%9E28%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/vMS=Pg3
- 城市文明出行的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7PC%E9%A2%84%E6%B5%8B%E7%BD%91-%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/042
- 节能生活方式的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7PC%E9%A2%84%E6%B5%8B%E7%BD%91-%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/gfe
- 居家防滑改造的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7PC%E9%A2%84%E6%B5%8B%E7%BD%91-%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/nYi
- 开放数据应用的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7PC%E9%A2%84%E6%B5%8B%E7%BD%91-%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/623=exz
- 就业技能培训的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7PC%E9%A2%84%E6%B5%8B%E7%BD%91-%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/cbx=412
- 科技馆参观体验的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%8A%A0%E6%8B%BF%E5%A4%A7PC%E9%A2%84%E6%B5%8B%E7%BD%91-%E5%BE%97%E7%89%A9%E4%BA%BA%E5%A4%A7?/75Z=Xkz
- 社区信息发布的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728pc%E9%A2%84%E6%B5%8B-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/414
- 生活服务数字化的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728pc%E9%A2%84%E6%B5%8B-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/lju
- 城市农夫市集的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728pc%E9%A2%84%E6%B5%8B-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/3xd
- 公共设施维护中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728pc%E9%A2%84%E6%B5%8B-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/286=khe
- 儿童户外活动的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728pc%E9%A2%84%E6%B5%8B-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/zvl=184
- 社区快递服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728pc%E9%A2%84%E6%B5%8B-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/1YR=6bJ
- 家庭用电安全的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/173
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/dbm
- 本地消费场景的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/kgB
- 新能源知识普及的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/445=sem
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/ysg=931
- 传统节日科普的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/fWW=qtw
- 终身学习资源的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/275
- 城市夜间生活的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/rbx
- 老年数字阅读的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/QjT
- 乡村产业科普的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/865=hoj
- 街道综合服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/eqo=453
- 环境监测科普的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/wxA=zhg
- 文明养宠科普的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-360%E4%B8%93%E9%A2%98?/165
- 社区花园共建的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-360%E4%B8%93%E9%A2%98?/dsv
- 绿色办公实践的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-360%E4%B8%93%E9%A2%98?/Nkw
- 数字阅读服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-360%E4%B8%93%E9%A2%98?/908=lzf
- 社区宣传栏更新的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-360%E4%B8%93%E9%A2%98?/isc=557
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%AE%98%E7%BD%91%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B-360%E4%B8%93%E9%A2%98?/122=tMB
- 青少年户外教育的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/679
- 家庭安全提示的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/uqj
- 音乐欣赏活动的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/MZZ
- 校园社团活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/489=kij
- 社区便利生活的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/dha=923
- 通勤路线规划的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E9%A3%9E%E9%A3%9E-%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/Kf0=Nfu
- 儿童友好空间的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E7%BD%91%E5%9D%80-%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/887
- 城市树木认养的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E7%BD%91%E5%9D%80-%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/qld
- 家庭消费规划的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E7%BD%91%E5%9D%80-%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/VAX
- 城市住房服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E7%BD%91%E5%9D%80-%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/141=oqi
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E7%BD%91%E5%9D%80-%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/wak=868
- 在线教育体验的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc%E5%BC%80%E5%A5%96%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E7%BD%91%E5%9D%80-%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/pYC=07J
- 智能手机助老的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C-%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/347
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C-%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/fir
- 环境教育课程的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C-%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/FmI
- 绿色建筑理念的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C-%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/676=sys
- 药品使用科普的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C-%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/inm=334
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%92%AA%E7%89%8C-%E8%B0%B7%E6%AD%8C%E6%B8%AF%E8%82%A1?/n0G=liB
- 市民热线服务的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B100%25%E6%AD%A3%E7%A1%AE-%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/562
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B100%25%E6%AD%A3%E7%A1%AE-%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/bvo
- 网络安全教育的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B100%25%E6%AD%A3%E7%A1%AE-%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/X7w
- 青年职业探索的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B100%25%E6%AD%A3%E7%A1%AE-%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/688=cft
- 线上阅读资源的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B100%25%E6%AD%A3%E7%A1%AE-%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/gsr=096
- 城市人文观察的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B100%25%E6%AD%A3%E7%A1%AE-%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/qH7=AxI
- 城市休闲步道的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/190
- 个人信息保护的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/ljf
- 在线教育体验的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/bVN
- 城市噪声观察的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/706=cjb
- 数字素养提升的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/qyj=354
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8pc-%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/WPM=rZC
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/861
- 城市绿色交通的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/coy
- 数字地图应用的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/wOu
- 邻里互助活动的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/652=clw
- 城市地名文化的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/osg=041
- 社区活动空间的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E9%A1%BA%E4%B8%B0%E8%A7%86%E9%A2%91?/F0x=1Wp
- 公共卫生宣传的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8-PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/436
- 公交站点体验的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8-PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/njb
- 地方戏曲体验的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8-PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/4Fo
- 乡村生活观察的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8-PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/003=fpp
- 公共卫生设施的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8-PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/roq=453
- 个人时间管理的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8-PC%E9%A2%84%E6%B5%8B%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/ORq=q5X
- 数字创意课程的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8qq%E7%BE%A4%E5%8F%B7%EF%BC%88KK%EF%BC%89-%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/980
- 家庭收纳实践的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8qq%E7%BE%A4%E5%8F%B7%EF%BC%88KK%EF%BC%89-%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/wkk
- 读书会组织的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8qq%E7%BE%A4%E5%8F%B7%EF%BC%88KK%EF%BC%89-%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/LPc
- 老年数字阅读的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8qq%E7%BE%A4%E5%8F%B7%EF%BC%88KK%EF%BC%89-%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/784=qrx
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8qq%E7%BE%A4%E5%8F%B7%EF%BC%88KK%EF%BC%89-%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/bke=160
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8qq%E7%BE%A4%E5%8F%B7%EF%BC%88KK%EF%BC%89-%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/XZP=bk0
- 公共图书馆服务的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/820
- 儿童运动体验的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/ghx
- 社区交通安全的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/2c4
- 绿色出行服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/423=var
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/yct=016
- 社区便民服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C-%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/WxG=lih
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/016
- 开放数据应用的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/ivc
- 社区垃圾回收的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/L1a
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/392=efl
- 节气饮食文化有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/ryx=129
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/fTn=FiG
- 节假日出行安排的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91-%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/362
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91-%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/lnr
- 家庭教育交流的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91-%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/LqO
- 社区修缮行动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91-%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/134=woo
- 市民热线服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91-%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/dox=688
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E6%B5%8B%E8%AF%84%E7%BD%91-%E8%B1%86%E7%93%A3%E6%B6%88%E8%B4%B9?/LOB=8pJ
- 社区阅读服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51-%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/732
- 城市噪声观察的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51-%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/jva
- 城市公共标识的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51-%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/Cfy
- 公共空间安全的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51-%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/563=dzv
- 光伏知识科普的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51-%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/aoa=594
- 城市农夫市集的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B51-%E6%90%9C%E7%8B%97%E5%9C%B0%E4%BA%A7?/4Ga=zcf
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84-360%E6%89%8B%E8%AE%B0?/304
- 青少年科技社团的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84-360%E6%89%8B%E8%AE%B0?/xcz
- 居民健康教育的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84-360%E6%89%8B%E8%AE%B0?/WIT
- 城市绿色交通的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84-360%E6%89%8B%E8%AE%B0?/364=fqh
- 课后服务体验的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84-360%E6%89%8B%E8%AE%B0?/pwk=562
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9026%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84-360%E6%89%8B%E8%AE%B0?/21i=gIK
- 网络信息辨识的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/955
- 城市慢行系统的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/obd
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/xFy
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/932=wfb
- 光伏知识科普的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/wjy=555
- 青少年户外教育的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3-%E7%9B%9B%E8%BE%89%E8%B4%A2%E7%BB%8F?/UMN=LF6
- 公共交通接驳的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/924
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/lhq
- 城市可持续生活中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/USY
- 青年志愿活动中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/453=suy
- 青少年户外教育的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/gbo=904
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/EDY=C2w
- 个人数据管理的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE-%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/514
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE-%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/aev
- 社区信息发布的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE-%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/Ffj
- 数字资源检索的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE-%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/927=gzq
- 社区活动空间的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE-%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/evs=673
- 数字档案服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E6%9C%80%E5%87%86%E7%A1%AE-%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/8ue=kDN
- 青少年科技社团的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B-%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/022
- 社区健康讲座的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B-%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/wdh
- 乡村产业科普的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B-%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/rRw
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B-%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/088=jap
- 数字设备回收的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B-%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/ttu=734
- 口袋公园建设的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%B0%BD%E4%BA%AB%E4%BA%91%E6%B5%8B-%E5%BF%85%E5%BA%94%E5%86%9C%E4%B8%9A?/XYm=ZHs
- 数字创作工具的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD-360%E5%81%A5%E5%BA%B7?/267
- 跨代沟通活动的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD-360%E5%81%A5%E5%BA%B7?/bod
- 安全出行教育的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD-360%E5%81%A5%E5%BA%B7?/oxv
- 小区公共照明的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD-360%E5%81%A5%E5%BA%B7?/032=pth
- 灵活就业交流的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD-360%E5%81%A5%E5%BA%B7?/ibg=148
- 社区家校合作中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8Bapp%E4%B8%8B%E8%BD%BD-360%E5%81%A5%E5%BA%B7?/GsV=N3D
- 新能源出行的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96-%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/835
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96-%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/xze
- 乡村阅读空间的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96-%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/uZn
- 乡村文化活动的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96-%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/126=ycj
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96-%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/mwf=554
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96-%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/jze=4KE
- 乡村产业科普的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88-%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/154
- 公交无障碍服务的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88-%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/inu
- 社区运动空间的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88-%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/4tl
- 口袋公园建设的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88-%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/885=tet
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88-%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/fst=509
- 口袋公园建设的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E6%96%B9%E6%A1%88-%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/bXX=9eS
- 小微企业服务的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F-%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/984
- 数字学习资源的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F-%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/knc
- 科学信息获取的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F-%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/5rB
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F-%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/424=bze
- 个人信息保护的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F-%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/bpt=908
- 绿色校园实践的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E5%85%AC%E5%BC%8F-%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/QRu=oX6
- 城市水环境观察的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88-%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/332
- 城市微更新实践的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88-%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/yja
- 光伏知识科普的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88-%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/Nvo
- 社区便利生活的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88-%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/670=lcq
- 乡村公共服务的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88-%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/bia=722
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9028%E6%9C%89%E9%A2%84%E6%B5%8B%E4%B9%88-%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/aYp=EmV
- 社区教育资源的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/547
- 数字便民地图的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/tci
- 智慧城市体验的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/BOG
- 生活技能分享的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/959=jmp
- 家庭环保习惯的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/lqi=860
- 城市游园体验的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B-%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/QqW=Voa
- 文化讲座服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/626
- 城市公共艺术的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/aax
- 社会体育指导的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/tGS
- 城市雨天出行中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/620=wgj
- 居民健康教育的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/atc=991
- 医院导诊服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E9%A3%9E%E9%A3%9Ejnd28pc28%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/BHo=eEP
- 城市环境志愿行动的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/984
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/pcd
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/Lwu
- 便民信息查询的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/845=jgh
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/zdc=722
- 租房信息服务的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E7%A5%9E%E6%B5%8B%E7%BD%91%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6%E5%8A%9F%E8%83%BD-%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/8q8=Lsr
- 街头绿植养护的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/513
- 公共交通接驳的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/dic
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/bGu
- 校园安全教育的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/982=kml
- 社区安全巡查的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/jlo=478
- 城市文化路线的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/oiL=Dgd
- 社区防暑服务的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90-%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/663
- 灵活就业交流的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90-%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/agd
- 绿色消费选择的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90-%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/HGd
- 校园安全教育的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90-%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/553=dtf
- 药品使用科普的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90-%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/hyt=473
- 公园休闲体验的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90-%E4%BC%98%E9%85%B7%E6%B1%87%E5%B8%82?/S21=ia7
- 城市农夫市集的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/522
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/jrk
- 城市公共自行车的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/ioa
- 节气饮食文化的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/697=ddh
- 线上阅读资源的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/ynr=004
- 户外活动组织的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E9%A2%84%E6%B5%8B-%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/Oci=xNx

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
