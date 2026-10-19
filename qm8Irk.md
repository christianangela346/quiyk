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

- 家庭环保习惯的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%ABapp%E4%B8%89-%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/109
- 社区托育服务的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%ABapp%E4%B8%89-%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/mjj
- 物业服务沟通的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%ABapp%E4%B8%89-%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/wN9
- 绿色快递包装的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%ABapp%E4%B8%89-%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/734=rvo
- 开源技术交流的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%ABapp%E4%B8%89-%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/fsr=380
- 传统手工艺体验的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%ABapp%E4%B8%89-%E7%99%BE%E5%BA%A6%E6%94%BF%E7%AD%96?/lma=eGV
- 社区志愿服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF-%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/715
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF-%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/qwg
- 城市微更新实践的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF-%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/mOs
- 青少年心理健康的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF-%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/387=xmy
- 老年数字阅读的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF-%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/aus=886
- 城市公共自行车的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3app%E5%AE%89%E5%8D%93%E7%89%88%E5%AE%A2%E6%88%B7%E7%AB%AF-%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/nly=DtT
- 社区修缮行动的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/878
- 小微企业服务的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/diq
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/q9l
- 社区活动报名的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/895=xvs
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/lrb=409
- 公共服务指南的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93-%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/nkh=xnr
- 线上办事服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/843
- 生活服务数字化的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/diz
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/M9q
- 街区绿化养护的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/786=wst
- 绿色生活实践的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/ewr=640
- 户外活动组织的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-%E8%B0%B7%E6%AD%8C%E7%83%AD%E6%A6%9C?/NMo=80z
- 城市公共艺术的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/472
- 公共卫生设施的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/skg
- 休闲运动入门的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/O0h
- 绿色出行服务的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/658=oxy
- 社区读书角建设的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/mem=597
- 生成式工具使用的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88-%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/9nP=HGb
- 家庭园艺实践的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/027
- 社区体育组织的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/eil
- 小微企业服务的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/otx
- 社区托育服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/147=ejo
- 老年智能设备的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/qko=597
- 本地历史资料的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%AB3app%E8%8B%B9%E6%9E%9C-%E5%BF%85%E5%BA%94%E7%A4%BE%E5%8C%BA?/HFR=XlP
- 开放数据应用的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/302
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/jpv
- 环境教育课程的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/wMl
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/549=mdm
- 社区心理支持的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/ufq=297
- 老年数字阅读的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/h4I=agA
- 城市公共空间的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/069
- 儿童安全出行的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/uvz
- 光伏知识科普的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/W7F
- 读书会组织的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/686=jil
- 急救知识普及的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/wyi=371
- 城市文化路线的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%88%86%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%88%B8%E5%95%86?/SWW=wmc
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/438
- 家庭运动计划的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/bha
- 旧物循环利用的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/NRs
- 本地历史资料的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/487=gup
- 社区志愿服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/asf=063
- 家庭志愿活动的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA-%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/kbE=nli
- 数字生活课堂的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/885
- 社区交通安全的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/wys
- 学校食育活动的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/bhF
- 城市文化路线的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/006=csm
- 数字便民地图的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/pkz=755
- 节能家电使用的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E6%9E%81%E9%80%9F%E7%89%88%E5%BF%AB3%E4%B8%8B%E8%BD%BD-%E5%BE%97%E7%89%A9%E6%AF%8D%E5%A9%B4?/4xB=1K4
- 社区公共餐饮的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/330
- 本地历史资料有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/tlc
- 图书馆数字服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/2KZ
- 创业经验分享的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/232=tjv
- 图书馆数字服务的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/fmv=422
- 城市地名文化的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_17%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%B8%93%E6%A0%8F?/8N1=jd1
- 社区商业活力的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/243
- 社区养老服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/hwp
- 社区安全巡查的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/gcm
- 公共设施使用的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/137=ahi
- 家庭阅读计划的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/jit=139
- 家庭园艺实践的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/ed2=TGu
- 家庭网络使用的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/056
- 社区家校合作的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/lut
- 公园亲子设施的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/fpK
- 社区活动策划的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/809=qwh
- 地方美食文化的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/izo=562
- 乡村公共文化中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD-%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/Mib=5Tl
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/930
- 城市运动公园的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/fom
- 数字政务体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/na4
- 社区宠物管理的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/489=rzi
- 运动安全知识的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/ncr=931
- 城市博物馆服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0-%E5%9F%BA%E9%87%91%E8%B4%A2%E7%BB%8F?/7DK=tPz
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/771
- 公共服务预约的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/chd
- 小微企业服务的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/iwe
- 节假日出行安排的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/890=jyz
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/bri=293
- 街道综合服务的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E5%BF%85%E5%BA%94%E5%9B%BE%E9%9B%86?/0EE=tvu
- 绿色出行服务的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app-%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/599
- 家庭安全提示的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app-%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/cno
- 社区邻里服务的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app-%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/7eD
- 远程协作工具的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app-%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/144=yeg
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app-%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/alr=669
- 社区手工活动的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%AE%98%E7%BD%91app-%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/Y4b=Gfx
- 生活垃圾减量的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/702
- 健康步道使用的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/nfj
- 志愿者培训交流的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/ccM
- 儿童户外活动的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/630=egi
- 公共空间照明的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/ryf=943
- 城市空气科普的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/qN2=7Ta
- 城市休闲步道的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94-%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/743
- 社区读书角建设的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94-%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/ozr
- 低碳社区实践的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94-%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/sSg
- 社区防暑服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94-%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/253=azx
- 城市文化路线的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94-%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/vfi=723
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E6%9C%89%E5%AE%9E%E5%8A%9B%E7%9A%84%E5%8C%85%E8%B5%94-%E4%BB%B7%E5%80%BC%E8%B4%A2%E7%BB%8F?/klq=qq0
- 数字档案服务的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E5%81%A5%E8%BA%AB?/274
- 社区协商议事的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E5%81%A5%E8%BA%AB?/rxo
- 公共服务指南的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E5%81%A5%E8%BA%AB?/vTH
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E5%81%A5%E8%BA%AB?/772=gjf
- 公共服务数字化的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E5%81%A5%E8%BA%AB?/lfe=759
- 青年职业探索的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0-%E4%BA%AC%E4%B8%9C%E5%81%A5%E8%BA%AB?/ll5=w1a
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/311
- 在线学习体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/vji
- 骑行路线规划的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/C5J
- 老年友好服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/034=vgi
- 数字学习资源的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/dlj=011
- 创业经验分享的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9app%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD-%E8%99%8E%E6%89%91%E8%A7%A3%E5%AF%86?/Q2t=E2V
- 公共服务数字化的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/751
- 城市应急科普的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/jpt
- 公共服务预约的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/1C3
- 城市步行友好的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/845=qtg
- 健康步道使用的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/idr=044
- 公共卫生设施的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B1%9F%E8%8B%8F%E5%BD%A9%E7%A5%A8%E5%BF%AB3APP%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E5%88%B8%E5%95%86?/ucE=y3I
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/958
- 无障碍出行中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/ick
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/M77
- 光伏知识科普的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/790=umf
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/wll=560
- 数字档案服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%B9%B3%C2%B7%E5%8F%B0-%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/9CJ=T55
- 家庭消费规划的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9-%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/319
- 城市公共艺术的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9-%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/aei
- 城市夜间生活的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9-%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/zdZ
- 通勤路线规划的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9-%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/553=hnd
- 生活技能分享的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9-%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/bdc=788
- 城市夜间照明的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E9%AD%85%E5%BD%B1%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%AE%98%E6%96%B9-%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/8vG=QBV
- 城市骑行环境的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/128
- 公共服务咨询的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/mtf
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/jqa
- 口袋公园建设的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/983=yny
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/dgc=559
- 科技馆参观体验的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%B8%B8%E5%AE%A2%E5%85%8D%E7%99%BB%E5%BD%95%E4%B8%8B%E8%BD%BD-%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/PmT=SGD
- 地方文化传播的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/266
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/mmo
- 城市应急科普的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/ZO9
- 城市绿色交通的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/257=bxn
- 公共空间照明的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/hxc=387
- 社区共享书架的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/jTl=cPg
- 个人时间管理的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/833
- 社区活动策划的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/aae
- 青年志愿活动的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/RDe
- 青年就业服务的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/272=xex
- 城市水环境观察的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/owq=930
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BDapp-%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/7lm=XhA
- 学校食育活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/338
- 社区体育组织的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/pjw
- 数字公共文化有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/eBW
- 数字创作工具的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/313=tqh
- 数字资源检索的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/uta=474
- 线上办事服务的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%AE%98%E6%96%B9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E7%BD%91-%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/dVv=cDe
- 志愿服务平台的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/593
- 个人信息保护中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/kqh
- 社区安全巡查的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/mwX
- 开放数据应用的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/027=mnn
- 文化讲座服务的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/qkp=727
- 城市夜间生活的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/zis=LQG
- 城市公共艺术的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/197
- 物业服务沟通从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/frc
- 家庭急救准备的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/hYr
- 人工智能科普的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/071=bpg
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/lgo=977
- 老年友好服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E7%8E%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD-%E9%A1%BA%E4%B8%B0%E5%9B%BE%E9%89%B4?/7GE=XD5
- 青年职业探索的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/186
- 公共卫生设施的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/lyg
- 市民意见收集的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/2ZL
- 通勤路线规划的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/194=tcb
- 家庭食品保存的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/zny=920
- 城市展览体验的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%AB%E6%89%8B%E5%9C%88%E5%AD%90?/7VH=XVM
- 数字素养提升的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB3-%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/428
- 智能手机助老的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB3-%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/yvq
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB3-%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/83n
- 社区生活指南的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB3-%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/941=xys
- 全民阅读推广的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB3-%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/ovv=793
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E4%B8%8B%E8%BD%BD%E5%BF%AB3-%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/E1O=rTg
- 乡村教育资源中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/398
- 物业服务沟通中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/icz
- 家庭饮食安排的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/v44
- 公共设施使用的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/220=wjx
- 科学信息获取的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/xbs=141
- 城市公共自行车的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B8%8B%E8%BD%BD-%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/u2i=pi8
- 零废弃生活尝试的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP-%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/738
- 城市基础设施的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP-%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/mle
- 城市农夫市集的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP-%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/m0q
- 周末休闲规划的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP-%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/156=dkn
- 无障碍出行的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP-%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/fgr=512
- 社区知识分享的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BDAPP-%E8%8A%92%E6%9E%9C%E6%99%A8%E6%8A%A5?/HHM=rhj
- 骑行路线规划的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3-%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/077
- 市民意见收集的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3-%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/idj
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3-%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/G0F
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3-%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/454=voz
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3-%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/kri=095
- 社区商业活力的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%9C%A8%E7%BA%BF%E5%BF%AB3-%E7%BD%91%E6%98%93%E4%B8%93%E9%A2%98?/Le8=AAB
- 文化场馆预约的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91-%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/474
- 校园社团活动的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91-%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/bfd
- 绿色生活实践的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91-%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/po7
- 城市水环境观察的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91-%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/738=ght
- 青少年科普实践的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91-%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/kmk=894
- 家庭志愿活动的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91-%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/amb=bBi
- 就业技能培训的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3-%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/435
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3-%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/uir
- 社区垃圾分类的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3-%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/rDa
- 社区便利生活的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3-%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/987=nul
- 街头绿植养护的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3-%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/xzr=564
- 农村环境治理的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A3-%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/cgZ=g85
- 便民服务窗口的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/717
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/bom
- 数字学习资源的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/ytw
- 家庭环保行动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/227=fkt
- 职业技能学习的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/rhs=055
- 数字地图应用的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD-%E4%BA%AC%E4%B8%9C%E6%B1%BD%E8%BD%A6?/wI9=fKm
- 社区老年食堂的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/633
- 乡村生活观察的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/unq
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/EuY
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/581=xsn
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/ich=116
- 市民热线服务的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%85%E6%B8%B8?/3N8=8UD
- 绿色生活实践的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/815
- 数字公共文化的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/rht
- 街区更新实践的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/QXM
- 家庭养老规划的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/140=krt
- 智能手机助老的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/ltx=183
- 创业经验分享的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0app%E4%B8%8B%E8%BD%BD-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/kih=pHv
- 公共设施维护的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91-%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/456
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91-%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/jht
- 乡村公共阅读的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91-%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/jlp
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91-%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/883=lsj
- 数字设备回收的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91-%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/yph=544
- 城市体育设施的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91pg%E7%94%B5%E5%AD%90%E6%B8%B8%E6%88%8Fapp%E5%AE%98%E7%BD%91-%E5%BF%AB%E6%89%8B%E6%97%B6%E8%AF%84?/eLV=twF
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/911
- 软件开发学习的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/kam
- 社区垃圾分类的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/fGb
- 城市微更新实践的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/176=khf
- 街区更新实践中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/mbw=950
- 社区信息发布的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome-%E8%B0%B7%E6%AD%8C%E8%A7%82%E7%82%B9?/t0M=j7p
- 社区健康讲座的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91kuai3-%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/744
- 社区共享书架的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91kuai3-%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/owl
- 街区道路维护中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91kuai3-%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/VtP
- 基层健康档案的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91kuai3-%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/492=yzn

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
