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

- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E-%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/558
- 数字公共文化的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E-%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/fhl
- 街道综合服务的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E-%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/qM8
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E-%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/389=lxn
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E-%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/lys=781
- 社区托育服务的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E-%E7%95%8C%E9%9D%A2%E8%81%8C%E5%9C%BA?/5TK=AVw
- 社区宠物管理的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk-%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/040
- 社区快递服务的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk-%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/ngb
- 科学教育活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk-%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/63j
- 非遗体验活动的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk-%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/288=sqz
- 基层健康档案的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk-%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/pnf=218
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk-%E6%90%9C%E7%8B%90%E9%97%AE%E7%AD%94?/qDV=AN8
- 农村环境治理的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_-%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/240
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_-%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/kbs
- 青年志愿活动的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_-%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/IZe
- 文化场馆预约的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_-%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/469=ymc
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_-%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/jkw=261
- 城市绿色交通的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97_-%E7%BD%91%E6%98%93%E6%B1%BD%E8%BD%A6?/ElU=BF2
- 社区便利生活的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/435
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/uyk
- 地方民俗记录的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/ghp
- 城市步行友好的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/588=lts
- 在线学习体验的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/ghd=208
- 数字资源检索的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/nV0=iYF
- 社区老年食堂的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F-%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/947
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F-%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/kxv
- 城市公共座椅的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F-%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/Q1w
- 光伏知识科普的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F-%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/326=zll
- 骑行路线规划的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F-%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/jzk=706
- 绿色出行服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F-%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/oXg=XEb
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/216
- 基层健康服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/rwp
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/vDZ
- 数字学习资源的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/800=oby
- 老年数字阅读的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ros=365
- 公益活动组织的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E4%BF%A1%E8%AF%9A%E8%B4%A2%E7%BB%8F?/w4y=hae
- 城乡交流活动的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82-%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/453
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82-%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/rdr
- 城市空气科普的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82-%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/i6j
- 城市雨天出行的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82-%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/303=hsn
- 物业服务沟通的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82-%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/aap=409
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82-%E4%BC%98%E9%85%B7%E5%9F%8E%E4%BA%8B?/Qbj=LnI
- 街区小店体验的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6_-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/119
- 旧物循环利用的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6_-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/kaq
- 家庭收纳实践的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6_-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/rT0
- 公交无障碍服务的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6_-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/842=ujo
- 社区便利生活的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6_-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/tqi=938
- 家庭网络使用的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6_-%E5%87%A4%E5%87%B0%E6%95%B0%E7%A0%81?/MzZ=N0C
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A-%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/067
- 非遗体验活动的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A-%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/ltg
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A-%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/4kM
- 城市农夫市集的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A-%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/430=obi
- 地方文化传播的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A-%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/vig=483
- 公共图书馆服务的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A-%E6%BE%8E%E6%B9%83%E9%94%90%E8%AF%84?/ghK=lgP
- 城市生活服务的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/662
- 绿色生活实践的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/hyz
- 个人时间管理的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/gRX
- 亲子阅读活动的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/039=wvx
- 基层健康档案中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/jir=058
- 青少年科技社团的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%AC%E5%91%8A?/jc8=hpU
- 数字生活课堂的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/291
- 社区环保活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wgv
- 公共空间休憩的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/f2n
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/915=zlx
- 儿童安全出行的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/brc=930
- 社区生活指南的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8-%E4%B8%AD%E7%9B%9B%E8%B4%A2%E7%BB%8F?/m1G=tLp
- 家庭理财科普的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/994
- 家庭健康科普的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/gvo
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/Gws
- 社区环保活动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/526=glm
- 本地旅行体验的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/ott=328
- 社区消防演练的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8-%E4%B8%9C%E6%AC%A7%E8%B4%A2%E7%BB%8F?/84c=TXG
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/283
- 社区共享书架的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/isu
- 家庭节能设备的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/wBp
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/262=kdq
- 家庭防灾准备的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/edi=200
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0-%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/Pg4=Zty
- 绿色校园实践的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/667
- 数字档案服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/zby
- 文明养宠科普的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/McV
- 街区道路维护的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/546=vzk
- 街道综合服务的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/eir=063
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/Cmo=bup
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B-%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/984
- 环境教育课程的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B-%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/rba
- 基层服务创新的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B-%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/zis
- 城乡公共服务的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B-%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/297=tbj
- 城市噪声观察的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B-%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/mlz=471
- 社区托育服务的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B-%E8%B0%B7%E6%AD%8C%E6%96%87%E5%8C%96?/mDi=EoX
- 公共场馆服务的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/005
- 城市社区治理的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/bbc
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/blP
- 智能手机助老中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/471=zfp
- 市民热线服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/wgq=311
- 社区健康讲座的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9-%E5%90%8C%E5%88%9B%E8%B4%A2%E7%BB%8F?/ytI=VwX
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/937
- 青年志愿活动的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/xvz
- 城市共享单车的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/HnS
- 科普展览体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/511=ejd
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/kkz=013
- 生活服务数字化的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C-%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/nce=lbj
- 社区便民集市的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/606
- 城市生活服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/sos
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/aef
- 志愿者培训交流的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/605=edb
- 社区生活指南的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/bmy=976
- 开放数据应用的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE-%E6%90%9C%E7%8B%90%E6%96%87%E6%91%98?/8F4=kCa
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/949
- 亲子阅读活动的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/bui
- 图书馆数字服务的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/wkJ
- 学校体育活动的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/633=tgh
- 软件开发学习的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/pxz=237
- 居家防滑改造的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E8%B4%A2%E7%BB%8F%E7%BE%8E%E5%A6%86?/Zd1=6Uo
- 绿色出行服务的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/593
- 社区商业活力的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/sda
- 社区志愿服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/KCn
- 志愿服务平台的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/834=wkn
- 家庭用电安全的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/ekf=474
- 乡村公共文化的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org-%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/TFZ=vxX
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top-%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/957
- 城市社区治理的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top-%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/vwx
- 智能手机助老的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top-%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/Nbx
- 环境教育课程的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top-%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/576=gwx
- 城市生活记录的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top-%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/imk=705
- 人工智能科普的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top-%E7%95%8C%E9%9D%A2%E7%BE%8E%E9%A3%9F?/90p=zOp
- 居民健康教育的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/164
- 低碳社区实践的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/aza
- 城市噪声观察的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/UEf
- 城市噪声观察的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/896=owv
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/apm=163
- 社区交通安全的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD-%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/zFa=UsT
- 儿童户外活动的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB-%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/077
- 社区科普课堂的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB-%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/ofy
- 老年运动活动的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB-%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/PW3
- 家庭养老规划的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB-%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/130=snv
- 城市文化路线的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB-%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/rbj=054
- 数字创意课程的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB-%E5%BF%AB%E6%89%8B%E8%83%BD%E6%BA%90?/kgU=FzZ
- 消防知识宣传的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/925
- 社区修缮行动的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/dec
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/xD2
- 乡村阅读空间的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/851=xzi
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/uzs=377
- 数字学习资源的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE-%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/680=ogr
- 社区生活指南的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91_-%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/574
- 城市体育设施的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91_-%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/vmg
- 老年学习活动的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91_-%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/FeO
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91_-%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/069=qik
- 科学观察活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91_-%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/rnl=009
- 本地消费场景的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%B9%8B%E5%AE%B6%E9%A6%96%E9%A1%B5%E7%BD%91_-%E6%90%9C%E7%8B%90%E6%94%BF%E5%8D%8F?/eI5=Tyt
- 城乡交流活动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9-%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/042
- 城市公共标识的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9-%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/gdl
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9-%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/FYD
- 城市基础设施的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9-%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/289=bap
- 数字创作工具的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9-%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/xml=041
- 全民健身活动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9-%E7%88%B1%E5%A5%87%E8%89%BA%E5%86%9C%E4%B8%9A?/m29=M14
- 儿童友好空间的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2-%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/443
- 儿童阅读角的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2-%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/bnc
- 城市绿道建设的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2-%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/v90
- 乡村公共文化的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2-%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/011=nxl
- 城市水环境观察的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2-%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/xgu=528
- 乡村公共阅读的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%8F%8C%E8%89%B2%E7%90%83%E4%B8%AD%E5%A5%96%E8%AE%B0%E5%BD%95%E6%9F%A5%E8%AF%A2-%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/XmG=Sy8
- 数字艺术创作的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F-%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/657
- 终身学习资源的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F-%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/hpw
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F-%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/zhb
- 小区公共照明的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F-%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/711=prh
- 药品使用科普的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F-%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/uuz=975
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E9%AB%98%E6%89%8B%E7%BB%9D%E5%AF%86%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F-%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/mLr=lwd
- 数字素养提升的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%B5%A2%E5%BD%A9%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/269
- 家庭防灾准备的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%B5%A2%E5%BD%A9%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/mcb
- 地方文化传播的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%B5%A2%E5%BD%A9%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/wix
- 公共场所导视的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%B5%A2%E5%BD%A9%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/723=yps
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%B5%A2%E5%BD%A9%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/bgg=874
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E8%B5%A2%E5%BD%A9%E7%BD%91-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%80%9F%E8%A7%88?/NFw=913
- 家庭健康科普的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/842
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/tec
- 社区消防演练的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/LrW
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/037=tbd
- 城市骑行环境的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/amo=671
- 光伏知识科普的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BB%93%E6%9E%9C-%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/a5Z=xEX
- 劳动教育实践的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84-%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/677
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84-%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/bsa
- 数字课堂应用中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84-%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/Ogb
- 社区花园共建的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84-%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/951=dtz
- 跨代沟通活动的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84-%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/heu=881
- 农产品品牌传播的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%BA%84%E5%AE%B6%E6%98%AF%E5%A6%82%E4%BD%95%E6%9D%80%E4%B8%80%E4%B8%AA%E7%8E%A9%E5%AE%B6%E7%9A%84-%E8%B4%A2%E7%BB%8F%E5%89%8D%E6%B2%BF?/jQM=5MF
- 城市农夫市集的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/511
- 乡村生态观察的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/dqu
- 地方美食文化中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/45f
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/019=zwr
- 社区消防演练的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/eqf=552
- 城市空气科普的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97-%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/HaP=GG4
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86-%E5%BE%97%E7%89%A9%E6%B6%88%E8%B4%B9?/960
- 新能源出行的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86-%E5%BE%97%E7%89%A9%E6%B6%88%E8%B4%B9?/vfp
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86-%E5%BE%97%E7%89%A9%E6%B6%88%E8%B4%B9?/5Eh
- 城市生活记录的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86-%E5%BE%97%E7%89%A9%E6%B6%88%E8%B4%B9?/551=wgv
- 城乡交通衔接的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86-%E5%BE%97%E7%89%A9%E6%B6%88%E8%B4%B9?/ino=728
- 开放式学习空间的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B5%A2%E4%B8%8D%E4%BA%86-%E5%BE%97%E7%89%A9%E6%B6%88%E8%B4%B9?/CNt=bRz
- 绿色消费选择的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/732
- 智慧城市体验的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/tvl
- 人工智能科普的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/iid
- 科技馆参观体验的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/358=ave
- 城市休闲步道的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/pmd=912
- 文明养宠科普的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E5%90%83%E5%A4%A7%E8%B5%94%E5%B0%8F-%E5%A4%B4%E6%9D%A1%E6%97%B6%E8%AF%84?/GGz=Jhn
- 城市体育设施的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91-%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/647
- 城市运动公园的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91-%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/ckh
- 数据分析入门中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91-%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/dP6
- 科学观察活动的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91-%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/918=wka
- 社区宠物管理的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91-%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/mvd=027
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80%E7%9A%84%E8%A7%86%E9%A2%91-%E6%90%9C%E7%8B%90%E6%92%AD%E6%8A%A5?/QYT=WEI
- 老年人文化生活的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E-%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/251
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E-%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/jzi
- 便民服务地图的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E-%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/zWT
- 社区停车服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E-%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/203=rbw
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E-%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/ued=392
- 公共服务咨询的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E6%8A%8A%E9%92%B1%E8%BF%BD%E5%9B%9E-%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/OKt=OjF
- 公共服务评价的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86-%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/950
- 数字学习资源的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86-%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/lvg
- 城市公共饮水的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86-%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/UcP
- 就业技能培训的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86-%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/799=ltq
- 科普展览体验的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86-%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/oja=508
- 城市地名文化的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E4%B8%8A%E7%98%BE%E4%BA%86-%E5%BF%AB%E6%89%8B%E6%96%87%E5%BA%93?/OhM=JnQ
- 社区宣传栏更新的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk-%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/474
- 全民阅读推广中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk-%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/pdz
- 家庭饮食安排的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk-%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/gV5
- 地方旅游导览的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk-%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/029=dwr
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk-%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/hwk=001
- 健康信息获取的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%AE%B3%E6%88%91--kk-%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/9mD=tl4
- 基层健康服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/372
- 城市夜间生活的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/lpz
- 城市公共厕所的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/sfW
- 家庭养老规划的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/357=mva
- 本地消费场景的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/tsf=283
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%BD%A9%E7%A5%A8%E7%9A%84%E7%BB%93%E5%B1%80-%E6%96%B0%E6%B5%AA%E8%A6%81%E9%97%BB?/437=SwB
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97-%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/429
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97-%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/lwn
- 智慧城市体验的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97-%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/gYb
- 老旧小区改造的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97-%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/150=axz
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97-%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/qkb=531
- 家庭食品保存的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E8%B5%8C%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E6%8A%A5%E8%AD%A6%E5%90%97-%E5%87%A4%E5%87%B0%E6%B3%95%E6%B2%BB?/wZT=CXn
- 城市公共艺术的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97-%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/536
- 社区手工活动的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97-%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/eut
- 家庭运动计划的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97-%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/die
- 乡村文化活动的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97-%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/517=vpo
- 城市文明实践的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97-%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/yso=347
- 学校食育活动中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E5%8F%AF%E4%BB%A5%E7%8E%B0%E9%87%91%E6%8D%A2%E6%94%AF%E4%BB%98%E5%AE%9D%E5%90%97-%E6%90%9C%E7%8B%90%E8%83%BD%E6%BA%90?/RIQ=qaD
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A_-%E5%A4%AE%E8%A7%86%E8%81%8C%E5%9C%BA?/613
- 社区绿色空间的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A_-%E5%A4%AE%E8%A7%86%E8%81%8C%E5%9C%BA?/oge
- 消防知识宣传的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A_-%E5%A4%AE%E8%A7%86%E8%81%8C%E5%9C%BA?/9wc
- 社区修缮行动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%B0%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E7%AE%97%E4%B8%8D%E7%AE%97%E8%B5%8C%E5%8D%9A_-%E5%A4%AE%E8%A7%86%E8%81%8C%E5%9C%BA?/249=yzm

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
