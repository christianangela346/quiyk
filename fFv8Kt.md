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

- 学校体育活动的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A8%81%E6%96%AF%E5%B0%BC%E6%96%AFww2299mc%E6%A3%8B%E7%89%8C_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/aru=955
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A8%81%E6%96%AF%E5%B0%BC%E6%96%AFww2299mc%E6%A3%8B%E7%89%8C_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/ZA3=qTr
- 青少年户外教育的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8D%9Aapp%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/903
- 地方戏曲体验的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8D%9Aapp%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/kaz
- 社区菜市场服务的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8D%9Aapp%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/60c
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8D%9Aapp%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/069=eik
- 老旧小区改造的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8D%9Aapp%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/drb=985
- 城市文明实践的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8D%9Aapp%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/ENZ=YHB
- 绿色快递包装的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_818%E6%A3%8B%E7%89%8Cwww%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/416
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_818%E6%A3%8B%E7%89%8Cwww%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/vdu
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_818%E6%A3%8B%E7%89%8Cwww%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/kpR
- 社区休闲设施的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_818%E6%A3%8B%E7%89%8Cwww%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/200=jpe
- 老年智能设备的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_818%E6%A3%8B%E7%89%8Cwww%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/huv=127
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_818%E6%A3%8B%E7%89%8Cwww%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/Ehk=VmN
- 科学教育活动的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BA%BF%E4%B8%8A%E7%BD%91%E5%9D%80_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/255
- 城市水环境观察的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BA%BF%E4%B8%8A%E7%BD%91%E5%9D%80_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/eaa
- 街区小店体验的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BA%BF%E4%B8%8A%E7%BD%91%E5%9D%80_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/wpH
- 个人时间管理的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BA%BF%E4%B8%8A%E7%BD%91%E5%9D%80_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/268=qvz
- 数字支付体验的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BA%BF%E4%B8%8A%E7%BD%91%E5%9D%80_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/tmt=195
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%8D%81%E5%A4%A7%E7%BD%91%E8%B5%8C%E7%BA%BF%E4%B8%8A%E7%BD%91%E5%9D%80_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/M0y=Ho9
- 健康步道使用的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/531
- 个人时间管理的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/gpm
- 地方戏曲体验的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/lPL
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/340=qkf
- 城市文化路线的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/zle=040
- 城市噪声观察的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/7cq=Eph
- 公共设施维护中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1688app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/425
- 线上办事服务的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1688app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/ywx
- 社区安全巡查的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1688app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/Dqi
- 社区文化节活动的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1688app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/482=ogx
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1688app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/bfy=982
- 老年友好服务的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_1688app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/Oit=DEE
- 儿童安全出行的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/871
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/tjf
- 街区绿化养护的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/O7u
- 社区垃圾回收的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/312=akp
- 青年就业服务的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/xrg=770
- 社区阅读服务中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/Lu2=SMC
- 个人时间管理的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%9B%BD%E5%AE%B6%E8%AE%A4%E5%8F%AF%E7%9A%84%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F%E6%97%A0%E5%B9%BF%E5%91%8A_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/044
- 家庭理财科普的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%9B%BD%E5%AE%B6%E8%AE%A4%E5%8F%AF%E7%9A%84%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F%E6%97%A0%E5%B9%BF%E5%91%8A_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/wfr
- 传统节日科普的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%9B%BD%E5%AE%B6%E8%AE%A4%E5%8F%AF%E7%9A%84%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F%E6%97%A0%E5%B9%BF%E5%91%8A_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/EHx
- 医院导诊服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%9B%BD%E5%AE%B6%E8%AE%A4%E5%8F%AF%E7%9A%84%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F%E6%97%A0%E5%B9%BF%E5%91%8A_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/597=mla
- 地方美食文化的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%9B%BD%E5%AE%B6%E8%AE%A4%E5%8F%AF%E7%9A%84%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F%E6%97%A0%E5%B9%BF%E5%91%8A_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/ssx=878
- 老年智能设备的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%9B%BD%E5%AE%B6%E8%AE%A4%E5%8F%AF%E7%9A%84%E8%B5%9A%E9%92%B1%E6%B8%B8%E6%88%8F%E6%97%A0%E5%B9%BF%E5%91%8A_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/Qbb=3Xx
- 城乡交流活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E6%89%93%E9%B1%BC%E5%B9%B3%C2%B7%E5%8F%B0%E8%83%BD%E6%8F%90%E7%8E%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/183
- 乡村阅读活动的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E6%89%93%E9%B1%BC%E5%B9%B3%C2%B7%E5%8F%B0%E8%83%BD%E6%8F%90%E7%8E%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/lbd
- 社区托育服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E6%89%93%E9%B1%BC%E5%B9%B3%C2%B7%E5%8F%B0%E8%83%BD%E6%8F%90%E7%8E%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/TzN
- 消防知识宣传的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E6%89%93%E9%B1%BC%E5%B9%B3%C2%B7%E5%8F%B0%E8%83%BD%E6%8F%90%E7%8E%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/386=lxm
- 城市基础设施的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E6%89%93%E9%B1%BC%E5%B9%B3%C2%B7%E5%8F%B0%E8%83%BD%E6%8F%90%E7%8E%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/pxt=111
- 社区修缮行动的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E6%AD%A3%E8%A7%84%E6%89%93%E9%B1%BC%E5%B9%B3%C2%B7%E5%8F%B0%E8%83%BD%E6%8F%90%E7%8E%B0_%E7%9F%A5%E4%B9%8E%E6%96%87%E5%BA%93?/0tL=pmD
- 社区交通安全的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%B8%AD%E5%AD%90%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E4%BF%9D%E9%99%A9?/807
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%B8%AD%E5%AD%90%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E4%BF%9D%E9%99%A9?/cho
- 邻里共享空间的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%B8%AD%E5%AD%90%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E4%BF%9D%E9%99%A9?/JTc
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%B8%AD%E5%AD%90%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E4%BF%9D%E9%99%A9?/251=yau
- 数字支付体验的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%B8%AD%E5%AD%90%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E4%BF%9D%E9%99%A9?/ffv=843
- 基层健康档案的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E9%B8%AD%E5%AD%90%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_360%E4%BF%9D%E9%99%A9?/D0E=TVg
- 节日文化体验的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/708
- 图书借阅体验的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/cfg
- 街区小店体验的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/G4U
- 街道综合服务的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/726=sri
- 志愿服务平台的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/lmp=155
- 社区交通安全的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1_%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F?/CWL=WMF
- 开放式学习空间的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E5%8E%8B%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/841
- 公共空间休憩的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E5%8E%8B%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/gmz
- 儿童阅读角的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E5%8E%8B%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/miX
- 节气饮食文化的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E5%8E%8B%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/181=xzl
- 家庭食品保存的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E5%8E%8B%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/tjj=791
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E4%B8%80%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%85%E9%92%B1%E5%8E%8B%E5%A4%A7%E5%B0%8F%E8%B5%9A%E9%92%B1_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%A9%E7%A5%A8?/8qQ=bP2
- 社区便利生活的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E6%89%93%E9%B1%BC%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/394
- 数字设备回收的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E6%89%93%E9%B1%BC%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/ikf
- 青少年心理健康的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E6%89%93%E9%B1%BC%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/QF8
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E6%89%93%E9%B1%BC%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/042=ukh
- 社区修缮行动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E6%89%93%E9%B1%BC%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/jxk=306
- 数字学习资源的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E6%89%93%E9%B1%BC%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E7%9A%84_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/vTX=HjI
- 公共交通接驳的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/047
- 社区科普课堂的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/rcw
- 社区家校合作的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/vrZ
- 气象科普传播的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/882=rry
- 软件开发学习的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/mjl=453
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E8%B5%A2%E9%92%B1%E6%B8%B8%E6%88%8F%E5%8F%AF%E4%BB%A5%E6%8F%90%E7%8E%B0%E5%BE%AE%E4%BF%A1_%E6%90%9C%E7%8B%90%E7%A4%BE%E8%AE%BA?/sXi=Vpf
- 社区公共卫生的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%88%86%E4%BA%AB%E4%B8%80%E4%B8%AA3D%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/587
- 社区教育资源的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%88%86%E4%BA%AB%E4%B8%80%E4%B8%AA3D%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/nma
- 绿色出行服务的设施维护观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%88%86%E4%BA%AB%E4%B8%80%E4%B8%AA3D%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/UMS
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%88%86%E4%BA%AB%E4%B8%80%E4%B8%AA3D%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/994=voj
- 家庭健康管理的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%88%86%E4%BA%AB%E4%B8%80%E4%B8%AA3D%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/wem=211
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%88%86%E4%BA%AB%E4%B8%80%E4%B8%AA3D%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/XSD=Hgo
- 城市应急广播的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/788
- 城市可持续生活的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/ksw
- 社区读书角建设的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/Ivd
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/898=woj
- 城市住房服务的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/mkf=169
- 家庭运动计划的服务体验观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E7%A6%8F%E5%BD%A93D%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E9%80%9A%E4%BF%A1?/iAx=DhV
- 城市公共厕所的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/767
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/zda
- 本地消费场景的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/3A5
- 城市游园体验的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/165=pgd
- 科学健身方法的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/xjd=246
- 低碳社区实践的日常使用指南 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E9%80%9A%E4%BF%A1?/xOq=kNa
- 家庭教育交流的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%BC%8F%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/154
- 老年友好服务的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%BC%8F%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/xwe
- 智能手机助老的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%BC%8F%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/63W
- 家庭安全提示的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%BC%8F%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/404=ahl
- 社区便利生活的公共信息获取方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%BC%8F%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/vsx=797
- 青少年心理健康的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%BC%8F%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D_%E5%A4%AE%E8%A7%86%E6%88%BF%E4%BA%A7?/nDF=eQY
- 社区公共餐饮的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/797
- 公益活动组织的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/grw
- 乡村电商实践的协作机制梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/1Z5
- 公共空间照明的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/840=nea
- 光伏知识科普的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/dqp=277
- 老年友好服务的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/e0F=vJB
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/833
- 城市展览体验的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/pch
- 社区公共议事的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/fPa
- 在线学习体验的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/310=akz
- 乡村公共服务的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/rwz=046
- 社区教育资源的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%80%8E%E4%B9%88%E5%88%A4%E6%96%AD%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/fUE=ako
- 终身学习资源的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%B0%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/787
- 节能家电使用的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%B0%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/bio
- 数字支付体验的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%B0%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/7uk
- 公共空间安全的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%B0%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/372=sbm
- 社区协商议事的组织方法与经验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%B0%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/dht=792
- 节日文化体验的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E4%B9%B0%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%BD%E8%B5%A2%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/n2b=4DJ
- 城市公共饮水的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/053
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/ryn
- 开放数据应用的日常实践笔记 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/bRC
- 公交无障碍服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/776=xhi
- 城市骑行环境的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/rhk=563
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%8D%95%E5%8F%8C_%E5%93%81%E7%89%8C%E8%B4%A2%E7%BB%8F?/a1R=edG
- 城市游园体验的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/191
- 基层健康档案的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/eqy
- 城乡公共服务的长期维护要点 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/TIk
- 垃圾分类指导的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/480=cqu
- 社区停车服务的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/sbs=913
- 急救知识普及的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F_%E5%9B%BD%E6%B1%87%E8%B4%A2%E7%BB%8F?/lNY=cUe
- 公共卫生宣传的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%BE%B3%E9%97%A8%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/802
- 开放数据应用的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%BE%B3%E9%97%A8%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/jdt
- 志愿服务平台的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%BE%B3%E9%97%A8%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/B81
- 家庭消费规划的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%BE%B3%E9%97%A8%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/163=srd
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%BE%B3%E9%97%A8%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/lck=024
- 公园休闲体验的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E6%BE%B3%E9%97%A8%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E5%BD%A9%E7%A5%A8?/prD=H82
- 数字资源检索的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/532
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/klc
- 社区教育资源的适老服务细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/7mi
- 城市水环境观察的日常记录与分享 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/380=eur
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/ece=071
- 社区停车服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/Pec=zaH
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%B0%8F%3D%E5%B0%8F_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/054
- 社区家校合作中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%B0%8F%3D%E5%B0%8F_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/yvx
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%B0%8F%3D%E5%B0%8F_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/tyz
- 节约用水实践的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%B0%8F%3D%E5%B0%8F_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/302=wxz
- 居家适老化改造的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%B0%8F%3D%E5%B0%8F_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/nhm=164
- 消防知识宣传的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E5%A4%A7%E5%A4%A7%E5%B0%8F%E5%B0%8F%3D%E5%B0%8F_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/RgE=37D
- 老年学习活动的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/586
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/wak
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/APl
- 家庭健康科普的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/773=oxl
- 社区艺术活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/kfw=752
- 城市慢跑路线的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/Oxc=ALS
- 乡村阅读活动从需求出发看服务设计 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E5%9B%BE_36%E6%B0%AA%E8%AF%BB%E6%8A%A5?/273
- 儿童友好街区的资源利用方法 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E5%9B%BE_36%E6%B0%AA%E8%AF%BB%E6%8A%A5?/yuj
- 光伏知识科普的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E5%9B%BE_36%E6%B0%AA%E8%AF%BB%E6%8A%A5?/HDo
- 物业服务沟通的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E5%9B%BE_36%E6%B0%AA%E8%AF%BB%E6%8A%A5?/936=htr
- 社区活动报名的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E5%9B%BE_36%E6%B0%AA%E8%AF%BB%E6%8A%A5?/ite=596
- 社区防暑服务的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E5%9B%BE_36%E6%B0%AA%E8%AF%BB%E6%8A%A5?/5B1=KIh
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%9A%84%E7%A8%B3%E8%B5%9A%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/512
- 社区读书角建设的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%9A%84%E7%A8%B3%E8%B5%9A%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/xjc
- 社区学习活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%9A%84%E7%A8%B3%E8%B5%9A%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/x1Z
- 家庭教育交流从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%9A%84%E7%A8%B3%E8%B5%9A%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/208=lqc
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%9A%84%E7%A8%B3%E8%B5%9A%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/hcu=032
- 公共服务预约的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%9A%84%E7%A8%B3%E8%B5%9A%E6%94%BB%E7%95%A5_%E8%84%89%E8%84%89%E6%B0%91%E7%94%9F?/bxJ=EmF
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/317
- 无障碍出行的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/hbo
- 通勤路线规划的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/QZU
- 社区学习活动的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/479=ajm
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/oin=727
- 创业经验分享的使用门槛与改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/Bo9=2Mj
- 社区公共卫生的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A7%98%E7%AC%88_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/990
- 家庭收纳实践的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A7%98%E7%AC%88_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/shg
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A7%98%E7%AC%88_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/Jzz
- 社区文化传播的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A7%98%E7%AC%88_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/045=zuc
- 城市夜间照明的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A7%98%E7%AC%88_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/jwc=534
- 节能家电使用的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A7%98%E7%AC%88_%E8%B4%A2%E7%BB%8F%E6%B0%91%E7%94%9F?/dwa=Zas
- 公共文化活动的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7%E4%B9%B0%E6%B3%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/331
- 城市公共座椅的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7%E4%B9%B0%E6%B3%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/eix
- 机器人科普活动的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7%E4%B9%B0%E6%B3%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/TQj
- 社区家政服务的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7%E4%B9%B0%E6%B3%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/134=udf
- 城市应急科普的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7%E4%B9%B0%E6%B3%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/pcq=077
- 老年友好服务的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E6%8A%80%E5%B7%A7%E4%B9%B0%E6%B3%95%E5%85%AC%E5%BC%8F_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/fA4=9wo
- 家庭消费规划的社区参与观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%939%E7%A0%81%E7%A8%B3%E8%B5%A2%E4%B9%88_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/054
- 城市公共座椅的常见问题梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%939%E7%A0%81%E7%A8%B3%E8%B5%A2%E4%B9%88_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/yij
- 家庭环保行动的线下体验记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%939%E7%A0%81%E7%A8%B3%E8%B5%A2%E4%B9%88_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/wp9
- 青少年心理健康的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%939%E7%A0%81%E7%A8%B3%E8%B5%A2%E4%B9%88_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/550=zva
- 家庭用电安全的活动策划思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%939%E7%A0%81%E7%A8%B3%E8%B5%A2%E4%B9%88_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/pyl=526
- 急救知识普及的空间设计要点 |来源：https://github.com/leemelody014/btju/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%89%939%E7%A0%81%E7%A8%B3%E8%B5%A2%E4%B9%88_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/MoE=lEj
- 城市文化路线的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E4%B8%80%E7%9B%B4%E5%8E%8B%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/722
- 城市共享单车的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E4%B8%80%E7%9B%B4%E5%8E%8B%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/ylu
- 社区文化节活动的行动步骤参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E4%B8%80%E7%9B%B4%E5%8E%8B%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/Cr2
- 乡村公共文化的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E4%B8%80%E7%9B%B4%E5%8E%8B%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/151=ura
- 日常摄影记录的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E4%B8%80%E7%9B%B4%E5%8E%8B%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/cju=690
- 社区学习活动的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E8%B5%8C%E5%A4%A7%E5%B0%8F%E4%B8%80%E7%9B%B4%E5%8E%8B%E4%B8%80%E4%B8%AA%E7%A8%B3%E8%B5%A2%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/Lhr=gIu
- 智能手机助老的流程优化思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_8%E8%BF%9B8%E5%87%BA%E9%AB%98%E6%B8%85%E7%9F%A9%E9%98%B5_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/211
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_8%E8%BF%9B8%E5%87%BA%E9%AB%98%E6%B8%85%E7%9F%A9%E9%98%B5_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/teo
- 电动汽车充电的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_8%E8%BF%9B8%E5%87%BA%E9%AB%98%E6%B8%85%E7%9F%A9%E9%98%B5_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/a0R
- 节日文化体验的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_8%E8%BF%9B8%E5%87%BA%E9%AB%98%E6%B8%85%E7%9F%A9%E9%98%B5_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/495=gab
- 便民维修服务的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_8%E8%BF%9B8%E5%87%BA%E9%AB%98%E6%B8%85%E7%9F%A9%E9%98%B5_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/xwn=767
- 家庭运动计划的家庭实践清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_8%E8%BF%9B8%E5%87%BA%E9%AB%98%E6%B8%85%E7%9F%A9%E9%98%B5_%E7%95%8C%E9%9D%A2%E6%95%B0%E8%AF%BB?/FXR=LnM
- 社区宠物管理的执行流程参考 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%AC%A3%E8%B5%8Fw%D1%851%E7%82%B9vip_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%94%BE?/489
- 城市公共座椅的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%AC%A3%E8%B5%8Fw%D1%851%E7%82%B9vip_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%94%BE?/mgw
- 社区安全巡查的资源整合思路 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%AC%A3%E8%B5%8Fw%D1%851%E7%82%B9vip_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%94%BE?/7Jz
- 社区运动空间的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%AC%A3%E8%B5%8Fw%D1%851%E7%82%B9vip_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%94%BE?/411=rfa
- 城市生活记录的活动组织技巧 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%AC%A3%E8%B5%8Fw%D1%851%E7%82%B9vip_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%94%BE?/hhz=506
- 社区便民服务的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E6%AC%A3%E8%B5%8Fw%D1%851%E7%82%B9vip_%E7%95%8C%E9%9D%A2%E5%9B%9E%E6%94%BE?/mgh=jVU
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/270
- 个人时间管理的日常管理方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/jvy
- 公共空间照明的活动体验回顾 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/53B
- 街区更新实践的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/630=wvd
- 本地消费场景的绿色实践方法 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/jum=061
- 城市公共饮水的持续改进方向 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/AVM=Zkv
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F351_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/045
- 软件开发学习的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F351_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/xnj
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F351_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/HMk
- 在线教育体验中的沟通与协作 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F351_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/167=aoy
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F351_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/qpu=567
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F351_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/9mr=WUd
- 居民健康教育的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E8%90%BD%E6%B3%A2%E5%BA%8F%E8%BF%98%E6%98%AF%E6%8C%89%E5%A4%A7%E5%B0%8F%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/063
- 电动汽车充电中的几个关键细节 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E8%90%BD%E6%B3%A2%E5%BA%8F%E8%BF%98%E6%98%AF%E6%8C%89%E5%A4%A7%E5%B0%8F%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/xbk
- 社区艺术活动的数字化应用观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E8%90%BD%E6%B3%A2%E5%BA%8F%E8%BF%98%E6%98%AF%E6%8C%89%E5%A4%A7%E5%B0%8F%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/b9L
- 公共图书馆服务的社区行动案例 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E8%90%BD%E6%B3%A2%E5%BA%8F%E8%BF%98%E6%98%AF%E6%8C%89%E5%A4%A7%E5%B0%8F%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/149=ngv
- 智能手机助老的入门知识整理 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E8%90%BD%E6%B3%A2%E5%BA%8F%E8%BF%98%E6%98%AF%E6%8C%89%E5%A4%A7%E5%B0%8F%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/abg=282
- 社区防暑服务的服务质量观察 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E8%90%BD%E6%B3%A2%E5%BA%8F%E8%BF%98%E6%98%AF%E6%8C%89%E5%A4%A7%E5%B0%8F%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84__%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E5%86%85?/LNa=TNb
- 骑行路线规划的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8Fv7.6.5_360%E7%A4%BE%E8%AE%BA?/290
- 公共空间休憩的服务范围梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8Fv7.6.5_360%E7%A4%BE%E8%AE%BA?/eht
- 地方戏曲体验的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8Fv7.6.5_360%E7%A4%BE%E8%AE%BA?/VYt
- 老年学习活动的数字工具使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8Fv7.6.5_360%E7%A4%BE%E8%AE%BA?/393=qmk
- 光伏知识科普的便民做法梳理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8Fv7.6.5_360%E7%A4%BE%E8%AE%BA?/nrx=379
- 公共服务预约的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8Fv7.6.5_360%E7%A4%BE%E8%AE%BA?/WYs=rJp
- 小微企业服务的便捷程度观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E7%A8%B3%E5%AE%9A_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/238
- 地方美食文化的儿童友好细节 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E7%A8%B3%E5%AE%9A_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/vhs
- 绿色生活实践的实用信息清单 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E7%A8%B3%E5%AE%9A_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/oik
- 城市可持续生活的安全使用提示 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E7%A8%B3%E5%AE%9A_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/482=wqs
- 城乡交通衔接的服务信息整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E7%A8%B3%E5%AE%9A_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/elp=135
- 城市微更新实践的学习资源整理 |来源：https://github.com/leemelody014/btju/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F-%E7%A8%B3%E5%AE%9A_%E8%B0%B7%E6%AD%8C%E5%9B%BE%E9%9B%86?/2FG=4EX
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E4%BB%80%E4%B9%88%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/511
- 城市运动公园的居民参与机会 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E4%BB%80%E4%B9%88%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/zho
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E4%BB%80%E4%B9%88%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/FDv
- 旧物循环利用的基础设施观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E4%BB%80%E4%B9%88%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/361=eaf
- 乡村电商实践的便利性观察 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E4%BB%80%E4%B9%88%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/wyc=008
- 老年人文化生活的空间使用体验 |来源：https://github.com/leemelody014/btju/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E6%98%AF%E6%8C%89%E4%BB%80%E4%B9%88%E5%BA%8F%E8%BF%9B%E8%A1%8C%E8%AE%A1%E7%AE%97%E7%9A%84_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/Mid=tIy
- 全民健身活动的服务细节记录 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%99%A8%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/982
- 城市展览体验的公共参与指南 |来源：https://github.com/leemelody014/btju/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97%E5%99%A8%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%9E%AD%E6%9C%9B?/rbg

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
