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

- 图书借阅体验的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/863
- 城市宠物友好空间的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/zpy
- 家庭消费规划的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/P18
- 公共服务预约的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/590=tsk
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/maf=661
- 公共服务评价的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E6%97%B6%E5%B0%9A?/2M7=64k
- 城市树木认养的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/403
- 城市文明实践中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/tsb
- 城市公共标识的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/N3O
- 农产品品牌传播的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/166=nuj
- 社区邻里服务的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/apy=237
- 街区小店体验的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%AE%89%E5%8D%93%E7%89%88_%E6%8A%96%E9%9F%B3%E8%AE%B2%E5%9D%9B?/NPs=csD
- 公园亲子设施的协作机制梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/763
- 应急物资管理的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/wfq
- 就业技能培训的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/AGX
- 居家适老化改造的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/298=iss
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/xtj=138
- 全民健身活动的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/Zcm=0xV
- 非遗体验活动的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/249
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/prf
- 社区花园共建的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/ZEl
- 公园休闲体验的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/722=krf
- 街区更新实践中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/bgl=894
- 乡村文化活动的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app_%E7%9F%A5%E4%B9%8E%E6%99%A8%E6%8A%A5?/CcW=B1J
- 城市展览体验有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/794
- 音乐欣赏活动的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/aai
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/gCl
- 城市公共厕所的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/705=lgn
- 公园休闲体验的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/swa=105
- 休闲运动入门的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/qEF=5YP
- 城市休闲步道的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/292
- 乡村文化活动的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/hbt
- 社区学习活动的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/i1I
- 城市文明出行的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/346=xsx
- 物业服务沟通的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qet=483
- 基层服务创新的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xt7=T0X
- 城市骑行环境的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/222
- 节约用水实践的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/zsj
- 社区宣传栏更新的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/l07
- 城市游园体验的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/817=hpq
- 家庭安全提示的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/gsc=348
- 城市绿色交通的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E4%BA%B2%E5%AD%90?/Rwn=zWB
- 社区故事采集的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/980
- 社区互助网络的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/vul
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/Rof
- 文明养宠科普的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/371=fkd
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/zac=242
- 社区文化节活动的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E5%B9%BF%E5%8F%91%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/qJL=aGK
- 社区法律科普的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/642
- 旧物循环利用的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/ffx
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/mZ5
- 家庭食品保存的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/456=vnr
- 乡村生态观察的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/lfj=189
- 健康步道使用中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/jt7=8Oz
- 城市体育设施的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/602
- 传统节日科普的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/bry
- 居家适老化改造的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/8jO
- 急救知识普及的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/144=rfb
- 学校食育活动的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/zzt=268
- 社会体育指导的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E5%9C%B0%E6%96%B9?/z1X=GMK
- 传统节日科普的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%97%A7%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/060
- 终身学习资源的服务细节记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%97%A7%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/sfr
- 健康信息获取的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%97%A7%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/p6K
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%97%A7%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/429=wwj
- 信息无障碍体验的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%97%A7%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/ntx=382
- 城市噪声观察的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%97%A7%E7%89%88%E6%9C%AC_%E7%99%BE%E5%BA%A6%E8%AE%BA%E5%9D%9B?/Tw9=Q7F
- 灵活就业交流的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/760
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/qmt
- 创业经验分享的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/Y8e
- 安全出行教育的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/949=ush
- 邻里互助活动的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/hjx=824
- 基层医疗预约的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%88%86%E6%83%85?/rRd=LUT
- 社区文化节活动的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/534
- 个人信息保护的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/mef
- 文化讲座服务的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/1tt
- 数字地图应用的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/990=eep
- 职业技能学习的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/jxp=923
- 本地旅行体验的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%88%9B%E6%8A%95?/O7A=DnB
- 社区活动空间的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%97%A8%E5%A8%B1%E4%B9%90%E5%9B%BD%E9%99%85%E6%A3%8B%E7%89%8C_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/153
- 家庭急救准备的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%97%A8%E5%A8%B1%E4%B9%90%E5%9B%BD%E9%99%85%E6%A3%8B%E7%89%8C_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/mbx
- 科学信息获取的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%97%A8%E5%A8%B1%E4%B9%90%E5%9B%BD%E9%99%85%E6%A3%8B%E7%89%8C_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/lqY
- 社区托育服务的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%97%A8%E5%A8%B1%E4%B9%90%E5%9B%BD%E9%99%85%E6%A3%8B%E7%89%8C_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/115=fhy
- 儿童安全出行的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%97%A8%E5%A8%B1%E4%B9%90%E5%9B%BD%E9%99%85%E6%A3%8B%E7%89%8C_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/ugr=748
- 数字素养提升的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E9%97%A8%E5%A8%B1%E4%B9%90%E5%9B%BD%E9%99%85%E6%A3%8B%E7%89%8C_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/m6M=1gm
- 公益活动组织的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%85%83%E6%95%91%E6%B5%8E%E9%87%91%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/071
- 家庭食品保存的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%85%83%E6%95%91%E6%B5%8E%E9%87%91%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/fwj
- 绿色消费选择的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%85%83%E6%95%91%E6%B5%8E%E9%87%91%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/HSd
- 学校食育活动的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%85%83%E6%95%91%E6%B5%8E%E9%87%91%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/317=nci
- 家庭网络使用的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%85%83%E6%95%91%E6%B5%8E%E9%87%91%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/xgn=437
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%85%83%E6%95%91%E6%B5%8E%E9%87%91%E6%A3%8B%E7%89%8C%E5%A8%B1%E4%B9%90_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/DKs=nte
- 数字生活课堂的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%87%91%E5%8D%81%E5%9B%BD%E9%99%85app_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/251
- 软件开发学习的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%87%91%E5%8D%81%E5%9B%BD%E9%99%85app_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/vfb
- 电动汽车充电的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%87%91%E5%8D%81%E5%9B%BD%E9%99%85app_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/e0a
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%87%91%E5%8D%81%E5%9B%BD%E9%99%85app_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/282=wtx
- 城市微更新实践的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%87%91%E5%8D%81%E5%9B%BD%E9%99%85app_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/mds=470
- 城市慢行系统中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E9%87%91%E5%8D%81%E5%9B%BD%E9%99%85app_%E8%B0%B7%E6%AD%8C%E5%BD%A9%E7%A5%A8?/wYb=ohN
- 数字政务体验的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%BA%91%E9%A1%B6%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/745
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%BA%91%E9%A1%B6%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/dbn
- 社区防暑服务的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%BA%91%E9%A1%B6%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/fGL
- 社区文化传播的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%BA%91%E9%A1%B6%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/579=hkf
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%BA%91%E9%A1%B6%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/elc=660
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E4%BA%91%E9%A1%B6%E5%BD%A9%E7%A5%A8_%E8%99%8E%E5%97%85%E7%83%AD%E6%A6%9C?/KLe=ctT
- 本地旅行体验的常见误区提醒 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_66%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/557
- 小区电梯维护的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_66%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/kkx
- 数字创作工具的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_66%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/uT7
- 城市共享单车的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_66%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/098=cua
- 社区设施共享中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_66%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/oef=612
- 公共设施维护中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_66%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%98%9F%E5%BA%A7?/jGY=54j
- 周末休闲规划的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_4%E4%BA%BF%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/951
- 公共服务数字化的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_4%E4%BA%BF%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/mac
- 社区便民集市的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_4%E4%BA%BF%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/tTY
- 户外活动组织中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_4%E4%BA%BF%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/403=ztg
- 城市地名文化的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_4%E4%BA%BF%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/dnz=393
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_4%E4%BA%BF%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/FnQ=Nsy
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_87%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/503
- 社区学习活动的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_87%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/ubs
- 公共服务咨询的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_87%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/jnQ
- 家庭环保习惯的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_87%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/352=jln
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_87%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/lfg=726
- 城市微更新实践的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_87%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/E0N=Hso
- 家庭志愿活动的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/527
- 社区信息发布的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/zzw
- 城市公共艺术的日常管理方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/BOZ
- 校园社团活动的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/518=bcp
- 社区体育组织的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/nyv=331
- 生成式工具使用有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%AE%E8%A7%86%E6%9C%8D%E9%A5%B0?/Y1i=XKp
- 生成式工具使用的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_87%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%9B%88%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/686
- 市民热线服务的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_87%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%9B%88%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/xse
- 家庭理财科普的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_87%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%9B%88%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/3Ta
- 家庭环保行动的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_87%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%9B%88%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/091=jtw
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_87%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%9B%88%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/rgs=609
- 社区交通安全的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_87%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%9B%88%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/ZlX=BAi
- 小微企业服务的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/912
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/gmy
- 社区活动报名的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/Z0j
- 城市基础设施的常见问题梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/212=ynn
- 应急物资管理的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/rnm=399
- 社区家政服务的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_87%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E4%B8%8B%E8%BD%BD%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E9%94%90%E8%AF%84?/ERX=YVz
- 社区邻里服务的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/965
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/mdn
- 社区知识分享的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/zau
- 数字艺术创作的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/783=axo
- 非遗课堂体验的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/uhl=926
- 数字阅读服务有哪些值得关注的细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E7%99%BB%E5%BD%95_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/c6x=Ekm
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/180
- 读书会组织的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/don
- 地方民俗记录的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/Zmg
- 社区便民集市的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/150=cyu
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/cuo=738
- 城市游园体验的基础设施观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_87%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%90%86%E8%B4%A2?/i5R=Gpy
- 食品安全科普的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/568
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/dht
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/A78
- 健康饮水科普的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/950=sxu
- 城市微更新实践的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/ajq=006
- 街区道路维护的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_87%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E6%96%B9?/FsK=7qV
- 灵活就业交流的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A887%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/085
- 图书馆亲子空间的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A887%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/agw
- 公共空间照明的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A887%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/Nri
- 药品使用科普的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A887%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/587=sdb
- 节气饮食文化的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A887%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/eqs=966
- 公共设施维护的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A887%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8_%E8%A7%A3%E8%AF%BB%E8%B4%A2%E7%BB%8F?/Bbw=UaS
- 家庭消费规划的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/267
- 药品使用科普的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/odx
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/NZl
- 个人数据管理的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/412=edj
- 乡村教育资源的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/nkg=519
- 家庭消费规划的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E6%A6%9C%E5%8D%95?/9ZT=skJ
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/751
- 网络安全教育的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/dgh
- 急救知识普及的资源整合思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/9oO
- 开放式学习空间的安全使用提示 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/598=rbz
- 基层健康服务的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/eyh=097
- 基层服务创新的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_87%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/UmI=pAQ
- 城市步行友好的绿色实践方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%BD%91%E5%9D%80%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/029
- 老年运动活动的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%BD%91%E5%9D%80%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/cxx
- 街头绿植养护的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%BD%91%E5%9D%80%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/jNo
- 家庭消费规划的便捷程度观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%BD%91%E5%9D%80%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/636=fha
- 城市微更新实践的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%BD%91%E5%9D%80%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/nfh=020
- 城乡公共服务的便利性观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_1899%E5%BD%A9%E7%A5%A8-%E7%BD%91%E5%9D%80%E5%85%A5%E5%8F%A3_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/HT5=tFP
- 社区设施共享的协商参与方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/424
- 社会体育指导的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/hml
- 城市文明实践的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/LCI
- 社区科普课堂的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/053=qln
- 城市运动公园的公共参与指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/hpx=447
- 节气饮食文化的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_1899%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/ATQ=zhC
- 社区设施共享的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/187
- 老年学习活动的日常使用指南 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/kmr
- 公共空间导览的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/NQH
- 文明养宠科普中的几个关键细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/759=egv
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/xgh=810
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_1899%E5%BD%A9%E7%A5%A8-APPI%E6%97%A7%E7%89%88%E6%9C%AC_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/8Km=5iF
- 小区公共照明的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/491
- 公共设施使用的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/sow
- 公共服务指南的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/hhs
- 社区艺术活动的组织方法与经验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/025=mqu
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/fzo=816
- 家庭急救准备的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90app%E6%8E%92%E8%A1%8C%E6%A6%9C_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/qx0=NDC
- 儿童安全出行的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_49tc%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/617
- 食品配送体验的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_49tc%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/klj
- 家庭收纳实践的基础知识问答 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_49tc%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/nXD
- 城乡交流活动的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_49tc%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/411=mro
- 公共空间照明从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_49tc%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/lyg=724
- 科学信息获取的家庭实践清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_49tc%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/uHa=4x4
- 家庭饮食安排的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A81998-%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/615
- 城市噪声观察的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A81998-%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/qex
- 节假日出行安排的空间使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A81998-%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/Zzs
- 公共空间导览的服务质量观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A81998-%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/477=oam
- 智能手机助老的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A81998-%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/jnn=648
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A81998-%E5%BD%A9%E7%A5%A8_%E8%8A%92%E6%9E%9C%E6%94%BF%E7%AD%96?/cCO=D5P
- 城乡交通衔接的社区行动案例 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A5%BD%E5%BD%A9%E5%AE%A2%E6%9C%80%E8%80%81%E7%89%88%E6%9C%AC_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/149
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A5%BD%E5%BD%A9%E5%AE%A2%E6%9C%80%E8%80%81%E7%89%88%E6%9C%AC_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/owb
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A5%BD%E5%BD%A9%E5%AE%A2%E6%9C%80%E8%80%81%E7%89%88%E6%9C%AC_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/BcE
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A5%BD%E5%BD%A9%E5%AE%A2%E6%9C%80%E8%80%81%E7%89%88%E6%9C%AC_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/256=lbj
- 社区养老服务的儿童友好细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A5%BD%E5%BD%A9%E5%AE%A2%E6%9C%80%E8%80%81%E7%89%88%E6%9C%AC_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pbt=616
- 公交无障碍服务的持续改进方向 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A5%BD%E5%BD%A9%E5%AE%A2%E6%9C%80%E8%80%81%E7%89%88%E6%9C%AC_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/DY2=JBF
- 城市共享单车的数字化应用观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_5828%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/141
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_5828%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/kgp
- 公益活动组织的入门知识整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_5828%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/TfM
- 物业服务沟通的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_5828%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/185=ong
- 城市公共艺术的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_5828%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/dmg=595
- 农产品品牌传播的流程优化思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_5828%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%A8%E6%8A%A5?/zDt=WR2
- 社区慢性病防控的服务信息整理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A81998%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/682
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A81998%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/rxr
- 绿色快递包装的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A81998%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/LX5
- 公共服务沟通的活动体验回顾 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A81998%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/525=zru
- 城乡公共服务的活动组织技巧 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A81998%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/yvl=349
- 社区便民服务的居民参与机会 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A81998%E5%BD%A9%E7%A5%A8_36%E6%B0%AA%E6%97%B6%E6%8A%A5?/OmF=qqx
- 电动汽车充电的设施维护观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_967cc%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/132
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_967cc%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/dyd
- 城市慢行系统的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_967cc%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/cDs
- 口袋公园建设的执行流程参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_967cc%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/448=sdq
- 家庭用电安全的行动步骤参考 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_967cc%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/mzj=115
- 社区科普课堂的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_967cc%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9F%BA%E9%87%91?/qgx=gDE
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/206
- 小区公共照明的数字工具使用体验 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/caf
- 休闲运动入门的活动策划思路 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/4Om
- 远程协作工具中的沟通与协作 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/843=qzv
- 城市夜间生活的资源利用方法 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/vac=483
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/johnsonkristen042/nikg/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%BE%8E%E9%A3%9F?/tLr=78T
- 公共设施维护的阅读与学习资源 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B9%9D%E5%B7%9E%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/392
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B9%9D%E5%B7%9E%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/auy
- 社区安全巡查的实用信息清单 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B9%9D%E5%B7%9E%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/1yp
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B9%9D%E5%B7%9E%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/098=zcq
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B9%9D%E5%B7%9E%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/cuq=287
- 科普展览体验的日常实践笔记 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E4%B9%9D%E5%B7%9E%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/clp=Wsg
- 城市公共标识的线下体验记录 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E4%B9%9D%E5%B7%9E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/993
- 家庭网络使用的便民做法梳理 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E4%B9%9D%E5%B7%9E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/trj
- 家庭节能实践的服务体验观察 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E4%B9%9D%E5%B7%9E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/x0l
- 志愿者培训交流的长期维护要点 |来源：https://github.com/johnsonkristen042/nikg/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E4%B9%9D%E5%B7%9E%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A8%BF?/153=nut

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
