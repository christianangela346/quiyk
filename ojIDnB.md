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

- 城乡公共服务中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1%E5%90%97-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/884
- 乡村教育资源的日常管理方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1%E5%90%97-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/xot
- 老年友好服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1%E5%90%97-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/QO7
- 无障碍信息设计的空间使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1%E5%90%97-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/003=mmb
- 市民热线服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1%E5%90%97-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/ycu=345
- 机器人科普活动的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E9%9D%A0%E8%B0%B1%E5%90%97-%E5%BE%97%E7%89%A9%E5%B9%B6%E8%B4%AD?/pqa=t2H
- 街区道路维护的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E9%AA%97%E5%B1%80-%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/572
- 社区修缮行动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E9%AA%97%E5%B1%80-%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/mbl
- 便民服务地图的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E9%AA%97%E5%B1%80-%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/tqd
- 公交站点体验的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E9%AA%97%E5%B1%80-%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/183=ttr
- 社区快递服务的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E9%AA%97%E5%B1%80-%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/ujr=773
- 社区读书角建设的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E9%AA%97%E5%B1%80-%E8%B0%B7%E6%AD%8C%E9%97%AE%E7%AD%94?/H2I=XXs
- 社区便民服务的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E5%BF%83%E9%85%B8-%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/051
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E5%BF%83%E9%85%B8-%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/xxd
- 社区运动空间的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E5%BF%83%E9%85%B8-%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/8Cu
- 智慧城市体验的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E5%BF%83%E9%85%B8-%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/089=lag
- 人工智能科普的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E5%BF%83%E9%85%B8-%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/tcm=740
- 公共设施维护的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E7%9A%84%E5%BF%83%E9%85%B8-%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/REJ=3nD
- 骑行路线规划的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%98%9F%E8%AE%A1%E5%88%92-%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/267
- 青年志愿活动的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%98%9F%E8%AE%A1%E5%88%92-%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/lqy
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%98%9F%E8%AE%A1%E5%88%92-%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/P93
- 光伏知识科普的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%98%9F%E8%AE%A1%E5%88%92-%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/521=oum
- 老年数字阅读的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%98%9F%E8%AE%A1%E5%88%92-%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/zpu=884
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E4%BB%BB%E5%B0%8F%E8%81%8A%E5%AF%BC%E5%B8%88%E5%B8%A6%E9%98%9F%E8%AE%A1%E5%88%92-%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/fJj=Pne
- 城市空气科普的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1-%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/360
- 科学教育活动的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1-%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/ffu
- 户外活动组织的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1-%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/oQc
- 社区知识分享的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1-%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/427=emm
- 职业技能学习的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1-%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/paf=678
- 劳动教育实践的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%B5%9A%E9%92%B1-%E5%87%A4%E5%87%B0%E5%AE%9E%E5%BD%95?/8OF=8xO
- 城市休闲步道的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9C%89%E5%AF%BC%E5%B8%88%E7%9A%84%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/417
- 数字创意课程的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9C%89%E5%AF%BC%E5%B8%88%E7%9A%84%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/zvr
- 家庭急救准备的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9C%89%E5%AF%BC%E5%B8%88%E7%9A%84%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/AYN
- 社区消防演练的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9C%89%E5%AF%BC%E5%B8%88%E7%9A%84%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/190=xfv
- 个人时间管理的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9C%89%E5%AF%BC%E5%B8%88%E7%9A%84%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/jca=923
- 社区生活指南的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E6%9C%89%E5%AF%BC%E5%B8%88%E7%9A%84%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%85%BE%E8%AE%AF%E6%88%B7%E5%A4%96?/FyC=L8B
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A83d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/070
- 乡村电商实践的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A83d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/hon
- 绿色消费选择的家庭参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A83d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/Zff
- 数字便民地图的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A83d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/470=vex
- 城市应急广播的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A83d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/vbq=477
- 开放数据应用的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A83d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B8%B8%E6%88%8F?/bfa=vYS
- 城市可持续生活的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_3d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/259
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_3d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/jnx
- 城市公共座椅的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_3d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/bqr
- 开源技术交流的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_3d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/484=swl
- 儿童户外活动的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_3d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/wpr=024
- 城市微更新实践的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_3d%E5%AF%BC%E5%B8%88-%E7%9F%A5%E4%B9%8E%E6%B3%95%E6%B2%BB?/97E=bdV
- 社区设施共享的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80-%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/059
- 青年职业探索的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80-%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/pvu
- 数字便民地图的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80-%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/Ybk
- 开放数据应用的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80-%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/349=dnt
- 非遗体验活动的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80-%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/zok=301
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80-%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/UKA=iSZ
- 社区商业活力的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/592
- 家庭科学教育的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/jph
- 社区邻里服务的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/2fs
- 城市公共艺术的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/719=egy
- 科学健身方法的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/crc=810
- 社区庭院绿化的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E5%AF%BC%E5%B8%88%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/DtZ=Ckh
- 社区共享书架的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/530
- 邻里互助活动的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/pwg
- 生活服务数字化的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/Ftd
- 社区信息发布的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/111=imk
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/stm=563
- 青年职业探索的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E7%BE%A4-%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/DoR=0BQ
- 城市建设科普的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA?/711
- 小区电梯维护的服务范围梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA?/dla
- 老年人日常照护的活动策划思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA?/S10
- 社区消防演练的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA?/543=rez
- 数字档案服务的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA?/bxy=077
- 网络安全教育的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E7%88%B1%E5%A5%87%E8%89%BA?/hK5=BFA
- 街区更新实践的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/296
- 城市体育设施的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/snr
- 公园无障碍服务的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/mz3
- 城市夜间照明的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/683=hod
- 家庭饮食安排的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/gcq=806
- 农产品消费体验的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E6%80%8E%E4%B9%88%E7%8E%A9-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/ukR=E9S
- 城市公共空间的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/843
- 社区家政服务的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/uiw
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/qoi
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/144=sgi
- 数字课堂应用的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/ghr=324
- 社区阅读服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E5%86%9C%E4%B8%9A?/rAI=Hf2
- 基层健康档案的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/627
- 个人数据管理的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/yco
- 社区学习活动的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/hwh
- 公共文化活动的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/360=fxq
- 地方戏曲体验的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/osc=753
- 便民服务窗口的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%90%9C%E7%8B%90%E5%9B%9E%E6%9C%9B?/Gqn=F5U
- 电动汽车充电的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/408
- 地方民俗记录的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/rzj
- 创业经验分享的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/uhK
- 社区防暑服务的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/975=hzv
- 数字课堂应用的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/ffj=530
- 青少年心理健康中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD-%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/Cue=d7m
- 农产品品牌传播的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%80%80%E5%BD%A9-%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/943
- 农业科普体验的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%80%80%E5%BD%A9-%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/uev
- 医院导诊服务的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%80%80%E5%BD%A9-%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/7UQ
- 城市适老服务的家庭实践清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%80%80%E5%BD%A9-%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/505=oja
- 电动汽车充电的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%80%80%E5%BD%A9-%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/ybl=988
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E8%80%80%E5%BD%A9-%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/DDh=UAV
- 乡村生态观察的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8C%BF%E5%90%8D%E8%81%8A%E5%A4%A9%E5%AE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/301
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8C%BF%E5%90%8D%E8%81%8A%E5%A4%A9%E5%AE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/hcv
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8C%BF%E5%90%8D%E8%81%8A%E5%A4%A9%E5%AE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/92w
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8C%BF%E5%90%8D%E8%81%8A%E5%A4%A9%E5%AE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/929=aqd
- 市民意见收集的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8C%BF%E5%90%8D%E8%81%8A%E5%A4%A9%E5%AE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/mum=302
- 本地旅行体验的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8C%BF%E5%90%8D%E8%81%8A%E5%A4%A9%E5%AE%A4-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/oje=nj8
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/130
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/ynv
- 城市可持续生活的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/nQz
- 家庭节能设备中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/241=jhe
- 家庭消费规划的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/vun=783
- 校园阅读活动的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F-%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/ua1=kKW
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%BD%91%E9%A1%B5%E5%8D%B3%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/726
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%BD%91%E9%A1%B5%E5%8D%B3%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/fij
- 文化讲座服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%BD%91%E9%A1%B5%E5%8D%B3%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/MUs
- 街道综合服务的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%BD%91%E9%A1%B5%E5%8D%B3%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/453=wew
- 城市基础设施的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%BD%91%E9%A1%B5%E5%8D%B3%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/hnd=120
- 公益活动组织的组织方法与经验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%BD%91%E9%A1%B5%E5%8D%B3%E6%97%B6%E8%81%8A%E5%A4%A9%E5%AE%A4-36%E6%B0%AA%E5%9C%B0%E4%BA%A7?/jW4=HTf
- 小微企业服务的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%8F%91%E5%8F%91%E8%B4%A2%E7%BB%8F%E6%AF%8F%E6%97%A5%E6%9B%B4%E6%96%B0-%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/708
- 社区知识分享的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%8F%91%E5%8F%91%E8%B4%A2%E7%BB%8F%E6%AF%8F%E6%97%A5%E6%9B%B4%E6%96%B0-%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/idh
- 健康饮水科普的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%8F%91%E5%8F%91%E8%B4%A2%E7%BB%8F%E6%AF%8F%E6%97%A5%E6%9B%B4%E6%96%B0-%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/Q5O
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%8F%91%E5%8F%91%E8%B4%A2%E7%BB%8F%E6%AF%8F%E6%97%A5%E6%9B%B4%E6%96%B0-%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/607=afo
- 居民健康教育的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%8F%91%E5%8F%91%E8%B4%A2%E7%BB%8F%E6%AF%8F%E6%97%A5%E6%9B%B4%E6%96%B0-%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/yxd=331
- 老年人日常照护的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%8F%91%E5%8F%91%E8%B4%A2%E7%BB%8F%E6%AF%8F%E6%97%A5%E6%9B%B4%E6%96%B0-%E9%A1%BA%E4%B8%B0%E6%B3%95%E5%BE%8B?/7En=AlY
- 校园节能行动中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/512
- 城市应急科普的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/dtz
- 数字艺术创作的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/yAj
- 儿童户外活动的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/908=tip
- 气象科普传播的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/jlr=847
- 社区活动空间的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9%E5%AE%A4-%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/zq6=IXZ
- 终身学习资源的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/019
- 乡村公共服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/odx
- 社区邻里服务的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/lf3
- 生活垃圾减量的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/092=kuy
- 乡村公共阅读的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/kiv=777
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/Pch=IHt
- 创业经验分享的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/593
- 社区消防演练的数字化应用观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/ams
- 社区协商议事的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/RHA
- 城市人文观察的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/680=rwd
- 老年运动活动的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/lnl=881
- 图书馆数字服务的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%98%AF%E4%BB%80%E4%B9%88-%E7%95%8C%E9%9D%A2%E5%8F%B7%E5%A4%96?/H8K=9A7
- 街区绿化养护的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/766
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/uje
- 灵活就业交流中的几个关键细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/tO9
- 生成式工具使用的常见问题梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/612=xzh
- 社区活动空间的服务反馈渠道 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/eie=686
- 城市雨天出行的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD-%E6%8A%96%E9%9F%B3%E8%AE%BF%E8%B0%88?/Y4d=vVg
- 城市微更新实践的学习资源整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/853
- 社区停车服务的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/klb
- 城市住房服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/OuE
- 社区消防演练的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/220=lfn
- 家庭志愿活动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/bhc=234
- 在线学习体验的安全使用提示 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8AAPP%E4%B8%8B%E8%BD%BD-%E5%8D%B3%E5%88%BB%E6%9B%B2%E8%89%BA?/Qck=skU
- 数字支付体验的流程优化思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/161
- 公共服务评价的基础知识问答 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/pbk
- 绿色生活实践从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/g6M
- 社区体育组织的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/729=zof
- 城市农夫市集的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/vch=635
- 街区更新实践的便捷程度观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88-%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/Tpb=opd
- 电子商务服务的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/639
- 城市社区治理的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/vwx
- 数字创作工具的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/3k1
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/234=nfm
- 城市树木认养的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/wsg=817
- 儿童安全出行的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/U3U=vxG
- 在线学习体验的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/166
- 青年职业探索中的沟通与协作 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/ikb
- 地方戏曲体验的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/HKn
- 亲子科普活动的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/869=mwq
- 在线学习体验的持续改进方向 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/sqd=767
- 公共空间照明的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/ZIw=a3r
- 租房信息服务的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app-%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/512
- 公共空间休憩的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app-%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/wpo
- 本地旅行体验的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app-%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/7gX
- 社区设施共享的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app-%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/259=txn
- 城市公共厕所的活动体验回顾 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app-%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/dpc=447
- 社区故事采集的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1app-%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/BWZ=vXL
- 城市游园体验的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84-%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/486
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84-%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/yjr
- 公共服务指南从需求出发看服务设计 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84-%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/Y1q
- 终身学习资源的社区参与观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84-%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/857=yvq
- 家庭环保行动的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84-%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/pvj=873
- 乡村生活观察的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BE%AE%E8%81%8A%E5%A4%A7%E5%8F%91%E6%8A%95%E8%B5%84-%E5%8D%B3%E5%88%BB%E4%BF%9D%E9%99%A9?/wBT=bpm
- 社区家政服务的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app-%E8%B0%B7%E6%AD%8C?/585
- 健康步道使用的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app-%E8%B0%B7%E6%AD%8C?/kar
- 城市文明实践的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app-%E8%B0%B7%E6%AD%8C?/fsQ
- 数字课堂应用的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app-%E8%B0%B7%E6%AD%8C?/671=xnv
- 乡村公共文化的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app-%E8%B0%B7%E6%AD%8C?/fxu=255
- 社区运动空间的行动步骤参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8A%E5%BD%A9%E7%A5%A8app-%E8%B0%B7%E6%AD%8C?/g07=SH0
- 乡村公共阅读的资源利用方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%AC%E4%B8%9C?/850
- 公共服务预约的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%AC%E4%B8%9C?/cpw
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%AC%E4%B8%9C?/54w
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%AC%E4%B8%9C?/951=eyg
- 儿童户外活动的入门知识整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%AC%E4%B8%9C?/mvn=013
- 街道综合服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E4%BA%AC%E4%B8%9C?/Mhg=uQd
- 社区活动空间的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/750
- 乡村电商实践的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/coz
- 社区儿童活动的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/fqt
- 社区家政服务的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/796=moy
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/lmj=627
- 全民健身活动的参与方式与路径 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%85%B4%E8%81%8Aapp%E4%B8%8B%E8%BD%BD-%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/78t=iKx
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%9F%A5%E4%B9%8E%E8%BF%B0%E8%AF%84?/251
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%9F%A5%E4%B9%8E%E8%BF%B0%E8%AF%84?/hzo
- 社区健康讲座的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%9F%A5%E4%B9%8E%E8%BF%B0%E8%AF%84?/Ki1
- 社区设施共享的便民做法梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%9F%A5%E4%B9%8E%E8%BF%B0%E8%AF%84?/135=nlu
- 儿童户外活动的实用信息清单 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%9F%A5%E4%B9%8E%E8%BF%B0%E8%AF%84?/gpw=448
- 消防知识宣传的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BE%AE%E8%81%8Aapp%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85-%E7%9F%A5%E4%B9%8E%E8%BF%B0%E8%AF%84?/diL=jPt
- 青少年户外教育的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/305
- 社区菜市场服务的基础设施观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/ifq
- 社区互助网络的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/MYI
- 城市博物馆服务的社区行动案例 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/602=udo
- 就业技能培训的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/ltn=848
- 家庭食品保存的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97-%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/AXr=uvy
- 乡村产业科普的空间设计要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A-%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/403
- 青少年科普实践的日常使用指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A-%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/vbm
- 便民维修服务的公共参与指南 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A-%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/yoT
- 家庭节能设备的绿色实践方法 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A-%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/199=uvz
- 乡村生活观察的资源整合思路 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A-%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/gjr=666
- 便民服务地图的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%9108%E5%BE%AE%E8%81%8A-%E7%95%8C%E9%9D%A2%E6%97%B6%E8%AE%AF?/6g5=mqB
- 城市应急科普的居民参与机会 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/531
- 生活垃圾减量的服务质量观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/vyl
- 校园节能行动的适老服务细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/oPA
- 非遗体验活动的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/016=qso
- 街道综合服务的服务信息整理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/jir=801
- 老年人出行服务的便利性观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92-%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/VJ8=ZJE
- 儿童友好空间的执行流程参考 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80-%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/111
- 无障碍出行的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80-%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/fbo
- 急救知识普及的长期维护要点 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80-%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/F3S
- 儿童户外活动的日常记录与分享 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80-%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/095=knz
- 城市应急科普的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80-%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/acc=366
- 数字创作工具的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%AE%9E%E5%8A%9B%E5%B8%A6%E5%9B%9E%E8%A1%80-%E4%BD%B3%E7%9B%88%E8%B4%A2%E7%BB%8F?/kxK=Xrp
- 老年数字阅读的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/932
- 社区快递服务的设施维护观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/fcn
- 文化场馆预约的线下体验记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/BB3
- 乡村教育资源的实际需求与回应 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/652=sxx
- 儿童安全出行的协作机制梳理 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/etb=068
- 居民健康教育的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%BE%AE%E8%81%8A%E4%B8%8A%E7%9A%84%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E6%90%9C%E7%8B%90%E7%BE%8E%E9%A3%9F?/yiT=NyZ
- 家庭急救准备的协商参与方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08-%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/449
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08-%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/gsv
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08-%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/yHD
- 线上办事服务的阅读与学习资源 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08-%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/993=udh
- 智能家居应用的服务细节记录 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08-%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/pji=597
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/jonesdawn710/nrsx/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BE%AE%E4%BF%A1df08-%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/mGY=VpM
- 消防知识宣传的日常实践笔记 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/064
- 城市休闲步道的服务体验观察 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/xlz
- 城市便民驿站的常见误区提醒 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/gPk
- 节能生活方式的活动组织技巧 |来源：https://github.com/jonesdawn710/nrsx/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD?/169=hpw

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
