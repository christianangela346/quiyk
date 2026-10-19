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

- 社区公共餐饮的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E4%BC%97%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/efj=642
- 城市游园体验的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E4%BC%97%E5%BD%A9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/BZL=VwQ
- 家庭志愿活动的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91jc_360%E7%95%85%E6%B8%B8?/232
- 家庭健康科普的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91jc_360%E7%95%85%E6%B8%B8?/jht
- 在线学习体验的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91jc_360%E7%95%85%E6%B8%B8?/Npz
- 儿童户外活动的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91jc_360%E7%95%85%E6%B8%B8?/560=ggp
- 地方美食文化的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91jc_360%E7%95%85%E6%B8%B8?/mzr=410
- 城市水环境观察的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E8%81%9A%E5%BD%A9%E5%AE%98%E7%BD%91jc_360%E7%95%85%E6%B8%B8?/N72=GHJ
- 社区修缮行动的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E5%90%97_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/593
- 节气饮食文化的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E5%90%97_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/wve
- 学校体育活动的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E5%90%97_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/kK5
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E5%90%97_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/965=dgd
- 数据分析入门的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E5%90%97_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/qzs=694
- 社区活动报名的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E5%8F%AF%E4%BB%A5%E5%90%97_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/ZXD=6L3
- 社区休闲设施的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BD%95%E4%B8%8D%E6%81%A2%E5%A4%8D_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/358
- 跨代沟通活动的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BD%95%E4%B8%8D%E6%81%A2%E5%A4%8D_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/mly
- 地方戏曲体验的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BD%95%E4%B8%8D%E6%81%A2%E5%A4%8D_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/NU5
- 绿色生活实践的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BD%95%E4%B8%8D%E6%81%A2%E5%A4%8D_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/062=ivs
- 城市休闲步道的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BD%95%E4%B8%8D%E6%81%A2%E5%A4%8D_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/gyg=280
- 环境教育课程的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E7%A5%A8%E4%B8%BA%E4%BD%95%E4%B8%8D%E6%81%A2%E5%A4%8D_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/n9Y=t0F
- 全民健身活动的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91.%E5%8F%B3%E4%BE%A7%E7%BD%91%E7%A5%893805%E7%A2%98top_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/043
- 数字创作工具的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91.%E5%8F%B3%E4%BE%A7%E7%BD%91%E7%A5%893805%E7%A2%98top_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/oib
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91.%E5%8F%B3%E4%BE%A7%E7%BD%91%E7%A5%893805%E7%A2%98top_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/24g
- 校园社团活动的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91.%E5%8F%B3%E4%BE%A7%E7%BD%91%E7%A5%893805%E7%A2%98top_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/874=bdo
- 社区菜市场服务的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91.%E5%8F%B3%E4%BE%A7%E7%BD%91%E7%A5%893805%E7%A2%98top_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/tae=783
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91.%E5%8F%B3%E4%BE%A7%E7%BD%91%E7%A5%893805%E7%A2%98top_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/Up5=aq6
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/663
- 安全出行教育的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/gpu
- 社区心理支持的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/vVy
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/646=wfu
- 健康饮食教育的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/mja=460
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9app%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A7%E5%85%A8_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/T4A=Tfr
- 城市公共座椅的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%83%BD%E6%81%A2%E5%A4%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/774
- 节能生活方式的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%83%BD%E6%81%A2%E5%A4%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/wmi
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%83%BD%E6%81%A2%E5%A4%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/NAI
- 科学教育活动的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%83%BD%E6%81%A2%E5%A4%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/397=vvp
- 公共设施使用的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%83%BD%E6%81%A2%E5%A4%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/gao=303
- 人工智能科普的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E7%BD%91%E4%B8%8A%E8%B4%AD%E5%BD%A9%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E8%83%BD%E6%81%A2%E5%A4%8D_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AE%AF?/rfY=OdO
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/167
- 儿童阅读角的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/plt
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/1ay
- 居家防滑改造的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/435=qwu
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/wrz=971
- 校园节能行动的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E4%BA%94%E5%BD%A9%E5%A0%82%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%83%BD%E6%BA%90?/SRa=kg2
- 食品配送体验的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/709
- 乡村教育资源的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/quq
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/Yvp
- 社区绿色空间的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/792=fwo
- 文明养宠科普的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/vta=527
- 机器学习入门的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E4%BA%94%E5%BD%A9%E5%A0%82%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/sW8=V6R
- 文明养宠科普的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/842
- 家庭网络使用的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/lxn
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/XAl
- 公共空间安全的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/526=lxy
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/jnk=742
- 家庭健康科普的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/pVF=C3f
- 青年就业服务的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/044
- 社区公共餐饮的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/jfa
- 学校食育活动的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/lEN
- 社区托育服务的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/971=glo
- 地方文化传播的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/zat=414
- 社区垃圾分类的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E4%B8%AD%E5%BF%83_%E6%8A%96%E9%9F%B3%E8%88%86%E6%83%85?/WvU=am2
- 远程协作工具的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/628
- 数字创作工具的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/whu
- 城市公共标识的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/YzW
- 基层服务创新中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/794=umc
- 青年志愿活动的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/lqv=869
- 城市展览体验的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%BF%AB%E8%AE%AF?/Ksn=K5p
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/263
- 城市步行友好中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/xln
- 公交无障碍服务的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/KSN
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/032=afj
- 乡村文化空间的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/pad=989
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/LvX=WrU
- 公共健身器材从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/130
- 本地旅行体验的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/jom
- 社区托育服务的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/ZNG
- 公共健身器材的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/693=dro
- 老年人日常照护的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/hwc=327
- 创业经验分享的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E5%8D%83%E5%B8%86?/rMS=t6S
- 志愿服务平台的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/522
- 乡村产业科普的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/fjl
- 城市公共标识的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/KM4
- 个人时间管理的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/569=zfw
- 科普展览体验的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/erf=047
- 智慧停车服务的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/fkH=WPP
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/898
- 校园阅读活动的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/krp
- 社区文化传播的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/Z1N
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/792=nvn
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/xgw=857
- 学校体育活动的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E9%87%91%E7%9B%88%E8%B4%A2%E7%BB%8F?/GAU=dVU
- 休闲运动入门的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/749
- 公交无障碍服务的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/tvb
- 数字设备回收的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/yNf
- 在线学习体验的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/482=zzz
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/vjw=446
- 公交站点体验的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/Cb8=jFF
- 儿童户外活动中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/011
- 运动安全知识的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/xwr
- 城市农夫市集的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/G3Q
- 健康信息获取的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/098=vcc
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/fxx=248
- 社区活动空间的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/JEO=f22
- 城市休闲步道的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/852
- 气象科普传播的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/sdy
- 家庭运动计划的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/VPv
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/526=hyw
- 社区商业活力的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/syv=389
- 智能手机助老的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E7%BE%8E%E5%A6%86?/8Be=cUq
- 校园安全教育的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/161
- 社区快递服务的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/ypx
- 家庭园艺实践的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/spD
- 数字创意课程的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/320=lnp
- 青少年户外教育的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/lng=111
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%85%BE%E8%BE%BE%E8%B4%A2%E7%BB%8F?/zdU=g6o
- 社区应急准备的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/556
- 家庭节能实践的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/qmz
- 城市公共饮水的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/KsG
- 公共卫生宣传的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/553=peg
- 科普展览体验的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/tdp=983
- 物业服务沟通的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%A8%B1%E4%B9%90?/j9n=yyW
- 线上阅读资源的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8welcome_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/398
- 城市农夫市集的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8welcome_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/xvq
- 家庭运动计划的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8welcome_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/AzN
- 社区绿色空间的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8welcome_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/837=mpd
- 城市生活记录的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8welcome_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/fdi=163
- 城市社区治理的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8welcome_%E6%96%B0%E6%B5%AA%E5%8F%B8%E6%B3%95?/kJW=1xW
- 城市建设科普的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/500
- 城市公共厕所的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/ekr
- 家庭收纳实践的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/GmJ
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/276=zdb
- 老年人出行服务的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/fbf=402
- 数字公共文化的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%BC%8E%E8%B4%A2%E7%BB%8F?/Jz9=LWR
- 城市空气科普的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/766
- 电动汽车充电的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/zku
- 亲子科普活动的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/yva
- 家庭安全提示的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/648=znp
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/tvj=363
- 城市骑行环境的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/UIZ=orc
- 城市可持续生活的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/541
- 城市噪声观察的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/xyw
- 城市便民驿站的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/t4R
- 电子商务服务的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/322=hzi
- 城市展览体验的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/mgt=351
- 乡村产业科普的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E6%A5%BC%E5%B8%82?/prm=xN4
- 青少年心理健康的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/206
- 新能源知识普及的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/fvf
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/9j3
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/964=mln
- 医院导诊服务的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/kpw=178
- 居家适老化改造的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/vpI=Z79
- 食品安全科普的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D24%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/255
- 社区邻里服务的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D24%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/hng
- 城市噪声观察的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D24%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/oT3
- 城市社区治理的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D24%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/995=hfx
- 传统节日科普的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D24%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/ruv=524
- 公共场馆服务的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D24%E5%B0%8F%E6%97%B6%E4%BA%BA%E5%B7%A5%E6%9C%8D%E5%8A%A1%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%89%B4?/Jvc=NSh
- 个人数据管理的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/075
- 社区故事采集的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/gzf
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/I87
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/620=pir
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/pvg=915
- 街区更新实践的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E4%BF%A1%E8%AE%BF?/mpM=U1Z
- 城市运动公园的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/538
- 城市建设科普的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/yqk
- 社区家校合作的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/6Yy
- 农产品消费体验的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/974=ztq
- 公共服务评价的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/elq=956
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E8%B7%9F%E5%8D%95%E7%B1%BB%E8%B5%84%E9%87%91%E7%9B%98%E9%AA%97%E5%B1%80_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/Joj=ymT
- 公共设施使用中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/700
- 居民健康教育的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/ldw
- 公共交通接驳的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/hCn
- 骑行路线规划的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/507=msu
- 在线教育体验中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/bla=042
- 传统手工艺体验的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%85%91%E5%A5%96_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/l8U=DwB
- 城市公共厕所中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/006
- 城市农夫市集的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/qpp
- 城市公共艺术的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/e9V
- 老年人文化生活有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/941=bag
- 公园无障碍服务的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/yzo=409
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E5%8D%B3%E5%88%BB%E9%9F%B3%E4%B9%90?/ER4=A4L
- 绿色办公实践的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/889
- 城市夜间生活的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/yrq
- 节约用水实践的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/Ja0
- 城市公共艺术的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/498=hsl
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/ies=408
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/vK4=5ra
- 城市公共标识的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/451
- 家庭陪伴活动的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/kau
- 休闲运动入门中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/oI9
- 乡村文化空间的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/667=gvf
- 药品使用科普的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/csf=919
- 乡村阅读空间的学习资源整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D%E5%A4%9A%E5%B0%91_%E6%BE%8E%E6%B9%83%E8%BE%9F%E8%B0%A3?/KSH=Kmm
- 数字学习资源的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/698
- 机器学习入门的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/okb
- 应急物资管理的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/As3
- 街区绿化养护的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/357=mqe
- 城市文明实践的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/ibp=661
- 公共设施使用的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E7%9E%AD%E6%9C%9B?/Jrc=QJ8
- 青少年心理健康的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/129
- 环境教育课程的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/ggi
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/Glv
- 公园亲子设施的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/284=fsn
- 文化场馆预约的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/fnv=713
- 科技馆参观体验的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E5%BF%AB%E6%89%8B%E6%99%A8%E6%8A%A5?/I0F=sLB
- 公共场所导视的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/851
- 数字档案服务的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/wir
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/PcF
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/409=qfo
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/jgi=057
- 公共交通信息服务的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_u28%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%9C%80%E6%96%B0%E6%B6%88%E6%81%AF_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/nSE=gPT
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/347
- 科学信息获取的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/hwo
- 亲子科普活动的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/wEz
- 城市适老服务的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/968=wgf
- 家庭急救准备的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/xwb=881
- 便民服务地图的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_u28%E5%BD%A9%E7%A5%A8%E4%BA%8C%E5%8D%83%E9%83%BD%E9%BB%91_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/sTo=m0S
- 食品安全科普的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/614
- 公共服务预约的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/fjo
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/iqu
- 校园安全教育的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/114=ltx
- 社区心理支持中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/sod=378
- 健康步道使用的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E4%BA%BA%E5%9B%9E%E5%BA%94_%E5%A4%B4%E6%9D%A1%E6%99%A8%E6%8A%A5?/IYa=KzU
- 科学运动指导的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/488
- 居民健康教育的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/bdp
- 城市建设科普中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/Crh
- 城市水环境观察中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/495=ujb
- 老年运动活动的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/wfh=716
- 青少年编程学习的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%88%E5%AD%90?/9UN=5cV
- 家庭消费规划的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/441
- 公园休闲体验的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/vxa
- 家庭理财科普的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/Yxn
- 街区小店体验的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/685=jyb
- 社区环保活动的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/jtf=260
- 电动汽车充电从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%A2%E6%9C%8D%E4%B8%8D%E5%9C%A8%E7%BA%BF%E6%AD%A3%E5%B8%B8%E5%90%97_%E9%9B%85%E8%99%8E%E7%BE%8E%E8%82%A1?/fR4=Q8c
- 校园阅读活动的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/333
- 社区商业活力的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/orf
- 公共服务指南的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/zkI
- 无障碍出行的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/234=tfv
- 无障碍出行的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/exv=520
- 环境监测科普的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E4%B8%8D%E4%BA%86%E6%AC%BE%E5%AE%A2%E6%9C%8D%E9%83%BD%E4%B8%8D%E5%9C%A8%E7%BA%BF%E4%BA%86%2C%E8%A2%AB%E9%BB%91%E4%BA%86_%E5%AE%9E%E5%8A%9B%E8%B4%A2%E7%BB%8F?/uUB=2US
- 城乡公共服务的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_360%E6%B3%95%E5%BE%8B?/592
- 城市公共空间的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_360%E6%B3%95%E5%BE%8B?/jnb
- 社区儿童活动的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_360%E6%B3%95%E5%BE%8B?/TAw
- 社区家校合作的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_360%E6%B3%95%E5%BE%8B?/707=pmt
- 社区绿色空间的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_360%E6%B3%95%E5%BE%8B?/ejl=614
- 网络安全教育中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%E6%9C%89%E4%BB%80%E4%B9%88%E5%8A%9E%E6%B3%95%E8%A7%A3%E5%86%B3_360%E6%B3%95%E5%BE%8B?/2ZG=MLI
- 创业经验分享的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%2C%E8%B5%84%E9%87%91%E4%B9%9F%E6%B2%A1%E9%80%80%E5%9B%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/628
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_u28%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%8F%90%E7%8E%B0%E4%B8%8D%E5%88%B0%E8%B4%A6%2C%E8%B5%84%E9%87%91%E4%B9%9F%E6%B2%A1%E9%80%80%E5%9B%9E%E5%B9%B3%C2%B7%E5%8F%B0_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/faq

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
