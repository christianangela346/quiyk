# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 生活技能分享的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%A5%97%E8%B7%AF%E7%9A%84%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95-%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/mev=770
- 职业技能学习的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%A5%97%E8%B7%AF%E7%9A%84%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95-%E5%93%94%E5%93%A9%E6%B6%88%E8%B4%B9?/9mO=yfi
- 公园亲子设施的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%A6%E5%B1%9E%E4%BA%8E%E8%AF%88%E9%AA%97-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/029
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%A6%E5%B1%9E%E4%BA%8E%E8%AF%88%E9%AA%97-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/vqv
- 公共服务沟通的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%A6%E5%B1%9E%E4%BA%8E%E8%AF%88%E9%AA%97-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/Erv
- 乡村电商实践的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%A6%E5%B1%9E%E4%BA%8E%E8%AF%88%E9%AA%97-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/258=tiy
- 终身学习资源的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%A6%E5%B1%9E%E4%BA%8E%E8%AF%88%E9%AA%97-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/ojk=533
- 科学观察活动的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%A6%E5%B1%9E%E4%BA%8E%E8%AF%88%E9%AA%97-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/tYz=ACO
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E8%BF%91%E6%9C%9F%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E6%A1%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/339
- 健康信息获取的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E8%BF%91%E6%9C%9F%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E6%A1%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/isu
- 创业经验分享的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E8%BF%91%E6%9C%9F%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E6%A1%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/Oaq
- 音乐欣赏活动的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E8%BF%91%E6%9C%9F%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E6%A1%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/985=kmo
- 公园亲子设施的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E8%BF%91%E6%9C%9F%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E6%A1%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/hjq=686
- 城市建设科普的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E8%BF%91%E6%9C%9F%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E8%AF%88%E9%AA%97%E6%A1%88-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E7%82%B9?/Vmr=VQg
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%BB%E5%8A%A1-%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/120
- 城市生活记录的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%BB%E5%8A%A1-%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/hdg
- 食品配送体验中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%BB%E5%8A%A1-%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/N4M
- 城市公共标识的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%BB%E5%8A%A1-%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/828=uti
- 地方民俗记录的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%BB%E5%8A%A1-%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rhv=455
- 街道综合服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%8E%A9%E8%B5%9A%E4%BD%A3%E9%87%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%BB%E5%8A%A1-%E5%AE%8F%E6%B3%B0%E8%B4%A2%E7%BB%8F?/NVw=Mzv
- 街区更新实践的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9app%E9%AA%97%E4%BA%86%E5%8D%81%E5%87%A0%E4%B8%87-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/448
- 科技馆参观体验的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9app%E9%AA%97%E4%BA%86%E5%8D%81%E5%87%A0%E4%B8%87-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/iix
- 公共服务预约的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9app%E9%AA%97%E4%BA%86%E5%8D%81%E5%87%A0%E4%B8%87-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/IUT
- 街区绿化养护的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9app%E9%AA%97%E4%BA%86%E5%8D%81%E5%87%A0%E4%B8%87-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/034=osu
- 居家适老化改造的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9app%E9%AA%97%E4%BA%86%E5%8D%81%E5%87%A0%E4%B8%87-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/ogp=814
- 运动安全知识的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E4%B8%AD%E5%BD%A9app%E9%AA%97%E4%BA%86%E5%8D%81%E5%87%A0%E4%B8%87-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/0Fl=8E8
- 社区志愿服务的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A9%E8%B5%9A300%E5%85%83-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/898
- 社区商业活力的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A9%E8%B5%9A300%E5%85%83-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/vjd
- 老年人日常照护的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A9%E8%B5%9A300%E5%85%83-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/tBz
- 节日文化体验的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A9%E8%B5%9A300%E5%85%83-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/707=sot
- 社区协商议事的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A9%E8%B5%9A300%E5%85%83-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/npu=878
- 乡村文化空间的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%A4%A9%E8%B5%9A300%E5%85%83-%E4%BC%98%E9%85%B7%E5%AE%8F%E8%A7%82?/97d=1yp
- 社区公共议事的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E9%92%B1-%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/433
- 城市绿道建设的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E9%92%B1-%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/efd
- 社区互助网络的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E9%92%B1-%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/ezQ
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E9%92%B1-%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/918=ica
- 社区科普课堂的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E9%92%B1-%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/pff=367
- 社区设施共享的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E8%B5%9A%E9%92%B1-%E6%BE%8E%E6%B9%83%E4%BD%93%E8%82%B2?/XrZ=L1c
- 城市休闲步道的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E8%BF%98%E6%98%AF%E5%81%87%E7%9A%84-%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/569
- 小区公共照明的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E8%BF%98%E6%98%AF%E5%81%87%E7%9A%84-%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/byp
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E8%BF%98%E6%98%AF%E5%81%87%E7%9A%84-%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/QeT
- 个人信息保护的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E8%BF%98%E6%98%AF%E5%81%87%E7%9A%84-%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/085=nou
- 社区休闲设施的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E8%BF%98%E6%98%AF%E5%81%87%E7%9A%84-%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/yzz=142
- 数字便民地图的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E8%BF%98%E6%98%AF%E5%81%87%E7%9A%84-%E8%B4%A2%E7%BB%8F%E6%97%85%E6%B8%B8?/Psk=2rf
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E7%9F%A5%E4%B9%8E-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/269
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E7%9F%A5%E4%B9%8E-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/rkg
- 地方美食文化的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E7%9F%A5%E4%B9%8E-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/iSH
- 社区公共议事的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E7%9F%A5%E4%B9%8E-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/054=yty
- 健康饮食教育的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E7%9F%A5%E4%B9%8E-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/lte=999
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E7%9F%A5%E4%B9%8E-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BD%E9%99%85?/PqB=1Vr
- 社区快递服务的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97-%E7%95%8C%E9%9D%A2?/085
- 老年人日常照护的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97-%E7%95%8C%E9%9D%A2?/udj
- 数字便民地图的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97-%E7%95%8C%E9%9D%A2?/Cre
- 社区休闲设施的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97-%E7%95%8C%E9%9D%A2?/441=fdk
- 亲子阅读活动的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97-%E7%95%8C%E9%9D%A2?/irk=053
- 数字支付体验的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97-%E7%95%8C%E9%9D%A2?/nNH=mxt
- 便民服务地图的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6-%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/682
- 城市公共饮水的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6-%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/vwp
- 社区教育资源的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6-%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/N5g
- 社区绿色空间中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6-%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/801=qkg
- 城市博物馆服务的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6-%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/zmj=861
- 运动安全知识的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%B5%9A%E9%92%B1%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6-%E8%B4%A2%E7%BB%8F%E5%8E%BF%E5%9F%9F?/MkX=WWE
- 药品使用科普的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84-36%E6%B0%AA%E7%9B%98%E7%82%B9?/285
- 智慧城市体验的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84-36%E6%B0%AA%E7%9B%98%E7%82%B9?/oiu
- 公共服务咨询的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84-36%E6%B0%AA%E7%9B%98%E7%82%B9?/VGN
- 城市公共饮水的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84-36%E6%B0%AA%E7%9B%98%E7%82%B9?/329=fsa
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84-36%E6%B0%AA%E7%9B%98%E7%82%B9?/wpe=956
- 无障碍出行的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%9C%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%8E%A9%E6%98%AF%E4%B8%8D%E6%98%AF%E7%9C%9F%E7%9A%84-36%E6%B0%AA%E7%9B%98%E7%82%B9?/ObR=3UU
- 公共交通接驳的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/962
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/omt
- 社区垃圾回收的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/CYS
- 城市应急科普的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/571=gkt
- 数字设备回收的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/ddp=206
- 电动汽车充电的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1%E7%9A%84-%E5%BF%85%E5%BA%94%E6%A6%9C%E5%8D%95?/42T=lZc
- 社区科普课堂的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1-%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/897
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1-%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/tno
- 家庭网络使用的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1-%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/lSV
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1-%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/073=hbm
- 环境监测科普的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1-%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/jjn=932
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1-%E5%BF%AB%E6%89%8B%E6%95%99%E8%82%B2?/p4b=lJ3
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7-%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/983
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7-%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/xyy
- 家庭防灾准备的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7-%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/ncD
- 个人时间管理的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7-%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/747=xee
- 老旧小区改造的实用信息清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7-%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/rof=351
- 志愿者培训交流的常见问题梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%80%8E%E4%B9%88%E6%A0%B7-%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/3hA=8oG
- 软件开发学习的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/893
- 社区休闲设施的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/mbi
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/Vct
- 城市住房服务中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/093=sso
- 课后服务体验的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/bob=109
- 劳动教育实践的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E9%A1%BA%E4%B8%B0%E9%97%AE%E5%8D%B7?/n7L=T5w
- 城市基础设施的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80-%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/139
- 街区绿化养护的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80-%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/hkk
- 公共交通接驳的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80-%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/s1e
- 居民健康教育的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80-%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/098=hnt
- 数字支付体验的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80-%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/qqa=042
- 城乡交流活动的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80-%E8%99%8E%E6%89%91%E6%96%B0%E9%97%BB?/ult=98g
- 家庭节能实践的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/780
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/tqq
- 家庭健康科普的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/R7v
- 儿童安全出行的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/068=dll
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/zug=116
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E6%8A%96%E9%9F%B3%E4%B9%A6%E7%94%BB?/Dar=wsz
- 公共空间导览的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/552
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/yfn
- 公共文化活动的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/aZ3
- 气象科普传播的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/828=bxj
- 数字创作工具的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/lgi=139
- 地方戏曲体验的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E9%87%91%E7%89%8C%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E7%95%8C%E9%9D%A2%E5%BD%A9%E7%A5%A8?/7DD=dyK
- 城市展览体验的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/083
- 地方旅游导览的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/oox
- 乡村公共文化的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/i6e
- 创业经验分享的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/241=qdm
- 绿色建筑理念的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/ewe=292
- 家庭健康科普的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1-%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F?/RAG=pgZ
- 基层服务创新的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/081
- 公共文化活动的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/mnk
- 家庭消费规划的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/Wo6
- 在线教育体验的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/211=ska
- 无障碍出行的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/qvp=451
- 旧物循环利用的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E4%BA%AC%E4%B8%9C%E8%AE%BA%E5%9D%9B?/tSH=hsk
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97-%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/190
- 家庭急救准备的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97-%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/bzw
- 绿色消费选择的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97-%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/xIi
- 个人时间管理的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97-%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/246=dhl
- 青少年科普实践的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97-%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/lbk=744
- 城市绿道建设的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97-%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/Vnn=fHN
- 青年就业服务的日常管理方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/006
- 社区养老服务的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/bug
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/BJI
- 新能源出行的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/248=wdf
- 开放式学习空间的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/fak=286
- 公共交通信息服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8D%9A%E5%AE%A2?/M5F=eDe
- 家庭陪伴活动的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80-%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/025
- 城市建设科普的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80-%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/wxl
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80-%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/JaF
- 智能家居应用的家庭实践清单 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80-%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/895=bjz
- 全民健身活动的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80-%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/qdi=274
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E8%B5%9A%E9%92%B1%E5%B9%B3%C2%B7%E5%8F%B0%E9%AA%97%E5%B1%80-%E5%87%A4%E5%87%B0%E6%96%87%E5%8C%96?/vPr=rRH
- 生成式工具使用的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/654
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/aft
- 数字创意课程中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/UWD
- 社区安全巡查的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/646=cvd
- 城市文明出行的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/bwp=427
- 城市慢行系统的资源整合思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%B5%9A%E9%92%B1%E5%8C%85%E8%B5%94%E5%B8%A6%E8%B5%9A%E6%98%AF%E7%9C%9F%E7%9A%84%E9%82%A3-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%91%A8%E6%8A%A5?/476=Z6j
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/941
- 数字创意课程的使用门槛与改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/zon
- 个人时间管理的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/IzV
- 儿童安全出行的社区参与观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/383=emm
- 社区垃圾回收的空间使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/ldo=629
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94%E4%BB%BB%E5%8A%A1%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97-%E7%9F%A5%E4%B9%8E%E7%BE%8E%E5%A6%86?/epK=8Yj
- 公共服务数字化的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/307
- 邻里共享空间的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/wpr
- 城市雨天出行的行动步骤参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/jGx
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/023=eft
- 机器人科普活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/axv=520
- 城市社区治理的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%8D%95%E5%B8%A6%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92-%E5%BE%97%E7%89%A9%E5%AE%9E%E5%BD%95?/AqC=DoX
- 节约用水实践的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/338
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/miy
- 社区停车服务的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/10v
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/338=txn
- 科技馆参观体验的日常使用指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/zwu=543
- 物业服务沟通的组织方法与经验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E8%AE%A1%E5%88%92-%E8%99%8E%E5%97%85%E6%88%B7%E5%A4%96?/Ugm=zcP
- 社区公共议事的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/467
- 城市文化路线的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/avm
- 老年人日常照护的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/FNq
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/777=uld
- 校园社团活动的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/jre=773
- 老年学习活动的便利性观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%A4%A9%E8%B5%9A2000%E5%8A%A0%E5%BE%AE%E4%BF%A1-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F?/7en=x5H
- 周末休闲规划的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/261
- 城乡公共服务的服务细节记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/psj
- 公交站点体验的学习资源整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/9tj
- 旧物循环利用中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/036=nsm
- 城市游园体验的安全使用提示 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/lqh=648
- 农产品消费体验的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E7%BD%91%E4%B8%8A%E8%B5%9A%E9%92%B1%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A-%E5%8D%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/NT1=XmM
- 人工智能科普的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/928
- 社区活动报名的社区行动案例 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/ooy
- 环境教育课程中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/KBq
- 数字素养提升的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/682=ojq
- 全民健身活动的便捷程度观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/qop=034
- 城市建设科普的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B9%B3%C2%B7%E5%8F%B0-%E5%BF%85%E5%BA%94%E8%AF%BB%E5%9B%BE?/Ybp=jZo
- 网络安全教育中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/015
- 乡村生态旅游的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/qes
- 乡村公共文化的居民参与机会 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/CCV
- 机器学习入门的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/942=fpi
- 节约用水实践的基础知识问答 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/uqu=764
- 农产品消费体验的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7-%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/XDh=dQ5
- 地方美食文化的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E8%A7%82%E5%AF%9F?/865
- 青少年职业启蒙的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E8%A7%82%E5%AF%9F?/kiq
- 基层服务创新的空间设计要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E8%A7%82%E5%AF%9F?/oko
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E8%A7%82%E5%AF%9F?/055=rkr
- 绿色快递包装的公共参与指南 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E8%A7%82%E5%AF%9F?/zjt=845
- 公园休闲体验的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0-36%E6%B0%AA%E8%A7%82%E5%AF%9F?/x4P=99f
- 社区环保活动的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/117
- 社区邻里服务的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lef
- 社区体育组织的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/FvL
- 家庭安全提示的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/000=zob
- 家庭消费规划的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/flq=040
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/47T=28c
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD-%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/286
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD-%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/nch
- 城市空气科普的入门知识整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD-%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/Nrv
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD-%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/977=ycn
- 家庭照护支持的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD-%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/hov=203
- 城市可持续生活的执行流程参考 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD-%E5%93%94%E5%93%A9%E6%97%B6%E8%AF%84?/Q8B=Mju
- 健康步道使用的活动组织技巧 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88-%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/760
- 城市住房服务的服务体验观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88-%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/keg
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88-%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/ERF
- 校园阅读活动的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88-%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/518=rdy
- 生活垃圾回收的长期维护要点 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88-%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/blw=073
- 社区邻里服务的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88-%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/Qp8=OlP
- 社区交通安全的日常记录与分享 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E5%80%BA%E5%B8%82?/833
- 小区公共照明的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E5%80%BA%E5%B8%82?/vck
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E5%80%BA%E5%B8%82?/2Iq
- 社区宠物管理的绿色实践方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E5%80%BA%E5%B8%82?/186=cht
- 劳动教育实践的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E5%80%BA%E5%B8%82?/ssq=952
- 公共设施维护的阅读与学习资源 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%9A%E9%92%B1-36%E6%B0%AA%E5%80%BA%E5%B8%82?/0Br=wFW
- 节日文化体验的持续改进方向 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C-%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/329
- 数字资源检索的日常实践笔记 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C-%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/grr
- 垃圾分类指导的适老服务细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C-%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/kqN
- 城市绿道建设的协作机制梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C-%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/788=drf
- 儿童友好街区的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C-%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/cuz=931
- 小区公共照明的便民做法梳理 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%BC%E8%81%8C-%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AF%84?/cjb=2sh
- 老年数字阅读的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/057
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/otd
- 远程协作工具的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/PNq
- 便民服务窗口的线下体验记录 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/170=ipi
- 电子商务服务的资源利用方法 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/fsm=389
- 消防知识宣传的儿童友好细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7-%E6%90%9C%E7%8B%97%E5%8D%83%E5%B8%86?/TDs=XTh
- 数字学习资源的协商参与方式 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/985
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/nia
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/VLT
- 数字生活课堂的参与方式与路径 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/786=zxd
- 智慧停车服务的设施维护观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/xlt=526
- 社区文化传播的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/XoF=UR5
- 城市公共标识的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/082
- 数字素养提升的服务信息整理 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/pfl
- 社区公共餐饮的活动策划思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/qXU
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/204=qaf
- 数字公共文化的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/qsc=663
- 个人信息保护的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E8%B5%9A%E9%92%B1-%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/g8X=PSq
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/492
- 家庭阅读计划的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/urm
- 社区老年食堂的常见误区提醒 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/pBv
- 家庭收纳实践的服务质量观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/321=flo
- 图书借阅体验的流程优化思路 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/gvf=148
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%AF%BC%E5%B8%88%E5%B8%A6%E6%88%91%E4%BB%AC%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E6%96%B9?/wLo=TJY
- 校园节能行动中的几个关键细节 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F-%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/103
- 家庭环保习惯的基础设施观察 |来源：https://github.com/jonesdawn710/gvas/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A%E5%85%AC%E5%BC%8F-%E5%BE%97%E7%89%A9%E4%B9%A6%E7%94%BB?/ows

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
