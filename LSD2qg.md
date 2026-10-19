# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 公共设施维护的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%85%AC%E7%9B%8A?/XBR
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%85%AC%E7%9B%8A?/928=sgj
- 城市公共饮水的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%85%AC%E7%9B%8A?/dct=505
- 旧物循环利用的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_3%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E5%85%AC%E7%9B%8A?/pjm=xS6
- 环境教育课程的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/959
- 社区慢性病防控的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/mvo
- 家庭环保行动的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/Gwj
- 城市文明出行的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/456=zwo
- 家庭节能实践的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/msu=974
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E8%B5%84%E8%AE%AF?/36t=ln4
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_3%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/449
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_3%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/cjy
- 基层健康档案的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_3%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/jye
- 城市可持续生活的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_3%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/967=ojw
- 居民健康教育的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_3%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/iju=000
- 小区公共照明的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_3%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E8%84%89%E8%84%89%E7%BE%8E%E8%82%A1?/EXv=Syp
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/541
- 校园安全教育的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/ika
- 家庭养老规划的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/QHv
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/237=wii
- 数字阅读服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/rrk=328
- 食品安全科普的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B0%B7%E6%AD%8C%E6%8A%95%E7%A8%BF?/xMk=A4x
- 校园安全教育的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/833
- 街道综合服务的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/kmc
- 社区共享书架的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/iqh
- 社区知识分享的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/926=rox
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/dar=633
- 家庭急救准备的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/pa6=xoR
- 社区文化节活动的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/241
- 城市适老服务的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/hda
- 农村环境治理的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/dYl
- 职业技能学习的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/935=sgp
- 健康信息获取的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/ftm=951
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_3%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/ZQk=5hE
- 绿色出行服务的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/872
- 城市噪声观察的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/vtj
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/8ys
- 图书馆活动策划的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/189=rtw
- 智慧停车服务的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/vha=130
- 数字公共文化的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_3%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/btc=axQ
- 无障碍信息设计的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_3%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/718
- 人工智能科普的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_3%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/lhg
- 社区活动报名的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_3%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/BjU
- 图书馆数字服务的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_3%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/805=gwl
- 儿童友好空间的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_3%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/ouw=957
- 农村环境治理的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_3%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/e7Z=HEI
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/163
- 数字资源检索的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/iit
- 公共设施使用的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/kpe
- 网络安全教育的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/791=ihh
- 邻里共享空间的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/vqp=264
- 城乡公共服务的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_3%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%90%9C%E7%8B%90%E5%86%9C%E4%B8%9A?/cAi=4jd
- 乡村文化活动的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/858
- 全民健身活动的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/feg
- 绿色办公实践的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/MmT
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/420=sjc
- 全民阅读推广的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/zoq=709
- 城市应急广播的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_3%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E8%88%86%E6%83%85?/1Ex=VVi
- 公共服务指南的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/056
- 家庭健康管理的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/yql
- 老年人日常照护的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/xUw
- 网络信息辨识的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/127=fkg
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/zed=099
- 数字政务体验的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E6%B3%95%E6%B2%BB?/vOD=m2z
- 绿色生活实践中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/003
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/ekt
- 乡村文化活动的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/C0g
- 线上阅读资源中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/231=irh
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/msa=361
- 社区手工活动中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%8D%E9%A5%B0?/sCt=qRX
- 公共服务评价的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/484
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/opl
- 食品配送体验的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/YkY
- 生成式工具使用的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/274=qna
- 公共空间休憩的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/adi=686
- 乡村文化空间的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E5%BF%85%E5%BA%94%E7%99%BE%E7%A7%91?/NSE=ALY
- 绿色生活实践的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/465
- 社区儿童活动的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/cdw
- 公共空间休憩的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/OkW
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/537=maw
- 公共场馆服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/jld=868
- 家庭安全提示的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%81%A5%E5%BA%B7?/P8u=CLh
- 校园阅读活动的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/471
- 基层健康档案的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/wdz
- 无障碍信息设计的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/1D0
- 骑行路线规划的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/408=cny
- 数字公共文化的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/xkl=670
- 城乡交流活动的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/Xyh=m99
- 灵活就业交流的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/053
- 青少年科普实践的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/qry
- 城市夜间照明的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/HEN
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/707=nxn
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/hua=317
- 图书借阅体验的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/FpS=5CN
- 地方文化传播的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/083
- 居民健康教育的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/jak
- 气象科普传播的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/ZHH
- 公共服务评价的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/134=dbn
- 社区宣传栏更新的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/lhg=888
- 社会体育指导的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E5%AE%8F%E8%A7%82?/fkT=DLt
- 课后服务体验的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/754
- 社区共享书架的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/oun
- 数字设备回收的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/JRY
- 健康信息获取的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/046=jgk
- 电子商务服务的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/qix=203
- 街区更新实践的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_3%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/q49=iNz
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/204
- 社区菜市场服务的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/xfe
- 终身学习资源的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ThQ
- 城市游园体验的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/947=ksn
- 在线学习体验的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ler=418
- 创业经验分享的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/WHH=k92
- 线上办事服务的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/717
- 社区健康讲座中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/jys
- 图书馆数字服务的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/Czr
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/796=mpv
- 城乡公共服务的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/ufs=609
- 药品使用科普的适老服务细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/W8A=osl
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/326
- 社区设施共享的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/kar
- 小微企业服务的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/TWf
- 社区学习活动的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/718=eog
- 城市慢行系统的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/nak=860
- 社区托育服务中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/ikO=kC0
- 校园节能行动的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/014
- 社区设施共享的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/crk
- 小区停车协商的家庭参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/LMO
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/867=dpu
- 城市建设科普的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/fxf=506
- 灵活就业交流中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BE%E9%9B%86?/1Om=3Px
- 社区信息发布从需求出发看服务设计 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/227
- 老年学习活动的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/rzv
- 社区公共议事的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/NcG
- 家庭安全提示中的沟通与协作 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/458=ljh
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/xpe=606
- 乡村电商实践的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B0%B7%E6%AD%8C%E5%85%AC%E7%9B%8A?/Wf9=RFd
- 节能家电使用的实际需求与回应 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/006
- 绿色办公实践的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/vhn
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/kSU
- 街区更新实践的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/577=knp
- 远程协作工具的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/kgo=300
- 节能生活方式的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/BNu=XM7
- 城市绿色交通的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/499
- 科学信息获取的行动步骤参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/nvu
- 公共服务数字化的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/XJn
- 城市空气科普的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/867=hnd
- 家庭健康管理的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/zyz=005
- 网络安全教育的组织方法与经验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/etQ=Qrd
- 城市公共饮水的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/599
- 社区家政服务的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/zrw
- 社区故事采集的日常记录与分享 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/VvP
- 社会体育指导的持续改进方向 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/279=gxd
- 开源技术交流的线下体验记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/vii=712
- 公共卫生宣传的基础知识问答 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E7%9F%A5%E4%B9%8E%E6%88%B7%E5%A4%96?/mD3=3Sq
- 社区教育资源的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/083
- 家庭用电安全的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/ejl
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/YfP
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/303=nwf
- 数字创作工具的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/xbp=876
- 乡村生活观察的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%88%B1%E5%A5%87%E8%89%BA%E6%97%B6%E8%AF%84?/Am1=XKl
- 日常摄影记录的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/845
- 街区小店体验的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/bpr
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/S4p
- 农业科普体验的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/533=got
- 基层健康档案的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/lvz=633
- 科普展览体验的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E4%BC%98%E9%85%B7%E7%99%BE%E7%A7%91?/IUB=FTr
- 儿童友好空间的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/496
- 社区公共议事的常见误区提醒 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/tmk
- 租房信息服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/eBJ
- 老年人日常照护的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/100=imp
- 物业服务沟通的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/yvx=749
- 乡村产业科普的活动体验回顾 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/Wdl=2tB
- 社区文化节活动的空间设计要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/150
- 青少年户外教育的协作机制梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/sba
- 科技馆参观体验的执行流程参考 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/bql
- 街道综合服务的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/083=azy
- 城市人文观察的空间使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/xpp=843
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_%E5%BF%85%E5%BA%94%E4%BA%B2%E5%AD%90?/HCz=LFN
- 开源技术交流的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/899
- 便民服务地图的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/vja
- 城市共享单车的实用信息清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/84p
- 社区体育组织的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/842=mwf
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/dfi=833
- 租房信息服务的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E6%91%98?/s5c=QsX
- 街头绿植养护的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/280
- 城市夜间照明的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/sof
- 跨代沟通活动的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/xte
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/087=snt
- 文化场馆预约的家庭实践清单 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/kjw=567
- 社区科普课堂的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E5%BF%AB%E6%89%8B%E6%89%8B%E8%AE%B0?/X8z=J3s
- 本地消费场景的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/508
- 公共空间休憩的设施维护观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/fmk
- 就业技能培训的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/GfG
- 绿色出行服务的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/978=hcd
- 城市游园体验中的几个关键细节 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/nmi=912
- 城市应急广播的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E5%A8%B1%E4%B9%90?/FEF=ajU
- 环境监测科普的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_360%E8%BD%AC%E8%BD%BD?/432
- 科学观察活动的流程优化思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_360%E8%BD%AC%E8%BD%BD?/ymt
- 城市社区治理的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_360%E8%BD%AC%E8%BD%BD?/m3a
- 生活垃圾回收的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_360%E8%BD%AC%E8%BD%BD?/231=kip
- 科学健身方法的长期维护要点 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_360%E8%BD%AC%E8%BD%BD?/qit=932
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E6%89%8B_360%E8%BD%AC%E8%BD%BD?/fKr=EKm
- 城乡交流活动的日常使用指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/339
- 城市便民驿站的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/mjp
- 社区公共餐饮的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/OwI
- 家庭安全提示的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/141=zqg
- 口袋公园建设的日常实践笔记 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/qhj=909
- 家庭节能实践的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%AE%97%E6%B3%95_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/U47=Nk1
- 城市公共艺术的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/015
- 城市骑行环境的学习资源整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/atv
- 社区知识分享的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/7LT
- 家庭照护支持的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/119=fdi
- 数字设备回收的社区参与观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/ooq=825
- 城市可持续生活的公共信息获取方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BB%8A%E6%97%A5%E4%B8%93%E5%AE%B6%E6%8E%A8%E8%8D%90%E5%8F%B7_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/Pwb=8Rx
- 药品使用科普的日常管理方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/259
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/apm
- 生活垃圾回收的便利性观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/JNG
- 智能家居应用的数字工具使用体验 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/220=pvq
- 城市微更新实践的活动组织技巧 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/pgg=296
- 科技馆参观体验的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8E%E6%8E%A8%E8%8D%90_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/izC=5Ha
- 骑行路线规划的服务信息整理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/128
- 市民热线服务的服务范围梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/yru
- 城市体育设施的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/Fed
- 绿色消费选择的便捷程度观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/884=whq
- 家庭健康科普的便民做法梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/amj=237
- 社区垃圾回收的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9B%BE_%E5%8D%B3%E5%88%BB%E7%A4%BE%E5%8C%BA?/blq=2cj
- 地方民俗记录的服务质量观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/895
- 家庭节能实践的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/glw
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/CMc
- 儿童安全出行的数字化应用观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/048=qsi
- 应急物资管理的活动策划思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/aea=205
- 社区故事采集的服务体验观察 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E4%BF%A1%E8%B4%B7?/Q20=rjC
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/403
- 青年志愿活动的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/nsz
- 校园节能行动的协商参与方式 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/pcs
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/582=rxe
- 校园社团活动的社区行动案例 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/jlb=607
- 数据分析入门的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_3%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/HEV=58o
- 城市公共艺术的绿色实践方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/657
- 医院导诊服务的居民参与机会 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/dwt
- 远程协作工具的常见问题梳理 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/rGk
- 医院导诊服务的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/406=psj
- 家庭环保习惯的公共参与指南 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/fig=378
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_3%E5%88%86%E6%B1%9F%E8%8B%8F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E6%99%9A%E6%8A%A5?/czP=rmS
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/145
- 图书借阅体验的服务细节记录 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/ker
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/Phz
- 家庭志愿活动的资源利用方法 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/167=gec
- 老年数字阅读的资源整合思路 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/vpz=074
- 数字地图应用的服务反馈渠道 |来源：https://github.com/griffinsean5247/tqcu/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_3%E5%88%86%E6%96%B0%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E8%99%8E%E5%97%85%E8%83%BD%E6%BA%90?/izM=xvG

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
